# Differential Predictions of the Causal Horizon Framework

**Kevin Muñoz**

---

## Abstract

Steps 1–4 of the Causal Horizon Framework (CHF) derived the primordial scalar power spectrum entirely from the geometry and thermodynamics of the apparent horizon, closing the four analytical gaps of the formalization document. The resulting tilt formula is $n_s - 1 = -2\varepsilon + 2\beta_S/3$, with $\varepsilon = \frac{1}{2}d\ln S/d\ln a$ (horizon entropy rate) and $\beta_S = 0$ for the minimal conformally coupled field on the two-dimensional horizon. This document identifies the observables by which the CHF differs from standard single-field inflation and specifies the conditions under which those differences are measurable. Four differential predictions are established. First, in the minimal case ($\beta_S = 0$), the CHF gives $n_s - 1 = -2\varepsilon$ — missing the second slow-roll contribution $\eta'$ that standard inflation allows as an independent degree of freedom. For the same background $\varepsilon$, the two frameworks predict tilts differing by $\eta'$; future CMB experiments with $\sigma(n_s) \sim 0.002$ will be sensitive to this at the level of $|\eta'| \sim 0.01$. Second, the standard consistency relation $r = 16\varepsilon$ was confirmed in Step 6 by deriving tensor modes from the horizon boundary, so the CHF predicts a specific line in the $(n_s, r)$ plane: $r = 8(1 - n_s)$, corresponding to $r \approx 0.28$ for the Planck 2018 central value $n_s = 0.9649$. This is in tension with the current bound $r < 0.056$. With $r = 16\varepsilon$ confirmed by Step 6, the tension is genuine: the minimal framework ($\beta_S = 0$) is excluded by Planck 2018, and $\beta_S < -0.042$ is required. Third, the running $\alpha_s = -d^2\ln S/dN^2$ contains no $\xi^2$ term from a cubic potential. Fourth, the Hayward trapping action expanded to third order in the horizon perturbation $\psi$ generates a genuine cubic vertex with coefficients $A_3 = -7/16$ (kinetic, $\psi\dot\psi^2$) and $B_3 = +1/4$ (angular gradient, $\psi(\nabla_\Omega\psi)^2$). The in-in calculation on the worldtube establishes two structural results: the kinetic vertex contributes identically zero to the bispectrum for all momentum triangle configurations, and the gradient vertex yields a universal time integral equal to $-\pi/2$ for every triangle. The resulting equilateral non-Gaussianity is $f_{\rm NL}^{\rm equil, CHF} \approx 1{-}2$ for $\varepsilon = 0.01$ — within the detection threshold of CMB-S4 and LiteBIRD ($\sigma(f_{\rm NL}^{\rm equil}) \sim 1$). Fifth, the bispectrum shape function is $S_{\rm CHF}(k_1,k_2,k_3) \propto k_1^2+k_2^2+k_3^2$, a template that does not reduce to any linear combination of the standard local, equilateral, or orthogonal shapes, and which constitutes an independent differential observable. These predictions are derived, not assumed, and provide the empirical handles by which the CHF can be discriminated from — or falsified against — the standard inflationary paradigm.

---

## 1. Introduction

A theoretical framework earns empirical weight by predicting observables differently from existing frameworks. Steps 1–4 of the CHF reproduced results already obtained in standard inflation (scale-invariant spectrum, tilt formula, boundary–bulk relation) from a different conceptual starting point — the horizon, not the bulk inflaton. Matching known results is necessary for consistency but not sufficient for discrimination.

This document turns to the question of falsifiability: what would the CHF predict differently from a bulk inflationary model operating on the same background? The analysis proceeds as follows. Section 2 establishes the parameter structure of the CHF and compares it to that of standard inflation. Sections 3–7 derive the five differential predictions. Section 8 summarizes the current observational status. Section 9 records how Step 6 resolved Prediction 1.

---

## 2. Parameter Structure: CHF vs. Standard Inflation

### 2.1 Standard single-field slow-roll inflation

In standard single-field slow-roll inflation, the scalar power spectrum is determined by two independent slow-roll parameters at leading order:

$$n_s - 1 = -2\varepsilon - \eta', \qquad r = 16\varepsilon \tag{1}$$

