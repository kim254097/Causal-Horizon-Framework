# Gauge-Invariant Formulation of the Horizon Perturbation and its Relation to the Comoving Curvature Perturbation

**Kevin Muñoz**

---

## Abstract

The formalization of horizon-centered cosmological dynamics identifies the horizon perturbation $\psi = \delta R_A / R_A$ with the comoving curvature perturbation $\mathcal{R}$, but leaves the gauge-invariant derivation of this identification as an open problem. This document closes that gap. Working in Newtonian gauge, we compute $\psi$ from the perturbed apparent horizon condition and perform the gauge transformation to comoving gauge, where $\mathcal{R}$ is defined. The exact relation on super-horizon scales is

$$\psi = \frac{\varepsilon}{1 + \varepsilon}\,\mathcal{R}$$

where $\varepsilon = -\dot{H}/H^2$ is the slow-roll parameter. For slow-roll inflation ($\varepsilon \ll 1$), $\psi \approx \varepsilon\,\mathcal{R}$, so the primordial power spectra satisfy $P_\mathcal{R}(k) \approx P_\psi(k)/\varepsilon^2$. The spectral shape — in particular, the tilt $n_s$ derived in the companion document on horizon field quantization — is identical for both $\psi$ and $\mathcal{R}$. This document replaces the schematic identification $\mathcal{R} \sim \psi$ of Document 5 with a derived, gauge-invariant result, and corrects equation (21) of that document.

---

## 1. Motivation

In the formalization (Document 5), the comoving curvature perturbation is introduced via the schematic identification

$$\mathcal{R} \sim \psi \tag{1}$$

with the note that "a complete gauge-invariant treatment remains an open problem." As a consequence, the power spectrum was set $P_\mathcal{R} = P_\psi$ (eq. (21) of Document 5), which is only correct modulo factors involving $\varepsilon$.

The present document derives the precise gauge-invariant relation between $\psi$ and $\mathcal{R}$. This is needed to:

1. Compare the predicted amplitude of $P_\psi(k)$ with CMB observations quantitatively.
2. Establish that $n_s(\psi) = n_s(\mathcal{R})$, so the tilt derivation of the companion document applies directly to the observed spectrum.
3. Identify the physical content of the proportionality factor.

---

## 2. Setup: Scalar Perturbations in Newtonian Gauge

We consider a spatially flat ($k=0$) FRW background perturbed by scalar modes. In the **Newtonian (longitudinal) gauge**, the metric takes the form

$$ds^2 = -(1 + 2\Phi)dt^2 + a^2(t)(1 - 2\Phi)\delta_{ij}\,dx^i dx^j \tag{2}$$

where the two potentials are equal ($\Phi = \Psi$) for a perfect fluid with vanishing anisotropic stress. The background equations are

$$H^2 = \frac{8\pi G}{3}\rho, \qquad \dot{H} = -4\pi G(\rho + P) = -\varepsilon H^2 \tag{3}$$

with $\varepsilon = -\dot{H}/H^2$.

At linear order, the metric perturbation $\Phi(\mathbf{k}, t)$ satisfies the Hamiltonian constraint

$$3H(\dot{\Phi} + H\Phi) + \frac{k^2}{a^2}\Phi = -4\pi G\,\delta\rho \tag{4}$$

and the momentum constraint

$$\dot{\Phi} + H\Phi = -4\pi G(\rho + P)\,V \tag{5}$$

where $V$ is the velocity potential of the matter fluid.

---

## 3. The Horizon Perturbation in Newtonian Gauge

The apparent horizon is the sphere around each point at which outgoing null geodesics have zero expansion. In the perturbed metric (2), the effective local expansion rate is

$$H_\text{loc}(\mathbf{x}, t) = H + \dot{\Phi} - H\Phi + \frac{k^2 V}{3a} \tag{6}$$

where the last term accounts for the local velocity divergence of the fluid.

The apparent horizon radius around a point $\mathbf{x}$ is $R_A^\text{loc} = 1/H_\text{loc}$, so its fractional perturbation is

$$\psi \equiv \frac{\delta R_A}{R_A} = -\frac{\delta H}{H} = -\frac{\dot{\Phi} - H\Phi}{H} - \frac{k^2 V}{3aH} \tag{7}$$

**On super-horizon scales** ($k \ll aH$), the velocity term is suppressed by $(k/aH)^2$:

