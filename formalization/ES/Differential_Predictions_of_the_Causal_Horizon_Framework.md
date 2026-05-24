# Predicciones Diferenciales del Marco del Horizonte Causal

**Kevin Muñoz**

---

## Resumen

Los Pasos 1–4 del Marco del Horizonte Causal (CHF) derivaron el espectro de potencias escalar primordial íntegramente a partir de la geometría y la termodinámica del horizonte aparente, cerrando las cuatro brechas analíticas del documento de formalización. La fórmula resultante para el tilt es $n_s - 1 = -2\varepsilon + 2\beta_S/3$, con $\varepsilon = \frac{1}{2}d\ln S/d\ln a$ (tasa de entropía del horizonte) y $\beta_S = 0$ para el campo mínimamente acoplado en el horizonte bidimensional. Este documento identifica los observables mediante los cuales el CHF difiere de la inflación estándar de campo único y especifica las condiciones bajo las cuales esas diferencias son medibles. Se establecen cuatro predicciones diferenciales. Primera: en el caso mínimo ($\beta_S = 0$), el CHF da $n_s - 1 = -2\varepsilon$ — omitiendo la contribución del segundo parámetro de rodadura lenta $\eta'$ que la inflación estándar permite como grado de libertad independiente. Para el mismo $\varepsilon$ de fondo, los dos marcos predicen tilts que difieren en $\eta'$; experimentos futuros del CMB con $\sigma(n_s) \sim 0.002$ serán sensibles a esto al nivel de $|\eta'| \sim 0.01$. Segunda: la relación de consistencia estándar $r = 16\varepsilon$ fue confirmada en el Paso 6 al derivar los modos tensoriales desde el borde del horizonte, por lo que el CHF predice una línea específica en el plano $(n_s, r)$: $r = 8(1 - n_s)$, correspondiente a $r \approx 0.28$ para el valor central de Planck 2018 $n_s = 0.9649$. Esto está en tensión con la cota actual $r < 0.056$. Con $r = 16\varepsilon$ confirmado por el Paso 6, la tensión es genuina: el marco mínimo ($\beta_S = 0$) queda excluido por Planck 2018, y se requiere $\beta_S < -0.042$. Tercera: el corrimiento $\alpha_s = -d^2\ln S/dN^2$ no contiene término $\xi^2$ de un potencial cúbico. Cuarta: la acción mínima del CHF es cuadrática en el campo de borde, prediciendo $f_{NL}^{\rm CHF} = 0$ a orden líder desde el horizonte, mientras que la inflación estándar de rodadura lenta da $f_{NL} = \mathcal{O}(\varepsilon, \eta')$, pequeño pero no nulo. Estas predicciones son derivadas, no supuestas, y proporcionan los indicadores empíricos mediante los cuales el CHF puede ser discriminado o falsificado frente al paradigma inflacionario estándar.

---

## 1. Introducción

Un marco teórico gana peso empírico al predecir observables de forma distinta a los marcos existentes. Los Pasos 1–4 del CHF reprodujeron resultados ya obtenidos en la inflación estándar (espectro escala-invariante, fórmula del tilt, relación borde-bulk) desde un punto de partida conceptual diferente — el horizonte, no el inflatón en el bulk. Reproducir resultados conocidos es necesario para la consistencia pero no es suficiente para la discriminación.

Este documento aborda la pregunta de la falsificabilidad: ¿qué predice el CHF de manera diferente a un modelo inflacionario en el bulk operando sobre el mismo fondo? El análisis procede como sigue. La Sección 2 establece la estructura de parámetros del CHF y la compara con la de la inflación estándar. Las Secciones 3–6 derivan las cuatro predicciones diferenciales. La Sección 7 resume el estado observacional actual. La Sección 8 registra cómo el Paso 6 resolvió la Predicción 1.

---

## 2. Estructura de Parámetros: CHF vs. Inflación Estándar

### 2.1 Inflación estándar de campo único con rodadura lenta

En la inflación estándar de campo único con rodadura lenta, el espectro de potencias escalar está determinado por dos parámetros de rodadura lenta independientes a orden líder:

$$n_s - 1 = -2\varepsilon - \eta', \qquad r = 16\varepsilon \tag{1}$$

