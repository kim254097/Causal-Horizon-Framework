# Spectral Tilt from Horizon Thermodynamics

**Kevin Muñoz**

---

## Abstract

The companion documents on horizon field quantization (Step 3) and gauge-invariant perturbation theory (Step 2) derived the spectral tilt formula $n_s - 1 = 3 - 2\nu$ in terms of the parameter $\nu(\varepsilon, \beta_S)$, where $\varepsilon = -\dot{H}/H^2$ is the slow-roll parameter and $\beta_S = m_\text{eff}^2/H^2$ is the normalized effective mass of the horizon field. Both parameters were treated as inputs. This document derives them from within the horizon-centered framework: $\varepsilon$ is identified as half the fractional rate of change of the horizon entropy per e-fold, and $\beta_S = 0$ is established as the minimal choice consistent with the two-dimensional conformal structure of the horizon action. The resulting spectral tilt takes the form

$$n_s - 1 = -\frac{d\ln S}{d\ln a}$$

where $S = \pi R_A^2 / G$ is the horizon entropy. This is the tilt expressed without explicit reference to the bulk inflaton field: the parameter $\varepsilon = \frac{1}{2}d\ln S/d\ln a$ is defined intrinsically in terms of the horizon entropy, though it encodes the same dynamical information as the bulk slow-roll parameter. A derivation of the time evolution of $\varepsilon$ from intrinsic horizon quantities alone — without bulk input — remains an open problem of the framework. The observed value $n_s \approx 0.965$ translates to a horizon entropy growth rate of $3.5\%$ per e-fold during inflation.

---

## 1. Motivation

The tilt formula derived in the quantization document is

$$n_s - 1 = 3 - 2\nu, \qquad \nu \approx \frac{3}{2} + \varepsilon - \frac{\beta_S}{3} \tag{1}$$

yielding

$$n_s - 1 \approx -2\varepsilon + \frac{2\beta_S}{3} \tag{2}$$

Both $\varepsilon$ and $\beta_S$ were introduced as external parameters. The program of horizon-centered cosmology requires that these be derivable from intrinsic horizon quantities — not imported from inflationary slow-roll field theory. This document provides those derivations and produces a tilt formula expressed entirely in thermodynamic variables of the horizon.

---

## 2. The Slow-Roll Parameter as a Horizon Entropy Rate

The apparent horizon carries entropy proportional to its area:

$$S = \frac{A}{4G} = \frac{\pi R_A^2}{G} = \frac{\pi}{G H^2} \tag{3}$$

Differentiating with respect to time:

$$\dot{S} = -\frac{2\pi \dot{H}}{G H^3} = \frac{2\pi \varepsilon H^2}{G H^3} = \frac{2\pi \varepsilon}{G H} \tag{4}$$

where we used $\dot{H} = -\varepsilon H^2$. Dividing by $S$:

$$\frac{\dot{S}}{S} = \frac{2\pi\varepsilon}{GH} \times \frac{GH^2}{\pi} = 2\varepsilon H \tag{5}$$

Therefore:

$$\varepsilon = \frac{\dot{S}}{2SH} = \frac{1}{2}\frac{d\ln S}{d\ln a} \tag{6}$$

The slow-roll parameter $\varepsilon$ is **half the fractional rate of change of the horizon entropy per e-fold**. This is a purely horizon-thermodynamic quantity: no reference to the bulk scalar field, its potential, or its kinetic energy is needed.

Equivalently, using $T = 1/(2\pi R_A) = H/(2\pi)$:

$$\varepsilon = -\frac{\dot{T}}{TH} = -\frac{d\ln T}{d\ln a} \tag{7}$$

The slow-roll parameter also equals the fractional decrease in the Hawking–Gibbons temperature per e-fold. Both expressions are intrinsic to the horizon geometry.

---

## 3. The Effective Mass from Two-Dimensional Conformal Minimality

### 3.1 The horizon action and its symmetry content

The action of the horizon field (eq. (23) of Document 5) is

$$S_\phi = \int dt\, d\Omega\, R_A^2 \left[(\partial_t\phi)^2 + H^2(\nabla_\Omega\phi)^2 + m_\text{eff}^2\phi^2\right] \tag{8}$$

