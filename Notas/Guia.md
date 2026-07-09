### Clase 1: Fundamentos Analíticos y Formalismo de la Zeta-Regularización
**Objetivo:** Establecer las bases matemáticas rigurosas de cómo asignar valores finitos a sumas y productos infinitos divergentes mediante la continuación analítica.
**Subtemas:**
1. **El problema de la divergencia:** Series de Dirichlet, productos infinitos y la necesidad de métodos de regularización en matemáticas y física.
2. **Definición formal del producto y suma Zeta-regularizada:** 
   * Construcción de la función zeta asociada a una secuencia $\zeta_\Lambda(s) = \sum \lambda_i^{-s}$.
   * Continuación analítica al plano complejo y evaluación en $s=0$ (o cálculo del residuo si hay polo).
   * La fórmula maestra: $\prod \lambda_i = \exp(-\zeta_\Lambda'(0))$.
3. **Propiedades algebraicas básicas:** Linealidad, particiones de conjuntos y el comportamiento ante escalas ($\prod a\lambda_i$).
4. **Ejemplos clásicos y la Fórmula de Lerch:** 
   * El producto de todos los números naturales ($\sqrt{2\pi}$).
   * Derivación de la Fórmula de Lerch generalizada y su conexión con la función Gamma y el teorema de los productos de Weierstrass.
5. **Series de potencias finitas y la función Zeta de Hurwitz:** Uso de $\zeta(s, a)$ para evaluar sumas desplazadas y su expansión asintótica.

### Clase 2: Justificación Física y Aplicaciones en Teoría Cuántica de Campos
**Objetivo:** Demostrar que la zeta-regularización no es solo un "truco matemático", sino que surge naturalmente de la sustracción de energías de referencia en sistemas físicos reales.
**Subtemas:**
1. **El significado físico de la regularización:** Energías de punto cero, cortes (cut-offs) energéticos finitos y la resta de estados de referencia ($\Delta \Omega = \Omega(B) - \Omega(0)$).
2. **El Efecto Casimir en geometría de placas paralelas:**
   * Formulación de la energía del vacío entre placas conductoras.
   * Regularización de la suma $\sum n^3$ mediante la función Zeta de Riemann y Hurwitz.
   * Demostración de cómo los términos divergentes (proporcionales a $m^4, m^3$) se cancelan exactamente al introducir el estado de referencia $V(0)$.
3. **Magnetización del Grafeno y Niveles de Landau:**
   * Potencial termodinámico en fermiones de Dirac bajo un campo magnético.
   * Límite de campo fuerte/baja temperatura y límite de campo débil/alta temperatura.
   * Cómo la expansión asintótica de $\zeta(-1/2, m+1)$ justifica la aparición de $\zeta(-1/2)$ en la respuesta física observable.
4. **Equivalencia de métodos:** Derivación alternativa usando diferencias finitas ($\delta B, \delta d$) y límites de cortes cuantizados.

### Clase 3: Teoría de Números, Primos y Fronteras Naturales
**Objetivo:** Explorar las aplicaciones en teoría de números analítica, enfrentando el reto de las "fronteras naturales" donde la continuación analítica estándar falla.
**Subtemas:**
1. **La Función Zeta Prima $P(s)$:** Definición, conexión con la función Zeta de Riemann mediante la inversión de Möbius y el producto de Euler.
2. **El obstáculo de la Frontera Natural:** Por qué $P(s)$ no es analítica alrededor de $s=0$ (acumulación de cortes de rama logarítmicos en el eje imaginario).
3. **Superando la Frontera (Método de Muñoz García y Pérez-Marco):**
   * Uso de la identidad de Artin-Hasse y la función de Möbius para evaluar $P'(0)$.
   * El producto de todos los números primos: $\Pi = 4\pi^2$.
   * La suma regularizada de todos los números primos $P(-1)$ y el cruce de la frontera natural.
4. **Generalización a Campos Cuadráticos Imaginarios:**
   * Enteros de Gauss ($\mathbb{Z}[i]$) y de Eisenstein ($\mathbb{Z}[\omega]$).
   * Funciones Zeta de Dedekind y funciones L de Dirichlet.
   * La ley de potencia universal: Relación entre el producto de enteros y primos en los 9 campos con factorización única ($|\Pi_\Delta| = |P_\Delta|^{2w_\Delta}$).

### Clase 4: Secuencias Automáticas, Combinatoria y Ecuaciones Funcionales
**Objetivo:** Estudiar la regularización aplicada a subconjuntos no triviales de los enteros definidos por propiedades combinatorias o de base.
**Subtemas:**
1. **Números Odiosos y Malvados (Evil numbers):** Definición basada en la paridad de la suma de los dígitos en base 2 y su conexión con la secuencia de Thue-Morse.
2. **Series de Dirichlet para secuencias automáticas:** Construcción de $\zeta_O(s)$ y $\zeta_E(s)$ y su relación con la función Zeta de Riemann.
3. **Ecuaciones funcionales infinitas:** Uso de relaciones de recurrencia para la continuación analítica de series asociadas a secuencias de Thue-Morse.
4. **Cálculo de productos regulados exóticos:**
   * Evaluación del producto de todos los números odiosos.
   * Aparición de la constante de Euler-Mascheroni ($\gamma$) y la constante de Flajolet-Martin ($\phi$).
5. **Generalizaciones y secuencias desplazadas:** Análisis de conjuntos como $OS = \{n+1 \mid n \in O\}$ y el uso de la función $f(s)$ de Hurwitz generalizada.

### Clase 5: Funciones Superzeta, Geometría Espectral y Anomalías Multiplicativas
**Objetivo:** Alcanzar el estado del arte de la investigación actual, estudiando funciones zeta construidas sobre los ceros de otras funciones zeta y las anomalías algebraicas que surgen.
**Subtemas:**
1. **Funciones Superzeta (Voros, Friedman, Jorgenson):**
   * Definición de $Z_f(s, z) = \sum (z - y_k)^{-s}$ donde $y_k$ son los ceros de una función entera $f$.
   * Continuación meromorfa mediante transformadas integrales de Mellin de $f'/f$.
2. **Aplicación a la Función Zeta de Selberg:**
   * Variedades hiperbólicas de volumen finito con cúspides.
   * Evaluación de productos regulados sobre ceros no triviales, ceros triviales y polos de la matriz de dispersión (Scattering matrix).
   * Determinantes regularizados del Laplaciano y el operador de dispersión de Lax-Phillips.
3. **Productos Trigonométricos sobre los Ceros de Riemann:**
   * Uso de las funciones $V(s)$ y $\phi(s)$ de Cramér.
   * Evaluación de productos tipo "ddotted" $\prod\prod \sin(\alpha_k \rho - z_k)$.
4. **La Anomalía Multiplicativa:**
   * Definición de la discrepancia $F$ cuando $\prod\prod (\lambda_n \mu_n) \neq (\prod\prod \lambda_n)(\prod\prod \mu_n)$.
   * Cálculo de discrepancias para secuencias trigonométricas y su especulativa (y profunda) conexión con la Hipótesis de Riemann y la conjetura 1/4 de Selberg.
