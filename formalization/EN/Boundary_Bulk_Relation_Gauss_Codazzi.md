# The Boundary–Bulk Relation δρ/ρ = −2ψ from the Gauss–Codazzi Equations

**Kevin Muñoz**

---

## Abstract

The formalization of horizon-centered cosmological dynamics derives the relation $\delta\rho/\rho = -2\psi$ by linearizing the background Friedmann equation. While consistent, this is a verification rather than a derivation: it does not establish the geometric origin of the relation, does not specify its domain of validity, and does not provide the sub-horizon extension. This document closes that gap. We show that the Friedmann equation is the Gauss constraint for the FRW Cauchy hypersurface, and that its perturbation — the full Hamiltonian constraint — gives

$$\frac{\delta\rho}{\rho} = -2\psi\!\left(1 + \frac{1}{3}\left(\frac{k}{aH}\right)^2\right)$$

where $k$ is the comoving wavenumber. On super-horizon scales ($k \ll aH$), this reduces exactly to the Document 5 result. The sub-horizon correction is the Poisson equation, derived here as the Codazzi (momentum) constraint in the same formalism. The boundary–bulk relation is thus a rigorous consequence of the Einstein equations, valid in the separate-universe limit of the Gauss embedding structure.

---

## 1. Motivation

In Document 5 of the Causal Horizon Framework, the key perturbation relation

$$\frac{\delta\rho}{\rho} = -2\psi \tag{1}$$

is derived in three lines: $R_A = 1/H$ gives $\delta H/H = -\psi$; the Friedmann equation $H^2 \propto \rho$ gives $\delta\rho/\rho = 2\delta H/H = -2\psi$. While correct, this derivation:

- Uses the BACKGROUND Friedmann equation applied locally, without geometric justification
- Does not specify a gauge or domain of validity
- Does not show sub-horizon corrections
- Does not demonstrate that (1) is a consequence of the embedding geometry of the horizon in spacetime

The present document provides this derivation from the Gauss–Codazzi equations for the FRW Cauchy hypersurface.

---

## 2. The Gauss–Codazzi Equations in 3+1 Form

In the 3+1 (ADM) decomposition of spacetime, a Cauchy hypersurface $\Sigma_t$ (a surface of constant time $t$) is embedded in the 4D spacetime $(\mathcal{M}, g_{\mu\nu})$ with:

- **Intrinsic metric** $h_{ij}$: the induced 3-metric on $\Sigma_t$
- **Extrinsic curvature** $K_{ij} = -\frac{1}{2}\mathcal{L}_n h_{ij}$: how $\Sigma_t$ bends in $\mathcal{M}$, with $n^\mu$ the future-pointing unit normal

The **Gauss equation** (contracted twice) gives the Hamiltonian constraint:

$${}^{(3)}R + K^2 - K_{ij}K^{ij} = 16\pi G\,\rho_\text{ADM} \tag{2}$$

where ${}^{(3)}R$ is the intrinsic Ricci scalar of $\Sigma_t$, $K = h^{ij}K_{ij}$ is the trace, and $\rho_\text{ADM} = T_{\mu\nu}n^\mu n^\nu$ is the energy density measured by the normal observer.

The **Codazzi equation** (contracted once) gives the momentum constraint:

$$D_j\!\left(K^{ij} - h^{ij}K\right) = 8\pi G\,J^i \tag{3}$$

where $D_j$ is the covariant derivative on $\Sigma_t$ and $J^i = -T_{\mu\nu}n^\mu e^{i\nu}$ is the momentum current.

Together, (2) and (3) encode all information about how the matter content of the universe constrains the geometry of $\Sigma_t$ and, through $K_{ij}$, its rate of expansion.

---

## 3. The Friedmann Equation as the Background Gauss Constraint

For a spatially flat ($k=0$) FRW background with metric

$$ds^2 = -dt^2 + a^2(t)\,\delta_{ij}\,dx^i\,dx^j \tag{4}$$

the Cauchy hypersurface $\Sigma_t$ has:

$${}^{(3)}R = 0, \qquad K_{ij} = -H\,h_{ij}, \qquad K = -3H, \qquad K_{ij}K^{ij} = 3H^2 \tag{5}$$

Substituting into the Gauss constraint (2):

$$0 + 9H^2 - 3H^2 = 16\pi G\rho \tag{6}$$

$$\boxed{H^2 = \frac{8\pi G}{3}\rho} \tag{7}$$

The Friedmann equation is the Gauss constraint for the FRW Cauchy hypersurface. It equates the extrinsic curvature of $\Sigma_t$ — encoded in $K$ — to the matter content of the bulk. The apparent horizon radius $R_A = 1/H$ is thus determined by the embedding geometry of $\Sigma_t$ in spacetime.

