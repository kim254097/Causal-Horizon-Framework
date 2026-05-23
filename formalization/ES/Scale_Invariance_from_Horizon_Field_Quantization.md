# Invarianza de Escala a partir de la Cuantización del Campo de Horizonte

**Kevin Muñoz**

---

## Resumen

La formalización de la dinámica cosmológica centrada en el horizonte introdujo un campo escalar efectivo $\phi(\Omega, t)$ sobre el horizonte aparente, cuyo espectro de potencias fue adoptado como hipótesis estadística mínima en lugar de derivarse desde primeros principios. Este documento cierra esa brecha. Mostramos que la cuantización canónica de $\phi$, combinada con una identificación natural entre los modos angulares sobre el horizonte y los modos de Fourier comóviles en el bulk, produce una ecuación modal de tipo Mukhanov–Sasaki. Con condiciones iniciales de Bunch–Davies, esta ecuación genera un espectro de potencias invariante de escala al momento del congelamiento como consecuencia de la estructura del vacío cuántico del campo, no como supuesto. El índice espectral $n_s - 1 = 3 - 2\nu$ se deriva del potencial efectivo que gobierna los modos del horizonte, con $\nu$ determinado por la masa efectiva $m_\text{eff}^2$ y la tasa de variación del radio del horizonte. Este trabajo reemplaza la ecuación (29) y la fórmula del tilt (33) del documento de formalización por resultados derivados.

---

## 1. Motivación

En la formalización centrada en el horizonte (Documento 5 del Marco Causal de Horizonte), el horizonte aparente porta un campo escalar efectivo $\phi(\Omega, t)$ con acción

$$S = \int dt\, d\Omega\, R_A^2 \left[(\partial_t \phi)^2 + \frac{c_s^2}{R_A^2}(\nabla_\Omega \phi)^2 + m_\text{eff}^2 \phi^2\right] \tag{1}$$

y la identificación $\psi \sim \phi$ vincula las fluctuaciones de borde con la variable de perturbación cosmológica $\psi = \delta R_A / R_A$.

Dos resultados quedaron sin derivar:

- **Ecuación (29):** $\langle \phi(x)\phi(0) \rangle \sim |x|^{-\alpha}$ adoptada como hipótesis estadística.
- **Ecuación (33):** $n_s - 1 \approx -2\beta_S$ enunciada por analogía con la teoría de campo escalar en de Sitter.

Derivamos ambas a partir de la acción (1) mediante cuantización canónica.

---

## 2. Identificación del Modo Comóvil

El campo $\phi(\Omega, t)$ vive sobre una dos-esfera de radio físico $R_A(t) = 1/H(t)$. Un modo armónico esférico $Y_{lm}$ corresponde a una escala angular $\theta \sim \pi / l$, es decir, a una escala física $\lambda_\text{fís} \sim \pi R_A / l = \pi / (lH)$ sobre el horizonte.

En el bulk, un modo de Fourier comóvil con número de onda $k$ tiene longitud de onda física $\lambda_\text{fís} = 2\pi a / k$, luego su número de onda físico es $k_\text{fís} = k/a$.

Igualando $k_\text{fís}$ con la escala angular sobre el horizonte:

$$k_\text{fís} = \frac{k}{a(t)} \quad \longleftrightarrow \quad l_k(t) = \frac{k_\text{fís}(t)}{H(t)} = \frac{k}{a(t)\,H(t)} \tag{2}$$

Esta es la identificación del modo comóvil: un número de onda comóvil $k$ corresponde al modo angular $l_k(t)$ en el tiempo $t$. La correspondencia depende del tiempo porque $a(t)H(t)$ evoluciona. Para de Sitter, $H = \text{const}$ y $a(t) = e^{Ht}$, de modo que

$$l_k(t) = \frac{k}{H}\,e^{-Ht} \tag{3}$$

$l_k$ decrece monótonamente. En tiempos tempranos ($t \to -\infty$), $l_k \to \infty$: el modo oscila rápidamente sobre el horizonte. A medida que el universo se expande, $l_k \to 1$, lo que define el tiempo de congelamiento

$$t_k: \quad l_k(t_k) = 1 \quad \Longrightarrow \quad k = a(t_k)\,H \tag{4}$$

Esta es precisamente la condición estándar de cruce del horizonte $k_\text{fís} = H$.

---

## 3. Cuantización Canónica

Para cada modo $(l, m)$, la acción (1) se reduce a

$$S_{lm} = \int dt\, R_A^2(t)\left[\dot{\phi}_{lm}^2 - \omega_l^2(t)\,\phi_{lm}^2\right] \tag{5}$$

con frecuencia modal

$$\omega_l^2(t) = \frac{c_s^2\,l(l+1)}{R_A^2(t)} + m_\text{eff}^2(t) \tag{6}$$

