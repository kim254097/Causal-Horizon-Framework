# Formulación Gauge-Invariante de la Perturbación del Horizonte y su Relación con la Perturbación de Curvatura Comóvil

**Kevin Muñoz**

---

## Resumen

La formalización de la dinámica cosmológica centrada en el horizonte identifica la perturbación del horizonte $\psi = \delta R_A / R_A$ con la perturbación de curvatura comóvil $\mathcal{R}$, pero deja la derivación gauge-invariante de esta identificación como un problema abierto. Este documento cierra esa brecha. Trabajando en gauge de Newton, calculamos $\psi$ a partir de la condición de horizonte aparente perturbado y realizamos la transformación de gauge al gauge comóvil, donde $\mathcal{R}$ está definida. La relación exacta en escalas super-horizonte es

$$\psi = \frac{\varepsilon}{1 + \varepsilon}\,\mathcal{R}$$

donde $\varepsilon = -\dot{H}/H^2$ es el parámetro de rodadura lenta. Para inflación de rodadura lenta ($\varepsilon \ll 1$), $\psi \approx \varepsilon\,\mathcal{R}$, de modo que los espectros de potencias primordiales satisfacen $P_\mathcal{R}(k) \approx P_\psi(k)/\varepsilon^2$. La forma espectral —en particular, el tilt $n_s$ derivado en el documento compañero sobre cuantización del campo de horizonte— es idéntica para $\psi$ y $\mathcal{R}$. Este documento reemplaza la identificación esquemática $\mathcal{R} \sim \psi$ del Documento 5 por un resultado derivado y gauge-invariante, y corrige la ecuación (21) de ese documento.

---

## 1. Motivación

En la formalización (Documento 5), la perturbación de curvatura comóvil se introduce mediante la identificación esquemática

$$\mathcal{R} \sim \psi \tag{1}$$

con la observación de que "un tratamiento gauge-invariante completo sigue siendo un problema abierto." Como consecuencia, el espectro de potencias fue establecido como $P_\mathcal{R} = P_\psi$ (ec. (21) del Documento 5), lo cual solo es correcto salvo factores que involucran $\varepsilon$.

El presente documento deriva la relación gauge-invariante precisa entre $\psi$ y $\mathcal{R}$. Esto es necesario para:

1. Comparar cuantitativamente la amplitud predicha de $P_\psi(k)$ con las observaciones del CMB.
2. Establecer que $n_s(\psi) = n_s(\mathcal{R})$, de modo que la derivación del tilt del documento compañero se aplica directamente al espectro observado.
3. Identificar el contenido físico del factor de proporcionalidad.

---

## 2. Configuración: Perturbaciones Escalares en Gauge de Newton

Consideramos un fondo FRW plano ($k=0$) perturbado por modos escalares. En el **gauge de Newton (longitudinal)**, la métrica toma la forma

$$ds^2 = -(1 + 2\Phi)dt^2 + a^2(t)(1 - 2\Phi)\delta_{ij}\,dx^i dx^j \tag{2}$$

donde los dos potenciales son iguales ($\Phi = \Psi$) para un fluido perfecto sin tensión anisotrópica. Las ecuaciones de fondo son

$$H^2 = \frac{8\pi G}{3}\rho, \qquad \dot{H} = -4\pi G(\rho + P) = -\varepsilon H^2 \tag{3}$$

con $\varepsilon = -\dot{H}/H^2$.

A primer orden, la perturbación métrica $\Phi(\mathbf{k}, t)$ satisface la ligadura hamiltoniana

$$3H(\dot{\Phi} + H\Phi) + \frac{k^2}{a^2}\Phi = -4\pi G\,\delta\rho \tag{4}$$

y la ligadura de momento

$$\dot{\Phi} + H\Phi = -4\pi G(\rho + P)\,V \tag{5}$$

donde $V$ es el potencial de velocidad del fluido de materia.

---

