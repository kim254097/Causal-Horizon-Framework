# Perturbaciones Tensoriales desde el Borde del Horizonte: Espectro de Ondas Gravitacionales y Relaciones de Consistencia

**Kevin Muñoz**

---

## Resumen

Los Pasos 1–4 del Marco del Horizonte Causal derivaron el espectro de potencias escalar primordial desde el horizonte aparente. El Paso 5 identificó la razón tensor-a-escalar $r$ como la predicción diferencial más aguda, condicional al Paso 7. Este documento cierra esa brecha. Mostramos que las dos polarizaciones transversas sin traza (TT) de la onda gravitacional, al restringirse a la dos-esfera del horizonte aparente, definen campos tensoriales de borde con variable canónica $\mu_k^\lambda = (M_{\rm Pl}/2)\,a(\eta)\,h_k^\lambda(\eta)$ — la misma normalización que la función de modo tensorial del bulk. La ecuación de modo para $\mu_k^\lambda$ es la ecuación de Mukhanov–Sasaki con $z_T = a$, en contraste con el caso escalar donde $z_A = a/\sqrt\varepsilon$. Esta diferencia estructural tiene un origen físico transparente: el campo escalar de borde $\psi = \delta R_A/R_A$ es una perturbación de TAMAÑO del horizonte (cambio fraccional en el radio), que está suprimida por rodadura lenta porque el horizonte apenas se mueve durante la inflación; el campo tensorial $h^\lambda$ es una perturbación de FORMA (cizallamiento transverso) que no altera la tasa de expansión ni el radio del horizonte, y por tanto no lleva supresión de $\varepsilon$. El índice espectral tensorial resultante es $n_T = -2\varepsilon$, el espectro de potencias tensorial es $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$, y la razón tensor-a-escalar es $r = 16\varepsilon$, en completo acuerdo con el resultado estándar de rodadura lenta. La relación de consistencia estándar $r = -8n_T$ se satisface. Para el CHF mínimo ($\beta_S = 0$), se obtiene una relación de consistencia adicional: $n_T = n_s - 1$, que implica $r = 8(1-n_s)$. Dado que $n_s = 0.9649$ (Planck 2018) da $r \approx 0.281 > 0.056$, el CHF mínimo queda excluido al 95\% CL por la cota actual $r < 0.056$. El marco requiere $\beta_S < -0.042$ para lograr compatibilidad simultánea con el $n_s$ observado y la cota sobre $r$.

---

## 1. Motivación

El Paso 5 identificó tres predicciones diferenciales del CHF. La más aguda fue la línea de consistencia $(n_s, r)$: $r = 8(1-n_s)$, que requirió asumir $r = 16\varepsilon$ — un resultado tomado prestado del cálculo estándar en el bulk y aún no derivado dentro del CHF. El Paso 5 dejó abiertas dos posibilidades: o bien el espectro tensorial del CHF coincide con el resultado estándar ($r = 16\varepsilon$ confirmado, marco mínimo falsificado), o bien difiere (relación de consistencia estándar rota, marco viable). El presente documento resuelve esto derivando el espectro de potencias tensorial directamente desde el borde del horizonte.

La estructura de la derivación es paralela al Paso 1 (cuantización escalar). Las dos polarizaciones tensoriales se identifican como campos en la dos-esfera del horizonte, se deriva una acción de borde por reducción dimensional desde la acción de Einstein–Hilbert en el bulk, y la ecuación de modo se obtiene mediante la identificación de modos comóviles $l_k(t) = k/(a(t)H(t))$ introducida en el Paso 1. El nuevo ingrediente clave es la distinción física entre perturbaciones escalares (de tamaño) y tensoriales (de forma) del horizonte, que determina por qué $z_T = a$ y no $z_A = a/\sqrt\varepsilon$.

---

## 2. Grados de Libertad Tensoriales en el Horizonte Aparente

### 2.1 Identificando los modos tensoriales de borde

En la descomposición ADM 3+1, las perturbaciones métricas se dividen en sectores escalar, vectorial y tensorial (TT). El sector tensorial está descrito por la parte transversa sin traza $h_{ij}^{TT}$ de la perturbación de la métrica espacial, que satisface $\partial^i h_{ij}^{TT} = 0$ y $h^{TT}_{ii} = 0$. Tiene dos grados de libertad físicos, correspondientes a los dos estados de polarización $\lambda = +, \times$.

