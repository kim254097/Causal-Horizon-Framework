# Una Formalización Centrada en el Horizonte de la Dinámica Cosmológica y las Perturbaciones

**Kevin Muñoz**

---

## Resumen

Desarrollamos una formalización centrada en el horizonte de la dinámica cosmológica y las perturbaciones, en la cual el horizonte aparente se trata como el grado de libertad físico primario. Construyendo sobre un marco conceptual previamente introducido, mostramos que la dinámica estándar de Friedmann puede recuperarse a partir de la termodinámica de horizontes y que las perturbaciones cosmológicas pueden describirse consistentemente como fluctuaciones de la frontera causal.

Derivamos una cadena lineal cerrada de perturbaciones que conecta las fluctuaciones del horizonte con las perturbaciones de densidad y con la perturbación de curvatura comóvil. Bajo supuestos estadísticos mínimos, el marco reproduce un espectro casi invariante de escala compatible con las observaciones. El enfoque permanece plenamente consistente con la Relatividad General y la fenomenología estándar, mientras proporciona una interpretación basada en el borde de la evolución cosmológica.

---

## 1. Introducción

La cosmología estándar describe el universo en términos de la dinámica del espacio-tiempo de bulk gobernada por la Relatividad General, con la expansión codificada en el factor de escala $a(t)$. Los horizontes se tratan típicamente como estructuras derivadas.

En contraste, la termodinámica de horizontes sugiere que las fronteras causales codifican información físicamente relevante, con entropía que escala con el área en lugar del volumen. Esto motiva perspectivas alternativas en las que los horizontes causales desempeñan un papel estructuralmente primario.

El presente trabajo proporciona una realización formal de un marco centrado en el horizonte en el que la dinámica cosmológica y las perturbaciones se describen en términos del horizonte aparente. El objetivo no es modificar la Relatividad General, sino reformular su contenido cosmológico en términos de accesibilidad causal y termodinámica de borde.

La recuperación termodinámica de la ecuación de Friedmann en la Sección 3 sigue el enfoque de Cai y Kim (2005), quienes demostraron por primera vez esta derivación para horizontes aparentes FRW. El presente trabajo la extiende desarrollando un pipeline de perturbaciones — que vincula las fluctuaciones del horizonte con las perturbaciones de densidad y la estructura espectral (Secciones 4–11) — no abordado en la literatura previa de gravedad termodinámica.

---

## 2. Geometría de Fondo y Variable del Horizonte

Consideramos un espacio-tiempo homogéneo e isótropo con parámetro de Hubble:

$$H = \frac{\dot{a}}{a} \tag{1}$$

El radio del horizonte aparente es:

$$R_A = \frac{1}{\sqrt{H^2 + \frac{k}{a^2}}} \tag{2}$$

Para geometría espacialmente plana ($k = 0$):

$$R_A = \frac{1}{H} \tag{3}$$

Tomamos $R_A(t)$ como la variable fundamental, interpretando la evolución cosmológica como el crecimiento de un dominio causalmente accesible.

---

## 3. Termodinámica del Horizonte y Dinámica de Fondo

Asignamos cantidades termodinámicas al horizonte:

$$S = \frac{A}{4G} = \frac{\pi R_A^2}{G} \tag{4}$$

$$T = \frac{1}{2\pi R_A} \tag{5}$$

$$V = \frac{4}{3}\pi R_A^3 \tag{6}$$

$$E = \rho V \tag{7}$$

Imponemos el primer principio:

$$dE = T\,dS - P\,dV \tag{8}$$

Usando la conservación de energía:

$$\dot{\rho} + 3H(\rho + P) = 0 \tag{9}$$

y $R_A = 1/H$, obtenemos:

$$\dot{H} = -4\pi G(\rho + P) \tag{10}$$

que se integra a:

$$H^2 = \frac{8\pi G}{3}\rho + C \tag{11}$$

Así, la dinámica estándar de Friedmann se recupera a partir de la termodinámica de horizontes. Para geometría espacialmente plana ($k = 0$), la constante de integración $C$ se anula, recuperando la ecuación de Friedmann plana estándar $H^2 = \frac{8\pi G}{3}\rho$. Todo el análisis de perturbaciones posterior asume este caso plano.

---

## 4. Perturbaciones del Horizonte

Introducimos perturbaciones en el radio del horizonte:

$$R_A(t, \mathbf{x}) = \bar{R}_A(t)\left[1 + \psi(t, \mathbf{x})\right] \tag{12}$$

donde:

$$\psi = \frac{\delta R_A}{R_A} \tag{13}$$

es adimensional y se trata como la variable de perturbación fundamental.

---

## 5. Relación con la Expansión y las Perturbaciones de Densidad

Usando $H = 1/R_A$, obtenemos a orden lineal:

$$\frac{\delta H}{H} = -\psi \tag{14}$$

A partir de la ecuación de Friedmann (válida para $k = 0$, caso de un solo fluido):

$$H^2 \propto \rho \tag{15}$$

obtenemos:

$$\frac{\delta\rho}{\rho} = 2\frac{\delta H}{H} = -2\psi \tag{16}$$

Por tanto:

$$\delta\rho \propto \psi \tag{17}$$

---

## 6. Relación con la Perturbación de Curvatura

Identificamos la perturbación de curvatura comóvil como:

$$\mathcal{R} \sim \psi \tag{18}$$

Esta identificación refleja que $\psi$ controla directamente la expansión local. Un tratamiento completo gauge-invariante sigue siendo un problema abierto.

---

## 7. Descripción Estadística