where $\varepsilon = -\dot{H}/H^2$ and $\eta'$ is a second slow-roll parameter encoding the rate of change of $\varepsilon$ and/or the curvature of the inflaton potential. The two parameters are independent: for fixed $\varepsilon$, $\eta'$ can range over a wide interval without violating any consistency condition. In the Hubble slow-roll hierarchy, $\eta' = \dot{\varepsilon}/(H\varepsilon) = d\ln\varepsilon/dN$.

This two-parameter freedom means that, for a given observed tilt $n_s$, the slow-roll parameter $\varepsilon$ — and hence the tensor-to-scalar ratio $r = 16\varepsilon$ — is not determined without additional information about $\eta'$.

### 2.2 The CHF scalar sector

The CHF (Steps 1–4) gives:

$$n_s - 1 = -2\varepsilon + \frac{2\beta_S}{3}, \qquad \varepsilon = \frac{1}{2}\frac{d\ln S}{d\ln a} \tag{2}$$

where $\beta_S = m_\text{eff}^2/H^2$ is the normalized effective mass of the horizon field. For the minimal horizon field ($\beta_S = 0$, the unique choice with no intrinsic coupling to the two-sphere curvature):

$$n_s - 1 = -2\varepsilon \qquad (\text{minimal CHF}) \tag{3}$$

This is a single-parameter relation: given the observed $n_s$, $\varepsilon$ is uniquely fixed to $(1-n_s)/2$. The second slow-roll parameter $\eta'$ that appears in standard inflation is absent from the CHF at this order.

The structural origin of this difference is the following. In standard inflation, the mode variable is $u_k = z\mathcal{R}_k$ with $z = a\sqrt{2\varepsilon}\,M_{\rm Pl}$. The effective potential in the mode equation is $z''/z$, which involves both $\varepsilon$ and $\eta' = \dot\varepsilon/(H\varepsilon)$ at leading slow-roll order. In the CHF, the mode variable is $u_k = z_A\psi_k$ with $z_A = a/\sqrt{\varepsilon}$. The effective potential $z_A''/z_A$ involves $\varepsilon$ at leading order but the $\eta'$ correction enters at a different subleading level, effectively absent from the tilt at the order computed in Step 3. For power-law inflation ($\eta' = 0$), the two mode equations are equivalent. For general slow-roll ($\eta' \neq 0$), the CHF and the bulk description predict different tilts for the same background.

---

## 3. Prediction 1: The $(n_s, r)$ Plane

### 3.1 The CHF locus (confirmed by Step 6)

Step 6 derived the tensor power spectrum from the horizon boundary field and confirmed the standard consistency relation $r = 16\varepsilon$ (see Step 6, Section 8). Equation (3) then implies:

$$r_{\rm CHF}(\beta_S = 0) = 16\varepsilon = 8(1 - n_s) \tag{4}$$

This is a line in the $(n_s, r)$ plane, parameterized by $\varepsilon$ alone. For the Planck 2018 central value $n_s = 0.9649$:

$$r_{\rm CHF} = 8 \times 0.0351 = 0.281 \tag{5}$$

Standard inflation, by contrast, spans a two-dimensional region in the $(n_s, r)$ plane: fixing $n_s$ leaves $r = 16\varepsilon = 8(1-n_s) - 8\eta'$ undetermined (since $\eta'$ is free). The CHF ($\beta_S=0$) collapses this to a single point.

### 3.2 Tension with current data

The Planck 2018 bound is $r < 0.056$ (95\% CL). The CHF prediction $r \approx 0.281$ lies well above this bound. Step 6 confirmed $r = 16\varepsilon$, so the tension is genuine and has two possible resolutions:

**(a) The minimal CHF ($\beta_S = 0$) is falsified.** With $r = 16\varepsilon$ confirmed, $\beta_S = 0$ is observationally excluded at 95\% CL by the combination $(n_s, r)_{\rm Planck}$. This is a genuine falsification of the minimal framework and a clear discriminant between the CHF and standard inflation (e.g., Starobinsky inflation, which gives $r \approx 0.004$ for $N = 55$).

**(b) The horizon field is non-minimal ($\beta_S \neq 0$).** For $\beta_S \neq 0$, the tilt is $n_s - 1 = -2\varepsilon + 2\beta_S/3$. With $r = 16\varepsilon$, for fixed $n_s$:

