# Predicciones Diferenciales del Marco del Horizonte Causal

**Kevin Muñoz**

---

## Resumen

Los Pasos 1–4 del Marco del Horizonte Causal (CHF) derivaron el espectro de potencias escalar primordial íntegramente a partir de la geometría y la termodinámica del horizonte aparente, cerrando las cuatro brechas analíticas del documento de formalización. La fórmula resultante para el tilt es $n_s - 1 = -2\varepsilon + 2\beta_S/3$, con $\varepsilon = \frac{1}{2}d\ln S/d\ln a$ (tasa de entropía del horizonte) y $\beta_S = 0$ para el campo mínimamente acoplado en el horizonte bidimensional. Este documento identifica los observables mediante los cuales el CHF difiere de la inflación estándar de campo único y especifica las condiciones bajo las cuales esas diferencias son medibles. Se establecen cinco predicciones diferenciales. Primera: en el caso mínimo ($\beta_S = 0$), el CHF da $n_s - 1 = -2\varepsilon$ — omitiendo la contribución del segundo parámetro de rodadura lenta $\eta'$ que la inflación estándar permite como grado de libertad independiente. Para el mismo $\varepsilon$ de fondo, los dos marcos predicen tilts que difieren en $\eta'$; experimentos futuros del CMB con $\sigma(n_s) \sim 0.002$ serán sensibles a esto al nivel de $|\eta'| \sim 0.01$. Segunda: la relación de consistencia estándar $r = 16\varepsilon$ fue confirmada en el Paso 6 al derivar los modos tensoriales desde el borde del horizonte, por lo que el CHF predice una línea específica en el plano $(n_s, r)$: $r = 8(1 - n_s)$, correspondiente a $r \approx 0.28$ para el valor central de Planck 2018 $n_s = 0.9649$. Esto está en tensión con la cota actual $r < 0.056$. Con $r = 16\varepsilon$ confirmado por el Paso 6, la tensión es genuina: el marco mínimo ($\beta_S = 0$) queda excluido por Planck 2018, y se requiere $\beta_S < -0.042$. Tercera: el corrimiento $\alpha_s = -d^2\ln S/dN^2$ no contiene término $\xi^2$ de un potencial cúbico. Cuarta: la acción de atrapamiento de Hayward expandida a tercer orden en la perturbación del horizonte $\psi$ genera un vértice cúbico genuino con coeficientes $A_3 = -7/16$ (cinético, $\psi\dot\psi^2$) y $B_3 = +1/4$ (gradiente angular, $\psi(\nabla_\Omega\psi)^2$). El cálculo in-in sobre el worldtube establece dos resultados estructurales: el vértice cinético contribuye idénticamente cero al bispectro para toda configuración de triángulo de momentos, y el vértice de gradiente produce una integral temporal universal igual a $-\pi/2$ para cada triángulo. La no-gaussianidad equilateral resultante es $f_{\rm NL}^{\rm equil, CHF} \approx 1{-}2$ para $\varepsilon = 0.01$ — dentro del umbral de detección de CMB-S4 y LiteBIRD ($\sigma(f_{\rm NL}^{\rm equil}) \sim 1$). Quinta: la función de forma del bispectro es $S_{\rm CHF}(k_1,k_2,k_3) \propto k_1^2+k_2^2+k_3^2$, un template que no se reduce a ninguna combinación lineal de las formas estándar local, equilateral u ortogonal, y que constituye un observable diferencial independiente. Estas predicciones son derivadas, no supuestas, y proporcionan los indicadores empíricos mediante los cuales el CHF puede ser discriminado o falsificado frente al paradigma inflacionario estándar.

---

## 1. Introducción

Un marco teórico gana peso empírico al predecir observables de forma distinta a los marcos existentes. Los Pasos 1–4 del CHF reprodujeron resultados ya obtenidos en la inflación estándar (espectro escala-invariante, fórmula del tilt, relación borde-bulk) desde un punto de partida conceptual diferente — el horizonte, no el inflatón en el bulk. Reproducir resultados conocidos es necesario para la consistencia pero no es suficiente para la discriminación.

Este documento aborda la pregunta de la falsificabilidad: ¿qué predice el CHF de manera diferente a un modelo inflacionario en el bulk operando sobre el mismo fondo? El análisis procede como sigue. La Sección 2 establece la estructura de parámetros del CHF y la compara con la de la inflación estándar. Las Secciones 3–7 derivan las cinco predicciones diferenciales. La Sección 8 resume el estado observacional actual. La Sección 9 registra cómo el Paso 6 resolvió la Predicción 1.

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

## 6. Predicción 4: No-Gaussianidad desde la Acción Cúbica de Hayward

### 6.1 La acción de atrapamiento de Hayward tiene un sector cúbico genuino