El horizonte aparente $\mathcal{H}$ es una dos-esfera de radio $R_A(t) = 1/H(t)$ inmersa en la hipersuperficie espacial $\Sigma_t$. Una perturbación TT en el bulk $h_{ij}^{TT}$ induce una deformación métrica en $\mathcal{H}$:

$$\delta\gamma_{AB} = h_{ij}^{TT}\,e^i_A\,e^j_B \tag{1}$$

donde $e^i_A$ son los vectores tangentes a la dos-esfera y $\gamma_{AB}$ es la métrica redonda. La deformación $\delta\gamma_{AB}$ es sin traza ($\gamma^{AB}\delta\gamma_{AB} = 0$) y transversa en $S^2$, por lo que representa una deformación genuina de FORMA de la dos-esfera. Sus dos componentes independientes corresponden a las amplitudes de polarización $h^+(t)$ y $h^\times(t)$ en el horizonte.

### 2.2 Identificación de modos

Cada modo de polarización $h_k^\lambda(t)$ con número de onda comóvil $k$ se identifica con el modo angular $l_k(t) = k/(a(t)H(t))$ en la dos-esfera del horizonte, exactamente como en el caso escalar (Paso 1, ec. (2)). El congelamiento ocurre cuando $l_k = 1$, es decir, $k = a(t_k)H$, que es la condición estándar de cruce del horizonte.

---

## 3. La Acción Tensorial de Borde

### 3.1 Reducción dimensional desde el bulk

La acción de Einstein–Hilbert en el bulk, expandida a segundo orden en $h_{ij}^{TT}$ alrededor del fondo FRW, da para cada modo de polarización $h_k^\lambda(\eta)$ en tiempo conforme:

$$S_T^{(k,\lambda)} = \frac{M_{\rm Pl}^2}{4}\int d\eta\, a^2\!\left[(h_k^{\lambda,\prime})^2 - k^2(h_k^\lambda)^2\right] \tag{2}$$

donde las primas denotan $d/d\eta$. Esto se obtiene de la expansión cuadrática estándar de $\sqrt{-g}\,R$ alrededor de la métrica FRW plana.

### 3.2 Variable canónica

Definiendo la variable canónica tensorial

$$\mu_k^\lambda \equiv \frac{M_{\rm Pl}}{2}\,a(\eta)\,h_k^\lambda(\eta) \tag{3}$$

y sustituyendo en (2), la integración por partes da:

$$S_T^{(k,\lambda)} = \frac{1}{2}\int d\eta\!\left[(\mu_k^{\lambda,\prime})^2 - \left(k^2 - \frac{a''}{a}\right)(\mu_k^\lambda)^2\right] \tag{4}$$

La ecuación de movimiento es:

$$\mu_k^{\lambda,''} + \left[k^2 - \frac{a''}{a}\right]\mu_k^\lambda = 0 \tag{5}$$

Esta es la **ecuación de Mukhanov–Sasaki para modos tensoriales**, con campo bomba $z_T = a$.

### 3.3 Comparación con el caso escalar

En el Paso 1, la variable canónica escalar era $u_k = z_A\psi_k$ con $z_A = a/\sqrt\varepsilon$. Para modos tensoriales, el campo bomba es simplemente $z_T = a$. Específicamente:

$$\frac{a''}{a} = \mathcal{H}^2(2 + \varepsilon + \cdots), \qquad \frac{z_A''}{z_A} = \mathcal{H}^2(2 + 3\varepsilon + \cdots) \tag{6}$$

donde $\mathcal{H} = aH$. Esta diferencia a nivel subleader en rodadura lenta es el origen de los valores distintos de $\nu$ (y por tanto de los tilts espectrales distintos) para modos escalares y tensoriales.

---

## 4. Origen Físico de $z_T = a$ frente a $z_A = a/\sqrt\varepsilon$

La distinción entre los campos bomba escalar y tensorial tiene una interpretación física clara dentro del CHF.

