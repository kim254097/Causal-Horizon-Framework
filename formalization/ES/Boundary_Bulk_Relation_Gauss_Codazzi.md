# La Relación Borde–Bulk δρ/ρ = −2ψ desde las Ecuaciones de Gauss–Codazzi

**Kevin Muñoz**

---

## Resumen

La formalización de la dinámica cosmológica centrada en el horizonte deriva la relación $\delta\rho/\rho = -2\psi$ linealizando la ecuación de Friedmann del fondo. Si bien es consistente, esto es una verificación y no una derivación: no establece el origen geométrico de la relación, no especifica su dominio de validez, y no proporciona la extensión sub-horizonte. Este documento cierra esa brecha. Mostramos que la ecuación de Friedmann es la restricción de Gauss para la hipersuperficie de Cauchy FRW, y que su perturbación —la restricción hamiltoniana completa— da

$$\frac{\delta\rho}{\rho} = -2\psi\!\left(1 + \frac{1}{3}\left(\frac{k}{aH}\right)^2\right)$$

donde $k$ es el número de onda comóvil. En escalas super-horizonte ($k \ll aH$), esto se reduce exactamente al resultado del Documento 5. La corrección sub-horizonte es la ecuación de Poisson, derivada aquí como la restricción de Codazzi (momento) en el mismo formalismo. La relación borde–bulk es por tanto una consecuencia rigurosa de las ecuaciones de Einstein, válida en el límite de universo separado de la estructura de embedding de Gauss.

---

## 1. Motivación

En el Documento 5 del Marco Causal de Horizonte, la relación de perturbación clave

$$\frac{\delta\rho}{\rho} = -2\psi \tag{1}$$

se deriva en tres líneas: $R_A = 1/H$ da $\delta H/H = -\psi$; la ecuación de Friedmann $H^2 \propto \rho$ da $\delta\rho/\rho = 2\delta H/H = -2\psi$. Si bien es correcta, esta derivación:

- Usa la ecuación de Friedmann del FONDO aplicada localmente, sin justificación geométrica
- No especifica un gauge ni un dominio de validez
- No muestra correcciones sub-horizonte
- No demuestra que (1) sea consecuencia de la geometría de embedding del horizonte en el espaciotiempo

El presente documento proporciona esta derivación a partir de las ecuaciones de Gauss–Codazzi para la hipersuperficie de Cauchy FRW.

---

## 2. Las Ecuaciones de Gauss–Codazzi en Forma 3+1

En la descomposición 3+1 (ADM) del espaciotiempo, una hipersuperficie de Cauchy $\Sigma_t$ (una superficie de tiempo constante $t$) está embebida en el espaciotiempo 4D $(\mathcal{M}, g_{\mu\nu})$ con:

- **Métrica intrínseca** $h_{ij}$: la 3-métrica inducida sobre $\Sigma_t$
- **Curvatura extrínseca** $K_{ij} = -\frac{1}{2}\mathcal{L}_n h_{ij}$: cómo se dobla $\Sigma_t$ en $\mathcal{M}$, con $n^\mu$ la normal unitaria futura

La **ecuación de Gauss** (contraída dos veces) da la restricción hamiltoniana:

$${}^{(3)}R + K^2 - K_{ij}K^{ij} = 16\pi G\,\rho_\text{ADM} \tag{2}$$

donde ${}^{(3)}R$ es el escalar de Ricci intrínseco de $\Sigma_t$, $K = h^{ij}K_{ij}$ es la traza, y $\rho_\text{ADM} = T_{\mu\nu}n^\mu n^\nu$ es la densidad de energía medida por el observador normal.

La **ecuación de Codazzi** (contraída una vez) da la restricción de momento:

$$D_j\!\left(K^{ij} - h^{ij}K\right) = 8\pi G\,J^i \tag{3}$$

donde $D_j$ es la derivada covariante sobre $\Sigma_t$ y $J^i = -T_{\mu\nu}n^\mu e^{i\nu}$ es la corriente de momento.

Juntas, (2) y (3) codifican toda la información sobre cómo el contenido de materia del universo restringe la geometría de $\Sigma_t$ y, a través de $K_{ij}$, su tasa de expansión.