La acción libre del campo de horizonte (ec. (23) del Documento 5) es cuadrática en $\phi$. Sin embargo, la condición de atrapamiento de Hayward — la restricción geométrica que define la ubicación del horizonte aparente perturbado — genera términos de orden superior cuando se expande en potencias de $\psi = \delta R_A/R_A$. Específicamente, $\delta^3 S_{\rm trapping}$ produce una acción cúbica no trivial después de que los grandes términos tipo masa $\sim\psi^3/\varepsilon^n$ se cancelan vía la condición de atrapamiento de tercer orden (por el mismo mecanismo que canceló los términos de masa en segundo orden):

$$\delta^3 S_{\rm trapping}\bigg|_{\mathcal{H}} = \frac{M_{\rm Pl}^2\sqrt{2\varepsilon}}{\varepsilon^2 H^3}\int dt\,d\Omega\left[A_3\,\psi\dot\psi^2 + \frac{B_3}{R_A^2}\,\psi(\nabla_\Omega\psi)^2\right] + \mathcal{O}(\varepsilon) \tag{15}$$

Los coeficientes están determinados íntegramente por la geometría de Hayward:

$$A_3 = -\frac{7}{16}, \qquad B_3 = +\frac{1}{4} \tag{16}$$

No entran parámetros libres. $A_3/B_3 = -7/4 \neq -1$ (la razón de Maldacena para la inflación estándar de campo único con rodadura lenta), por lo que la acción cúbica del CHF tiene una ponderación estructuralmente diferente de los vértices cinético y de gradiente.

### 6.2 Cálculo in-in sobre el worldtube

El cálculo in-in de $\langle\psi_{k_1}\psi_{k_2}\psi_{k_3}\rangle$ sobre el worldtube de la dos-esfera produce dos resultados estructurales, válidos para toda configuración de triángulo de momentos $(k_1, k_2, k_3)$:

**Teorema 1 (vértice cinético).** El vértice $A_3\psi\dot\psi^2$ contribuye idénticamente cero al bispectro para todo triángulo de momentos. El integrando temporal $\eta^3(1+ik_i\eta)e^{-iK_t\eta}$ (donde $K_t = k_1+k_2+k_3$) es puramente real para todo $k_i > 0$, por lo que su parte imaginaria se anula.

**Teorema 2 (vértice de gradiente).** La integral temporal del vértice de gradiente $B_3\psi(\nabla_\Omega\psi)^2$ es universal:

$$\mathcal{J}(k_1,k_2,k_3) \equiv {\rm Im}\!\left[\int_{-\infty}^{0}\frac{d\eta}{\eta}(1+ik_1\eta)(1+ik_2\eta)(1+ik_3\eta)e^{-iK_t\eta}\right] = -\frac{\pi}{2} \tag{17}$$

para todo triángulo de momentos cerrado. Solo el polo $1/\eta$ contribuye; todos los términos de orden superior en la expansión del modo son reales.

**Consecuencia.** Toda la información de forma del bispectro del CHF está contenida íntegramente en el acoplamiento angular del vértice de gradiente, sin contribución del vértice cinético.

### 6.3 El parámetro de no-gaussianidad equilateral

El bispectro equilateral del vértice de gradiente, tras integrar sobre la dos-esfera y convertir al espacio de Fourier tridimensional mediante el mapeo de coeficientes de Gaunt (aproximación de Limber, $C_{\rm geom} \approx \pi/8$), da:

$$f_{\rm NL}^{\rm equil, CHF} \approx \frac{3\pi^5\sqrt{2\varepsilon}\,B_3}{16} \times C_{\rm geom} \approx 1{-}2 \qquad (\varepsilon = 0.01) \tag{18}$$

Esto es mayor que el resultado estándar de inflación de campo único con rodadura lenta ($f_{\rm NL}^{\rm equil, std} \sim \mathcal{O}(\varepsilon) \approx 0.01$) en dos órdenes de magnitud, porque en la inflación estándar los vértices cinético y de gradiente se cancelan parcialmente, mientras que en el CHF solo contribuye el vértice de gradiente y no hay cancelación.

### 6.4 Comparación con la inflación estándar

En la inflación estándar de campo único con rodadura lenta (Maldacena 2003):

$$f_{NL}^{\rm equil, std} = \frac{5}{12}(n_s - 1) + \frac{5}{6}\varepsilon + \frac{5}{12}\eta' \approx \mathcal{O}(0.01) \tag{19}$$

La predicción del CHF $f_{\rm NL}^{\rm equil} \approx 1{-}2$ difiere de esto por un factor $\sim 100{-}200$. Tanto CMB-S4 como LiteBIRD esperan alcanzar $\sigma(f_{\rm NL}^{\rm equil}) \sim 1$, colocando la predicción del CHF dentro del umbral de detección de experimentos de próxima generación.