**Modos escalares ($z_A = a/\sqrt\varepsilon$):** El campo escalar de borde es $\psi = \delta R_A/R_A$ — una perturbación fraccional del RADIO del horizonte. El radio del horizonte aparente $R_A = 1/H$ cambia en el tiempo a tasa $\dot R_A/R_A = \varepsilon H$. Durante la rodadura lenta ($\varepsilon \ll 1$), el horizonte está casi congelado. Una perturbación de curvatura comóvil dada $\mathcal{R}$ induce solo un pequeño cambio fraccional $\psi \approx \varepsilon\mathcal{R}$ en el tamaño del horizonte (Paso 2). La supresión por rodadura lenta $\psi \ll \mathcal{R}$ está capturada por el $1/\sqrt\varepsilon$ en $z_A = a/\sqrt\varepsilon$: la variable canónica $u_k = z_A\psi_k$ está amplificada por $1/\sqrt\varepsilon$ para compensar la supresión física de $\psi$.

**Modos tensoriales ($z_T = a$):** El campo tensorial de borde $h^\lambda$ es una perturbación transversa sin traza de FORMA de la dos-esfera del horizonte — deforma la esfera en un elipsoide sin cambiar el radio del horizonte. Dado que $h^\lambda$ satisface $h^{TT}_{ii} = 0$ (sin traza) y $\partial^i h_{ij}^{TT} = 0$ (divergencia nula), no lleva perturbación de la tasa de expansión local $H$. El horizonte aparente se define por la condición de expansión nula, no de cizallamiento nulo. Una perturbación de forma no desencadena un desplazamiento en $R_A$ y por tanto no está suprimida por rodadura lenta. La normalización canónica está fijada enteramente por $M_{\rm Pl}$ (el acoplamiento gravitacional), sin factor $\varepsilon$.

La diferencia estructural $z_T/z_A = \sqrt\varepsilon$ es el origen microscópico de la razón tensor-a-escalar: el espectro tensorial no está suprimido mientras que el espectro escalar en el horizonte está suprimido por $\varepsilon^2$ (en potencia), amplificado de vuelta a $\mathcal{R}$ por $1/\varepsilon^2$ mediante la relación gauge-invariante $P_\mathcal{R} = P_\psi/\varepsilon^2$.

---

## 5. Vacío de Bunch–Davies y Congelamiento Tensorial

### 5.1 Potencial efectivo

Para rodadura lenta con $\varepsilon = -\dot H/H^2 \ll 1$ y $\dot\varepsilon \ll H\varepsilon$:

$$\frac{a''}{a} = \frac{\nu_T^2 - \tfrac{1}{4}}{\eta^2}, \qquad \nu_T = \frac{3}{2} + \varepsilon + \mathcal{O}(\varepsilon^2) \tag{7}$$

La ecuación de modo tensorial (5) se convierte en:

$$\mu_k^{\lambda,''} + \left[k^2 - \frac{\nu_T^2 - \tfrac{1}{4}}{\eta^2}\right]\mu_k^\lambda = 0 \tag{8}$$

Esta tiene la misma forma que la ecuación escalar (Paso 1, ec. (17)) con $\nu_S = 3/2 + \varepsilon - \beta_S/3$. Para $\beta_S = 0$: $\nu_S = \nu_T = 3/2 + \varepsilon$. Las dos ecuaciones de modo son idénticas a este orden.

### 5.2 Condiciones iniciales de Bunch–Davies

En tiempos tempranos ($|k\eta| \gg 1$), la ecuación (8) se reduce a un oscilador libre. La condición de Bunch–Davies selecciona el modo de frecuencia positiva:

$$\mu_k^\lambda(\eta) \xrightarrow{|k\eta|\to\infty} \frac{1}{\sqrt{2k}}\,e^{-ik\eta} \tag{9}$$

Esta es la única elección compatible con el vacío de Minkowski local en escalas sub-horizonte, y es la misma condición impuesta para los modos escalares en el Paso 1.

### 5.3 Solución exacta y amplitud en el congelamiento

La solución exacta de (8) con condición (9) es:

$$\mu_k^\lambda(\eta) = \frac{\sqrt{\pi}}{2}\,e^{i(\nu_T + \tfrac{1}{2})\frac{\pi}{2}}\,\sqrt{-\eta}\,H_{\nu_T}^{(1)}(-k\eta) \tag{10}$$

En escalas super-horizonte ($|k\eta| \to 0$):

$$|\mu_k^\lambda(\eta)|^2 \xrightarrow{|k\eta|\to 0} \frac{2^{2\nu_T - 3}\,\Gamma(\nu_T)^2}{\pi k}\left(\frac{1}{-k\eta}\right)^{2\nu_T - 1} \tag{11}$$