donde $\varepsilon = -\dot{H}/H^2$ y $\eta'$ es un segundo parámetro de rodadura lenta que codifica la tasa de cambio de $\varepsilon$ y/o la curvatura del potencial del inflatón. Los dos parámetros son independientes: para $\varepsilon$ fijo, $\eta'$ puede variar en un amplio intervalo sin violar ninguna condición de consistencia. En la jerarquía de rodadura lenta de Hubble, $\eta' = \dot{\varepsilon}/(H\varepsilon) = d\ln\varepsilon/dN$.

Esta libertad de dos parámetros significa que, para un tilt observado $n_s$ dado, el parámetro de rodadura lenta $\varepsilon$ — y por tanto la razón tensor-a-escalar $r = 16\varepsilon$ — no queda determinado sin información adicional sobre $\eta'$.

### 2.2 El sector escalar del CHF

El CHF (Pasos 1–4) da:

$$n_s - 1 = -2\varepsilon + \frac{2\beta_S}{3}, \qquad \varepsilon = \frac{1}{2}\frac{d\ln S}{d\ln a} \tag{2}$$

donde $\beta_S = m_\text{eff}^2/H^2$ es la masa efectiva normalizada del campo de horizonte. Para el campo de horizonte mínimo ($\beta_S = 0$, la única elección sin acoplamiento intrínseco a la curvatura de la dos-esfera):

$$n_s - 1 = -2\varepsilon \qquad (\text{CHF mínimo}) \tag{3}$$

Esta es una relación de un solo parámetro: dado el $n_s$ observado, $\varepsilon$ queda fijado unívocamente a $(1-n_s)/2$. El segundo parámetro de rodadura lenta $\eta'$ que aparece en la inflación estándar está ausente del CHF a este orden.

El origen estructural de esta diferencia es el siguiente. En la inflación estándar, la variable del modo es $u_k = z\mathcal{R}_k$ con $z = a\sqrt{2\varepsilon}\,M_{\rm Pl}$. El potencial efectivo en la ecuación del modo, $z''/z$, involucra tanto $\varepsilon$ como $\eta' = \dot\varepsilon/(H\varepsilon)$ a orden líder en rodadura lenta. En el CHF, la variable del modo es $u_k = z_A\psi_k$ con $z_A = a/\sqrt{\varepsilon}$. El potencial efectivo $z_A''/z_A$ involucra $\varepsilon$ a orden líder, pero la corrección por $\eta'$ entra a un nivel subleader diferente, efectivamente ausente del tilt al orden calculado en el Paso 3. Para la inflación en ley de potencias ($\eta' = 0$), las dos ecuaciones de modo son equivalentes. Para la rodadura lenta general ($\eta' \neq 0$), el CHF y la descripción en el bulk predicen tilts diferentes para el mismo fondo.

---

## 3. Predicción 1: El Plano $(n_s, r)$

### 3.1 El lugar geométrico del CHF (confirmado por el Paso 6)

El Paso 6 derivó el espectro de potencias tensorial desde los modos TT del borde del horizonte aparente y confirmó la relación de consistencia estándar $r = 16\varepsilon$ (véase Paso 6, Sección 8). La ecuación (3) implica entonces:

$$r_{\rm CHF}(\beta_S = 0) = 16\varepsilon = 8(1 - n_s) \tag{4}$$

Esta es una línea en el plano $(n_s, r)$, parametrizada únicamente por $\varepsilon$. Para el valor central de Planck 2018 $n_s = 0.9649$:

$$r_{\rm CHF} = 8 \times 0.0351 = 0.281 \tag{5}$$

La inflación estándar, por el contrario, abarca una región bidimensional en el plano $(n_s, r)$: fijar $n_s$ deja $r = 16\varepsilon = 8(1-n_s) - 8\eta'$ indeterminado (dado que $\eta'$ es libre). El CHF ($\beta_S=0$) colapsa esta región a un único punto.

### 3.2 Tensión con los datos actuales

La cota de Planck 2018 es $r < 0.056$ (al 95\% CL). La predicción del CHF $r \approx 0.281$ se encuentra bien por encima de esta cota. El Paso 6 confirmó $r = 16\varepsilon$, por lo que la tensión es genuina y tiene dos posibles resoluciones:

**(a) El CHF mínimo ($\beta_S = 0$) está falsificado.** Con $r = 16\varepsilon$ confirmado, $\beta_S = 0$ queda excluido observacionalmente al 95\% CL por la combinación $(n_s, r)_{\rm Planck}$. Esto es una falsificación genuina del marco mínimo y un discriminador claro entre el CHF y la inflación estándar (p.ej., la inflación de Starobinsky, que da $r \approx 0.004$ para $N = 55$).

**(b) El campo de horizonte no es mínimo ($\beta_S \neq 0$).** Para $\beta_S \neq 0$, el tilt es $n_s - 1 = -2\varepsilon + 2\beta_S/3$. Con $r = 16\varepsilon$, para $n_s$ fijo:

$$r = 8(1 - n_s) + \frac{16\beta_S}{3} \tag{6}$$

Exigir $r < 0.056$ para $n_s = 0.9649$ da:

$$\frac{16\beta_S}{3} < 0.056 - 0.281 = -0.225 \qquad \Longrightarrow \qquad \beta_S < -0.042 \tag{7}$$

Se requiere un campo de horizonte ligeramente taquiónico ($m_\text{eff}^2 < 0$). Esto no está excluido a priori pero introduce un nuevo parámetro con una restricción de signo. La física es: una masa taquiónica reduce el $\nu$ efectivo y contribuye un corrimiento al azul al tilt, permitiendo que un $n_s$ dado se alcance con $\varepsilon$ menor (y por tanto $r$ menor).

### 3.3 Discriminación del lugar estándar