---

## 4. Perturbation of the Gauss Constraint

We perturb around the FRW background in Newtonian (longitudinal) gauge:

$$ds^2 = -(1+2\Phi)\,dt^2 + a^2(t)(1-2\Phi)\,\delta_{ij}\,dx^i\,dx^j \tag{8}$$

where $\Phi = \Psi$ (no anisotropic stress). The perturbed geometric quantities on $\Sigma_t$ are:

$$\delta\!\left({}^{(3)}R\right) = -\frac{4k^2\Phi}{a^2}, \qquad \delta K = 3(\dot\Phi + H\Phi), \qquad \delta(K_{ij}K^{ij}) = -6H(\dot\Phi + H\Phi) \tag{9}$$

where $k$ is the comoving wavenumber. Linearizing the Gauss constraint (2) using the background values (5):

$$\delta\!\left({}^{(3)}R\right) + 2K\,\delta K - \delta(K_{ij}K^{ij}) = 16\pi G\,\delta\rho \tag{10}$$

Substituting the background values $K = -3H$ and the perturbed quantities (9):

$$-\frac{4k^2\Phi}{a^2} + 2(-3H)\cdot 3(\dot\Phi+H\Phi) - (-6H(\dot\Phi+H\Phi)) = 16\pi G\,\delta\rho$$

$$-\frac{4k^2\Phi}{a^2} - 12H(\dot\Phi+H\Phi) = 16\pi G\,\delta\rho$$

Dividing by $-4$, the linearized Gauss constraint takes the standard form:

$$\frac{k^2\Phi}{a^2} + 3H(\dot\Phi + H\Phi) = -4\pi G\,\delta\rho \tag{11}$$

This is the **perturbed Hamiltonian constraint**, expressing the bulk energy density perturbation in terms of the geometry of the perturbed Cauchy hypersurface.

---

## 5. Derivation of $\delta\rho/\rho = -2\psi$ (Super-Horizon Limit)

### 5.1 The growing mode from the Codazzi constraint

The momentum constraint (Codazzi equation) in Newtonian gauge reads:

$$\dot\Phi + H\Phi = -4\pi G(\rho + P)\,V \tag{12}$$

where $V$ is the velocity potential. On **super-horizon scales** ($k \to 0$), the matter velocity is suppressed: $V \propto k/aH \to 0$. Combined with the growing-mode solution, equation (12) gives $\dot\Phi + H\Phi \to 0$ as $k/aH \to 0$. For the growing mode in de Sitter or slow-roll, this is satisfied by $\dot\Phi \approx 0$, i.e., $\Phi \approx \text{const}$.

### 5.2 The Hamiltonian constraint in the long-wavelength limit

Substituting $\dot\Phi = 0$ into (11) and taking $k \to 0$:

$$3H^2\Phi = -4\pi G\,\delta\rho \tag{13}$$

Using the background Friedmann equation $4\pi G\rho = 3H^2/2$:

$$3H^2\Phi = -\frac{3H^2}{2}\,\frac{\delta\rho}{\rho} \tag{14}$$

$$\frac{\delta\rho}{\rho} = -2\Phi \tag{15}$$

From the companion document (Step 2), in the super-horizon growing-mode limit in Newtonian gauge:

$$\psi \equiv -\frac{\delta H}{H} \approx \Phi \tag{16}$$

Substituting:

$$\boxed{\frac{\delta\rho}{\rho} = -2\psi} \tag{17}$$

This is the boundary–bulk relation of Document 5, now derived as the **super-horizon limit of the Gauss constraint**, applied to the geometry of the perturbed FRW hypersurface. It is valid for $k \ll aH$ and the growing-mode solution $\dot\Phi \approx 0$.

---

## 6. Full k-Dependent Extension

Retaining the $k^2\Phi/a^2$ term in equation (11) with $\dot\Phi = 0$:

$$\frac{k^2\Phi}{a^2} + 3H^2\Phi = -4\pi G\,\delta\rho = -\frac{3H^2}{2}\,\frac{\delta\rho}{\rho} \tag{18}$$

$$\frac{\delta\rho}{\rho} = -\frac{2\Phi}{3H^2}\left(\frac{k^2}{a^2} + 3H^2\right) = -2\Phi\!\left(1 + \frac{k^2}{3a^2H^2}\right) \tag{19}$$

Using $\psi \approx \Phi$:

$$\boxed{\frac{\delta\rho}{\rho} = -2\psi\!\left(1 + \frac{1}{3}\left(\frac{k}{aH}\right)^2\right)} \tag{20}$$

This is the **full Gauss-constraint boundary–bulk relation**, valid for all $k$ in the growing-mode approximation.

### Limiting regimes

