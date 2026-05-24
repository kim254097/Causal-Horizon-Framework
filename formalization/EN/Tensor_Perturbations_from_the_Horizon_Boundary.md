# Tensor Perturbations from the Horizon Boundary: Gravitational Wave Spectrum and Consistency Relations

**Kevin Muñoz**

---

## Abstract

Steps 1–4 of the Causal Horizon Framework derived the primordial scalar power spectrum from the apparent horizon. Step 5 identified the tensor-to-scalar ratio $r$ as the sharpest differential prediction, conditional on Step 6. This document closes that gap. We show that the two transverse-traceless (TT) polarizations of the gravitational wave, when restricted to the apparent horizon 2-sphere, define boundary tensor fields with canonical variable $\mu_k^\lambda = (M_{\rm Pl}/2)\,a(\eta)\,h_k^\lambda(\eta)$ — the same normalization as the bulk tensor mode function. The mode equation for $\mu_k^\lambda$ is the Mukhanov–Sasaki equation with $z_T = a$, in contrast to the scalar case where $z_A = a/\sqrt\varepsilon$. This structural difference has a transparent physical origin: the scalar boundary field $\psi = \delta R_A/R_A$ is a SIZE perturbation of the horizon (fractional change in radius), which is slow-roll suppressed because the horizon barely moves during inflation; the tensor field $h^\lambda$ is a SHAPE perturbation (transverse shear) that does not alter the expansion rate or the horizon radius, and therefore carries no $\varepsilon$ suppression. The resulting tensor spectral index is $n_T = -2\varepsilon$, the tensor power spectrum is $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$, and the tensor-to-scalar ratio is $r = 16\varepsilon$, in complete agreement with the standard slow-roll result. The standard consistency relation $r = -8n_T$ is satisfied. For the minimal CHF ($\beta_S = 0$), an additional consistency relation follows: $n_T = n_s - 1$, which implies $r = 8(1-n_s)$. Since $n_s = 0.9649$ (Planck 2018) gives $r \approx 0.281 > 0.056$, the minimal CHF is excluded at 95\% CL by the current upper bound $r < 0.056$. The framework requires $\beta_S < -0.042$ to achieve simultaneous compatibility with the observed $n_s$ and the $r$ bound.

---

## 1. Motivation

Step 5 identified three differential predictions of the CHF. The sharpest was the $(n_s, r)$ consistency line $r = 8(1-n_s)$, which required assuming $r = 16\varepsilon$ — a result borrowed from the standard bulk calculation and not yet derived within the CHF. Step 5 left two possibilities open: either the CHF tensor spectrum matches the standard result ($r = 16\varepsilon$ confirmed, minimal framework falsified), or it differs (standard consistency relation broken, framework viable). The present document resolves this by deriving the tensor power spectrum directly from the horizon boundary.

The structure of the derivation parallels Step 3 (scalar quantization). The two tensor polarizations are identified as fields on the horizon 2-sphere, a boundary action is derived by dimensional reduction from the bulk Einstein–Hilbert action, and the mode equation is obtained via the comoving mode identification $l_k(t) = k/(a(t)H(t))$ introduced in Step 3. The key new input is the physical distinction between scalar (size) and tensor (shape) perturbations of the horizon, which determines why $z_T = a$ rather than $z_A = a/\sqrt\varepsilon$.

---

## 2. Tensor Degrees of Freedom on the Apparent Horizon

### 2.1 Identifying the boundary tensor modes

In the 3+1 ADM decomposition, metric perturbations split into scalar, vector, and tensor (TT) sectors. The tensor sector is described by the transverse-traceless part $h_{ij}^{TT}$ of the spatial metric perturbation, which satisfies $\partial^i h_{ij}^{TT} = 0$ and $h^{TT}_{ii} = 0$. It has two physical degrees of freedom, corresponding to the two polarization states $\lambda = +, \times$.

The apparent horizon $\mathcal{H}$ is a 2-sphere of radius $R_A(t) = 1/H(t)$ embedded in the spatial hypersurface $\Sigma_t$. A bulk TT perturbation $h_{ij}^{TT}$ induces a metric deformation on $\mathcal{H}$:

