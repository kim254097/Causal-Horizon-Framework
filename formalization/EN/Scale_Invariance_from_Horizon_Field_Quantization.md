# Scale Invariance from Horizon Field Quantization

**Kevin Muñoz**

---

## Abstract

The formalization of horizon-centered cosmological dynamics introduced an effective scalar field $\phi(\Omega, t)$ on the apparent horizon, whose power spectrum was adopted as a minimal statistical hypothesis rather than derived from first principles. This document closes that gap. We show that the canonical quantization of $\phi$, combined with a natural identification between angular modes on the horizon and comoving Fourier modes in the bulk, yields a mode equation of Mukhanov–Sasaki form. With Bunch–Davies initial conditions, this equation produces a scale-invariant power spectrum at freeze-out as a consequence of the field's quantum vacuum structure, not as an assumption. The spectral tilt $n_s - 1 = 3 - 2\nu$ is derived from the effective potential governing the horizon modes, with $\nu$ determined by the effective mass $m_\text{eff}^2$ and the rate of change of the horizon radius. This work replaces equation (29) and the tilt formula (33) of the formalization document with derived results.

---

## 1. Motivation

In the horizon-centered formalization (Document 5 of the Causal Horizon Framework), the apparent horizon carries an effective scalar field $\phi(\Omega, t)$ with action

$$S = \int dt\, d\Omega\, R_A^2 \left[(\partial_t \phi)^2 + \frac{c_s^2}{R_A^2}(\nabla_\Omega \phi)^2 + m_\text{eff}^2 \phi^2\right] \tag{1}$$

and the identification $\psi \sim \phi$ links boundary fluctuations to the cosmological perturbation variable $\psi = \delta R_A / R_A$.

Two results were left underived:

- **Equation (29):** $\langle \phi(x)\phi(0) \rangle \sim |x|^{-\alpha}$ adopted as a statistical hypothesis.
- **Equation (33):** $n_s - 1 \approx -2\beta$ stated by analogy with de Sitter scalar field theory.

We derive both from the action (1) by canonical quantization.

---

## 2. Comoving Mode Identification

The field $\phi(\Omega, t)$ lives on a two-sphere of physical radius $R_A(t) = 1/H(t)$. A spherical harmonic mode $Y_{lm}$ corresponds to an angular scale $\theta \sim \pi / l$, hence a physical scale $\lambda_\text{phys} \sim \pi R_A / l = \pi / (lH)$ on the horizon.

In the bulk, a comoving Fourier mode with wavenumber $k$ has physical wavelength $\lambda_\text{phys} = 2\pi a / k$, so its physical wavenumber is $k_\text{phys} = k/a$.

Matching $k_\text{phys}$ to the angular scale on the horizon:

$$k_\text{phys} = \frac{k}{a(t)} \quad \longleftrightarrow \quad l_k(t) = \frac{k_\text{phys}(t)}{H(t)} = \frac{k}{a(t)\,H(t)} \tag{2}$$

This is the comoving mode identification: a comoving wavenumber $k$ corresponds to angular mode $l_k(t)$ at time $t$. The mapping is time-dependent because $a(t)H(t)$ evolves. For de Sitter, $H = \text{const}$ and $a(t) = e^{Ht}$, so

$$l_k(t) = \frac{k}{H}\,e^{-Ht} \tag{3}$$

$l_k$ decreases monotonically. At early times ($t \to -\infty$), $l_k \to \infty$: the mode oscillates rapidly on the horizon. As the universe expands, $l_k \to 1$, which defines the freeze-out time

$$t_k: \quad l_k(t_k) = 1 \quad \Longrightarrow \quad k = a(t_k)\,H \tag{4}$$

This is precisely the standard horizon-crossing condition $k_\text{phys} = H$.

---

## 3. Canonical Quantization

For each mode $(l, m)$, the action (1) reduces to

$$S_{lm} = \int dt\, R_A^2(t)\left[\dot{\phi}_{lm}^2 - \omega_l^2(t)\,\phi_{lm}^2\right] \tag{5}$$

with mode frequency

$$\omega_l^2(t) = \frac{c_s^2\,l(l+1)}{R_A^2(t)} + m_\text{eff}^2(t) \tag{6}$$

Define the canonical variable

$$v_{lm}(t) \equiv R_A(t)\,\phi_{lm}(t) \tag{7}$$