Definimos la variable canónica

$$v_{lm}(t) \equiv R_A(t)\,\phi_{lm}(t) \tag{7}$$

cuyo término cinético tiene coeficiente unitario. Sustituyendo e integrando por partes se obtiene la acción

$$S_{lm} = \int dt\left[\dot{v}_{lm}^2 - \Omega_l^2(t)\,v_{lm}^2\right] \tag{8}$$

con frecuencia efectiva

$$\Omega_l^2(t) = \omega_l^2(t) - \frac{\ddot{R}_A}{R_A} \tag{9}$$

El momento canónico es $\pi_{lm} = 2\dot{v}_{lm}$ y la ecuación de movimiento es

$$\ddot{v}_{lm} + \Omega_l^2(t)\,v_{lm} = 0 \tag{10}$$

Promovemos $v_{lm}$ a operador e imponemos $[\hat{v}_{lm}, \hat{\pi}_{l'm'}] = i\delta_{ll'}\delta_{mm'}$. Expandiendo en funciones modales:

$$\hat{v}_{lm}(t) = v_l^{\,}(t)\,\hat{a}_{lm} + v_l^*(t)\,\hat{a}_{lm}^\dagger \tag{11}$$

donde $v_l(t)$ satisface (10) con normalización $v_l \dot{v}_l^* - v_l^* \dot{v}_l = i/2$.

---

## 4. Ecuación de Mukhanov–Sasaki para Modos del Horizonte

### 4.1 Reformulación en tiempo conforme

Introducimos el tiempo conforme $d\eta = dt/a(t)$, con $' \equiv d/d\eta$. Para un fondo FRW plano con $H(t)$:

$$R_A = \frac{1}{H}, \qquad \frac{\dot{R}_A}{R_A} = -\frac{\dot{H}}{H^2} = \varepsilon H \tag{12}$$

donde $\varepsilon \equiv -\dot{H}/H^2 \geq 0$ es el parámetro de rodadura lenta.

Usando la identificación del modo comóvil (2), la frecuencia efectiva (9) evaluada en $l = l_k(\eta)$ en tiempo conforme toma la forma

$$\Omega_k^2(\eta) = c_s^2 k^2 - \frac{z_A''}{z_A} \tag{13}$$

donde $z_A(\eta) \equiv a(\eta)/\sqrt{\varepsilon(\eta)}$. La variable $u_k \equiv z_A \psi_k$ satisface entonces

$$u_k'' + \left[c_s^2 k^2 - \frac{z_A''}{z_A}\right]u_k = 0 \tag{14}$$

Esta es la **ecuación de Mukhanov–Sasaki** para la perturbación del horizonte $\psi_k$, derivada aquí directamente desde la acción (1) mediante la identificación del modo comóvil.

### 4.2 Potencial efectivo para de Sitter

Para de Sitter con $H = \text{const}$, $\varepsilon = 0$. Incluyendo $m_\text{eff}^2 = \beta_S H^2$ como corrección pequeña, el potencial efectivo toma la forma

$$\frac{z_A''}{z_A} = \frac{\nu^2 - \frac{1}{4}}{\eta^2} \tag{15}$$

con

$$\nu^2 = \frac{9}{4} - \frac{m_\text{eff}^2}{H^2} = \frac{9}{4} - \beta_S \tag{16}$$

La ecuación modal queda

$$u_k'' + \left[c_s^2 k^2 - \frac{\nu^2 - \frac{1}{4}}{\eta^2}\right]u_k = 0 \tag{17}$$

---

## 5. Vacío de Bunch–Davies y Congelamiento

### 5.1 Condiciones iniciales

En tiempos tempranos ($k_\text{fís} \gg H$, equivalentemente $|k\eta| \gg 1$), el modo $k$ se encuentra bien dentro del horizonte y el término de potencial $(\nu^2 - 1/4)/\eta^2$ es despreciable. La ecuación (17) se reduce a un oscilador libre:

$$u_k'' + c_s^2 k^2\, u_k = 0 \tag{18}$$

Imponemos la condición inicial de Bunch–Davies (frecuencia positiva):

$$u_k(\eta) \xrightarrow{|k\eta| \to \infty} \frac{1}{\sqrt{2c_s k}}\,e^{-ic_s k\eta} \tag{19}$$

Esta es la única elección compatible con el vacío de Minkowski local a distancias cortas.

### 5.2 Solución exacta

La solución general de (17) regular para $k\eta \to -\infty$ es una función de Hankel de primera especie:

$$u_k(\eta) = \frac{\sqrt{\pi}}{2}\,e^{i(\nu + \frac{1}{2})\frac{\pi}{2}}\,\sqrt{-\eta}\,H_\nu^{(1)}(-c_s k\eta) \tag{20}$$