$$r = 8(1 - n_s) + \frac{16\beta_S}{3} \tag{6}$$

Requiring $r < 0.056$ for $n_s = 0.9649$ gives:

$$\frac{16\beta_S}{3} < 0.056 - 0.281 = -0.225 \qquad \Longrightarrow \qquad \beta_S < -0.042 \tag{7}$$

A slightly tachyonic horizon field ($m_\text{eff}^2 < 0$) is required. This is not excluded a priori but introduces a new parameter with a sign constraint. The physics is: a tachyonic mass reduces the effective $\nu$ and contributes a blue shift to the tilt, allowing a given $n_s$ to be achieved with smaller $\varepsilon$ (and hence smaller $r$).

### 3.3 Discrimination from the standard locus

In the $(n_s, r)$ plane, the CHF prediction (4) lies on the line $r = 8(1-n_s)$. Standard slow-roll inflationary models populate a broad region below this line (since $\eta' < 0$ for models with concave potentials, making $n_s$ redder for the same $\varepsilon$ and hence the same $r$). The CHF line passes through or above most of the standard model predictions (Starobinsky, natural inflation, $\alpha$-attractors) that satisfy the Planck 2018 bound.

The key diagnostic: a future measurement of $r$ above the current bound (e.g., $r \sim 0.01$–$0.05$) would be consistent with the $\beta_S < 0$ CHF but not with the minimal $\beta_S = 0$ case. A measurement of $r < 0.01$ would constrain $\beta_S \lesssim -0.065$ and further test the framework.

---

## 4. Prediction 2: Absence of the Second Slow-Roll Parameter

### 4.1 The $\eta'$ correction

In standard inflation, the tilt receives a contribution from $\eta' = d\ln\varepsilon/dN$:

$$\left(n_s - 1\right)_{\rm std} = -2\varepsilon - \eta' \tag{8}$$

In the CHF ($\beta_S = 0$):

$$\left(n_s - 1\right)_{\rm CHF} = -2\varepsilon \tag{9}$$

For the same cosmological background (same $\varepsilon(t)$), the difference is:

$$\Delta(n_s - 1) \equiv \left(n_s - 1\right)_{\rm CHF} - \left(n_s - 1\right)_{\rm std} = \eta' = \frac{d\ln\varepsilon}{dN} \tag{10}$$

This difference vanishes for power-law inflation ($\varepsilon = \text{const}$, $\eta' = 0$) but is nonzero for all models where the Hubble rate is not decelerating at a constant rate.

### 4.2 Magnitude and observational reach

For typical inflationary models, $|\eta'| \sim |\varepsilon| \sim 0.01$–$0.03$. The Planck 2018 measurement has $\sigma(n_s) \approx 0.004$; future experiments (Simons Observatory, CMB-S4, LiteBIRD) are expected to reach $\sigma(n_s) \sim 0.002$. The difference $|\Delta(n_s-1)| = |\eta'| \sim 0.01$ is potentially detectable at the $\sim 5\sigma$ level with next-generation CMB data.

The discriminating power depends on whether $\eta'$ can be independently constrained. If $r$ is measured (fixing $\varepsilon = r/16$), then $\eta'$ is the residual $\eta' = -(n_s - 1) - 2\varepsilon$ in standard inflation, while the CHF predicts this residual to vanish. A joint measurement of $(n_s, r)$ with small uncertainties would thus distinguish between the two frameworks.

### 4.3 Physical content

In the CHF, the tilt has a single thermodynamic origin: $n_s - 1 = -d\ln S/d\ln a$. The rate of entropy change of the horizon encodes the full tilt. No second parameter is needed because the CHF treats $\varepsilon$ as the fundamental degree of freedom, fixing its relation to the spectrum through the geometry of the mode equation for $z_A = a/\sqrt\varepsilon$. Standard inflation allows an additional deformation of the mode equation through the curvature of the inflaton potential, producing the $\eta'$ term.

The CHF prediction $\eta' = 0$ is equivalent to the statement that **the inflaton potential is exponential** (power-law inflation), which is the unique case where the CHF and standard inflation agree exactly.

---

## 5. Prediction 3: Spectral Running from Horizon Thermodynamics

### 5.1 CHF running formula

The running of the spectral index is defined as $\alpha_s \equiv dn_s/d\ln k \approx d(n_s-1)/dN$ (at leading slow-roll order, $d\ln k \approx dN$). From equation (3):

$$\alpha_s = \frac{d(n_s-1)}{dN} = -2\frac{d\varepsilon}{dN} = -2\varepsilon\,\eta_\varepsilon \tag{11}$$

where $\eta_\varepsilon \equiv d\ln\varepsilon/dN$ is the fractional rate of change of $\varepsilon$ per e-fold.

In thermodynamic language, using $\varepsilon = \frac{1}{2}d\ln S/d\ln a = \frac{1}{2}d\ln S/dN$:

$$\alpha_s = -\frac{d^2\ln S}{dN^2} \tag{12}$$

The running of the spectral index equals **minus the second derivative of the horizon entropy** with respect to the number of e-folds. This is a fully intrinsic, thermodynamic formula for the running: no bulk scalar field, no potential, no kinetic energy.

### 5.2 Relation to the standard running

In standard inflation at leading order: $\alpha_s = -2\varepsilon\eta_H - \xi^2$, where $\xi^2 = M_{\rm Pl}^4 V'V'''/(V^2)$ involves the third derivative of the potential. The CHF running (11) matches the first term but has no analogue of $\xi^2$, since the horizon field action has no cubic potential. This predicts:

$$\alpha_s^{\rm CHF} = -2\varepsilon\eta_\varepsilon = (1-n_s)\,\eta_\varepsilon \tag{13}$$

For $n_s = 0.965$ and $\eta_\varepsilon \sim -0.01$: $\alpha_s \approx 3.5\times10^{-4}$, consistent with Planck 2018 ($\alpha_s = -0.0045 \pm 0.0067$).

The differential prediction is the absence of $\xi^2$: in the CHF, $\alpha_s$ is entirely determined by $\varepsilon$ and $\eta_\varepsilon$ (both expressible in terms of $S$ and its derivatives), with no independent third-order parameter. A measurement of $|\alpha_s|$ significantly larger than $(1-n_s)|\eta_\varepsilon|$ would be inconsistent with the minimal CHF.

### 5.3 Consistency relation

Combining (9) and (13) for the minimal CHF:

$$\frac{\alpha_s}{(n_s - 1)^2} = \frac{-2\varepsilon\eta_\varepsilon}{4\varepsilon^2} = -\frac{\eta_\varepsilon}{2\varepsilon} = -\frac{d\ln\varepsilon/dN}{d\ln S/dN} \tag{14}$$

This ratio is a pure horizon quantity: the rate of change of $\ln\varepsilon$ relative to the rate of change of $\ln S$. If the entropy grows at a constant rate ($\eta_\varepsilon = 0$, power-law inflation), both $\alpha_s$ and this ratio vanish exactly.

---

## 6. Prediction 4: Non-Gaussianity from the Hayward Cubic Action

### 6.1 The Hayward trapping action has a genuine cubic sector

The free horizon-field action (eq. (23) of Document 5) is quadratic in $\phi$. However, the Hayward trapping condition — the geometric constraint that defines the location of the perturbed apparent horizon — generates higher-order terms when expanded in powers of $\psi = \delta R_A/R_A$. Specifically, $\delta^3 S_{\rm trapping}$ produces a non-trivial cubic action after the large mass-like terms $\sim\psi^3/\varepsilon^n$ cancel via the third-order trapping condition (by the same mechanism that cancelled the mass terms at second order):

$$\delta^3 S_{\rm trapping}\bigg|_{\mathcal{H}} = \frac{M_{\rm Pl}^2\sqrt{2\varepsilon}}{\varepsilon^2 H^3}\int dt\,d\Omega\left[A_3\,\psi\dot\psi^2 + \frac{B_3}{R_A^2}\,\psi(\nabla_\Omega\psi)^2\right] + \mathcal{O}(\varepsilon) \tag{15}$$

The coefficients are determined entirely by the Hayward geometry:

$$A_3 = -\frac{7}{16}, \qquad B_3 = +\frac{1}{4} \tag{16}$$

No free parameters enter. $A_3/B_3 = -7/4 \neq -1$ (Maldacena's ratio for single-field slow-roll inflation), so the CHF cubic action has a structurally different weighting of kinetic and gradient vertices.

### 6.2 In-in calculation on the worldtube

The in-in computation of $\langle\psi_{k_1}\psi_{k_2}\psi_{k_3}\rangle$ on the two-sphere worldtube yields two structural results, valid for all momentum triangle configurations $(k_1, k_2, k_3)$:

**Theorem 1 (kinetic vertex).** The vertex $A_3\psi\dot\psi^2$ contributes identically zero to the bispectrum for every momentum triangle. The time integrand $\eta^3(1+ik_i\eta)e^{-iK_t\eta}$ (where $K_t = k_1+k_2+k_3$) is purely real for all $k_i > 0$, so its imaginary part vanishes.

**Theorem 2 (gradient vertex).** The time integral of the gradient vertex $B_3\psi(\nabla_\Omega\psi)^2$ is universal:

$$\mathcal{J}(k_1,k_2,k_3) \equiv {\rm Im}\!\left[\int_{-\infty}^{0}\frac{d\eta}{\eta}(1+ik_1\eta)(1+ik_2\eta)(1+ik_3\eta)e^{-iK_t\eta}\right] = -\frac{\pi}{2} \tag{17}$$

for every closed momentum triangle. Only the $1/\eta$ pole contributes; all higher-order terms in the mode expansion are real.

**Consequence.** The full shape information of the CHF bispectrum is carried entirely by the angular coupling from the gradient vertex, with no contribution from the kinetic vertex.

### 6.3 The equilateral non-Gaussianity parameter

The equilateral bispectrum from the gradient vertex, after integrating over the two-sphere and converting to three-dimensional Fourier space via the Gaunt coefficient mapping (Limber approximation, $C_{\rm geom} \approx \pi/8$), gives:

$$f_{\rm NL}^{\rm equil, CHF} \approx \frac{3\pi^5\sqrt{2\varepsilon}\,B_3}{16} \times C_{\rm geom} \approx 1{-}2 \qquad (\varepsilon = 0.01) \tag{18}$$

This is larger than the standard single-field slow-roll result ($f_{\rm NL}^{\rm equil, std} \sim \mathcal{O}(\varepsilon) \approx 0.01$) by two orders of magnitude, because in standard inflation the kinetic and gradient vertices partially cancel, whereas in the CHF only the gradient vertex contributes and there is no cancellation.

### 6.4 Standard inflation comparison

In standard single-field slow-roll inflation (Maldacena 2003):

$$f_{NL}^{\rm equil, std} = \frac{5}{12}(n_s - 1) + \frac{5}{6}\varepsilon + \frac{5}{12}\eta' \approx \mathcal{O}(0.01) \tag{19}$$

The CHF prediction $f_{\rm NL}^{\rm equil} \approx 1{-}2$ differs from this by a factor $\sim 100{-}200$. Both CMB-S4 and LiteBIRD are expected to achieve $\sigma(f_{\rm NL}^{\rm equil}) \sim 1$, placing the CHF prediction within the detection threshold of next-generation experiments.

---

## 7. Prediction 5: The CHF Bispectrum Shape

### 7.1 Shape function from the angular coupling

The bispectrum amplitude from Theorem 2 (Section 6.2) is universal in $\eta$, so all momentum dependence comes from the angular coupling of the gradient vertex integrated over the two-sphere. Summing the three cyclic permutations of the gradient vertex $\psi_{k_a}(\nabla_\Omega\psi_{k_b}\cdot\nabla_\Omega\psi_{k_c})$:

$$\sum_{\rm cyclic}\int d\Omega\,\frac{1}{R_A^2}\psi_{k_a}(\nabla_\Omega\psi_{k_b}\cdot\nabla_\Omega\psi_{k_c})\bigg|_{K=0} = \frac{4\pi B_3(k_1^2+k_2^2+k_3^2)}{3H^2} \tag{20}$$

where the sum $k_1^2+k_2^2+k_3^2$ follows from the angular average $\int d\Omega(\mathbf{k}_{b\perp}\cdot\mathbf{k}_{c\perp}) = (8\pi/3)(\mathbf{k}_b\cdot\mathbf{k}_c)$ with $\mathbf{k}_b\cdot\mathbf{k}_c = (k_a^2-k_b^2-k_c^2)/2$ (momentum conservation), cycled over the three permutations.

The resulting bispectrum shape is:

$$\boxed{S_{\rm CHF}(k_1,k_2,k_3) \propto k_1^2+k_2^2+k_3^2} \tag{21}$$

### 7.2 Properties and comparison with standard templates

The normalized shape $s_{\rm CHF}(k_1,k_2,k_3) = (k_1^2+k_2^2+k_3^2)/(3k^2)$ (normalized to 1 at equilateral) has the following properties:

| Configuration | $s_{\rm CHF}$ | Local template | Equilateral template |
|---------------|---------------|----------------|----------------------|
| Equilateral ($k_1=k_2=k_3$) | $1$ | $\sim 1$ | $1$ |
| Squeezed ($k_3\to 0$) | $2/3$ | $\to \infty$ | $\to 0$ |
| Folded ($k_3 = k_1+k_2$) | $> 1$ | intermediate | suppressed |

The CHF shape does not reduce to any linear combination of the standard local, equilateral, or orthogonal templates. Projected onto the CMB template basis, it has a non-zero component in the direction orthogonal to the Maldacena equilateral template — a purely differential observable of the worldtube geometry.

### 7.3 Consistency with the Maldacena single-field relation

In the squeezed limit $k_3 \to 0$, the CHF satisfies the Maldacena single-field consistency relation:

$$\lim_{k_3\to 0}B_{\rm CHF}(k_1,k_2,k_3) = -\frac{5}{12}(n_s-1)\,P_\psi(k_1)P_\psi(k_3) + \mathcal{O}(k_3^0)$$

because the mode $\psi_k$ is conserved outside the Hubble horizon and the CHF is a single-field framework. The non-trivial differential prediction is in the equilateral and intermediate configurations — which probe the interaction at horizon crossing — not in the squeezed limit.

---

## 8. Observational Status

The following table summarizes the five differential predictions against current Planck 2018 constraints.

| Prediction | CHF ($\beta_S=0$) | Standard inflation | Current constraint | Status |
|------------|----------------|-------------------|-------------------|--------|
| $r$ given $n_s = 0.9649$ | $r = 0.281$ | $r \in [0, 0.28]$ (2D family) | $r < 0.056$ | **Tension confirmed** — requires $\beta_S < -0.042$ |
| $\eta'$ contribution to tilt | $\eta' = 0$ | $\eta'$ free | $\sigma(n_s) = 0.004$ | Not yet discriminated |
| $\alpha_s$ | $-2\varepsilon\eta_\varepsilon$, no $\xi^2$ | $-2\varepsilon\eta_H - \xi^2$ | $\alpha_s = -0.0045 \pm 0.0067$ | Consistent |
| $f_{\rm NL}^{\rm equil}$ (Hayward cubic) | $\approx 1{-}2$ ($\varepsilon=0.01$) | $\mathcal{O}(0.01)$ | $|f_{\rm NL}^{\rm equil}| < 100$ (Planck) | **Consistent; within reach of CMB-S4** |
| Shape: $S_{\rm CHF}\propto k_1^2+k_2^2+k_3^2$ | new template | equilateral/local/ortho | no current search | **Differential observable — new template** |

The only prediction currently in tension is (i) the value of $r$ from the minimal CHF. Step 6 confirmed $r = 16\varepsilon$, establishing that the minimal framework ($\beta_S = 0$) is excluded by Planck 2018. Consistency with current data requires $\beta_S < -0.042$. Prediction 4 ($f_{\rm NL}^{\rm equil}\approx 1{-}2$) and Prediction 5 (the CHF bispectrum shape) are consistent with all current data and will be tested by CMB-S4 and LiteBIRD.

---

## 9. Resolution by Step 6 (Tensor Perturbations)

Prediction 1 (the $(n_s, r)$ locus) depended on whether the CHF satisfies the standard consistency relation $r = 16\varepsilon$. Step 6 derived the tensor power spectrum from the two TT polarization modes on the apparent horizon boundary.

**Key result of Step 6:** The tensor pump field is $z_T = a$ (vs. $z_A = a/\sqrt{\varepsilon}$ for scalars). This difference has a clear physical origin — tensor modes are perturbations of the *shape* of the horizon (traceless transverse shear), carrying no slow-roll suppression, while scalar modes perturb the *size* ($\psi = \delta R_A/R_A$), which is suppressed by $\sqrt\varepsilon$. The calculation yields:

$$\Delta_h^2 = \frac{2H^2}{\pi^2 M_{\rm Pl}^2}, \qquad n_T = -2\varepsilon, \qquad r = 16\varepsilon \tag{18}$$

The standard consistency relation $r = -8n_T$ is satisfied. The standard consistency relation $r = 16\varepsilon$ is confirmed.

**Consequence for Prediction 1:** With $r = 16\varepsilon$ confirmed, the minimal CHF ($\beta_S = 0$) predicts $r \approx 0.281$ for $n_s = 0.9649$. This lies above the Planck 2018 bound $r < 0.056$ and the minimal framework is excluded at 95\% CL. A non-minimal scalar sector with $\beta_S < -0.042$ is required for consistency with current data.

**CHF-specific relation:** Step 6 also established an additional consistency relation specific to the CHF (for $\beta_S = \beta_T = 0$):

$$n_T = n_s - 1 \qquad \Longrightarrow \qquad r = 8(1 - n_s) \tag{19}$$

This relation is a differential prediction of the CHF relative to standard inflation, where $n_T$ and $n_s - 1$ are independent at the same slow-roll order.

---

## 10. Summary

| Prediction | Expression | Observable | Discriminating power |
|-----------|------------|------------|---------------------|
| $(n_s, r)$ locus | $r = 8(1-n_s)$, confirmed $r=16\varepsilon$ (Step 6) | CMB $B$-modes | High — minimal CHF excluded at 95% CL by Planck 2018 |
| Absence of $\eta'$ | $(n_s - 1)_{\rm CHF} - (n_s-1)_{\rm std} = \eta'$ | Future $\sigma(n_s) \sim 0.002$ | Moderate — accessible with CMB-S4/LiteBIRD |
| Running from thermodynamics | $\alpha_s = -d^2\ln S/dN^2$, no $\xi^2$ | CMB multipole shape | Low — $\xi^2$ contribution too small for current experiments |
| Equilateral non-Gaussianity | $f_{\rm NL}^{\rm equil} \approx 1{-}2$ ($\varepsilon=0.01$) | CMB bispectrum | **High** — within CMB-S4 reach ($\sigma\sim 1$); factor $\sim 100$ above std inflation |
| Bispectrum shape | $S_{\rm CHF}\propto k_1^2+k_2^2+k_3^2$ | CMB bispectrum template | **High** — new template; non-zero orthogonal component; no free parameters |

The framework's most immediate empirical handles are the value of $r$ and the primordial non-Gaussianity. The minimal CHF ($\beta_S = 0$) predicts $r \approx 0.28$ — excluded by Planck 2018 — requiring $\beta_S < -0.042$. The equilateral non-Gaussianity $f_{\rm NL}^{\rm equil}\approx 1{-}2$ is the first CHF prediction without free parameters that is both derived from geometry and accessible to near-future experiments. The shape $S_{\rm CHF}\propto k_1^2+k_2^2+k_3^2$ provides an independent discriminant: a bispectrum detection with this shape would uniquely identify the worldtube origin of the non-Gaussianity.

---

## References

1. Planck Collaboration, "Planck 2018 results. X. Constraints on inflation," *A&A* **641**, A10 (2020).
2. J. M. Maldacena, "Non-Gaussian perturbations in inflationary cosmologies," *JHEP* **0305**, 013 (2003).
3. D. Baumann, "TASI Lectures on Inflation," arXiv:0907.5424 (2009).
4. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Causal Horizon Framework, Document 5 (2025).
5. K. Muñoz, "Scale Invariance from Horizon Field Quantization," Causal Horizon Framework (2025).
6. K. Muñoz, "Gauge-Invariant Formulation of the Horizon Perturbation," Causal Horizon Framework (2025).
7. K. Muñoz, "Spectral Tilt from Horizon Thermodynamics," Causal Horizon Framework (2025).
8. K. Muñoz, "The Boundary–Bulk Relation from the Gauss–Codazzi Equations," Causal Horizon Framework (2025).
9. K. Muñoz, "Tensor Perturbations from the Horizon Boundary," Causal Horizon Framework (2025).