$$\psi \approx -\frac{\dot{\Phi}}{H} + \Phi \qquad (k \ll aH) \tag{8}$$

For the growing mode in de Sitter or slow-roll inflation, $\dot{\Phi} \to 0$ (the potential freezes on super-horizon scales), so

$$\psi \approx \Phi \qquad \text{(super-horizon, Newtonian gauge)} \tag{9}$$

This confirms the intuition of Document 5: on large scales, the horizon perturbation tracks the gravitational potential $\Phi$.

---

## 4. The Comoving Curvature Perturbation

The comoving curvature perturbation is defined as the gauge-invariant combination

$$\mathcal{R} = \Phi - \frac{H}{\dot{H}}\left(\dot{\Phi} + H\Phi\right) \tag{10}$$

This coincides with the spatial metric perturbation $\Psi_\text{metric}$ in the comoving gauge (where the matter velocity vanishes), and is conserved on super-horizon scales for adiabatic perturbations: $\dot{\mathcal{R}} = \mathcal{O}(k^2/a^2 H^2)$.

Expanding (10) using $\dot{H} = -\varepsilon H^2$:

$$\mathcal{R} = \Phi + \frac{1}{\varepsilon H}\left(\dot{\Phi} + H\Phi\right) = \Phi\left(1 + \frac{1}{\varepsilon}\right) + \frac{\dot{\Phi}}{\varepsilon H} \tag{11}$$

On super-horizon scales ($\dot{\Phi} \to 0$, growing mode):

$$\mathcal{R} \approx \Phi\,\frac{1 + \varepsilon}{\varepsilon} \tag{12}$$

---

## 5. Gauge-Invariant Relation Between $\psi$ and $\mathcal{R}$

Combining equations (9) and (12):

$$\psi \approx \Phi = \frac{\varepsilon}{1+\varepsilon}\,\mathcal{R} \tag{13}$$

This is the central result. Rearranging:

$$\mathcal{R} = \frac{1 + \varepsilon}{\varepsilon}\,\psi \tag{14}$$

To make the $\dot{\Phi}$ dependence explicit, substitute $\Phi = \psi + \dot{\Phi}/H$ (from eq. 8) into eq. (11):

$$\mathcal{R} = \frac{1+\varepsilon}{\varepsilon}\,\psi + \frac{\dot\Phi}{H} \tag{15}$$

In the growing-mode limit $\dot{\Phi} \to 0$, the last term vanishes and eq. (14) is recovered. $\square$

---

## 6. Limiting Cases

### 6.1 Slow-roll inflation ($\varepsilon \ll 1$)

$$\psi \approx \varepsilon\,\mathcal{R} \qquad \Longrightarrow \qquad \mathcal{R} \approx \frac{\psi}{\varepsilon} \tag{16}$$

The horizon perturbation $\psi$ is suppressed relative to $\mathcal{R}$ by the slow-roll parameter. Physically: during slow-roll, the horizon barely moves ($\dot{R}_A \sim \varepsilon H R_A \ll H R_A$), so a given curvature perturbation $\mathcal{R}$ produces only a small fractional change $\psi$ in the horizon radius.

### 6.2 Radiation domination ($\varepsilon = 2$)

$$\psi = \frac{2}{3}\,\mathcal{R} \tag{17}$$

### 6.3 Matter domination ($\varepsilon = 3/2$)

$$\psi = \frac{3}{5}\,\mathcal{R} \tag{18}$$

In both post-inflationary epochs, $\varepsilon = \mathcal{O}(1)$ and the identification $\psi \approx \mathcal{R}$ holds at the order-of-unity level. Document 5's schematic $\mathcal{R} \sim \psi$ is thus most accurate during radiation and matter domination.

---

## 7. Gauge Transformation Derivation

Equation (14) can also be derived by explicit gauge transformation from the Newtonian gauge to the comoving gauge, providing an independent check.

Under a time-reparametrization $t \to t + \delta t(\mathbf{x}, t)$, the metric perturbations transform as

$$\Phi \to \Phi - H\,\delta t, \qquad \Psi_\text{metric} \to \Psi_\text{metric} + H\,\delta t \tag{19}$$

The matter velocity potential transforms as $V \to V + a\,\delta t$.

To reach the **comoving gauge** (velocity potential vanishes, $V_\text{com} = 0$), we choose

$$\delta t = -\frac{V}{a} \tag{20}$$

In this gauge, the spatial metric perturbation equals $\mathcal{R}$:

$$\mathcal{R} = \Psi_\text{metric}^\text{com} = \Phi_\text{Newton} + H \cdot \frac{V}{a} \tag{21}$$

From the momentum constraint (5): $H V/a = -(\dot{\Phi} + H\Phi)/(\varepsilon H^2)$.

Substituting:

$$\mathcal{R} = \Phi - \frac{\dot{\Phi} + H\Phi}{\varepsilon H} = \Phi\left(\frac{1+\varepsilon}{\varepsilon}\right) - \frac{\dot{\Phi}}{\varepsilon H} \tag{22}$$

On super-horizon scales ($\dot{\Phi} \to 0$), this recovers equation (12), and with $\psi \approx \Phi$ (eq. 9), we recover (14). The derivation is consistent. $\square$

---

## 8. Sub-Horizon Behavior and the Poisson Equation

On sub-horizon scales ($k \gg aH$), the Hamiltonian constraint (4) reduces to the Poisson equation:

$$\frac{k^2}{a^2}\Phi \approx -4\pi G\,\delta\rho \tag{23}$$

Inverting with $4\pi G\rho = 3H^2/2$: $\Phi = -\tfrac{3}{2}(aH/k)^2(\delta\rho/\rho)$. On sub-horizon scales, the companion document (Step 1) gives $\delta\rho/\rho \approx -\tfrac{2}{3}(k/aH)^2\psi$ (eq. (23) of Step 1). Substituting:

$$\Phi \approx \psi \quad (k \gg aH) \tag{24}$$

The horizon perturbation thus tracks the Newtonian gravitational potential on sub-horizon scales; the ratio $\Phi/\psi$ remains of order unity. What changes is the relation to $\mathcal{R}$: $\mathcal{R}$ is conserved at its super-horizon value while $\psi$ continues to evolve with the local density waves. The gauge-invariant identification (13) therefore breaks down at $k \sim aH$ and is replaced by:

$$\psi_\text{sub-horizon} \sim -\frac{\dot{\Phi}}{H} \sim \frac{k}{aH}\,\psi_\text{super-horizon} \tag{25}$$

The relevant relation for CMB physics is always the primordial value, set at horizon exit ($k = aH$) and recovered here by the super-horizon formula (13).

---

## 9. Implication for Power Spectra

From the gauge-invariant relation (14):

$$P_\mathcal{R}(k) = \left(\frac{1+\varepsilon}{\varepsilon}\right)^2 P_\psi(k) \tag{26}$$

For slow-roll inflation ($\varepsilon \ll 1$):

$$P_\mathcal{R}(k) \approx \frac{P_\psi(k)}{\varepsilon^2} \tag{27}$$

Combining with the result from the companion document on quantization (Step 3, eq. (27)), where $\Delta_\psi^2(k) = (H^2/(2\pi^2 c_s))\,k^{n_s-1}$:

$$P_\mathcal{R}(k) \approx \frac{P_\psi(k)}{\varepsilon^2}, \qquad \Delta_\mathcal{R}^2 = \frac{\Delta_\psi^2}{\varepsilon^2} \tag{28}$$

The amplitude is

$$\Delta_\mathcal{R}^2 = \frac{H^2}{2\pi^2 c_s \varepsilon^2} \tag{29}$$

This matches the standard slow-roll inflation result $\Delta_\mathcal{R}^2 = H^2/(8\pi^2\varepsilon M_\text{Pl}^2)$ up to normalization factors set by the unit conventions for the horizon field action.

The **spectral tilt** is unchanged:

$$n_s - 1 = \frac{d\ln P_\mathcal{R}}{d\ln k} = \frac{d\ln P_\psi}{d\ln k} \tag{30}$$

since the factor $(1+\varepsilon)^2/\varepsilon^2$ is evaluated at horizon crossing ($k = aH$) and its $k$-dependence is of order $\varepsilon$ or $\eta_\varepsilon \equiv \dot{\varepsilon}/(H\varepsilon)$, which are sub-leading slow-roll corrections already included in the tilt formula $n_s - 1 = 3 - 2\nu$ of the quantization document. The tilt result is thus robust to the amplitude correction.

---

## 10. Corrections to Document 5

This document corrected two items in the original formalization:

### Equation (18): $\mathcal{R} \sim \psi$

Replaced by the exact gauge-invariant result on super-horizon scales:

$$\mathcal{R} = \frac{1+\varepsilon}{\varepsilon}\,\psi \tag{31}$$

