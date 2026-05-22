# A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations

**Kevin Muñoz**

---

## Abstract

We develop a horizon-centered formalization of cosmological dynamics and perturbations in which the apparent horizon is treated as the primary physical degree of freedom. Building on a previously introduced conceptual framework, we show that standard Friedmann dynamics can be recovered from horizon thermodynamics and that cosmological perturbations may be consistently described as fluctuations of the causal boundary.

We derive a closed linear perturbation pipeline linking horizon fluctuations to density perturbations and to the comoving curvature perturbation. Under minimal statistical assumptions, the framework reproduces a nearly scale-invariant spectrum compatible with observations. The approach remains fully consistent with General Relativity and standard phenomenology, while providing a boundary-based interpretation of cosmological evolution.

---

## 1. Introduction

Standard cosmology describes the universe in terms of bulk spacetime dynamics governed by General Relativity, with expansion encoded in the scale factor $a(t)$. Horizons are typically treated as derived structures.

In contrast, horizon thermodynamics suggests that causal boundaries encode physically relevant information, with entropy scaling with area rather than volume. This motivates alternative perspectives in which causal horizons play a structurally primary role.

The present work provides a formal realization of a horizon-centered framework in which cosmological dynamics and perturbations are described in terms of the apparent horizon. The goal is not to modify General Relativity, but to reformulate its cosmological content in terms of causal accessibility and boundary thermodynamics.

The thermodynamic recovery of the Friedmann equation in Section 3 follows the approach of Cai and Kim (2005), who first demonstrated this derivation for FRW apparent horizons. The present work extends this by developing a perturbation pipeline — linking horizon fluctuations to density perturbations and spectral structure (Sections 4–11) — not addressed in prior thermodynamic gravity literature.

---

## 2. Background Geometry and Horizon Variable

We consider a homogeneous and isotropic spacetime with Hubble parameter:

$$H = \frac{\dot{a}}{a} \tag{1}$$

The apparent horizon radius is:

$$R_A = \frac{1}{\sqrt{H^2 + \frac{k}{a^2}}} \tag{2}$$

For spatially flat geometry ($k = 0$):

$$R_A = \frac{1}{H} \tag{3}$$

We take $R_A(t)$ as the fundamental variable, interpreting cosmological evolution as the growth of a causally accessible domain.

---

## 3. Horizon Thermodynamics and Background Dynamics

We assign thermodynamic quantities to the horizon:

$$S = \frac{A}{4G} = \frac{\pi R_A^2}{G} \tag{4}$$

$$T = \frac{1}{2\pi R_A} \tag{5}$$

$$V = \frac{4}{3}\pi R_A^3 \tag{6}$$

$$E = \rho V \tag{7}$$

We impose the first law:

$$dE = T\,dS - P\,dV \tag{8}$$

Using energy conservation:

$$\dot{\rho} + 3H(\rho + P) = 0 \tag{9}$$

and $R_A = 1/H$, we obtain:

$$\dot{H} = -4\pi G(\rho + P) \tag{10}$$

which integrates to:

$$H^2 = \frac{8\pi G}{3}\rho + C \tag{11}$$

Thus, standard Friedmann dynamics are recovered from horizon thermodynamics. For spatially flat geometry ($k = 0$), the integration constant $C$ vanishes, recovering the standard flat Friedmann equation $H^2 = \frac{8\pi G}{3}\rho$. All subsequent perturbation analysis assumes this flat case.

---

## 4. Perturbations of the Horizon

We introduce perturbations in the horizon radius:

$$R_A(t, \mathbf{x}) = \bar{R}_A(t)\left[1 + \psi(t, \mathbf{x})\right] \tag{12}$$

where:

$$\psi = \frac{\delta R_A}{R_A} \tag{13}$$

is dimensionless and treated as the fundamental perturbation variable.

---

## 5. Relation to Expansion and Density Perturbations

Using $H = 1/R_A$, we obtain at linear order:

$$\frac{\delta H}{H} = -\psi \tag{14}$$