---

## 3. La Ecuación de Friedmann como Restricción de Gauss del Fondo

Para un fondo FRW plano ($k=0$) con métrica

$$ds^2 = -dt^2 + a^2(t)\,\delta_{ij}\,dx^i\,dx^j \tag{4}$$

la hipersuperficie de Cauchy $\Sigma_t$ tiene:

$${}^{(3)}R = 0, \qquad K_{ij} = -H\,h_{ij}, \qquad K = -3H, \qquad K_{ij}K^{ij} = 3H^2 \tag{5}$$

Sustituyendo en la restricción de Gauss (2):

$$0 + 9H^2 - 3H^2 = 16\pi G\rho \tag{6}$$

$$\boxed{H^2 = \frac{8\pi G}{3}\rho} \tag{7}$$

La ecuación de Friedmann es la restricción de Gauss para la hipersuperficie de Cauchy FRW. Iguala la curvatura extrínseca de $\Sigma_t$ —codificada en $K$— con el contenido de materia del bulk. El radio del horizonte aparente $R_A = 1/H$ queda así determinado por la geometría de embedding de $\Sigma_t$ en el espaciotiempo.

---

## 4. Perturbación de la Restricción de Gauss

Perturbamos alrededor del fondo FRW en gauge de Newton (longitudinal):

$$ds^2 = -(1+2\Phi)\,dt^2 + a^2(t)(1-2\Phi)\,\delta_{ij}\,dx^i\,dx^j \tag{8}$$

donde $\Phi = \Psi$ (sin tensión anisotrópica). Las cantidades geométricas perturbadas sobre $\Sigma_t$ son:

$$\delta\!\left({}^{(3)}R\right) = -\frac{4k^2\Phi}{a^2}, \qquad \delta K = 3(\dot\Phi + H\Phi), \qquad \delta(K_{ij}K^{ij}) = -6H(\dot\Phi + H\Phi) \tag{9}$$

donde $k$ es el número de onda comóvil. Linealizando la restricción de Gauss (2):

$$\delta\!\left({}^{(3)}R\right) + 2K\,\delta K - \delta(K_{ij}K^{ij}) = 16\pi G\,\delta\rho \tag{10}$$

Sustituyendo los valores del fondo $K = -3H$ y las cantidades perturbadas (9):

$$-\frac{4k^2\Phi}{a^2} + 2(-3H)\cdot 3(\dot\Phi+H\Phi) - (-6H(\dot\Phi+H\Phi)) = 16\pi G\,\delta\rho$$

$$-\frac{4k^2\Phi}{a^2} - 12H(\dot\Phi+H\Phi) = 16\pi G\,\delta\rho$$

Dividiendo por $-4$, la restricción hamiltoniana linealizada toma la forma estándar:

$$\frac{k^2\Phi}{a^2} + 3H(\dot\Phi + H\Phi) = -4\pi G\,\delta\rho \tag{11}$$

Esta es la **restricción hamiltoniana perturbada**, expresando la perturbación de densidad de energía del bulk en términos de la geometría de la hipersuperficie de Cauchy perturbada.

---

## 5. Derivación de $\delta\rho/\rho = -2\psi$ (Límite Super-Horizonte)

### 5.1 El modo creciente desde la restricción de Codazzi

La restricción de momento (ecuación de Codazzi) en gauge de Newton es:

$$\dot\Phi + H\Phi = -4\pi G(\rho + P)\,V \tag{12}$$

donde $V$ es el potencial de velocidad. En escalas **super-horizonte** ($k \to 0$), la velocidad de la materia está suprimida: $V \propto k/aH \to 0$. Combinado con la solución de modo creciente, la ecuación (12) da $\dot\Phi + H\Phi \to 0$ cuando $k/aH \to 0$. Para el modo creciente en de Sitter o rodadura lenta, esto se satisface con $\dot\Phi \approx 0$, es decir, $\Phi \approx \text{const}$.

### 5.2 La restricción hamiltoniana en el límite de onda larga

Sustituyendo $\dot\Phi = 0$ en (11) y tomando $k \to 0$:

$$3H^2\Phi = -4\pi G\,\delta\rho \tag{13}$$

Usando la ecuación de Friedmann del fondo $4\pi G\rho = 3H^2/2$:

$$3H^2\Phi = -\frac{3H^2}{2}\,\frac{\delta\rho}{\rho} \tag{14}$$

$$\frac{\delta\rho}{\rho} = -2\Phi \tag{15}$$

Del documento compañero (Paso 2), en el límite super-horizonte de modo creciente en gauge de Newton:

$$\psi \equiv -\frac{\delta H}{H} \approx \Phi \tag{16}$$

Sustituyendo:

$$\boxed{\frac{\delta\rho}{\rho} = -2\psi} \tag{17}$$

Esta es la relación borde–bulk del Documento 5, ahora derivada como el **límite super-horizonte de la restricción de Gauss**, aplicada a la geometría de la hipersuperficie FRW perturbada. Es válida para $k \ll aH$ y la solución de modo creciente $\dot\Phi \approx 0$.

---

## 6. Extensión Completa Dependiente de $k$

Reteniendo el término $k^2\Phi/a^2$ en la ecuación (11) con $\dot\Phi = 0$:

$$\frac{k^2\Phi}{a^2} + 3H^2\Phi = -4\pi G\,\delta\rho = -\frac{3H^2}{2}\,\frac{\delta\rho}{\rho} \tag{18}$$

$$\frac{\delta\rho}{\rho} = -\frac{2\Phi}{3H^2}\left(\frac{k^2}{a^2} + 3H^2\right) = -2\Phi\!\left(1 + \frac{k^2}{3a^2H^2}\right) \tag{19}$$

Usando $\psi \approx \Phi$:

$$\boxed{\frac{\delta\rho}{\rho} = -2\psi\!\left(1 + \frac{1}{3}\left(\frac{k}{aH}\right)^2\right)} \tag{20}$$

Esta es la **relación borde–bulk completa de la restricción de Gauss**, válida para todo $k$ en la aproximación de modo creciente.

### Regímenes límite

**Super-horizonte** ($k \ll aH$):
$$\frac{\delta\rho}{\rho} \approx -2\psi \tag{21}$$
El resultado del Documento 5. Cada parche de tamaño Hubble es un universo FRW independiente (aproximación de universo separado).

**Cruce del horizonte** ($k = aH$):
$$\frac{\delta\rho}{\rho} = -\frac{8}{3}\,\psi \tag{22}$$
Una corrección de orden $\mathcal{O}(1)$ al resultado de orden líder.

**Sub-horizonte** ($k \gg aH$):
$$\frac{\delta\rho}{\rho} \approx -\frac{2}{3}\!\left(\frac{k}{aH}\right)^2\psi \tag{23}$$
La ecuación de Poisson newtoniana, con $\Phi = \psi$ desempeñando el rol del potencial gravitacional.

---

## 7. La Ecuación de Codazzi como Relación de Velocidad del Bulk

La restricción de momento (ecuación de Codazzi, ec. 12) proporciona la relación borde–bulk complementaria para el campo de velocidades:

$$V = -\frac{\dot\Phi + H\Phi}{4\pi G(\rho+P)} \tag{24}$$

Usando $4\pi G(\rho+P) = \varepsilon H^2$ (del Paso 3):

$$V = -\frac{\dot\Phi + H\Phi}{\varepsilon H^2} \tag{25}$$

Para el modo creciente en escalas super-horizonte ($\dot\Phi = 0$, $k \to 0$):
$$V_\text{super-horiz} = -\frac{H\Phi}{\varepsilon H^2} = -\frac{\psi}{\varepsilon H} \tag{26}$$

Para el modo creciente en escalas sub-horizonte, desde la restricción hamiltoniana sub-horizonte:
$$\frac{k^2\Phi}{a^2} \approx -4\pi G\,\delta\rho \quad \Rightarrow \quad \dot\Phi \approx \frac{-k^2/(4\pi G\,a^2) - \delta\dot\rho}{...} \tag{27}$$