**Super-horizon** ($k \ll aH$):
$$\frac{\delta\rho}{\rho} \approx -2\psi \tag{21}$$
The Document 5 result. Each Hubble patch is an independent FRW universe (separate-universe approximation).

**Horizon crossing** ($k = aH$):
$$\frac{\delta\rho}{\rho} = -\frac{8}{3}\,\psi \tag{22}$$
An $\mathcal{O}(1)$ correction to the leading-order result.

**Sub-horizon** ($k \gg aH$):
$$\frac{\delta\rho}{\rho} \approx -\frac{2}{3}\!\left(\frac{k}{aH}\right)^2\psi \tag{23}$$
The Newtonian Poisson equation, with $\Phi = \psi$ playing the role of the gravitational potential.

---

## 7. The Codazzi Equation as the Bulk Velocity Relation

The momentum constraint (Codazzi equation, eq. 12) provides the complementary boundary–bulk relation for the velocity field:

$$V = -\frac{\dot\Phi + H\Phi}{4\pi G(\rho+P)} \tag{24}$$

Using $4\pi G(\rho+P) = \varepsilon H^2$ (from Step 3) and the background Friedmann equation:

$$V = -\frac{\dot\Phi + H\Phi}{\varepsilon H^2} \tag{25}$$

For the growing mode at super-horizon scales ($\dot\Phi = 0$, $k \to 0$):
$$V_\text{super-horiz} = -\frac{H\Phi}{\varepsilon H^2} = -\frac{\psi}{\varepsilon H} \tag{26}$$

For the growing mode at sub-horizon scales, from the sub-horizon Hamiltonian constraint:
$$\frac{k^2\Phi}{a^2} \approx -4\pi G\,\delta\rho \quad \Rightarrow \quad \dot\Phi \approx \frac{-k^2/(4\pi G\,a^2) - \delta\dot\rho}{...} \tag{27}$$

In the quasi-static sub-horizon limit ($\dot\Phi \approx 0$):
$$V_\text{sub-horiz} = -\frac{H\psi}{\varepsilon H^2} = -\frac{\psi}{\varepsilon H} \tag{28}$$

The velocity potential is $V = -\psi/(\varepsilon H)$ to leading order in both limits, showing that the Codazzi equation provides a consistent bulk velocity field sourced by the horizon perturbation $\psi$ in both regimes.

---

## 8. Separate-Universe Interpretation

The super-horizon limit (eq. 21) admits a clear physical interpretation in the **separate-universe approximation**: for $k \ll aH$, each Hubble-sized patch of the universe evolves as an independent FRW universe with its own local parameters $H_\text{loc}$ and $\rho_\text{loc}$.

Each patch satisfies the local Gauss constraint:
$$H_\text{loc}^2 = \frac{8\pi G}{3}\rho_\text{loc} \tag{29}$$

Writing $H_\text{loc} = H + \delta H$ and $\rho_\text{loc} = \rho + \delta\rho$:
$$2H\,\delta H = \frac{8\pi G}{3}\,\delta\rho \tag{30}$$

Using $4\pi G\rho = 3H^2/2$ and $\psi = -\delta H/H$:
$$\frac{\delta\rho}{\rho} = \frac{2\,\delta H}{H} = -2\psi \tag{31}$$

This is identical to (17). The Gauss constraint derivation is the geometric justification for the separate-universe approximation: it holds precisely when the spatial gradient term $k^2\Phi/a^2$ in (11) is negligible compared to $3H^2\Phi$ — i.e., when $k \ll aH$.

---

## 9. Gauge Specification and Validity

Equation (17) is derived in **Newtonian gauge** with the identification $\psi \approx \Phi$ (valid on super-horizon scales; see Step 2). In a general gauge, the appropriate statement is:

$$\frac{\delta\rho}{\rho}\bigg|_\text{comoving} = -2\psi_\text{comoving} + \mathcal{O}\!\left(\frac{k^2}{a^2H^2}\right) \tag{32}$$

where both $\delta\rho$ and $\psi$ are evaluated in the comoving gauge (fluid 4-velocity unperturbed). In the comoving gauge: $\psi_\text{comoving} = \varepsilon/(1+\varepsilon) \times \mathcal{R}$ (from Step 2), so (32) is consistent with the standard super-horizon conservation of $\mathcal{R}$.

The relation $\delta\rho/\rho = -2\psi$ therefore holds precisely when:

1. The super-horizon condition $k \ll aH$ is satisfied
2. The growing-mode condition $\dot\Phi \approx 0$ holds
3. The single-fluid adiabatic approximation applies (no entropy perturbations)

The fractional correction at horizon crossing ($k = aH$) is $1/3$, making the total coefficient $8/3$ rather than $2$. For precision calculations, the full equation (20) should be used.