where $\nabla_\Omega$ is the gradient on the unit two-sphere $S^2$ and $R_A = 1/H$. The spatial part of this action is that of a scalar field on a two-dimensional Riemannian manifold $(S^2, R_A^2 \gamma_{ij})$, where $\gamma_{ij}$ is the round metric on $S^2$.

### 3.2 Coupling to intrinsic curvature

A scalar field on a two-dimensional manifold can couple to the intrinsic Ricci scalar $\mathcal{R}_2$ of the surface:

$$S_\phi \supset -\xi \int dt\, d\Omega\, R_A^2\, \mathcal{R}_2\, \phi^2 \tag{9}$$

The Ricci scalar of a two-sphere of radius $R_A$ is $\mathcal{R}_2 = 2/R_A^2 = 2H^2$. Thus the coupling (9) contributes an effective mass:

$$m_\text{eff}^2 = \xi \mathcal{R}_2 = 2\xi H^2 \qquad \Longrightarrow \qquad \beta_S = 2\xi \tag{10}$$

### 3.3 Conformal minimality in two dimensions

In two spacetime dimensions, the Weyl-invariant (conformally coupled) action for a scalar field has $\xi = 0$. This is special to $d=2$: the conformal coupling $\xi_\text{conf} = (d-2)/(4(d-1))$ vanishes identically for $d=2$, meaning that the minimal and conformal couplings coincide.

The horizon is a two-dimensional spatial surface. The minimal action for $\phi$ on the horizon — the one that introduces no new dimensionless parameter beyond those already present in the background — therefore has

$$\xi = 0 \qquad \Longrightarrow \qquad \beta_S = 0 \tag{11}$$

This is the **minimal horizon field**: it couples to the background only through the kinetic structure $R_A^2(\nabla_\Omega\phi)^2$, which is already fixed by the geometry of $S^2$, and carries no intrinsic mass term. This result receives independent geometric support from the second variation of the Hayward trapping horizon action $\delta^2 S_{\rm trapping}$: the mass terms of order $\psi^2/\varepsilon^n$ cancel exactly at leading slow-roll order via the second-order trapping condition, and the residual mass is proportional to $\eta_s = \dot\varepsilon/(H\varepsilon)$, which vanishes for constant $\varepsilon$. The $d=2$ conformal argument and the Hayward derivation thus reach the same conclusion by independent routes.

### 3.4 When $\beta_S \neq 0$

A non-zero $\beta_S$ arises if:

- The horizon field couples to the ambient four-dimensional curvature: $\mathcal{R}_4 = 12H^2$ in de Sitter, giving $\beta_S = 12\xi_4$.
- There is a coupling to the matter stress-energy at the horizon.
- Quantum corrections generate a renormalized mass.

In all these cases $\beta_S$ becomes a coupling constant of the microscopic model, not a prediction of the minimal framework. The minimal framework ($\beta_S = 0$) produces the cleanest prediction.

---

## 4. The Tilt as a Horizon Thermodynamic Rate

Substituting $\beta_S = 0$ into equation (2):

$$n_s - 1 = -2\varepsilon \tag{12}$$

Substituting the thermodynamic expression (6):

$$\boxed{n_s - 1 = -\frac{d\ln S}{d\ln a}} \tag{13}$$

The **spectral tilt equals minus the fractional growth rate of the horizon entropy per e-fold.** This is the central result of the present document.

Equivalently, from equation (7):

$$n_s - 1 = \frac{d\ln T}{d\ln a} \tag{14}$$

The tilt equals the fractional change in the Hawking–Gibbons temperature per e-fold. A red tilt ($n_s < 1$) follows from $\dot{T} < 0$: the horizon temperature was decreasing during inflation, i.e., the Hubble rate was slowly decreasing.

### Physical interpretation

In exact de Sitter ($H = \text{const}$): $S = \text{const}$, $\varepsilon = 0$, $n_s = 1$. Perfect scale invariance is a consequence of perfect thermodynamic stationarity of the horizon.