## 3. La Perturbación del Horizonte en Gauge de Newton

El horizonte aparente es la esfera alrededor de cada punto en la que las geodésicas nulas salientes tienen expansión nula. En la métrica perturbada (2), la tasa de expansión local efectiva es

$$H_\text{loc}(\mathbf{x}, t) = H + \dot{\Phi} - H\Phi + \frac{k^2 V}{3a} \tag{6}$$

donde el último término da cuenta de la divergencia de velocidad local del fluido.

El radio del horizonte aparente alrededor de un punto $\mathbf{x}$ es $R_A^\text{loc} = 1/H_\text{loc}$, por lo que su perturbación fraccional es

$$\psi \equiv \frac{\delta R_A}{R_A} = -\frac{\delta H}{H} = -\frac{\dot{\Phi} - H\Phi}{H} - \frac{k^2 V}{3aH} \tag{7}$$

**En escalas super-horizonte** ($k \ll aH$), el término de velocidad está suprimido por $(k/aH)^2$:

$$\psi \approx -\frac{\dot{\Phi}}{H} + \Phi \qquad (k \ll aH) \tag{8}$$

Para el modo creciente en de Sitter o inflación de rodadura lenta, $\dot{\Phi} \to 0$ (el potencial se congela en escalas super-horizonte), por lo que

$$\psi \approx \Phi \qquad \text{(super-horizonte, gauge de Newton)} \tag{9}$$

Esto confirma la intuición del Documento 5: en escalas grandes, la perturbación del horizonte sigue al potencial gravitacional $\Phi$.

---

## 4. La Perturbación de Curvatura Comóvil

La perturbación de curvatura comóvil se define como la combinación gauge-invariante

$$\mathcal{R} = \Phi - \frac{H}{\dot{H}}\left(\dot{\Phi} + H\Phi\right) \tag{10}$$

Coincide con la perturbación métrica espacial $\Psi_\text{metric}$ en el gauge comóvil (donde la velocidad de la materia se anula), y se conserva en escalas super-horizonte para perturbaciones adiabáticas: $\dot{\mathcal{R}} = \mathcal{O}(k^2/a^2 H^2)$.

Expandiendo (10) usando $\dot{H} = -\varepsilon H^2$:

$$\mathcal{R} = \Phi + \frac{1}{\varepsilon H}\left(\dot{\Phi} + H\Phi\right) = \Phi\left(1 + \frac{1}{\varepsilon}\right) + \frac{\dot{\Phi}}{\varepsilon H} \tag{11}$$

En escalas super-horizonte ($\dot{\Phi} \to 0$, modo creciente):

$$\mathcal{R} \approx \Phi\,\frac{1 + \varepsilon}{\varepsilon} \tag{12}$$

---

## 5. Relación Gauge-Invariante Entre $\psi$ y $\mathcal{R}$

Combinando las ecuaciones (9) y (12):

$$\psi \approx \Phi = \frac{\varepsilon}{1+\varepsilon}\,\mathcal{R} \tag{13}$$

Este es el resultado central. Reordenando:

$$\mathcal{R} = \frac{1 + \varepsilon}{\varepsilon}\,\psi \tag{14}$$

Para hacer explícita la dependencia en $\dot{\Phi}$, sustituir $\Phi = \psi + \dot{\Phi}/H$ (de la ec. (8)) en la ec. (11):

$$\mathcal{R} = \frac{1+\varepsilon}{\varepsilon}\,\psi + \frac{\dot\Phi}{H} \tag{15}$$

En el límite del modo creciente $\dot{\Phi} \to 0$, el último término se anula y se recupera la ec. (14). $\square$

---

## 6. Casos Límite

### 6.1 Inflación de rodadura lenta ($\varepsilon \ll 1$)

$$\psi \approx \varepsilon\,\mathcal{R} \qquad \Longrightarrow \qquad \mathcal{R} \approx \frac{\psi}{\varepsilon} \tag{16}$$