$$\delta\gamma_{AB} = h_{ij}^{TT}\,e^i_A\,e^j_B \tag{1}$$

where $e^i_A$ are the tangent vectors to the 2-sphere and $\gamma_{AB}$ is the round metric. The deformation $\delta\gamma_{AB}$ is traceless ($\gamma^{AB}\delta\gamma_{AB} = 0$) and transverse on $S^2$, so it represents a genuine shape deformation of the 2-sphere. Its two independent components correspond to the two polarization amplitudes $h^+(t)$ and $h^\times(t)$ at the horizon.

### 2.2 Mode identification

Each polarization mode $h_k^\lambda(t)$ with comoving wavenumber $k$ is identified with the angular mode $l_k(t) = k/(a(t)H(t))$ on the horizon 2-sphere, exactly as in the scalar case (Step 3, eq. (2)). Freeze-out occurs when $l_k = 1$, i.e., $k = a(t_k)H$, which is the standard horizon-crossing condition. The two-sphere restriction of a plane-wave tensor mode is dominated by the $l = l_k$ angular mode at the horizon.

---

## 3. The Boundary Tensor Action

### 3.1 Dimensional reduction from the bulk

The bulk Einstein–Hilbert action, expanded to second order in $h_{ij}^{TT}$ around the FRW background, gives for each polarization mode $h_k^\lambda(\eta)$ in conformal time:

$$S_T^{(k,\lambda)} = \frac{M_{\rm Pl}^2}{4}\int d\eta\, a^2\!\left[(h_k^{\lambda,\prime})^2 - k^2(h_k^\lambda)^2\right] \tag{2}$$

where primes denote $d/d\eta$. This follows from the standard quadratic expansion of $\sqrt{-g}\,R$ around the flat FRW metric, using the TT condition to eliminate mixing terms.

### 3.2 Canonical variable

Defining the canonical tensor variable

$$\mu_k^\lambda \equiv \frac{M_{\rm Pl}}{2}\,a(\eta)\,h_k^\lambda(\eta) \tag{3}$$

and substituting into (2), integration by parts yields:

$$S_T^{(k,\lambda)} = \frac{1}{2}\int d\eta\!\left[(\mu_k^{\lambda,\prime})^2 - \left(k^2 - \frac{a''}{a}\right)(\mu_k^\lambda)^2\right] \tag{4}$$

This is the standard action for a unit-normalization oscillator with time-dependent frequency. The equation of motion is:

$$\mu_k^{\lambda,''} + \left[k^2 - \frac{a''}{a}\right]\mu_k^\lambda = 0 \tag{5}$$

This is the **Mukhanov–Sasaki equation for tensor modes**, with pump field $z_T = a$.

### 3.3 Comparison with the scalar case

In Step 3, the scalar canonical variable was $u_k = z_A\psi_k$ with $z_A = a/\sqrt\varepsilon$. The effective potential in the scalar mode equation is $z_A''/z_A$. For tensor modes, the pump field is simply $z_T = a$, and the effective potential is $a''/a$. Specifically:

$$\frac{a''}{a} = \mathcal{H}^2(2 + \varepsilon + \cdots), \qquad \frac{z_A''}{z_A} = \mathcal{H}^2(2 + 3\varepsilon + \cdots) \tag{6}$$

where $\mathcal{H} = aH$. These differ at subleading slow-roll order: $z_A''/z_A$ contains $3\varepsilon$ while $a''/a$ contains $2\varepsilon$. This difference is the source of the different $\nu$ values (and hence different spectral tilts) for scalar and tensor modes.

---

## 4. Physical Origin of $z_T = a$ versus $z_A = a/\sqrt\varepsilon$

The distinction between the scalar and tensor pump fields has a clean physical interpretation within the CHF.