En el plano $(n_s, r)$, la predicción del CHF (4) se ubica sobre la línea $r = 8(1-n_s)$. Los modelos estándar de inflación de rodadura lenta pueblan una región amplia por debajo de esta línea (dado que $\eta' < 0$ para modelos con potenciales cóncavos, haciendo el tilt más rojo para el mismo $\varepsilon$ y por tanto el mismo $r$). La línea del CHF pasa por encima de la mayoría de las predicciones de modelos estándar (Starobinsky, inflación natural, $\alpha$-atractores) que satisfacen la cota de Planck 2018.

El diagnóstico clave: una medición futura de $r$ por encima de la cota actual (p.ej., $r \sim 0.01$–$0.05$) sería consistente con el CHF de $\beta_S < 0$ pero no con el caso mínimo $\beta_S = 0$. Una medición de $r < 0.01$ restringiría $\beta_S \lesssim -0.065$ y pondría a prueba adicionalmente el marco.

---

## 4. Predicción 2: Ausencia del Segundo Parámetro de Rodadura Lenta

### 4.1 La corrección $\eta'$

En la inflación estándar, el tilt recibe una contribución de $\eta' = d\ln\varepsilon/dN$:

$$\left(n_s - 1\right)_{\rm std} = -2\varepsilon - \eta' \tag{8}$$

En el CHF ($\beta_S = 0$):

$$\left(n_s - 1\right)_{\rm CHF} = -2\varepsilon \tag{9}$$

Para el mismo fondo cosmológico (mismo $\varepsilon(t)$), la diferencia es:

$$\Delta(n_s - 1) \equiv \left(n_s - 1\right)_{\rm CHF} - \left(n_s - 1\right)_{\rm std} = \eta' = \frac{d\ln\varepsilon}{dN} \tag{10}$$

Esta diferencia se anula para la inflación en ley de potencias ($\varepsilon = \text{const}$, $\eta' = 0$) pero es no nula para todos los modelos en los que la tasa de Hubble no desacelera a velocidad constante.

### 4.2 Magnitud y alcance observacional

Para modelos inflacionarios típicos, $|\eta'| \sim |\varepsilon| \sim 0.01$–$0.03$. La medición de Planck 2018 tiene $\sigma(n_s) \approx 0.004$; experimentos futuros (Simons Observatory, CMB-S4, LiteBIRD) esperan alcanzar $\sigma(n_s) \sim 0.002$. La diferencia $|\Delta(n_s-1)| = |\eta'| \sim 0.01$ es potencialmente detectable al nivel de $\sim 5\sigma$ con datos del CMB de próxima generación.

El poder discriminante depende de si $\eta'$ puede restringirse independientemente. Si se mide $r$ (fijando $\varepsilon = r/16$), entonces $\eta'$ es el residuo $\eta' = -(n_s - 1) - 2\varepsilon$ en la inflación estándar, mientras que el CHF predice que este residuo se anula. Una medición conjunta de $(n_s, r)$ con pequeñas incertidumbres distinguiría así entre los dos marcos.

### 4.3 Contenido físico

En el CHF, el tilt tiene un origen termodinámico único: $n_s - 1 = -d\ln S/d\ln a$. La tasa de cambio de entropía del horizonte codifica el tilt completo. No se necesita un segundo parámetro porque el CHF trata $\varepsilon$ como el grado de libertad fundamental, fijando su relación con el espectro a través de la geometría de la ecuación del modo para $z_A = a/\sqrt\varepsilon$. La inflación estándar permite una deformación adicional de la ecuación del modo a través de la curvatura del potencial del inflatón, produciendo el término $\eta'$.

La predicción del CHF $\eta' = 0$ es equivalente a afirmar que **el potencial del inflatón es exponencial** (inflación en ley de potencias), que es el único caso en que el CHF y la inflación estándar coinciden exactamente.

---

## 5. Predicción 3: Corrimiento Espectral desde la Termodinámica del Horizonte

### 5.1 Fórmula del corrimiento en el CHF

El corrimiento del índice espectral se define como $\alpha_s \equiv dn_s/d\ln k \approx d(n_s-1)/dN$ (a orden líder en rodadura lenta, $d\ln k \approx dN$). De la ecuación (3):

$$\alpha_s = \frac{d(n_s-1)}{dN} = -2\frac{d\varepsilon}{dN} = -2\varepsilon\,\eta_\varepsilon \tag{11}$$

donde $\eta_\varepsilon \equiv d\ln\varepsilon/dN$ es la tasa fraccional de cambio de $\varepsilon$ por e-fold.

En lenguaje termodinámico, usando $\varepsilon = \frac{1}{2}d\ln S/d\ln a = \frac{1}{2}d\ln S/dN$:

$$\alpha_s = -\frac{d^2\ln S}{dN^2} \tag{12}$$

El corrimiento del índice espectral iguala **menos la segunda derivada de la entropía del horizonte** respecto al número de e-folds. Esta es una fórmula puramente intrínseca y termodinámica para el corrimiento: sin campo escalar en el bulk, sin potencial, sin energía cinética.

### 5.2 Relación con el corrimiento estándar

En la inflación estándar a orden líder: $\alpha_s = -2\varepsilon\eta_H - \xi^2$, donde $\xi^2 = M_{\rm Pl}^4 V'V'''/(V^2)$ involucra la tercera derivada del potencial. El corrimiento del CHF (11) coincide con el primer término pero no tiene análogo de $\xi^2$, dado que la acción del campo de horizonte no tiene potencial cúbico. Esto predice:

$$\alpha_s^{\rm CHF} = -2\varepsilon\eta_\varepsilon = (1-n_s)\,\eta_\varepsilon \tag{13}$$

Para $n_s = 0.965$ y $\eta_\varepsilon \sim -0.01$: $\alpha_s \approx 3.5\times10^{-4}$, consistente con Planck 2018 ($\alpha_s = -0.0045 \pm 0.0067$).

La predicción diferencial es la ausencia de $\xi^2$: en el CHF, $\alpha_s$ está completamente determinado por $\varepsilon$ y $\eta_\varepsilon$ (ambos expresables en términos de $S$ y sus derivadas), sin parámetro independiente de tercer orden. Una medición de $|\alpha_s|$ significativamente mayor que $(1-n_s)|\eta_\varepsilon|$ sería inconsistente con el CHF mínimo.

### 5.3 Relación de consistencia

Combinando (9) y (13) para el CHF mínimo:

$$\frac{\alpha_s}{(n_s - 1)^2} = \frac{-2\varepsilon\eta_\varepsilon}{4\varepsilon^2} = -\frac{\eta_\varepsilon}{2\varepsilon} = -\frac{d\ln\varepsilon/dN}{d\ln S/dN} \tag{14}$$

Este cociente es una cantidad puramente del horizonte: la tasa de cambio de $\ln\varepsilon$ relativa a la tasa de cambio de $\ln S$. Si la entropía crece a tasa constante ($\eta_\varepsilon = 0$, inflación en ley de potencias), tanto $\alpha_s$ como este cociente se anulan exactamente.

---

## 6. Predicción 4: No-Gaussianidad de Borde Nula

### 6.1 La acción del campo de horizonte es cuadrática

La acción mínima del CHF para el campo de horizonte $\phi(\Omega, t)$ es (ec. (23) del Documento 5):

$$S_\phi = \int dt\, d\Omega\, R_A^2 \left[(\partial_t\phi)^2 + H^2(\nabla_\Omega\phi)^2\right] \tag{15}$$

Esta acción es **puramente cuadrática** en $\phi$: no hay términos de auto-interacción cúbicos ni de orden superior. La cuantización de una acción cuadrática produce un estado de vacío gaussiano. Por tanto, la función de tres puntos $\langle\psi_k\psi_{k'}\psi_{k''}\rangle$ se anula a orden líder desde el campo de borde solo:

$$f_{NL}^{\rm CHF,\, borde} = 0 \tag{16}$$

### 6.2 Predicción de la inflación estándar

En la inflación estándar de campo único con rodadura lenta, la no-gaussianidad es generada por las auto-interacciones del inflatón en el bulk. El resultado líder es (Maldacena 2003):

$$f_{NL}^{\rm std} = \frac{5}{12}(n_s - 1) + \frac{5}{6}\varepsilon + \frac{5}{12}\eta' \approx \mathcal{O}(\varepsilon, \eta') \sim -0.02 \tag{17}$$

Este valor es pequeño pero no nulo. El CHF predice una contribución del borde que es idénticamente nula, mientras que la contribución estándar del bulk (17) solo aparecería si el acoplamiento bulk–borde en el horizonte genera un vértice cúbico efectivo en $\phi$.

### 6.3 Estado observacional y discriminabilidad

La diferencia predicha $|f_{NL}^{\rm CHF} - f_{NL}^{\rm std}| \sim 0.02$ está muy por debajo de la cota actual de Planck 2018 $|f_{NL}| < 5$ y por debajo de la sensibilidad de experimentos futuros (CMB-S4 apunta a $\sigma(f_{NL}) \sim 1$). La no-gaussianidad primordial al nivel $f_{NL} \sim \mathcal{O}(1)$ sería inconsistente tanto con la rodadura lenta estándar como con el CHF mínimo: requeriría un mecanismo inflacionario fundamentalmente diferente.

La utilidad práctica de esta predicción es negativa: una detección futura de $f_{NL} \sim 0.01$ con alta significancia estadística (muy por encima del alcance experimental actual) discriminaría entre los dos marcos. En el futuro observacional previsible, ambos predicen fluctuaciones primordiales efectivamente gaussianas.

---

## 7. Estado Observacional

La siguiente tabla resume las cuatro predicciones diferenciales frente a las restricciones actuales de Planck 2018.

| Predicción | CHF ($\beta_S=0$) | Inflación estándar | Restricción actual | Estado |
|------------|----------------|-------------------|-------------------|--------|
| $r$ dado $n_s = 0.9649$ | $r = 0.281$ | $r \in [0, 0.28]$ (familia 2D) | $r < 0.056$ | **Tensión confirmada** — $r = 16\varepsilon$ por el Paso 6; se requiere $\beta_S < -0.042$ |
| Contribución de $\eta'$ al tilt | $\eta' = 0$ | $\eta'$ libre | $\sigma(n_s) = 0.004$ | No discriminado aún |
| $\alpha_s$ | $-2\varepsilon\eta_\varepsilon$, sin $\xi^2$ | $-2\varepsilon\eta_H - \xi^2$ | $\alpha_s = -0.0045 \pm 0.0067$ | Consistente |
| $f_{NL}$ (borde) | $0$ | $\mathcal{O}(0.01)$ | $|f_{NL}| < 5$ | Consistente, no discriminable |

La única predicción actualmente en tensión es (i) el valor de $r$ del CHF mínimo. El Paso 6 confirmó $r = 16\varepsilon$, estableciendo que el marco mínimo ($\beta_S = 0$) queda excluido por Planck 2018. La consistencia con los datos actuales requiere $\beta_S < -0.042$.

---

## 8. Resolución por el Paso 6 (Perturbaciones Tensoriales)

La Predicción 1 (el lugar en el plano $(n_s, r)$) dependía de si el CHF satisface la relación de consistencia estándar $r = 16\varepsilon$. El Paso 6 derivó el espectro de potencias tensorial desde los dos modos TT de polarización sobre el borde del horizonte aparente.

**Resultado clave del Paso 6:** El campo bomba tensorial es $z_T = a$ (frente a $z_A = a/\sqrt{\varepsilon}$ para escalares). Esta diferencia tiene un origen físico claro — los modos tensoriales son perturbaciones de la *forma* del horizonte (cizallamiento TT sin traza), sin supresión de rodadura lenta, mientras que los modos escalares perturban el *tamaño* ($\psi = \delta R_A/R_A$), suprimido por $\sqrt\varepsilon$. El cálculo da:

$$\Delta_h^2 = \frac{2H^2}{\pi^2 M_{\rm Pl}^2}, \qquad n_T = -2\varepsilon, \qquad r = 16\varepsilon \tag{18}$$

La relación de consistencia estándar $r = -8n_T$ se satisface. La relación de consistencia estándar $r = 16\varepsilon$ queda confirmada.

**Consecuencia para la Predicción 1:** Con $r = 16\varepsilon$ confirmado, el CHF mínimo ($\beta_S = 0$) predice $r \approx 0.281$ para $n_s = 0.9649$. Esto supera la cota de Planck 2018 $r < 0.056$ y el marco mínimo queda excluido al 95\% CL. Se requiere un sector escalar no mínimo con $\beta_S < -0.042$ para la consistencia con los datos actuales.

**Relación adicional del CHF:** El Paso 6 también estableció una relación de consistencia adicional específica del CHF (para $\beta_S = \beta_T = 0$):

$$n_T = n_s - 1 \qquad \Longrightarrow \qquad r = 8(1 - n_s) \tag{19}$$

Esta relación es una predicción diferencial del CHF respecto a la inflación estándar, donde $n_T$ y $n_s - 1$ son independientes al mismo orden de rodadura lenta.

---

## 9. Resumen

| Predicción | Expresión | Observable | Poder discriminante |
|-----------|------------|------------|---------------------|
| Lugar en $(n_s, r)$ | $r = 8(1-n_s)$, confirmado $r=16\varepsilon$ (Paso 6) | Modos $B$ del CMB | Alto — CHF mínimo excluido al 95% CL por Planck 2018 |
| Ausencia de $\eta'$ | $(n_s - 1)_{\rm CHF} - (n_s-1)_{\rm std} = \eta'$ | Futuro $\sigma(n_s) \sim 0.002$ | Moderado — accesible con CMB-S4/LiteBIRD |
| Corrimiento desde termodinámica | $\alpha_s = -d^2\ln S/dN^2$, sin $\xi^2$ | Forma del espectro CMB | Bajo — contribución de $\xi^2$ demasiado pequeña |
| No-gaussianidad de borde | $f_{NL}^{\rm borde} = 0$ | Bispectro CMB | Muy bajo — $|f_{NL}| \sim 0.01$ bajo alcance experimental |

El indicador empírico más inmediato del marco es el valor de $r$. El CHF mínimo ($\beta_S = 0$) predice $r \approx 0.28$; el Paso 6 confirmó $r = 16\varepsilon$, estableciendo esta predicción como genuina y el marco mínimo como excluido al 95\% CL por Planck 2018. La consistencia con los datos actuales requiere $\beta_S < -0.042$. El siguiente observable discriminante es la ausencia de $\eta'$ en el tilt, accesible con experimentos futuros del CMB a $\sigma(n_s) \sim 0.002$.

---

## Referencias

1. Planck Collaboration, "Planck 2018 results. X. Constraints on inflation," *A&A* **641**, A10 (2020).
2. J. M. Maldacena, "Non-Gaussian perturbations in inflationary cosmologies," *JHEP* **0305**, 013 (2003).
3. D. Baumann, "TASI Lectures on Inflation," arXiv:0907.5424 (2009).
4. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Marco del Horizonte Causal, Documento 5 (2025).
5. K. Muñoz, "Scale Invariance from Horizon Field Quantization," Marco del Horizonte Causal (2025).
6. K. Muñoz, "Gauge-Invariant Formulation of the Horizon Perturbation," Marco del Horizonte Causal (2025).
7. K. Muñoz, "Spectral Tilt from Horizon Thermodynamics," Marco del Horizonte Causal (2025).
8. K. Muñoz, "The Boundary–Bulk Relation from the Gauss–Codazzi Equations," Marco del Horizonte Causal (2025).
9. K. Muñoz, "Tensor Perturbations from the Horizon Boundary," Marco del Horizonte Causal (2025).