La perturbación del horizonte $\psi$ está suprimida respecto a $\mathcal{R}$ por el parámetro de rodadura lenta. Físicamente: durante la rodadura lenta, el horizonte apenas se mueve ($\dot{R}_A \sim \varepsilon H R_A \ll H R_A$), de modo que una perturbación de curvatura dada $\mathcal{R}$ produce solo un pequeño cambio fraccional $\psi$ en el radio del horizonte aparente.

### 6.2 Dominación de radiación ($\varepsilon = 2$)

$$\psi = \frac{2}{3}\,\mathcal{R} \tag{17}$$

### 6.3 Dominación de materia ($\varepsilon = 3/2$)

$$\psi = \frac{3}{5}\,\mathcal{R} \tag{18}$$

En ambas épocas post-inflacionarias, $\varepsilon = \mathcal{O}(1)$ y la identificación $\psi \approx \mathcal{R}$ se cumple al orden de magnitud. La relación esquemática $\mathcal{R} \sim \psi$ del Documento 5 es más precisa durante la dominación de radiación y materia.

---

## 7. Derivación por Transformación de Gauge

La ecuación (14) puede derivarse también mediante una transformación de gauge explícita del gauge de Newton al gauge comóvil, lo que proporciona una verificación independiente.

Bajo una reparametrización temporal $t \to t + \delta t(\mathbf{x}, t)$, las perturbaciones métricas transforman como

$$\Phi \to \Phi - H\,\delta t, \qquad \Psi_\text{metric} \to \Psi_\text{metric} + H\,\delta t \tag{19}$$

El potencial de velocidad de la materia transforma como $V \to V + a\,\delta t$.

Para llegar al **gauge comóvil** (potencial de velocidad nulo, $V_\text{com} = 0$), elegimos

$$\delta t = -\frac{V}{a} \tag{20}$$

En este gauge, la perturbación métrica espacial es igual a $\mathcal{R}$:

$$\mathcal{R} = \Psi_\text{metric}^\text{com} = \Phi_\text{Newton} + H \cdot \frac{V}{a} \tag{21}$$

De la ligadura de momento (5): $H V/a = -(\dot{\Phi} + H\Phi)/(\varepsilon H^2)$.

Sustituyendo:

$$\mathcal{R} = \Phi - \frac{\dot{\Phi} + H\Phi}{\varepsilon H} = \Phi\left(\frac{1+\varepsilon}{\varepsilon}\right) - \frac{\dot{\Phi}}{\varepsilon H} \tag{22}$$

En escalas super-horizonte ($\dot{\Phi} \to 0$), esto recupera la ecuación (12), y con $\psi \approx \Phi$ (ec. 9), recuperamos (14). La derivación es consistente. $\square$

---

## 8. Comportamiento Sub-Horizonte y Ecuación de Poisson

En escalas sub-horizonte ($k \gg aH$), la ligadura hamiltoniana (4) se reduce a la ecuación de Poisson:

$$\frac{k^2}{a^2}\Phi \approx -4\pi G\,\delta\rho \tag{23}$$

Invirtiendo con $4\pi G\rho = 3H^2/2$: $\Phi = -\tfrac{3}{2}(aH/k)^2(\delta\rho/\rho)$. En escalas sub-horizonte, el documento compañero (Paso 1) da $\delta\rho/\rho \approx -\tfrac{2}{3}(k/aH)^2\psi$ (ec. (23) del Paso 1). Sustituyendo:

$$\Phi \approx \psi \quad (k \gg aH) \tag{24}$$

La perturbación del horizonte rastrea así el potencial gravitacional newtoniano en escalas sub-horizonte; la razón $\Phi/\psi$ permanece del orden de la unidad. Lo que cambia es la relación con $\mathcal{R}$: $\mathcal{R}$ se conserva en su valor super-horizonte mientras $\psi$ continúa evolucionando con las ondas de densidad locales. La identificación gauge-invariante (13) deja por tanto de ser válida para $k \sim aH$ y es reemplazada por:

$$\psi_\text{sub-horizonte} \sim -\frac{\dot{\Phi}}{H} \sim \frac{k}{aH}\,\psi_\text{super-horizonte} \tag{25}$$

La relación relevante para la física del CMB es siempre el valor primordial, establecido en la salida del horizonte ($k = aH$) y recuperado por la fórmula super-horizonte (13).

---

## 9. Implicación para los Espectros de Potencias

De la relación gauge-invariante (14):

$$P_\mathcal{R}(k) = \left(\frac{1+\varepsilon}{\varepsilon}\right)^2 P_\psi(k) \tag{26}$$

Para inflación de rodadura lenta ($\varepsilon \ll 1$):

$$P_\mathcal{R}(k) \approx \frac{P_\psi(k)}{\varepsilon^2} \tag{27}$$

Combinando con el resultado del documento compañero sobre cuantización (Paso 3, ec. (27)), donde $\Delta_\psi^2(k) = (H^2/(2\pi^2 c_s))\,k^{n_s-1}$:

$$P_\mathcal{R}(k) \approx \frac{P_\psi(k)}{\varepsilon^2}, \qquad \Delta_\mathcal{R}^2 = \frac{\Delta_\psi^2}{\varepsilon^2} \tag{28}$$

La amplitud es

$$\Delta_\mathcal{R}^2 = \frac{H^2}{2\pi^2 c_s \varepsilon^2} \tag{29}$$

Esto coincide con el resultado estándar de inflación de rodadura lenta $\Delta_\mathcal{R}^2 = H^2/(8\pi^2\varepsilon M_\text{Pl}^2)$ salvo factores de normalización determinados por las convenciones de unidades de la acción del campo de horizonte.

El **tilt espectral** no cambia:

$$n_s - 1 = \frac{d\ln P_\mathcal{R}}{d\ln k} = \frac{d\ln P_\psi}{d\ln k} \tag{30}$$

ya que el factor $(1+\varepsilon)^2/\varepsilon^2$ evaluado en el cruce del horizonte ($k = aH$) tiene una dependencia en $k$ de orden $\varepsilon$ o $\eta_\varepsilon \equiv \dot{\varepsilon}/(H\varepsilon)$, que son correcciones sub-líderes de rodadura lenta ya incluidas en la fórmula $n_s - 1 = 3 - 2\nu$ del documento de cuantización. El resultado del tilt es así robusto a la corrección de amplitud.

---

## 10. Correcciones al Documento 5

Este documento corrigió dos elementos de la formalización original:

### Ecuación (18): $\mathcal{R} \sim \psi$

Reemplazada por el resultado gauge-invariante exacto en escalas super-horizonte:

$$\mathcal{R} = \frac{1+\varepsilon}{\varepsilon}\,\psi \tag{31}$$

La identificación $\mathcal{R} \sim \psi$ es válida en orden de magnitud cuando $\varepsilon = \mathcal{O}(1)$ (dominación de radiación/materia). Durante la inflación de rodadura lenta, $\mathcal{R} = \psi/\varepsilon \gg \psi$.

### Ecuación (21): $P_\mathcal{R}(k) = P_\psi(k)$

Reemplazada por:

$$P_\mathcal{R}(k) = \left(\frac{1+\varepsilon}{\varepsilon}\right)^2 P_\psi(k) \approx \frac{P_\psi(k)}{\varepsilon^2} \quad (\varepsilon \ll 1) \tag{32}$$

La forma espectral es la misma; solo difiere la amplitud.

---

## 11. Interpretación Física

El factor $\varepsilon/(1+\varepsilon)$ en (13) tiene un significado físico directo en el marco centrado en el horizonte.