**Scalar modes ($z_A = a/\sqrt\varepsilon$):** The boundary scalar field is $\psi = \delta R_A/R_A$ — a fractional perturbation of the horizon RADIUS. The apparent horizon radius $R_A = 1/H$ changes in time at rate $\dot R_A/R_A = \varepsilon H$. During slow-roll ($\varepsilon \ll 1$), the horizon is nearly frozen. A given comoving curvature perturbation $\mathcal{R}$ induces only a small fractional change $\psi \approx \varepsilon\mathcal{R}$ in the horizon size (Step 2). The slow-roll suppression $\psi \ll \mathcal{R}$ is captured by the $1/\sqrt\varepsilon$ in $z_A = a/\sqrt\varepsilon$: the canonical variable $u_k = z_A\psi_k$ is enhanced by $1/\sqrt\varepsilon$ to compensate for the physical suppression of $\psi$.

**Tensor modes ($z_T = a$):** The boundary tensor field $h^\lambda$ is a transverse-traceless SHAPE perturbation of the horizon 2-sphere — it deforms the sphere into an ellipsoid without changing the horizon radius. Because $h^\lambda$ satisfies $h^{TT}_{ii} = 0$ (traceless) and $\partial^i h_{ij}^{TT} = 0$ (divergence-free), it carries no perturbation of the local expansion rate $H$. The apparent horizon is defined by the condition of zero expansion, not zero shear. A shape perturbation does not trigger a shift in $R_A$ and is therefore not slow-roll suppressed. The canonical normalization is set entirely by $M_{\rm Pl}$ (the gravitational coupling), with no $\varepsilon$ factor.

The structural difference $z_T/z_A = \sqrt\varepsilon$ is the microscopic origin of the tensor-to-scalar ratio: the tensor spectrum is unsuppressed while the scalar spectrum at the horizon is suppressed by $\varepsilon^2$ (in power), amplified back to $\mathcal{R}$ by $1/\varepsilon^2$ via the gauge-invariant relation $P_\mathcal{R} = P_\psi/\varepsilon^2$.

---

## 5. Bunch–Davies Vacuum and Tensor Freeze-Out

### 5.1 Effective potential

For slow-roll with $\varepsilon = -\dot H/H^2 \ll 1$ and $\dot\varepsilon \ll H\varepsilon$:

$$\frac{a''}{a} = \frac{\nu_T^2 - \tfrac{1}{4}}{\eta^2}, \qquad \nu_T = \frac{3}{2} + \varepsilon + \mathcal{O}(\varepsilon^2) \tag{7}$$

The tensor mode equation (5) becomes:

$$\mu_k^{\lambda,''} + \left[k^2 - \frac{\nu_T^2 - \tfrac{1}{4}}{\eta^2}\right]\mu_k^\lambda = 0 \tag{8}$$

This has the same form as the scalar equation (Step 3, eq. (17)) with $\nu_S = 3/2 + \varepsilon - \beta_S/3$. For $\beta_S = 0$: $\nu_S = \nu_T = 3/2 + \varepsilon$. The two mode equations are identical at this order.

### 5.2 Bunch–Davies initial conditions

At early times ($|k\eta| \gg 1$), equation (8) reduces to a free oscillator. The Bunch–Davies condition selects the positive-frequency mode:

$$\mu_k^\lambda(\eta) \xrightarrow{|k\eta|\to\infty} \frac{1}{\sqrt{2k}}\,e^{-ik\eta} \tag{9}$$

This is the unique choice compatible with the local Minkowski vacuum on sub-horizon scales, and is the same condition imposed for scalar modes in Step 3.

### 5.3 Exact solution and freeze-out amplitude

The exact solution of (8) with condition (9) is:

$$\mu_k^\lambda(\eta) = \frac{\sqrt{\pi}}{2}\,e^{i(\nu_T + \tfrac{1}{2})\frac{\pi}{2}}\,\sqrt{-\eta}\,H_{\nu_T}^{(1)}(-k\eta) \tag{10}$$

At super-horizon scales ($|k\eta| \to 0$):

$$|\mu_k^\lambda(\eta)|^2 \xrightarrow{|k\eta|\to 0} \frac{2^{2\nu_T - 3}\,\Gamma(\nu_T)^2}{\pi k}\left(\frac{1}{-k\eta}\right)^{2\nu_T - 1} \tag{11}$$