Asumimos estadística gaussiana:

$$\langle\psi(\mathbf{k})\psi(\mathbf{k}')\rangle = (2\pi)^3\delta(\mathbf{k} + \mathbf{k}')P_\psi(k) \tag{19}$$

con:

$$P_\psi(k) = Ak^{n_s - 1} \tag{20}$$

Entonces:

$$P_\mathcal{R}(k) = P_\psi(k) \tag{21}$$

---

## 8. Campo Efectivo del Horizonte

Introducimos un campo escalar efectivo definido sobre el horizonte:

$$\phi(\Omega, t) \tag{22}$$

con acción:

$$S = \int dt\, d\Omega\, R_A^2 \left[(\partial_t\phi)^2 + \frac{c_s^2}{R_A^2}(\nabla_\Omega\phi)^2 + m_\text{eff}^2\phi^2\right] \tag{23}$$

e identificamos:

$$\psi \sim \phi \tag{24}$$

---

## 9. Estructura de Modos y Congelamiento

Expandiendo en armónicos esféricos:

$$\phi = \sum_{l,m} \phi_{lm}(t) Y_{lm}(\Omega) \tag{25}$$

la frecuencia del modo es:

$$\omega_l^2 = \frac{c_s^2}{R_A^2}l(l+1) + m_\text{eff}^2 \tag{26}$$

Los modos se congelan cuando:

$$\omega \sim H \tag{27}$$

Usando $R_A = 1/H$, esto da:

$$l \sim kR_A \tag{28}$$

---

## 10. Espectro

Adoptamos como hipótesis estadística mínima la forma de correlación escala-invariante (no derivada de la acción de la ec. (23)):

$$\langle\phi(x)\phi(0)\rangle \sim \frac{1}{|x|^\alpha} \tag{29}$$

Esto da:

$$P(k) \sim k^{\alpha - 3} \tag{30}$$

Para $\alpha \approx 3$:

$$n_s \approx 1 \tag{31}$$

Introduciendo:

$$m_\text{eff}^2 = \beta_S H^2 \tag{32}$$

se obtiene:

$$n_s - 1 \approx -2\beta_S \tag{33}$$

El coeficiente $-2$ sigue por analogía con la dinámica de un campo escalar en un fondo de de Sitter; una derivación rigurosa a partir de la acción del campo del horizonte (23) sigue siendo un problema abierto.

---

## 11. Conexión con los Observables

El espectro angular de potencia está dado por:

$$C_\ell = 4\pi \int \frac{dk}{k} P_\mathcal{R}(k) |\Delta_\ell(k)|^2 \tag{34}$$

con:

$$\ell \sim kr_* \tag{35}$$

---

## 12. Interpretación

El marco proporciona una descripción dual:

- **Estándar:** los campos de bulk generan perturbaciones
- **Centrado en el horizonte:** las fluctuaciones del borde codifican las perturbaciones

---

## 13. Limitaciones y Problemas Abiertos

- Sin modelo microscópico de los grados de libertad del horizonte
- Relación gauge-invariante $\mathcal{R} = [(1+\varepsilon)/\varepsilon]\,\psi$ y corrección de amplitud $P_\mathcal{R} \approx P_\psi/\varepsilon^2$ derivadas en el documento compañero *Gauge-Invariant Formulation of the Horizon Perturbation*
- Espectro escala-invariante (ec. 29) e inclinación espectral (ec. 33) derivados desde cuantización canónica y condiciones de Bunch–Davies en *Scale Invariance from Horizon Field Quantization*
- Tilt expresado como tasa de entropía del horizonte $n_s - 1 = -(d\ln S)/(d\ln a)$ y masa efectiva derivada de la estructura conforme 2D en *Spectral Tilt from Horizon Thermodynamics*
- Perturbaciones tensoriales derivadas en *Tensor Perturbations from the Horizon Boundary*: $n_T = -2\varepsilon$, $\Delta_h^2 = 2H^2/(\pi^2 M_{\rm Pl}^2)$, $r = 16\varepsilon$, CHF mínimo excluido al 95% CL; se requiere $\beta_S < -0.042$
- Pendiente: determinación dinámica de $\varepsilon$ desde el propio marco; función de transferencia sub-horizonte

---

## 14. Conclusión

Hemos construido una formalización centrada en el horizonte de la dinámica cosmológica y las perturbaciones que reproduce los resultados estándar mientras proporciona una interpretación basada en el borde. El marco es compatible con la Relatividad General y los datos observacionales, e identifica un conjunto claro de problemas abiertos para desarrollo futuro.

---

## Referencias

1. J. D. Bekenstein, "Black holes and entropy," *Phys. Rev. D* **7**, 2333 (1973).
2. S. W. Hawking, "Particle creation by black holes," *Commun. Math. Phys.* **43**, 199 (1975).
3. G. W. Gibbons y S. W. Hawking, "Cosmological event horizons, thermodynamics, and particle creation," *Phys. Rev. D* **15**, 2738 (1977).
4. T. Jacobson, "Thermodynamics of spacetime: The Einstein equation of state," *Phys. Rev. Lett.* **75**, 1260 (1995).
5. R.-G. Cai y S. P. Kim, "First law of thermodynamics and Friedmann equations of Friedmann-Robertson-Walker universe," *JHEP* **0502**, 050 (2005).
6. T. Padmanabhan, "Thermodynamical aspects of gravity: New insights," *Phys. Rep.* **531**, 115 (2013).
7. V. Mukhanov, *Physical Foundations of Cosmology*, Cambridge University Press (2005).