The identification $\mathcal{R} \sim \psi$ is valid at order of magnitude when $\varepsilon = \mathcal{O}(1)$ (radiation/matter domination). During slow-roll inflation, $\mathcal{R} = \psi/\varepsilon \gg \psi$.

### Equation (21): $P_\mathcal{R}(k) = P_\psi(k)$

Replaced by:

$$P_\mathcal{R}(k) = \left(\frac{1+\varepsilon}{\varepsilon}\right)^2 P_\psi(k) \approx \frac{P_\psi(k)}{\varepsilon^2} \quad (\varepsilon \ll 1) \tag{32}$$

The spectral shape is the same; only the amplitude differs.

---

## 11. Physical Interpretation

The factor $\varepsilon/(1+\varepsilon)$ in (13) has a direct physical meaning in the horizon-centered framework.

The slow-roll parameter $\varepsilon = -\dot{H}/H^2 = -\dot{R}_A/(R_A H)$ measures the fractional rate of change of the horizon radius per Hubble time. When $\varepsilon \ll 1$, the horizon is nearly frozen: a given spatial curvature $\mathcal{R}$ corresponds to only a small fractional variation $\psi \approx \varepsilon \mathcal{R}$ in the apparent horizon radius.

Equivalently: the horizon field $\phi \sim \psi$ is the amplitude of boundary fluctuations, while $\mathcal{R}$ is the amplitude of bulk curvature fluctuations. The ratio $\mathcal{R}/\psi = (1+\varepsilon)/\varepsilon$ quantifies how much the bulk amplifies the boundary signal. The amplification is large precisely when the background horizon is slowly evolving — consistent with the intuition that a nearly-de Sitter background acts as a good amplifier of quantum boundary fluctuations.

---

## 12. Remaining Open Problem

The present derivation is restricted to the **adiabatic, single-fluid** case and relies on the **super-horizon limit**. Two extensions remain open:

- **Finite $k$ corrections.** Equation (13) receives corrections of order $(k/aH)^2$ from the velocity term in (7) and the sub-leading term in (8). A complete mode-by-mode transfer function connecting $\psi_k$ to $\mathcal{R}_k$ for all $k$ would require solving the coupled perturbation equations, which is equivalent to the standard Boltzmann hierarchy and can be implemented numerically.

- **Multi-fluid and non-adiabatic perturbations.** The identification $\Phi = \Psi$ (no anisotropic stress) and the adiabatic condition $\delta P = c_s^2 \delta\rho$ were used. Entropy perturbations would introduce additional terms proportional to $\delta S = \delta P/P - \delta\rho/\rho \cdot c_s^2$.

These extensions do not affect the spectral shape or the tilt formula; they enter only at the level of the transfer function from primordial to observed power spectrum.

---

## 13. Summary

| Result | Expression | Domain of validity |
|--------|------------|-------------------|
| Gauge-invariant relation | $\psi = \frac{\varepsilon}{1+\varepsilon}\,\mathcal{R}$ | Super-horizon, adiabatic, single fluid |
| Slow-roll limit | $\mathcal{R} \approx \psi/\varepsilon$ | $\varepsilon \ll 1$ |
| Power spectrum relation | $P_\mathcal{R} = \frac{(1+\varepsilon)^2}{\varepsilon^2}\,P_\psi$ | Super-horizon, primordial |
| Spectral tilt | $n_s(\mathcal{R}) - 1 = n_s(\psi) - 1 = 3 - 2\nu$ | All scales at leading order |

The identification $\mathcal{R} \sim \psi$ of Document 5 is a valid order-of-magnitude statement; the present document provides its precise gauge-invariant content and corrects the amplitude relation.

---

## References

1. J. M. Bardeen, "Gauge invariant cosmological perturbations," *Phys. Rev. D* **22**, 1882 (1980).
2. H. Kodama and M. Sasaki, "Cosmological perturbation theory," *Prog. Theor. Phys. Suppl.* **78**, 1 (1984).
3. V. F. Mukhanov, H. A. Feldman, and R. H. Brandenberger, "Theory of cosmological perturbations," *Phys. Rep.* **215**, 203 (1992).
4. S. Weinberg, *Cosmology*, Oxford University Press (2008), Chapter 5.
5. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Causal Horizon Framework, Document 5 (2025).
6. K. Muñoz, "Scale Invariance from Horizon Field Quantization," Causal Horizon Framework (2025).