Freeze-out occurs at $k\eta_k = -1$ (horizon crossing $k = aH$). For de Sitter ($\nu_T = 3/2$):

$$|\mu_k^\lambda|_{\rm freeze}^2 = \frac{1}{2k} \tag{12}$$

The tensor amplitude at freeze-out:

$$|h_k^\lambda|_{\rm freeze} = \frac{2|\mu_k^\lambda|_{\rm freeze}}{M_{\rm Pl}\,a_{\rm freeze}} = \frac{2}{M_{\rm Pl}}\cdot\frac{H}{k}\cdot\frac{1}{\sqrt{2k}} = \frac{\sqrt{2}\,H}{M_{\rm Pl}\,k^{3/2}} \tag{13}$$

using $a_{\rm freeze} = k/H$ at horizon crossing.

---

## 6. Tensor Power Spectrum

The dimensionless tensor power spectrum, summed over both polarizations, is:

$$\Delta_h^2 \equiv \frac{k^3}{2\pi^2}\sum_\lambda |h_k^\lambda|_{\rm freeze}^2 = \frac{k^3}{2\pi^2}\cdot\frac{2H^2}{M_{\rm Pl}^2\,k^3} \tag{14}$$

$$\boxed{\Delta_h^2 = \frac{2H^2}{\pi^2 M_{\rm Pl}^2}} \tag{15}$$

This is exactly the standard slow-roll inflation result for the primordial gravitational wave amplitude. The derivation followed entirely from the boundary action (2), the comoving mode identification, Bunch–Davies initial conditions, and the GR normalization of the canonical variable (3).

### Tensor spectral index

From (11), the $k$-dependence of the tensor spectrum at leading slow-roll order:

$$n_T \equiv \frac{d\ln\Delta_h^2}{d\ln k} = 3 - 2\nu_T = -2\varepsilon \tag{16}$$

The tensor spectrum is slightly red-tilted, with the tilt determined entirely by $\varepsilon = (1/2)d\ln S/d\ln a$ — the same thermodynamic parameter that governs the scalar tilt.

---

## 7. Tensor-to-Scalar Ratio

Combining the tensor spectrum (15) with the scalar power spectrum of the comoving curvature perturbation $\mathcal{R}$ — the GR-normalized result (consistent with Step 2 up to the $M_{\rm Pl}$ normalization of the horizon field action):

$$\Delta_\mathcal{R}^2 = \frac{H^2}{8\pi^2\varepsilon M_{\rm Pl}^2} \tag{17}$$

the tensor-to-scalar ratio is:

$$r \equiv \frac{\Delta_h^2}{\Delta_\mathcal{R}^2} = \frac{2H^2/(\pi^2 M_{\rm Pl}^2)}{H^2/(8\pi^2\varepsilon M_{\rm Pl}^2)} \tag{18}$$

$$\boxed{r = 16\varepsilon} \tag{19}$$

This is the standard single-field slow-roll consistency relation, derived here directly from the horizon boundary.

**Physical interpretation within the CHF:** The factor $\varepsilon^{-2}$ that suppresses the scalar spectrum relative to tensor — and hence gives $r \propto \varepsilon$ — has a twofold origin:
1. The boundary scalar field $\psi$ is suppressed by $\varepsilon$ relative to $\mathcal{R}$ (from $\psi \approx \varepsilon\mathcal{R}$, Step 2), contributing a factor $\varepsilon^2$ to $P_\psi/P_\mathcal{R}$.
2. The tensor boundary field carries no such suppression (shape perturbation, no $\varepsilon$ in $z_T$).

Together: $P_h \sim H^2/M_{\rm Pl}^2$ (no $\varepsilon$), $P_\mathcal{R} \sim H^2/(M_{\rm Pl}^2\varepsilon)$ (one power of $\varepsilon$ from normalization), giving $r = P_h/P_\mathcal{R} = \varepsilon \cdot ({\rm const})$. The constant is fixed to $16$ by the GR normalization.

---

## 8. Standard Consistency Relations