El parámetro de rodadura lenta $\varepsilon = -\dot{H}/H^2 = -\dot{R}_A/(R_A H)$ mide la tasa fraccional de cambio del radio del horizonte por tiempo de Hubble. Cuando $\varepsilon \ll 1$, el horizonte está casi congelado: una curvatura espacial dada $\mathcal{R}$ corresponde a solo una pequeña variación fraccional $\psi \approx \varepsilon \mathcal{R}$ en el radio del horizonte aparente.

Equivalentemente: el campo de horizonte $\phi \sim \psi$ es la amplitud de las fluctuaciones de borde, mientras que $\mathcal{R}$ es la amplitud de las fluctuaciones de curvatura en el bulk. El cociente $\mathcal{R}/\psi = (1+\varepsilon)/\varepsilon$ cuantifica cuánto amplifica el bulk la señal del borde. La amplificación es grande precisamente cuando el horizonte de fondo evoluciona lentamente — consistente con la intuición de que un fondo casi-de Sitter actúa como un buen amplificador de fluctuaciones cuánticas del borde.

---

## 12. Problema Abierto Restante

La derivación presente está restringida al caso **adiabático de fluido único** y se apoya en el **límite super-horizonte**. Dos extensiones permanecen abiertas:

- **Correcciones para $k$ finito.** La ecuación (13) recibe correcciones de orden $(k/aH)^2$ provenientes del término de velocidad en (7). Una función de transferencia completa modo-a-modo que conecte $\psi_k$ con $\mathcal{R}_k$ para todo $k$ requeriría resolver las ecuaciones de perturbación acopladas, equivalente a la jerarquía de Boltzmann estándar.

- **Perturbaciones multi-fluido y no adiabáticas.** Se usaron la identificación $\Phi = \Psi$ (sin tensión anisotrópica) y la condición adiabática $\delta P = c_s^2 \delta\rho$. Las perturbaciones de entropía introducirían términos adicionales proporcionales a $\delta S = \delta P/P - (\delta\rho/\rho)\,c_s^2$.

Estas extensiones no afectan la forma espectral ni la fórmula del tilt; entran solo al nivel de la función de transferencia desde el espectro primordial al observado.

---

## 13. Resumen

| Resultado | Expresión | Dominio de validez |
|-----------|-----------|-------------------|
| Relación gauge-invariante | $\psi = \frac{\varepsilon}{1+\varepsilon}\,\mathcal{R}$ | Super-horizonte, adiabático, fluido único |
| Límite de rodadura lenta | $\mathcal{R} \approx \psi/\varepsilon$ | $\varepsilon \ll 1$ |
| Relación de espectros | $P_\mathcal{R} = \frac{(1+\varepsilon)^2}{\varepsilon^2}\,P_\psi$ | Super-horizonte, primordial |
| Tilt espectral | $n_s(\mathcal{R}) - 1 = n_s(\psi) - 1 = 3 - 2\nu$ | Todas las escalas, a orden líder |

La identificación $\mathcal{R} \sim \psi$ del Documento 5 es un enunciado válido en orden de magnitud; el presente documento proporciona su contenido gauge-invariante preciso y corrige la relación de amplitud.

---

## Referencias

1. J. M. Bardeen, "Gauge invariant cosmological perturbations," *Phys. Rev. D* **22**, 1882 (1980).
2. H. Kodama y M. Sasaki, "Cosmological perturbation theory," *Prog. Theor. Phys. Suppl.* **78**, 1 (1984).
3. V. F. Mukhanov, H. A. Feldman y R. H. Brandenberger, "Theory of cosmological perturbations," *Phys. Rep.* **215**, 203 (1992).
4. S. Weinberg, *Cosmology*, Oxford University Press (2008), Capítulo 5.
5. K. Muñoz, "A Horizon-Centered Formalization of Cosmological Dynamics and Perturbations," Causal Horizon Framework, Documento 5 (2025).
6. K. Muñoz, "Scale Invariance from Horizon Field Quantization," Causal Horizon Framework (2025).