normalizada para satisfacer (19). Para argumento pequeño $|k\eta| \to 0$ (super-horizonte, tras el congelamiento):

$$|u_k(\eta)|^2 \xrightarrow{|k\eta| \to 0} \frac{2^{2\nu-3}\Gamma(\nu)^2}{\pi c_s k}\,\left(\frac{1}{-k\eta}\right)^{2\nu - 1} \tag{21}$$

### 5.3 Amplitud al congelamiento

Al congelamiento, $k = a(t_k)H$, lo que en tiempo conforme para de Sitter da $k\eta_k = -1$. La variable centrada en el horizonte $\psi_k = u_k / z_A$ con $z_A = a = -1/(H\eta)$:

$$|\psi_k(\eta_k)|^2 = \frac{|u_k(\eta_k)|^2}{a^2(\eta_k)} \tag{22}$$

Usando (21) evaluada cerca de $|k\eta| = 1$:

$$|\psi_k|_\text{cong}^2 \approx \frac{2^{2\nu - 3}\,\Gamma(\nu)^2}{\pi}\,\frac{H^2}{c_s k^3}\,(1 + \mathcal{O}(\beta_S)) \tag{23}$$

---

## 6. Invarianza de Escala

El espectro de potencias adimensional de $\psi$ es

$$\Delta_\psi^2(k) \equiv \frac{k^3}{2\pi^2}\,P_\psi(k) = \frac{k^3}{2\pi^2} \times 2|\psi_k|^2 \tag{24}$$

Sustituyendo (23):

$$\Delta_\psi^2(k) = \frac{2^{2\nu-2}\,\Gamma(\nu)^2}{\pi^3}\,\frac{H^2}{c_s}\,(k^{n_s - 1}) \tag{25}$$

donde

$$n_s - 1 = 3 - 2\nu \tag{26}$$

**Para el caso sin masa** $\beta_S = 0$: $\nu = 3/2$, luego $n_s - 1 = 0$.

El espectro de potencias es exactamente invariante de escala:

$$\Delta_\psi^2(k)\big|_{\beta_S=0} = \frac{H^2}{2\pi^2 c_s} = \text{const} \tag{27}$$

Este es el resultado principal: **la invarianza de escala no es una hipótesis estadística sino una consecuencia del vacío de Bunch–Davies y el mecanismo de congelamiento en de Sitter**, aplicados al campo del horizonte mediante la identificación del modo comóvil (2).

La función de dos puntos en espacio de posiciones se sigue directamente de (27):

$$\langle\phi(x)\phi(0)\rangle \sim \frac{1}{|x|^{2\nu}} = \frac{1}{|x|^3} \quad (\beta_S = 0) \tag{28}$$

recuperando la ecuación (29) del documento de formalización con $\alpha = 3$ como consecuencia de $\nu = 3/2$.

---

## 7. Índice Espectral

### 7.1 Corrección de masa

Para $m_\text{eff}^2 = \beta_S H^2$ con $|\beta_S| \ll 1$:

$$\nu = \sqrt{\frac{9}{4} - \beta_S} \approx \frac{3}{2} - \frac{\beta_S}{3} \tag{29}$$

El índice espectral:

$$n_s - 1 = 3 - 2\nu \approx 3 - \left(3 - \frac{2\beta_S}{3}\right) = \frac{2\beta_S}{3} \tag{30}$$

Una masa efectiva positiva $\beta_S > 0$ produce un leve tilt azul; un campo ligeramente taquiónico $\beta_S < 0$ produce un tilt rojo compatible con las observaciones.

### 7.2 Corrección de rodadura lenta

Cuando $H$ varía lentamente ($\varepsilon \ll 1$, $|\dot{\varepsilon}| \ll H\varepsilon$), el potencial efectivo recibe correcciones:

$$\frac{z_A''}{z_A} = \frac{1}{\eta^2}\left(2 + 3\varepsilon + \cdots\right) \tag{31}$$

lo que conduce a

$$\nu \approx \frac{3}{2} + \varepsilon - \frac{\beta_S}{3} \tag{32}$$

y

$$n_s - 1 \approx -2\varepsilon + \frac{2\beta_S}{3} \tag{33}$$

El tilt rojo observado $n_s \approx 0.965$ se reproduce para $\varepsilon \approx 0.02$ con $\beta_S \approx 0$, o para una combinación de $\varepsilon$ y $\beta_S$ no nulos.

### 7.3 Comparación con el Documento 5

La ecuación (33) del documento de formalización enunciaba originalmente $n_s - 1 \approx -2\beta_S$ sin derivación. Desde el análisis presente, esto corresponde a la parametrización

$$\nu \equiv \frac{3}{2} + \beta_\nu \quad \Longrightarrow \quad n_s - 1 = -2\beta_\nu \tag{34}$$