El congelamiento ocurre en $k\eta_k = -1$. Para de Sitter ($\nu_T = 3/2$):

$$|\mu_k^\lambda|_{\rm congel}^2 = \frac{1}{2k} \tag{12}$$

La amplitud tensorial en el congelamiento:

$$|h_k^\lambda|_{\rm congel} = \frac{2|\mu_k^\lambda|_{\rm congel}}{M_{\rm Pl}\,a_{\rm congel}} = \frac{2}{M_{\rm Pl}}\cdot\frac{H}{k}\cdot\frac{1}{\sqrt{2k}} = \frac{\sqrt{2}\,H}{M_{\rm Pl}\,k^{3/2}} \tag{13}$$

usando $a_{\rm congel} = k/H$ en el cruce del horizonte.

---

## 6. Espectro de Potencias Tensorial

El espectro de potencias tensorial adimensional, sumado sobre ambas polarizaciones, es:

$$\Delta_h^2 \equiv \frac{k^3}{2\pi^2}\sum_\lambda |h_k^\lambda|_{\rm congel}^2 = \frac{k^3}{2\pi^2}\cdot\frac{2H^2}{M_{\rm Pl}^2\,k^3} \tag{14}$$

$$\boxed{\Delta_h^2 = \frac{2H^2}{\pi^2 M_{\rm Pl}^2}} \tag{15}$$

Este es exactamente el resultado estándar de inflación con rodadura lenta para la amplitud de ondas gravitacionales primordiales. La derivación siguió íntegramente desde la acción de borde (2), la identificación de modos comóviles, las condiciones iniciales de Bunch–Davies y la normalización GR de la variable canónica (3).

### Índice espectral tensorial

De (11), la dependencia en $k$ del espectro tensorial a orden líder en rodadura lenta:

$$n_T \equiv \frac{d\ln\Delta_h^2}{d\ln k} = 3 - 2\nu_T = -2\varepsilon \tag{16}$$

El espectro tensorial tiene un ligero tilt rojo, con el tilt determinado íntegramente por $\varepsilon = (1/2)d\ln S/d\ln a$ — el mismo parámetro termodinámico que gobierna el tilt escalar.

---

## 7. Razón Tensor-a-Escalar

Combinando el espectro tensorial (15) con el espectro de potencias escalar de la perturbación de curvatura comóvil $\mathcal{R}$ — el resultado normalizado en GR (consistente con el Paso 2 salvo por la normalización $M_{\rm Pl}$ de la acción del campo de horizonte):

$$\Delta_\mathcal{R}^2 = \frac{H^2}{8\pi^2\varepsilon M_{\rm Pl}^2} \tag{17}$$

la razón tensor-a-escalar es:

$$r \equiv \frac{\Delta_h^2}{\Delta_\mathcal{R}^2} = \frac{2H^2/(\pi^2 M_{\rm Pl}^2)}{H^2/(8\pi^2\varepsilon M_{\rm Pl}^2)} \tag{18}$$

$$\boxed{r = 16\varepsilon} \tag{19}$$

Esta es la relación de consistencia estándar de inflación de campo único con rodadura lenta, derivada aquí directamente desde el borde del horizonte.

**Interpretación física en el CHF:** El factor $\varepsilon^{-2}$ que suprime el espectro escalar respecto al tensorial — y que da $r \propto \varepsilon$ — tiene un doble origen:
1. El campo escalar de borde $\psi$ está suprimido por $\varepsilon$ respecto a $\mathcal{R}$ (de $\psi \approx \varepsilon\mathcal{R}$, Paso 2), contribuyendo un factor $\varepsilon^2$ a $P_\psi/P_\mathcal{R}$.
2. El campo tensorial de borde no lleva tal supresión (perturbación de forma, sin $\varepsilon$ en $z_T$).

En conjunto: $P_h \sim H^2/M_{\rm Pl}^2$ (sin $\varepsilon$), $P_\mathcal{R} \sim H^2/(M_{\rm Pl}^2\varepsilon)$ (una potencia de $\varepsilon$ de la normalización), dando $r = P_h/P_\mathcal{R} = \varepsilon\cdot({\rm const})$. La constante queda fijada en $16$ por la normalización GR.

---

## 8. Relaciones de Consistencia Estándar