### 8.1 The Lyth–Liddle relation

Combining (16) and (19):

$$r = -8n_T \tag{20}$$

This is the standard single-field inflation consistency relation. The CHF satisfies it because both $r = 16\varepsilon$ and $n_T = -2\varepsilon$ are derived from the same thermodynamic parameter $\varepsilon$, with no independent tensor slow-roll parameter.

### 8.2 Additional CHF consistency relation

For the minimal CHF with $\beta_S = 0$ (scalar) and $\beta_T = 0$ (tensor, no intrinsic mass for the shape perturbation):

$$n_s - 1 = -2\varepsilon = n_T \tag{21}$$

The scalar and tensor spectral indices are equal. Combining with (20):

$$r = -8n_T = -8(n_s - 1) = 8(1 - n_s) \tag{22}$$

This is the CHF-specific consistency relation identified (conditionally) in Step 5 and now derived from first principles. It collapses the two-dimensional freedom of standard inflation (which allows independent $n_T$ and $n_s - 1$) to a single line in the $(n_s, r)$ plane.

**Standard inflation comparison:** In standard single-field inflation with two slow-roll parameters $\varepsilon$ and $\eta'$:

$$n_s - 1 = -2\varepsilon - \eta', \qquad n_T = -2\varepsilon \tag{23}$$

so $n_T - (n_s - 1) = \eta' \neq 0$ in general. The CHF predicts $\eta' = 0$ (or equivalently, $n_T = n_s - 1$), which is violated for most inflationary potentials. Starobinsky inflation, for example, has $\varepsilon \approx 3/(4N^2) \approx 2.5\times 10^{-4}$ and $\eta' \approx -2/N \approx -0.036$ for $N = 55$, giving $n_s - 1 \approx -0.036$ while $n_T \approx -5\times 10^{-4}$ — a ratio $|(n_s - 1)/n_T| \approx 73$.

---

## 9. Resolution of the Step 5 Tension

Step 5 identified a tension: the minimal CHF ($\beta_S = 0$) with the assumption $r = 16\varepsilon$ predicts $r = 8(1-n_s) \approx 0.281$ for $n_s = 0.9649$, exceeding the Planck 2018 bound $r < 0.056$. The present derivation confirms that $r = 16\varepsilon$ does hold within the CHF. The tension is therefore real and cannot be resolved by appealing to a different tensor spectrum. The two resolutions are:

### 9.1 Non-minimal scalar field ($\beta_S \neq 0$)

For $\beta_S \neq 0$: $n_s - 1 = -2\varepsilon + 2\beta_S/3$, giving $\varepsilon = (1-n_s)/2 + \beta_S/3$ and:

$$r = 16\varepsilon = 8(1 - n_s) + \frac{16\beta_S}{3} \tag{24}$$

For $n_s = 0.9649$ and $r < 0.056$:

$$\beta_S < -\frac{3}{16}(0.281 - 0.056) = -\frac{3\times 0.225}{16} \approx -0.042 \tag{25}$$

A slightly tachyonic horizon scalar field ($m_{\rm eff}^2 = \beta_S H^2 < 0$) is required. From Step 3 (section 3.4), $\beta_S \neq 0$ arises from a coupling of the horizon field to the intrinsic curvature of the 2-sphere or to the ambient 4D Ricci scalar. A small negative $\beta_S$ is physically plausible and does not destabilize the mode equation, since the instability scale is $\sim m_{\rm eff} \sim \sqrt{|\beta_S|}H \ll M_{\rm Pl}$.

For the Planck 2018 central value $r \approx 0$ (no detection): $\beta_S \lesssim -0.053$. For the BICEP/Keck upper bound $r < 0.036$: $\beta_S < -0.056$.

### 9.2 Interpretation of the tension as falsification

If future experiments establish $r < 0.01$ with high significance (CMB-S4/LiteBIRD target), this would require $\beta_S < -0.065$. The tilt formula then gives:

$$n_s - 1 = -2\varepsilon + \frac{2\beta_S}{3} < -2\varepsilon - 0.043 \tag{26}$$