whose kinetic term has unit coefficient. Substituting and integrating by parts yields the action

$$S_{lm} = \int dt\left[\dot{v}_{lm}^2 - \Omega_l^2(t)\,v_{lm}^2\right] \tag{8}$$

with effective frequency

$$\Omega_l^2(t) = \omega_l^2(t) - \frac{\ddot{R}_A}{R_A} \tag{9}$$

The canonical momentum is $\pi_{lm} = 2\dot{v}_{lm}$ and the equation of motion is

$$\ddot{v}_{lm} + \Omega_l^2(t)\,v_{lm} = 0 \tag{10}$$

We promote $v_{lm}$ to an operator and impose $[\hat{v}_{lm}, \hat{\pi}_{l'm'}] = i\delta_{ll'}\delta_{mm'}$. Expanding in mode functions:

$$\hat{v}_{lm}(t) = v_l^{\,}(t)\,\hat{a}_{lm} + v_l^*(t)\,\hat{a}_{lm}^\dagger \tag{11}$$

where $v_l(t)$ satisfies (10) and the normalization $v_l \dot{v}_l^* - v_l^* \dot{v}_l = i/2$.

---

## 4. Mukhanov–Sasaki Equation for Horizon Modes

### 4.1 Conformal time reformulation

Introduce conformal time $d\eta = dt/a(t)$, with $' \equiv d/d\eta$. For a flat FRW background with $H(t)$:

$$R_A = \frac{1}{H}, \qquad \frac{\dot{R}_A}{R_A} = -\frac{\dot{H}}{H^2} = \varepsilon H \tag{12}$$

where $\varepsilon \equiv -\dot{H}/H^2 \geq 0$ is the slow-roll parameter.

Using the comoving mode identification (2), the effective frequency (9) evaluated at $l = l_k(\eta)$ in conformal time becomes

$$\Omega_k^2(\eta) = c_s^2 k^2 - \frac{z_A''}{z_A} \tag{13}$$

where $z_A(\eta) \equiv a(\eta)/\sqrt{\varepsilon(\eta)}$ and primes denote $d/d\eta$. The variable $u_k \equiv z_A \psi_k$ then satisfies

$$u_k'' + \left[c_s^2 k^2 - \frac{z_A''}{z_A}\right]u_k = 0 \tag{14}$$

This is the **Mukhanov–Sasaki equation** for the horizon perturbation $\psi_k$, derived here directly from the horizon field action (1) through the comoving mode identification.

### 4.2 Effective potential for de Sitter

For de Sitter with $H = \text{const}$, $\varepsilon = 0$. Including $m_\text{eff}^2 = \beta H^2$ as a small correction, the effective potential takes the form

$$\frac{z_A''}{z_A} = \frac{\nu^2 - \frac{1}{4}}{\eta^2} \tag{15}$$

with

$$\nu^2 = \frac{9}{4} - \frac{m_\text{eff}^2}{H^2} = \frac{9}{4} - \beta \tag{16}$$

The mode equation becomes

$$u_k'' + \left[c_s^2 k^2 - \frac{\nu^2 - \frac{1}{4}}{\eta^2}\right]u_k = 0 \tag{17}$$

---

## 5. Bunch–Davies Vacuum and Freeze-out

### 5.1 Initial conditions

At early times ($k_\text{phys} \gg H$, equivalently $|k\eta| \gg 1$), the mode $k$ lies well inside the horizon and the potential term $(\nu^2 - 1/4)/\eta^2$ is negligible. Equation (17) reduces to a free oscillator:

$$u_k'' + c_s^2 k^2\, u_k = 0 \tag{18}$$

We impose the Bunch–Davies (positive frequency) initial condition:

$$u_k(\eta) \xrightarrow{|k\eta| \to \infty} \frac{1}{\sqrt{2c_s k}}\,e^{-ic_s k\eta} \tag{19}$$

This is the unique choice compatible with the local Minkowski vacuum at short distances.

### 5.2 Exact solution

The general solution to (17) regular at $k\eta \to -\infty$ is a Hankel function of the first kind:

$$u_k(\eta) = \frac{\sqrt{\pi}}{2}\,e^{i(\nu + \frac{1}{2})\frac{\pi}{2}}\,\sqrt{-\eta}\,H_\nu^{(1)}(-c_s k\eta) \tag{20}$$