A red tilt emerges whenever $S$ grows: as the universe inflates and $H$ decreases slightly, the horizon expands and its entropy increases. Each mode that freezes out does so at a slightly different value of $H$ (and hence $S$), acquiring a slightly different amplitude. The tilt records the rate at which the thermodynamic state of the horizon changes across the freeze-out history.

---

## 5. Leading Correction: Variation of $\varepsilon$

Equation (13) holds to leading order in $\varepsilon$. The first subleading correction comes from the time variation of $\varepsilon$ itself, parameterized by

$$\eta_\varepsilon \equiv \frac{\dot{\varepsilon}}{H\varepsilon} = \frac{d\ln\varepsilon}{d\ln a} \tag{15}$$

In the effective potential for the mode equation (Step 3, eq. (31)), the next term in the expansion gives

$$n_s - 1 = -2\varepsilon - \eta_\varepsilon + \mathcal{O}(\varepsilon^2) \tag{16}$$

In horizon thermodynamic language:

$$\eta_\varepsilon = \frac{d\ln\varepsilon}{d\ln a} = \frac{d}{d\ln a}\left(\frac{d\ln S}{d\ln a}\right) \bigg/ \frac{d\ln S}{d\ln a} \tag{17}$$

This is the "acceleration" of the entropy growth rate, normalized by the growth rate itself. The leading result (13) applies when this acceleration is small compared to $\varepsilon$ — i.e., when the horizon is evolving at a nearly constant rate per e-fold.

For constant $\varepsilon$ (power-law inflation $a \propto t^{1/\varepsilon}$, $S \propto a^{2\varepsilon}$): $\eta_\varepsilon = 0$ and (13) is exact at this order.

---

## 6. General Tilt with Non-Zero $\beta_S$

For a non-minimal horizon field with $\beta_S \neq 0$:

$$n_s - 1 = -2\varepsilon + \frac{2\beta_S}{3} = -\frac{d\ln S}{d\ln a} + \frac{2\beta_S}{3} \tag{18}$$

The $\beta_S$ term shifts the tilt by a constant (k-independent) amount. In terms of the curvature coupling $\xi$ (eq. 10):

$$n_s - 1 = -\frac{d\ln S}{d\ln a} + \frac{4\xi}{3} \tag{19}$$

Conformal coupling to the four-dimensional curvature ($\xi_4 = 1/6$, $\beta_S = 2$) gives a blue shift of $4/3$, which would require $\varepsilon > 2/3$ to maintain a red tilt — inconsistent with observationally required $\varepsilon \ll 1$. This rules out conformal four-dimensional coupling for the horizon field and supports the two-dimensional minimal choice $\beta_S = 0$.

---

## 7. Observational Constraint

The Planck 2018 measurement $n_s = 0.9649 \pm 0.0042$ gives, for the minimal case $\beta_S = 0$:

$$\varepsilon = \frac{1 - n_s}{2} = 0.0176 \pm 0.0021 \tag{20}$$

In thermodynamic language:

$$\frac{d\ln S}{d\ln a}\bigg|_\text{inflation} = 0.0351 \pm 0.0042 \tag{21}$$

The horizon entropy was growing at approximately $3.5\%$ per e-fold during the inflationary epoch that seeded the CMB modes.

From (3): $S \propto H^{-2}$, so $d\ln S/d\ln a = -2\, d\ln H/d\ln a = 2\varepsilon$. The Hubble rate was decreasing at $\varepsilon \approx 1.76\%$ per e-fold.

---

## 8. Connection to Previous Documents

### Relation to Document 5

Document 5 introduced $m_\text{eff}^2 = \beta_S H^2$ and stated $n_s - 1 \approx -2\beta_S$ by analogy. The present derivation shows:

- The quantity called $\beta_S$ in Document 5 corresponds, in the notation of the quantization document, to the compound parameter $\beta_\nu = \varepsilon - \beta_S/3$ (eq. (34) of the quantization document).
- For the minimal horizon field ($\beta_S = 0$): $\beta_\nu = \varepsilon$ and $n_s - 1 = -2\varepsilon = -2\beta_\nu$, which recovers Document 5's formula with the identification $\beta_\text{Doc5} = \varepsilon$.

### Relation to the quantization document (Step 3)