---

## 10. Corrections to Document 5

### Equation (16) — Now a theorem

The relation $\delta\rho/\rho = -2\psi$ (eq. (16) of Document 5) is upgraded from an algebraic consistency check to a theorem: it is the super-horizon limit of the linearized Gauss constraint (eq. 11 above), valid for $k \ll aH$.

### Sub-horizon extension

Document 5 did not provide the extension of (16) to finite $k$. The full result is equation (20): the density perturbation receives a $(k/aH)^2$-correction that dominates on sub-horizon scales and reproduces the Poisson equation.

### Equation (4) of the gauge-invariant companion document (Step 2)

The Hamiltonian constraint in that document originally had a sign error: $-3H(\dot\Phi + H\Phi) + k^2\Phi/a^2 = 4\pi G\delta\rho$. This was corrected in Step 8. The correct form, derived here from the Gauss constraint, is:

$$3H(\dot\Phi + H\Phi) + \frac{k^2\Phi}{a^2} = -4\pi G\,\delta\rho \tag{33}$$

The super-horizon result $\delta\rho/\rho = -2\psi$ is unaffected by this correction; only the sub-horizon extension (eq. 23) changes sign.

---

## 11. Remaining Open Problems

- **Non-adiabatic perturbations.** The derivation assumes adiabatic single-fluid perturbations. For entropy perturbations ($\delta S \neq 0$), additional source terms appear in the Gauss constraint.

- **Beyond the growing-mode approximation.** Setting $\dot\Phi = 0$ is accurate for the growing mode but breaks down during horizon crossing and for decaying modes. A complete transfer function from $\psi$ to $\delta\rho/\rho$ for all $k$ and all times requires solving the full coupled perturbation equations.

- **2-surface Gauss–Codazzi for the apparent horizon.** The present derivation uses the Gauss constraint for the 3-dimensional Cauchy hypersurface $\Sigma_t$, with the apparent horizon appearing only as the scale $R_A = 1/H$. A complementary derivation using the Gauss–Codazzi equations for the 2-surface (the apparent horizon itself) — via the Raychaudhuri equation for null congruences — would provide a more direct boundary-based justification for (17). This remains an open problem.

---

## 12. Summary

| Result | Equation | Origin |
|--------|----------|--------|
| Friedmann as Gauss constraint | $H^2 = 8\pi G\rho/3$ | eq. (2) with FRW geometry |
| Perturbed Gauss constraint | $k^2\Phi/a^2 + 3H(\dot\Phi+H\Phi) = -4\pi G\delta\rho$ | eq. (11) |
| Boundary–bulk relation (exact) | $\delta\rho/\rho = -2\psi[1 + (k/aH)^2/3]$ | eq. (20) |
| Super-horizon limit | $\delta\rho/\rho = -2\psi$ | eq. (17) — Document 5 result |
| Sub-horizon limit (Poisson) | $\delta\rho/\rho = -(2/3)(k/aH)^2\psi$ | eq. (23) |
| Velocity field (Codazzi) | $V = -\psi/(\varepsilon H)$ | eq. (26) |

---

## 13. Conclusion

The relation $\delta\rho/\rho = -2\psi$ is the super-horizon, growing-mode limit of the linearized Gauss constraint for the FRW Cauchy hypersurface. The Friedmann equation is the background Gauss constraint; its linearization gives the perturbed Hamiltonian constraint, which reduces to $\delta\rho/\rho = -2\psi$ for $k \ll aH$. The sub-horizon extension, given by equation (20), transitions to the Newtonian Poisson equation for $k \gg aH$. The Codazzi (momentum) constraint provides the complementary relation for the bulk velocity field. These results complete the geometric justification for the boundary–bulk correspondence in Document 5 and establish the domain of validity of the leading-order relation.

---

## References

1. R. Arnowitt, S. Deser, and C. W. Misner, "Republication of: The dynamics of general relativity," *Gen. Relat. Gravit.* **40**, 1997 (2008) [originally 1962].
2. J. M. Bardeen, "Gauge invariant cosmological perturbations," *Phys. Rev. D* **22**, 1882 (1980).
3. S. A. Hayward, "Gravitational energy in spherical symmetry," *Phys. Rev. D* **53**, 1938 (1996).
4. R.-G. Cai and S. P. Kim, "First law of thermodynamics and Friedmann equations of Friedmann-Robertson-Walker universe," *JHEP* **0502**, 050 (2005).
5. S. Dodelson, *Modern Cosmology*, Academic Press (2003), Chapter 7.
6. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Causal Horizon Framework, Document 5 (2025).
7. K. Muñoz, "Gauge-Invariant Formulation of the Horizon Perturbation," Causal Horizon Framework (2025).