normalized to satisfy (19). For small argument $|k\eta| \to 0$ (super-horizon, after freeze-out):

$$|u_k(\eta)|^2 \xrightarrow{|k\eta| \to 0} \frac{2^{2\nu-3}\Gamma(\nu)^2}{\pi c_s k}\,\left(\frac{1}{-k\eta}\right)^{2\nu - 1} \tag{21}$$

### 5.3 Freeze-out amplitude

At freeze-out, $k = a(t_k)H$, which in conformal time for de Sitter gives $k\eta_k = -1$. The horizon-centered variable $\psi_k = u_k / z_A$ with $z_A = a = -1/(H\eta)$:

$$|\psi_k(\eta_k)|^2 = \frac{|u_k(\eta_k)|^2}{a^2(\eta_k)} \tag{22}$$

Using (21) evaluated near $|k\eta| = 1$:

$$|\psi_k|_\text{freeze}^2 \approx \frac{2^{2\nu - 3}\,\Gamma(\nu)^2}{\pi}\,\frac{H^2}{c_s k^3}\,(1 + \mathcal{O}(\beta)) \tag{23}$$

---

## 6. Scale Invariance

The dimensionless power spectrum of $\psi$ is

$$\Delta_\psi^2(k) \equiv \frac{k^3}{2\pi^2}\,P_\psi(k) = \frac{k^3}{2\pi^2} \times 2|\psi_k|^2 \tag{24}$$

Substituting (23):

$$\Delta_\psi^2(k) = \frac{2^{2\nu-2}\,\Gamma(\nu)^2}{\pi^3}\,\frac{H^2}{c_s}\,(k^{n_s - 1}) \tag{25}$$

where

$$n_s - 1 = 3 - 2\nu \tag{26}$$

**For the massless case** $\beta = 0$: $\nu = 3/2$, so $n_s - 1 = 0$.

The power spectrum is exactly scale invariant:

$$\Delta_\psi^2(k)\big|_{\beta=0} = \frac{H^2}{2\pi^2 c_s} = \text{const} \tag{27}$$

This is the main result: **scale invariance is not a statistical hypothesis but a consequence of the Bunch–Davies vacuum and the de Sitter freeze-out mechanism**, applied to the horizon field through the comoving mode identification (2).

The two-point function in position space follows directly from (27):

$$\langle\phi(x)\phi(0)\rangle \sim \frac{1}{|x|^{2\nu}} = \frac{1}{|x|^3} \quad (\beta = 0) \tag{28}$$

recovering equation (29) of the formalization document with $\alpha = 3$ as a consequence of $\nu = 3/2$.

---

## 7. Spectral Tilt

### 7.1 Mass correction

For $m_\text{eff}^2 = \beta H^2$ with $|\beta| \ll 1$:

$$\nu = \sqrt{\frac{9}{4} - \beta} \approx \frac{3}{2} - \frac{\beta}{3} \tag{29}$$

The spectral index:

$$n_s - 1 = 3 - 2\nu \approx 3 - \left(3 - \frac{2\beta}{3}\right) = \frac{2\beta}{3} \tag{30}$$

A positive effective mass $\beta > 0$ gives a mild blue tilt; a slightly tachyonic horizon field $\beta < 0$ gives a red tilt consistent with observations.

### 7.2 Slow-roll correction

When $H$ varies slowly ($\varepsilon \ll 1$, $|\dot{\varepsilon}| \ll H\varepsilon$), the effective potential receives corrections:

$$\frac{z_A''}{z_A} = \frac{1}{\eta^2}\left(2 + 3\varepsilon + \cdots\right) \tag{31}$$

leading to

$$\nu \approx \frac{3}{2} + \varepsilon - \frac{\beta}{3} \tag{32}$$

and

$$n_s - 1 \approx -2\varepsilon + \frac{2\beta}{3} \tag{33}$$

The observed red tilt $n_s \approx 0.965$ is reproduced for $\varepsilon \approx 0.02$ with $\beta \approx 0$, or for a combination of non-zero $\varepsilon$ and $\beta$.

### 7.3 Comparison with Document 5

Equation (33) of the formalization document originally stated $n_s - 1 \approx -2\beta$ without derivation. From the present analysis, this corresponds to the parameterization