From the Friedmann equation (the Gauss constraint for the FRW Cauchy hypersurface, $H^2 = 8\pi G\rho/3$):

$$H^2 \propto \rho \tag{15}$$

the linearized Gauss constraint (see companion document *The Boundary–Bulk Relation from Gauss–Codazzi*) gives, in the super-horizon limit ($k \ll aH$):

$$\frac{\delta\rho}{\rho} = -2\psi\!\left(1 + \frac{1}{3}\!\left(\frac{k}{aH}\right)^{\!2}\right) \approx -2\psi \tag{16}$$

The leading term $\delta\rho/\rho = -2\psi$ is exact for $k \ll aH$ (separate-universe limit). The sub-horizon extension gives the Poisson equation $\delta\rho/\rho \approx -(2/3)(k/aH)^2\psi$ for $k \gg aH$. Thus:

$$\delta\rho \propto \psi \tag{17}$$

---

## 6. Relation to the Curvature Perturbation

The gauge-invariant relation between $\psi$ and the comoving curvature perturbation, derived in the companion document *Gauge-Invariant Formulation of the Horizon Perturbation*, is exact on super-horizon scales:

$$\mathcal{R} = \frac{1+\varepsilon}{\varepsilon}\,\psi \tag{18}$$

where $\varepsilon = -\dot{H}/H^2$. For slow-roll inflation ($\varepsilon \ll 1$), $\mathcal{R} \approx \psi/\varepsilon$; during radiation and matter domination ($\varepsilon = \mathcal{O}(1)$), $\mathcal{R} \approx \psi$ at order of magnitude. The schematic $\mathcal{R} \sim \psi$ holds as an order-of-magnitude statement in post-inflationary epochs.

---

## 7. Statistical Description

We assume Gaussian statistics:

$$\langle\psi(\mathbf{k})\psi(\mathbf{k}')\rangle = (2\pi)^3\delta(\mathbf{k} + \mathbf{k}')P_\psi(k) \tag{19}$$

with:

$$P_\psi(k) = Ak^{n_s - 1} \tag{20}$$

The primordial power spectra are related by (see companion document):

$$P_\mathcal{R}(k) = \left(\frac{1+\varepsilon}{\varepsilon}\right)^2 P_\psi(k) \approx \frac{P_\psi(k)}{\varepsilon^2} \quad (\varepsilon \ll 1) \tag{21}$$

The spectral shape is identical; only the amplitude differs by the factor $[(1+\varepsilon)/\varepsilon]^2$.

---

## 8. Effective Horizon Field

We introduce an effective scalar field defined on the horizon:

$$\phi(\Omega, t) \tag{22}$$

with action:

$$S = \int dt\, d\Omega\, R_A^2 \left[(\partial_t\phi)^2 + \frac{c_s^2}{R_A^2}(\nabla_\Omega\phi)^2 + m_\text{eff}^2\phi^2\right] \tag{23}$$

and identify:

$$\psi \sim \phi \tag{24}$$

---

## 9. Mode Structure and Freeze-out

Expanding in spherical harmonics:

$$\phi = \sum_{l,m} \phi_{lm}(t) Y_{lm}(\Omega) \tag{25}$$

the mode frequency is:

$$\omega_l^2 = \frac{c_s^2}{R_A^2}l(l+1) + m_\text{eff}^2 \tag{26}$$

Modes freeze when:

$$\omega \sim H \tag{27}$$

Using $R_A = 1/H$, this yields:

$$l \sim kR_A \tag{28}$$

---

## 10. Spectrum

Canonical quantization of $\phi$ with Bunch–Davies initial conditions, combined with the comoving mode identification $l_k(t) = k/(a(t)H(t))$, yields a mode equation of Mukhanov–Sasaki form (see companion document: *Scale Invariance from Horizon Field Quantization*). The resulting two-point function is:

$$\langle\phi(x)\phi(0)\rangle \sim \frac{1}{|x|^{2\nu}} \tag{29}$$