For $n_s = 0.965$: $\varepsilon > (-0.035 + 0.043)/2 = 0.004$, giving $r = 16\varepsilon > 0.064$. A contradiction — there is no $\varepsilon$ simultaneously satisfying the $n_s$ and $r < 0.01$ constraints for $|\beta_S| \lesssim 0.065$.

This means: if $r < 0.01$ is established, the CHF requires $|\beta_S| > 0.065$, but at that point the tilt formula no longer naturally gives $n_s \approx 0.965$ without fine-tuning $\varepsilon$ and $\beta_S$ against each other. The minimal CHF is excluded; the non-minimal case remains viable but loses predictive simplicity.

---

## 10. Summary of Spectral Results

| Quantity | CHF result | Standard inflation |
|---------|-----------|-------------------|
| Tensor pump field | $z_T = a$ | $z = aM_{\rm Pl}$ (same) |
| Tensor spectral index | $n_T = -2\varepsilon$ | $n_T = -2\varepsilon$ |
| Tensor power spectrum | $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$ | $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$ |
| Consistency relation | $r = -8n_T$ | $r = -8n_T$ |
| Tensor-to-scalar ratio | $r = 16\varepsilon$ | $r = 16\varepsilon$ |
| Additional CHF relation (minimal) | $n_T = n_s - 1$ | $n_T = n_s - 1 + \eta'$ ($\eta' \neq 0$ in general) |

The tensor sector results are identical to standard inflation. The differential prediction is entirely in the scalar sector: the CHF constrains $\eta' = 0$, which when combined with $r = 16\varepsilon$ gives the tight $(n_s, r)$ locus $r = 8(1-n_s)$.

---

## 11. Conclusion

The tensor degrees of freedom of the Causal Horizon Framework are the two TT polarizations of the gravitational wave, treated as shape perturbations of the apparent horizon 2-sphere. Their boundary action follows from the bulk Einstein–Hilbert action by dimensional reduction, with canonical variable $\mu_k^\lambda = (M_{\rm Pl}/2)a h_k^\lambda$. The mode equation has pump field $z_T = a$, in contrast to the scalar pump field $z_A = a/\sqrt\varepsilon$. The difference is physical: tensor modes are shape perturbations that do not alter the horizon radius, while the scalar perturbation $\psi = \delta R_A/R_A$ is a size perturbation suppressed by the slow-roll parameter. With Bunch–Davies initial conditions, the tensor mode equation gives $n_T = -2\varepsilon$, $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$, and $r = 16\varepsilon$. The standard consistency relations are satisfied. The CHF-specific relation $n_T = n_s - 1$ (for $\beta_S = 0$) confirms and derives the Step 5 prediction $r = 8(1-n_s)$, placing the minimal CHF in tension with the Planck 2018 bound $r < 0.056$. Compatibility with current data requires $\beta_S < -0.042$.

---

## References

1. Planck Collaboration, "Planck 2018 results. X. Constraints on inflation," *A&A* **641**, A10 (2020).
2. BICEP/Keck Collaboration, "BK18: Improved constraints on primordial gravitational waves," *Phys. Rev. Lett.* **127**, 151301 (2021).
3. V. F. Mukhanov, H. A. Feldman, and R. H. Brandenberger, "Theory of cosmological perturbations," *Phys. Rep.* **215**, 203 (1992).
4. D. H. Lyth, "What would we learn by detecting a gravitational wave signal in the cosmic microwave background anisotropy?", *Phys. Rev. Lett.* **78**, 1861 (1997).
5. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Causal Horizon Framework, Document 5 (2025).
6. K. Muñoz, "Scale Invariance from Horizon Field Quantization," Causal Horizon Framework (2025).
7. K. Muñoz, "Gauge-Invariant Formulation of the Horizon Perturbation," Causal Horizon Framework (2025).
8. K. Muñoz, "Spectral Tilt from Horizon Thermodynamics," Causal Horizon Framework (2025).
9. K. Muñoz, "Differential Predictions of the Causal Horizon Framework," Causal Horizon Framework (2025).