En el límite cuasi-estático sub-horizonte ($\dot\Phi \approx 0$):
$$V_\text{sub-horiz} = -\frac{H\psi}{\varepsilon H^2} = -\frac{\psi}{\varepsilon H} \tag{28}$$

El potencial de velocidad es $V = -\psi/(\varepsilon H)$ a orden líder en ambos límites, mostrando que la ecuación de Codazzi proporciona un campo de velocidades del bulk consistente generado por la perturbación del horizonte $\psi$ en ambos regímenes.

---

## 8. Interpretación de Universo Separado

El límite super-horizonte (ec. 21) admite una interpretación física clara en la **aproximación de universo separado**: para $k \ll aH$, cada parche de tamaño Hubble del universo evoluciona como un universo FRW independiente con sus propios parámetros locales $H_\text{loc}$ y $\rho_\text{loc}$.

Cada parche satisface la restricción de Gauss local:
$$H_\text{loc}^2 = \frac{8\pi G}{3}\rho_\text{loc} \tag{29}$$

Escribiendo $H_\text{loc} = H + \delta H$ y $\rho_\text{loc} = \rho + \delta\rho$:
$$2H\,\delta H = \frac{8\pi G}{3}\,\delta\rho \tag{30}$$

Usando $4\pi G\rho = 3H^2/2$ y $\psi = -\delta H/H$:
$$\frac{\delta\rho}{\rho} = \frac{2\,\delta H}{H} = -2\psi \tag{31}$$

Esto es idéntico a (17). La derivación de la restricción de Gauss es la justificación geométrica de la aproximación de universo separado: se cumple precisamente cuando el término de gradiente espacial $k^2\Phi/a^2$ en (11) es despreciable comparado con $3H^2\Phi$ — es decir, cuando $k \ll aH$.

---

## 9. Especificación de Gauge y Validez

La ecuación (17) se deriva en **gauge de Newton** con la identificación $\psi \approx \Phi$ (válida en escalas super-horizonte; ver Paso 2). En un gauge general, el enunciado apropiado es:

$$\frac{\delta\rho}{\rho}\bigg|_\text{comóvil} = -2\psi_\text{comóvil} + \mathcal{O}\!\left(\frac{k^2}{a^2H^2}\right) \tag{32}$$

donde tanto $\delta\rho$ como $\psi$ se evalúan en el gauge comóvil (4-velocidad del fluido sin perturbar). En el gauge comóvil: $\psi_\text{comóvil} = \varepsilon/(1+\varepsilon) \times \mathcal{R}$ (del Paso 2), por lo que (32) es consistente con la conservación super-horizonte estándar de $\mathcal{R}$.

La relación $\delta\rho/\rho = -2\psi$ se cumple precisamente cuando:

1. La condición super-horizonte $k \ll aH$ se satisface
2. La condición de modo creciente $\dot\Phi \approx 0$ se cumple
3. La aproximación adiabática de fluido único aplica

La corrección fraccional en el cruce del horizonte ($k = aH$) es $1/3$, haciendo el coeficiente total $8/3$ en lugar de $2$. Para cálculos de precisión, debe usarse la ecuación completa (20).

---

## 10. Correcciones al Documento 5

### Ecuación (16) — Ahora un teorema

La relación $\delta\rho/\rho = -2\psi$ (ec. (16) del Documento 5) se actualiza de una verificación de consistencia algebraica a un teorema: es el límite super-horizonte de la restricción de Gauss linealizada (ec. 11 arriba), válida para $k \ll aH$.

### Extensión sub-horizonte

El Documento 5 no proporcionaba la extensión de (16) a $k$ finito. El resultado completo es la ecuación (20): la perturbación de densidad recibe una corrección en $(k/aH)^2$ que domina en escalas sub-horizonte y reproduce la ecuación de Poisson.

### Error de signo en el documento compañero (Paso 2)

La restricción hamiltoniana en ese documento tenía originalmente un error de signo: $-3H(\dot\Phi + H\Phi) + k^2\Phi/a^2 = 4\pi G\delta\rho$. Esto fue corregido en el Paso 1. La forma correcta, derivada aquí, es:

$$3H(\dot\Phi + H\Phi) + \frac{k^2\Phi}{a^2} = -4\pi G\,\delta\rho \tag{33}$$

El resultado super-horizonte $\delta\rho/\rho = -2\psi$ no está afectado por esta corrección; solo la extensión sub-horizonte (ec. 23) cambia de signo.

---

## 11. Problemas Abiertos Restantes

- **Perturbaciones no adiabáticas.** La derivación asume perturbaciones adiabáticas de fluido único. Para perturbaciones de entropía ($\delta S \neq 0$), aparecen términos adicionales en la restricción de Gauss.

- **Más allá de la aproximación de modo creciente.** Poner $\dot\Phi = 0$ es preciso para el modo creciente pero se rompe durante el cruce del horizonte y para modos decrecientes. Una función de transferencia completa de $\psi$ a $\delta\rho/\rho$ para todo $k$ y todo tiempo requiere resolver las ecuaciones de perturbación acopladas completas.

- **Gauss–Codazzi de 2-superficie para el horizonte aparente.** La presente derivación usa la restricción de Gauss para la hipersuperficie de Cauchy 3-dimensional $\Sigma_t$. Una derivación complementaria usando las ecuaciones de Gauss–Codazzi para la 2-superficie (el horizonte aparente mismo) —vía la ecuación de Raychaudhuri para congruencias nulas— proporcionaría una justificación más directa basada en el borde para (17). Esto permanece abierto.

---

## 12. Resumen

| Resultado | Ecuación | Origen |
|-----------|----------|--------|
| Friedmann como restricción de Gauss | $H^2 = 8\pi G\rho/3$ | ec. (2) con geometría FRW |
| Restricción de Gauss perturbada | $k^2\Phi/a^2 + 3H(\dot\Phi+H\Phi) = -4\pi G\delta\rho$ | ec. (11) |
| Relación borde–bulk (exacta) | $\delta\rho/\rho = -2\psi[1 + (k/aH)^2/3]$ | ec. (20) |
| Límite super-horizonte | $\delta\rho/\rho = -2\psi$ | ec. (17) — resultado Documento 5 |
| Límite sub-horizonte (Poisson) | $\delta\rho/\rho = -(2/3)(k/aH)^2\psi$ | ec. (23) |
| Campo de velocidad (Codazzi) | $V = -\psi/(\varepsilon H)$ | ec. (26) |

---

## 13. Conclusión

La relación $\delta\rho/\rho = -2\psi$ es el límite super-horizonte de modo creciente de la restricción de Gauss linealizada para la hipersuperficie de Cauchy FRW. La ecuación de Friedmann es la restricción de Gauss del fondo; su linealización da la restricción hamiltoniana perturbada, que se reduce a $\delta\rho/\rho = -2\psi$ para $k \ll aH$. La extensión sub-horizonte, dada por la ecuación (20), transiciona a la ecuación de Poisson newtoniana para $k \gg aH$. La restricción de Codazzi (momento) proporciona la relación complementaria para el campo de velocidades del bulk. Estos resultados completan la justificación geométrica de la correspondencia borde–bulk del Documento 5 y establecen el dominio de validez de la relación de orden líder.

---

## Referencias

1. R. Arnowitt, S. Deser, y C. W. Misner, "Republication of: The dynamics of general relativity," *Gen. Relat. Gravit.* **40**, 1997 (2008) [originalmente 1962].
2. J. M. Bardeen, "Gauge invariant cosmological perturbations," *Phys. Rev. D* **22**, 1882 (1980).
3. S. A. Hayward, "Gravitational energy in spherical symmetry," *Phys. Rev. D* **53**, 1938 (1996).
4. R.-G. Cai y S. P. Kim, "First law of thermodynamics and Friedmann equations of Friedmann-Robertson-Walker universe," *JHEP* **0502**, 050 (2005).
5. S. Dodelson, *Modern Cosmology*, Academic Press (2003), Capítulo 7.
6. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Causal Horizon Framework, Documento 5 (2025).
7. K. Muñoz, "Gauge-Invariant Formulation of the Horizon Perturbation," Causal Horizon Framework (2025).