with $\nu$ determined by the effective potential (eq. (15) of the companion document). For the massless de Sitter case, $\nu = 3/2$, so $\alpha = 2\nu = 3$.

This yields:

$$P(k) \sim k^{3 - 2\nu} \tag{30}$$

For $\nu = 3/2$ (massless, de Sitter):

$$n_s = 1 \tag{31}$$

Introducing:

$$m_\text{eff}^2 = \beta H^2 \tag{32}$$

and including the slow-roll parameter $\varepsilon = -\dot{H}/H^2 = \frac{1}{2}\frac{d\ln S}{d\ln a}$:

$$n_s - 1 = 3 - 2\nu \approx -2\varepsilon + \frac{2\beta}{3} \tag{33}$$

For the minimal horizon field ($\beta = 0$, from the two-dimensional conformal structure of the action), this reduces to

$$n_s - 1 = -\frac{d\ln S}{d\ln a} \tag{33a}$$

where $S = \pi R_A^2/G$ is the horizon entropy. The tilt equals minus the fractional growth rate of the horizon entropy per e-fold. The full derivation of $\varepsilon$ and $\beta$ from intrinsic horizon quantities is given in the companion document *Spectral Tilt from Horizon Thermodynamics*.

---

## 11. Connection to Observables

The angular power spectrum is given by:

$$C_\ell = 4\pi \int \frac{dk}{k} P_\mathcal{R}(k) |\Delta_\ell(k)|^2 \tag{34}$$

with:

$$\ell \sim kr_* \tag{35}$$

---

## 12. Interpretation

The framework provides a dual description:

- **Standard:** bulk fields generate perturbations
- **Horizon-centered:** boundary fluctuations encode perturbations

---

## 13. Limitations and Open Problems

- No microscopic model of horizon degrees of freedom
- Gauge-invariant relation $\mathcal{R} = [(1+\varepsilon)/\varepsilon]\,\psi$ and amplitude correction $P_\mathcal{R} \approx P_\psi/\varepsilon^2$ derived in companion document *Gauge-Invariant Formulation of the Horizon Perturbation*
- Scale-invariant spectrum (eq. 29) and spectral tilt (eq. 33) derived from canonical quantization and Bunch–Davies initial conditions in *Scale Invariance from Horizon Field Quantization*
- Tilt expressed as horizon entropy rate $n_s - 1 = -(d\ln S)/(d\ln a)$ and effective mass derived from 2D conformal structure in *Spectral Tilt from Horizon Thermodynamics*
- Tensor perturbations derived in *Tensor Perturbations from the Horizon Boundary*: $n_T = -2\varepsilon$, $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$, $r = 16\varepsilon$, minimal CHF excluded at 95% CL; $\beta_S < -0.042$ required
- Remaining open: dynamical determination of $\varepsilon$ from within the framework; sub-horizon transfer function

---

## 14. Conclusion

We have constructed a horizon-centered formalization of cosmological dynamics and perturbations that reproduces standard results while providing a boundary-based interpretation. The framework is compatible with General Relativity and observational data, and identifies a clear set of open problems for future development.

---

## References

1. J. D. Bekenstein, "Black holes and entropy," *Phys. Rev. D* **7**, 2333 (1973).
2. S. W. Hawking, "Particle creation by black holes," *Commun. Math. Phys.* **43**, 199 (1975).
3. G. W. Gibbons and S. W. Hawking, "Cosmological event horizons, thermodynamics, and particle creation," *Phys. Rev. D* **15**, 2738 (1977).
4. T. Jacobson, "Thermodynamics of spacetime: The Einstein equation of state," *Phys. Rev. Lett.* **75**, 1260 (1995).
5. R.-G. Cai and S. P. Kim, "First law of thermodynamics and Friedmann equations of Friedmann-Robertson-Walker universe," *JHEP* **0502**, 050 (2005).
6. T. Padmanabhan, "Thermodynamical aspects of gravity: New insights," *Phys. Rep.* **531**, 115 (2013).
7. V. Mukhanov, *Physical Foundations of Cosmology*, Cambridge University Press (2005).