### 8.1 La relación de Lyth–Liddle

Combinando (16) y (19):

$$r = -8n_T \tag{20}$$

Esta es la relación de consistencia estándar de inflación de campo único. El CHF la satisface porque tanto $r = 16\varepsilon$ como $n_T = -2\varepsilon$ se derivan del mismo parámetro termodinámico $\varepsilon$, sin parámetro de rodadura lenta tensorial independiente.

### 8.2 Relación de consistencia adicional del CHF

Para el CHF mínimo con $\beta_S = 0$ (escalar) y $\beta_T = 0$ (tensorial, sin masa intrínseca para la perturbación de forma):

$$n_s - 1 = -2\varepsilon = n_T \tag{21}$$

Los índices espectrales escalar y tensorial son iguales. Combinando con (20):

$$r = -8n_T = -8(n_s - 1) = 8(1 - n_s) \tag{22}$$

Esta es la relación de consistencia específica del CHF identificada (condicionalmente) en el Paso 5 y ahora derivada desde primeros principios. Colapsa la libertad bidimensional de la inflación estándar — que permite $n_T$ y $n_s - 1$ independientes — a una única línea en el plano $(n_s, r)$.

**Comparación con la inflación estándar:** En la inflación estándar de campo único con dos parámetros de rodadura lenta $\varepsilon$ y $\eta'$:

$$n_s - 1 = -2\varepsilon - \eta', \qquad n_T = -2\varepsilon \tag{23}$$

por lo que $n_T - (n_s - 1) = \eta' \neq 0$ en general. El CHF predice $\eta' = 0$ (equivalentemente, $n_T = n_s - 1$), lo cual es violado por la mayoría de los potenciales inflacionarios. La inflación de Starobinsky, por ejemplo, tiene $\varepsilon \approx 3/(4N^2) \approx 1.4\times 10^{-4}$ y $\eta' \approx -2/N \approx -0.036$ para $N = 55$, dando $n_s - 1 \approx -0.036$ mientras que $n_T \approx -2.8\times 10^{-4}$ — una razón $|(n_s - 1)/n_T| \approx 130$.

---

## 9. Resolución de la Tensión del Paso 5

El Paso 5 identificó una tensión: el CHF mínimo ($\beta_S = 0$) con la suposición $r = 16\varepsilon$ predice $r = 8(1-n_s) \approx 0.281$ para $n_s = 0.9649$, superando la cota de Planck 2018 $r < 0.056$. La presente derivación confirma que $r = 16\varepsilon$ sí se cumple dentro del CHF. La tensión es por tanto real y no puede resolverse apelando a un espectro tensorial diferente. Las dos resoluciones son:

### 9.1 Campo escalar no mínimo ($\beta_S \neq 0$)

Para $\beta_S \neq 0$: $n_s - 1 = -2\varepsilon + 2\beta_S/3$, dando $\varepsilon = (1-n_s)/2 + \beta_S/3$ y:

$$r = 16\varepsilon = 8(1 - n_s) + \frac{16\beta_S}{3} \tag{24}$$

Para $n_s = 0.9649$ y $r < 0.056$:

$$\beta_S < -\frac{3}{16}(0.281 - 0.056) \approx -0.042 \tag{25}$$

Se requiere un campo escalar de horizonte ligeramente taquiónico ($m_{\rm eff}^2 = \beta_S H^2 < 0$). Del Paso 3 (sección 3.4), $\beta_S \neq 0$ surge de un acoplamiento del campo de horizonte a la curvatura intrínseca de la dos-esfera o al escalar de Ricci 4D. Un $\beta_S$ negativo pequeño es físicamente plausible y no desestabiliza la ecuación de modo, dado que la escala de inestabilidad es $\sim m_{\rm eff} \sim \sqrt{|\beta_S|}H \ll M_{\rm Pl}$.

Para el valor central de Planck 2018 $r \approx 0$ (sin detección): $\beta_S \lesssim -0.053$. Para la cota BICEP/Keck $r < 0.036$: $\beta_S < -0.056$.

### 9.2 Interpretación de la tensión como falsificación

Si experimentos futuros establecen $r < 0.01$ con alta significancia (objetivo CMB-S4/LiteBIRD), esto requeriría $\beta_S < -0.065$. La fórmula del tilt da entonces:

$$n_s - 1 = -2\varepsilon + \frac{2\beta_S}{3} < -2\varepsilon - 0.043 \tag{26}$$

Para $n_s = 0.965$: $\varepsilon > 0.004$, dando $r = 16\varepsilon > 0.064$ — una contradicción con $r < 0.01$. Esto significa: si se establece $r < 0.01$, el CHF requiere $|\beta_S| > 0.065$, pero en ese punto la fórmula del tilt ya no da naturalmente $n_s \approx 0.965$ sin ajuste fino entre $\varepsilon$ y $\beta_S$. El CHF mínimo queda excluido; el caso no mínimo permanece viable pero pierde simplicidad predictiva.

---

## 10. Resumen de Resultados Espectrales

| Cantidad | Resultado CHF | Inflación estándar |
|---------|-----------|-------------------|
| Campo bomba tensorial | $z_T = a$ | $z = aM_{\rm Pl}$ (igual) |
| Índice espectral tensorial | $n_T = -2\varepsilon$ | $n_T = -2\varepsilon$ |
| Espectro de potencias tensorial | $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$ | $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$ |
| Relación de consistencia | $r = -8n_T$ | $r = -8n_T$ |
| Razón tensor-a-escalar | $r = 16\varepsilon$ | $r = 16\varepsilon$ |
| Relación adicional CHF (mínimo) | $n_T = n_s - 1$ | $n_T = n_s - 1 + \eta'$ ($\eta' \neq 0$ en general) |

Los resultados del sector tensorial son idénticos a los de la inflación estándar. La predicción diferencial está íntegramente en el sector escalar: el CHF restringe $\eta' = 0$, lo que combinado con $r = 16\varepsilon$ da el lugar ajustado $(n_s, r)$: $r = 8(1-n_s)$.

---

## 11. Conclusión

Los grados de libertad tensoriales del Marco del Horizonte Causal son las dos polarizaciones TT de la onda gravitacional, tratadas como perturbaciones de forma de la dos-esfera del horizonte aparente. Su acción de borde se obtiene de la acción de Einstein–Hilbert en el bulk por reducción dimensional, con variable canónica $\mu_k^\lambda = (M_{\rm Pl}/2)a h_k^\lambda$. La ecuación de modo tiene campo bomba $z_T = a$, en contraste con el campo bomba escalar $z_A = a/\sqrt\varepsilon$. La diferencia es física: los modos tensoriales son perturbaciones de forma que no alteran el radio del horizonte, mientras que la perturbación escalar $\psi = \delta R_A/R_A$ es una perturbación de tamaño suprimida por el parámetro de rodadura lenta. Con condiciones iniciales de Bunch–Davies, la ecuación de modo tensorial da $n_T = -2\varepsilon$, $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$ y $r = 16\varepsilon$. Las relaciones de consistencia estándar se satisfacen. La relación específica del CHF $n_T = n_s - 1$ (para $\beta_S = 0$) confirma y deriva la predicción del Paso 5 $r = 8(1-n_s)$, colocando al CHF mínimo en tensión con la cota de Planck 2018 $r < 0.056$. La compatibilidad con los datos actuales requiere $\beta_S < -0.042$.

---

## Referencias

1. Planck Collaboration, "Planck 2018 results. X. Constraints on inflation," *A&A* **641**, A10 (2020).
2. BICEP/Keck Collaboration, "BK18: Improved constraints on primordial gravitational waves," *Phys. Rev. Lett.* **127**, 151301 (2021).
3. V. F. Mukhanov, H. A. Feldman y R. H. Brandenberger, "Theory of cosmological perturbations," *Phys. Rep.* **215**, 203 (1992).
4. D. H. Lyth, "What would we learn by detecting a gravitational wave signal in the cosmic microwave background anisotropy?", *Phys. Rev. Lett.* **78**, 1861 (1997).
5. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Marco del Horizonte Causal, Documento 5 (2025).
6. K. Muñoz, "Scale Invariance from Horizon Field Quantization," Marco del Horizonte Causal (2025).
7. K. Muñoz, "Gauge-Invariant Formulation of the Horizon Perturbation," Marco del Horizonte Causal (2025).
8. K. Muñoz, "Spectral Tilt from Horizon Thermodynamics," Marco del Horizonte Causal (2025).
9. K. Muñoz, "Differential Predictions of the Causal Horizon Framework," Marco del Horizonte Causal (2025).