---

## 7. Predicción 5: El Shape del Bispectro del CHF

### 7.1 Función de forma desde el acoplamiento angular

La amplitud del bispectro del Teorema 2 (Sección 6.2) es universal en $\eta$, por lo que toda la dependencia en momentos proviene del acoplamiento angular del vértice de gradiente integrado sobre la dos-esfera. Sumando las tres permutaciones cíclicas del vértice de gradiente $\psi_{k_a}(\nabla_\Omega\psi_{k_b}\cdot\nabla_\Omega\psi_{k_c})$:

$$\sum_{\rm cíclico}\int d\Omega\,\frac{1}{R_A^2}\psi_{k_a}(\nabla_\Omega\psi_{k_b}\cdot\nabla_\Omega\psi_{k_c})\bigg|_{K=0} = \frac{4\pi B_3(k_1^2+k_2^2+k_3^2)}{3H^2} \tag{20}$$

donde la suma $k_1^2+k_2^2+k_3^2$ se obtiene del promedio angular $\int d\Omega(\mathbf{k}_{b\perp}\cdot\mathbf{k}_{c\perp}) = (8\pi/3)(\mathbf{k}_b\cdot\mathbf{k}_c)$ con $\mathbf{k}_b\cdot\mathbf{k}_c = (k_a^2-k_b^2-k_c^2)/2$ (conservación del momento), ciclado sobre las tres permutaciones.

La función de forma del bispectro resultante es:

$$\boxed{S_{\rm CHF}(k_1,k_2,k_3) \propto k_1^2+k_2^2+k_3^2} \tag{21}$$

### 7.2 Propiedades y comparación con los templates estándar

La forma normalizada $s_{\rm CHF}(k_1,k_2,k_3) = (k_1^2+k_2^2+k_3^2)/(3k^2)$ (normalizada a 1 en equiláteral) tiene las siguientes propiedades:

| Configuración | $s_{\rm CHF}$ | Template local | Template equilateral |
|---------------|---------------|----------------|----------------------|
| Equiláteral ($k_1=k_2=k_3$) | $1$ | $\sim 1$ | $1$ |
| Squeezed ($k_3\to 0$) | $2/3$ | $\to \infty$ | $\to 0$ |
| Folded ($k_3 = k_1+k_2$) | $> 1$ | intermedio | suprimido |

El shape del CHF no se reduce a ninguna combinación lineal de los templates estándar local, equilateral u ortogonal. Proyectado sobre la base de templates del CMB, tiene una componente no nula en la dirección ortogonal al template equilateral de Maldacena — un observable puramente diferencial de la geometría del worldtube.

### 7.3 Consistencia con la relación de campo único de Maldacena

En el límite squeezed $k_3 \to 0$, el CHF satisface la relación de consistencia de campo único de Maldacena:

$$\lim_{k_3\to 0}B_{\rm CHF}(k_1,k_2,k_3) = -\frac{5}{12}(n_s-1)\,P_\psi(k_1)P_\psi(k_3) + \mathcal{O}(k_3^0)$$

porque el modo $\psi_k$ se conserva fuera del horizonte de Hubble y el CHF es un marco de campo único. La predicción diferencial no trivial está en las configuraciones equilateral e intermedia — que sondean la interacción en el cruce del horizonte — no en el límite squeezed.

---

## 8. Estado Observacional

La siguiente tabla resume las cinco predicciones diferenciales frente a las restricciones actuales de Planck 2018.

| Predicción | CHF ($\beta_S=0$) | Inflación estándar | Restricción actual | Estado |
|------------|----------------|-------------------|-------------------|--------|
| $r$ dado $n_s = 0.9649$ | $r = 0.281$ | $r \in [0, 0.28]$ (familia 2D) | $r < 0.056$ | **Tensión confirmada** — requiere $\beta_S < -0.042$ |
| Contribución de $\eta'$ al tilt | $\eta' = 0$ | $\eta'$ libre | $\sigma(n_s) = 0.004$ | No discriminado aún |
| $\alpha_s$ | $-2\varepsilon\eta_\varepsilon$, sin $\xi^2$ | $-2\varepsilon\eta_H - \xi^2$ | $\alpha_s = -0.0045 \pm 0.0067$ | Consistente |
| $f_{\rm NL}^{\rm equil}$ (cúbico de Hayward) | $\approx 1{-}2$ ($\varepsilon=0.01$) | $\mathcal{O}(0.01)$ | $|f_{\rm NL}^{\rm equil}| < 100$ (Planck) | **Consistente; al alcance de CMB-S4** |
| Shape: $S_{\rm CHF}\propto k_1^2+k_2^2+k_3^2$ | template nuevo | equilateral/local/ortog | sin búsqueda actual | **Observable diferencial — template nuevo** |