donde $\beta_\nu = \varepsilon - \beta_S/3$ combina el parámetro de rodadura lenta y la corrección de masa. La fórmula (33) del Documento 5 se recupera con la identificación $\beta_S \to \beta_\nu$: un parámetro compuesto que captura tanto la variación lenta del horizonte como la masa efectiva de $\phi$.

---

## 8. Imagen Física

La derivación admite una interpretación física clara.

En tiempos tempranos, cada modo comóvil $k$ se ubica en $l_k \gg 1$ sobre el horizonte. Su frecuencia $\omega_l = c_s l H \gg H$ lo sitúa en el régimen oscilatorio, bien aproximado por el vacío de Minkowski (19).

A medida que el universo se expande, $l_k(t) = k\,e^{-Ht}/H$ decrece. Cuando $l_k \to 1$ (congelamiento), la longitud de onda física del modo alcanza la escala de Hubble. En ese momento, la incertidumbre cuántica en $\phi_l$ se vuelve clásica: la amplitud del modo queda fijada por la fluctuación de vacío $\langle|\phi_l|^2\rangle \sim H^2 / \omega_l \sim H$ (en $l = 1$).

Como $H$ es el mismo para todos los modos al congelamiento en de Sitter, cada modo adquiere la misma amplitud independientemente de $k$. Este es el origen de la invarianza de escala: es consecuencia de la simetría de traslación temporal de de Sitter combinada con el hecho de que el congelamiento siempre ocurre en $l_k = 1$.

---

## 9. Conexión con el Documento 5

Este documento reemplaza dos problemas abiertos de la formalización:

| Ítem | Estado original en Documento 5 | Estado presente |
|------|-------------------------------|-----------------|
| Ec. (29): $\langle\phi(x)\phi(0)\rangle \sim |x|^{-\alpha}$ | Hipótesis estadística mínima | Derivada del vacío BD: $\alpha = 2\nu = 3 - (n_s - 1)$ |
| Ec. (33): $n_s - 1 \approx -2\beta_S$ | Analogía con escalar de de Sitter | Derivada: $n_s - 1 = 3 - 2\nu$, con $\nu(\beta_S, \varepsilon)$ de la ec. (32) |

La derivación utiliza la acción (23) del Documento 5 sin modificación. El único ingrediente adicional es la identificación del modo comóvil (2) y la condición inicial de Bunch–Davies (19).

---

## 10. Problemas Abiertos

Quedan las siguientes brechas:

- **Evolución dinámica de $m_\text{eff}$.** La relación $m_\text{eff}^2 = \beta_S H^2$ se asume constante. Un modelo dinámico que relacione $\beta_S$ con el contenido de materia haría la ecuación (33) predictiva.

- **Origen microscópico.** El vacío de Bunch–Davies se impone como condición UV natural; su justificación desde un modelo microscópico de los grados de libertad del horizonte permanece abierta.

Las dos brechas listadas en la versión original de esta sección han sido cerradas: la identificación gauge-invariante $\mathcal{R} = [(1+\varepsilon)/\varepsilon]\psi$ fue derivada de forma exacta en el Paso 2, y el espectro de potencias tensorial fue derivado desde los modos del borde del horizonte en el Paso 6.

---

## 11. Conclusión

La cuantización canónica del campo de horizonte $\phi(\Omega, t)$, combinada con la identificación del modo comóvil $l_k(t) = k/(a(t)H(t))$, produce una ecuación modal de tipo Mukhanov–Sasaki. Con condiciones iniciales de Bunch–Davies, esta ecuación genera un espectro de potencias invariante de escala al congelamiento como resultado derivado. El índice espectral es $n_s - 1 = 3 - 2\nu$, con $\nu$ controlado por la masa efectiva $m_\text{eff}^2 = \beta_S H^2$ y el parámetro de rodadura lenta $\varepsilon$. Los dos problemas abiertos centrales del Documento 5 —ecuaciones (29) y (33)— quedan cerrados.

---

## Referencias

1. V. Mukhanov y G. Chibisov, "Quantum fluctuations and a nonsingular universe," *JETP Lett.* **33**, 532 (1981).
2. S. W. Hawking, "The development of irregularities in a single bubble inflationary universe," *Phys. Lett. B* **115**, 295 (1982).
3. V. F. Mukhanov, H. A. Feldman y R. H. Brandenberger, "Theory of cosmological perturbations," *Phys. Rep.* **215**, 203 (1992).
4. R.-G. Cai y S. P. Kim, "First law of thermodynamics and Friedmann equations of Friedmann-Robertson-Walker universe," *JHEP* **0502**, 050 (2005).
5. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Causal Horizon Framework, Documento 5 (2025).