$$\nu \equiv \frac{3}{2} + \beta_\nu \quad \Longrightarrow \quad n_s - 1 = -2\beta_\nu \tag{34}$$

where $\beta_\nu = \varepsilon - \beta/3$ combines the slow-roll parameter and the mass correction. The formula (33) of Document 5 is recovered with the identification $\beta \to \beta_\nu$: a compound parameter capturing both slow variation of the horizon and the effective mass of $\phi$.

---

## 8. Physical Picture

The derivation admits a clean physical interpretation.

At early times, each comoving mode $k$ sits at large $l_k \gg 1$ on the horizon. Its frequency $\omega_l = c_s l H \gg H$ places it in the oscillatory regime, well approximated by the Minkowski vacuum (19).

As the universe expands, $l_k(t) = k\,e^{-Ht}/H$ decreases. When $l_k \to 1$ (freeze-out), the mode's physical wavelength reaches the Hubble scale. At this moment, the quantum uncertainty in $\phi_l$ becomes classical: the mode's amplitude is fixed by the vacuum fluctuation $\langle|\phi_l|^2\rangle \sim H^2 / \omega_l \sim H$ (at $l = 1$).

Since $H$ is the same for all modes at freeze-out in de Sitter, every mode acquires the same amplitude regardless of $k$. This is the origin of scale invariance: it is a consequence of the time-translation symmetry of de Sitter combined with the fact that freeze-out always occurs at $l_k = 1$.

---

## 9. Connection to Document 5

This document replaces two open items in the formalization:

| Item | Original Document 5 status | Present status |
|------|---------------------------|----------------|
| Eq. (29): $\langle\phi(x)\phi(0)\rangle \sim |x|^{-\alpha}$ | Minimal statistical hypothesis | Derived from BD vacuum: $\alpha = 2\nu = 3 - (n_s - 1)$ |
| Eq. (33): $n_s - 1 \approx -2\beta$ | Analogy with de Sitter scalar | Derived: $n_s - 1 = 3 - 2\nu$, with $\nu(\beta, \varepsilon)$ from eq. (32) |

The derivation uses the action (23) of Document 5 without modification. The only additional ingredient is the comoving mode identification (2) and the Bunch–Davies initial condition (19).

---

## 10. Open Problems

The following gaps remain:

- **Slow-roll evolution of $m_\text{eff}$.** The relation $m_\text{eff}^2 = \beta H^2$ is assumed constant. A dynamical model relating $\beta$ to the matter content would make (33) predictive.

- **Microscopic origin.** The Bunch–Davies vacuum is imposed as a natural UV condition; its justification from a microscopic model of horizon degrees of freedom remains open.

The two gaps listed in the original version of this section have since been closed: the gauge-invariant identification $\mathcal{R} = [(1+\varepsilon)/\varepsilon]\psi$ was derived exactly in Step 2, and the tensor power spectrum was derived from horizon boundary modes in Step 7.

---

## 11. Conclusion

Canonical quantization of the horizon field $\phi(\Omega, t)$, combined with the comoving mode identification $l_k(t) = k/(a(t)H(t))$, produces a mode equation of Mukhanov–Sasaki form. With Bunch–Davies initial conditions, this equation generates a scale-invariant power spectrum at freeze-out as a derived result. The spectral tilt is $n_s - 1 = 3 - 2\nu$, with $\nu$ controlled by the effective mass $m_\text{eff}^2 = \beta H^2$ and the slow-roll parameter $\varepsilon$. The two central open problems of Document 5 — equations (29) and (33) — are closed.

---

## References

1. V. Mukhanov and G. Chibisov, "Quantum fluctuations and a nonsingular universe," *JETP Lett.* **33**, 532 (1981).
2. S. W. Hawking, "The development of irregularities in a single bubble inflationary universe," *Phys. Lett. B* **115**, 295 (1982).
3. V. F. Mukhanov, H. A. Feldman, and R. H. Brandenberger, "Theory of cosmological perturbations," *Phys. Rep.* **215**, 203 (1992).
4. R.-G. Cai and S. P. Kim, "First law of thermodynamics and Friedmann equations of Friedmann-Robertson-Walker universe," *JHEP* **0502**, 050 (2005).
5. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Causal Horizon Framework, Document 5 (2025).