La única predicción actualmente en tensión es (i) el valor de $r$ del CHF mínimo. El Paso 6 confirmó $r = 16\varepsilon$, estableciendo que el marco mínimo ($\beta_S = 0$) queda excluido por Planck 2018. La consistencia con los datos actuales requiere $\beta_S < -0.042$. La Predicción 4 ($f_{\rm NL}^{\rm equil}\approx 1{-}2$) y la Predicción 5 (el shape del bispectro del CHF) son consistentes con todos los datos actuales y serán verificadas por CMB-S4 y LiteBIRD.

---

## 9. Resolución por el Paso 6 (Perturbaciones Tensoriales)

La Predicción 1 (el lugar en el plano $(n_s, r)$) dependía de si el CHF satisface la relación de consistencia estándar $r = 16\varepsilon$. El Paso 6 derivó el espectro de potencias tensorial desde los dos modos TT de polarización sobre el borde del horizonte aparente.

**Resultado clave del Paso 6:** El campo bomba tensorial es $z_T = a$ (frente a $z_A = a/\sqrt{\varepsilon}$ para escalares). Esta diferencia tiene un origen físico claro — los modos tensoriales son perturbaciones de la *forma* del horizonte (cizallamiento TT sin traza), sin supresión de rodadura lenta, mientras que los modos escalares perturban el *tamaño* ($\psi = \delta R_A/R_A$), suprimido por $\sqrt\varepsilon$. El cálculo da:

$$\Delta_h^2 = \frac{2H^2}{\pi^2 M_{\rm Pl}^2}, \qquad n_T = -2\varepsilon, \qquad r = 16\varepsilon \tag{18}$$

La relación de consistencia estándar $r = -8n_T$ se satisface. La relación de consistencia estándar $r = 16\varepsilon$ queda confirmada.

**Consecuencia para la Predicción 1:** Con $r = 16\varepsilon$ confirmado, el CHF mínimo ($\beta_S = 0$) predice $r \approx 0.281$ para $n_s = 0.9649$. Esto supera la cota de Planck 2018 $r < 0.056$ y el marco mínimo queda excluido al 95\% CL. Se requiere un sector escalar no mínimo con $\beta_S < -0.042$ para la consistencia con los datos actuales.

**Relación adicional del CHF:** El Paso 6 también estableció una relación de consistencia adicional específica del CHF (para $\beta_S = \beta_T = 0$):

$$n_T = n_s - 1 \qquad \Longrightarrow \qquad r = 8(1 - n_s) \tag{19}$$

Esta relación es una predicción diferencial del CHF respecto a la inflación estándar, donde $n_T$ y $n_s - 1$ son independientes al mismo orden de rodadura lenta.

---

## 10. Resumen

| Predicción | Expresión | Observable | Poder discriminante |
|-----------|------------|------------|---------------------|
| Lugar en $(n_s, r)$ | $r = 8(1-n_s)$, confirmado $r=16\varepsilon$ (Paso 6) | Modos $B$ del CMB | Alto — CHF mínimo excluido al 95% CL por Planck 2018 |
| Ausencia de $\eta'$ | $(n_s - 1)_{\rm CHF} - (n_s-1)_{\rm std} = \eta'$ | Futuro $\sigma(n_s) \sim 0.002$ | Moderado — accesible con CMB-S4/LiteBIRD |
| Corrimiento desde termodinámica | $\alpha_s = -d^2\ln S/dN^2$, sin $\xi^2$ | Forma del espectro CMB | Bajo — contribución de $\xi^2$ demasiado pequeña |
| No-gaussianidad equilateral | $f_{\rm NL}^{\rm equil} \approx 1{-}2$ ($\varepsilon=0.01$) | Bispectro CMB | **Alto** — al alcance de CMB-S4 ($\sigma\sim 1$); factor $\sim 100$ sobre inflación estándar |
| Shape del bispectro | $S_{\rm CHF}\propto k_1^2+k_2^2+k_3^2$ | Template bispectro CMB | **Alto** — template nuevo; componente ortogonal no nula; sin parámetros libres |

Los indicadores empíricos más inmediatos del marco son el valor de $r$ y la no-gaussianidad primordial. El CHF mínimo ($\beta_S = 0$) predice $r \approx 0.28$ — excluido por Planck 2018 — requiriendo $\beta_S < -0.042$. La no-gaussianidad equilateral $f_{\rm NL}^{\rm equil}\approx 1{-}2$ es la primera predicción del CHF sin parámetros libres que está tanto derivada de la geometría como accesible a experimentos de próxima generación. El shape $S_{\rm CHF}\propto k_1^2+k_2^2+k_3^2$ proporciona un discriminante independiente: una detección del bispectro con este shape identificaría unívocamente el origen en el worldtube de la no-gaussianidad.

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