The derivation $n_s - 1 = 3 - 2\nu$ with $\nu \approx 3/2 + \varepsilon$ (for $\beta_S = 0$) established the functional form. The present document provides the physical content: $\varepsilon = (1/2)\, d\ln S/d\ln a$ and $\beta_S = 0$ from 2D conformal minimality.

### Relation to the gauge-invariant document (Step 2)

Step 2 established $n_s(\mathcal{R}) = n_s(\psi)$: the tilt is the same whether computed from the boundary field $\psi$ or the bulk curvature perturbation $\mathcal{R}$. The present result therefore applies directly to the observed CMB tilt without further gauge corrections.

---

## 9. Summary Table

| Quantity | Horizon-thermodynamic expression | Value (Planck 2018) |
|----------|----------------------------------|---------------------|
| $\varepsilon$ | $\frac{1}{2}\frac{d\ln S}{d\ln a} = -\frac{d\ln T}{d\ln a}$ | $0.0176$ |
| $\beta_S$ | $2\xi = 0$ (minimal, 2D conformal) | $0$ |
| $n_s - 1$ | $-\frac{d\ln S}{d\ln a} = \frac{d\ln T}{d\ln a}$ | $-0.0351$ |
| $\frac{d\ln S}{d\ln a}$ | $2\varepsilon$ | $0.0351$ |

---

## 10. Open Problems

- **Dynamical determination of $\varepsilon$.** Equation (6) expresses $\varepsilon$ in terms of $\dot{S}$, but within the horizon-centered framework, $\dot{S}$ is not predicted from the boundary field action alone. A complete dynamical theory of the horizon would need to specify what drives the change in $S$ — whether matter content, an inflaton field, or an intrinsic horizon mechanism.

- **Tensor modes.** Derived in Step 6: the tensor pump field is $z_T = a$ (vs. $z_A = a/\sqrt\varepsilon$ for scalars), giving $n_T = -2\varepsilon$, $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$, and $r = 16\varepsilon$. The standard consistency relation $r = -8n_T$ is satisfied.

- **Running of the tilt.** The subleading correction (16) involves $\eta_\varepsilon$, which is not independently constrained by the present framework. A horizon-thermodynamic expression for $\eta_\varepsilon$ would require a model for $\ddot{S}$.

- **Non-minimal coupling.** If future observations constrain $\xi$ (e.g., through primordial non-Gaussianity), equation (19) would connect $\xi$ to the coupling of the horizon field to the background curvature.

---

## 11. Conclusion

The spectral tilt of the primordial power spectrum is determined by two horizon quantities: the rate of change of the horizon entropy $\varepsilon = (1/2)\, d\ln S/d\ln a$, and the effective mass of the horizon field, which vanishes ($\beta_S = 0$) for the minimal two-dimensional conformally invariant coupling. The resulting formula $n_s - 1 = -(d\ln S)/(d\ln a)$ expresses the observed red tilt as a consequence of the gradual growth of the causal horizon's entropy during inflation, derived entirely from intrinsic horizon-thermodynamic quantities. This closes the derivation of the tilt begun in the quantization document and completes the parameter-free specification of the spectral shape within the minimal horizon-centered framework.

---

## References

1. Planck Collaboration, "Planck 2018 results. X. Constraints on inflation," *A&A* **641**, A10 (2020).
2. G. W. Gibbons and S. W. Hawking, "Cosmological event horizons, thermodynamics, and particle creation," *Phys. Rev. D* **15**, 2738 (1977).
3. T. Jacobson, "Thermodynamics of spacetime: The Einstein equation of state," *Phys. Rev. Lett.* **75**, 1260 (1995).
4. R.-G. Cai and S. P. Kim, "First law of thermodynamics and Friedmann equations of Friedmann-Robertson-Walker universe," *JHEP* **0502**, 050 (2005).
5. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Causal Horizon Framework, Document 5 (2025).
6. K. Muñoz, "Scale Invariance from Horizon Field Quantization," Causal Horizon Framework (2025).
7. K. Muñoz, "Gauge-Invariant Formulation of the Horizon Perturbation," Causal Horizon Framework (2025).
