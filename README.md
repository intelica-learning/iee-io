# Modelos Cuantitativos e Investigación de Operaciones
Curso de Modelos Cuantitativos e Investigación de Operaciones para alumnos de la Maestría en Finanzas del IEE 2024

## Ligas de interés
- Link de las sesiones en [Google Meet](https://meet.google.com/uyo-dtks-qta)
- [Temario del curso](https://drive.google.com/file/d/1xe8BHi05IHPSS84VSQ_zUyRYaNNox6GI/view?usp=drive_link)


## Sesiones
### Sesión 1 [02/07/2024]. Introducción a la Investigación de Operaciones en Finanzas

En esta sesión damos una introducción a los modelos cuantitativos y la investigación de operaciones, sobre todo en lo que respecta a aplicaciones en finanzas corporativas.

El análisis cuantitativo es el enfoque científico de la toma de decisiones administrativa. El capricho, las emociones y la adivinación no forman parte del enfoque del análisis cuantitativo. Este enfoque comienza con datos. Al igual que con la materia prima para una fábrica, los datos se manipulan o se procesan para convertirlos en información para quienes toman decisiones. Este proceso y manipulación de los datos convertidos en información significativa son la esencia del análisis cuantitativo. Las computadoras han jugado un papel decisivo en el uso creciente del análisis cuantitativo.		

Al resolver un problema, los gerentes deben considerar factores tanto cualitativos como cuantitativos. Por ejemplo, podríamos considerar varias alternativas de inversión distintas que incluyan certificados de depósito bancario, inversiones en el mercado de valores y una inversión en bienes raíces. Podemos usar análisis cuantitativo para determinar cuánto valdría nuestra inversión en el futuro, si depositamos en un banco a una tasa de interés dada por cierto número de años. El análisis cualitativo también sirve para calcular razones financieras de los estados de resultados en varias compañías cuyas acciones se estén considerando. Algunas compañías de bienes raíces han desarrollado programas de cómputo que utilizan análisis cuantitativo para examinar flujos de efectivo y tasas de rendimiento para las inversiones en propiedades.

Además del análisis cuantitativo, deberían considerarse factores cualitativos. El clima, la legislación estatal y federal, los nuevos desarrollos tecnológicos, los resultados de una elección y otros son factores que quizá sean difíciles de cuantificar. 

La investigación de operaciones (IO), también conocida como investigación operativa o análisis de operaciones, es una disciplina que aplica métodos analíticos avanzados para ayudar a tomar decisiones mejores. Utiliza técnicas matemáticas, estadísticas y de optimización para modelar, analizar y resolver problemas complejos que se presentan en la administración y operación de sistemas organizacionales.

De acuerdo a ChatGpt, algunas de las aplicaciones de interés de la investigación de operaciones en finanzas, son:

En finanzas bursátiles:

- Optimización de Portafolios
  - Modelo de Markowitz: Utilizar técnicas de programación cuadrática para encontrar la mejor combinación de activos que maximice el rendimiento esperado para un nivel dado de riesgo o minimice el riesgo para un nivel dado de rendimiento esperado.
  - Análisis de frontera eficiente: Determinar el conjunto de portafolios óptimos que ofrecen el máximo rendimiento esperado para un nivel específico de riesgo.
 
- Gestión de Riesgos
  - Valor en Riesgo (VaR): Calcular el VaR utilizando simulaciones de Monte Carlo y otros métodos para cuantificar el riesgo potencial de pérdidas en un portafolio.
  - Optimización de cobertura: Utilizar programación lineal y no lineal para diseñar estrategias de cobertura que minimicen el riesgo de exposición a movimientos adversos en precios de activos.

En finanzas corporativas:

- Planificación Financiera y Presupuestaria
  - Modelos de flujo de caja: Utilizar técnicas de programación matemática para optimizar el flujo de caja y la asignación de recursos en una empresa.
  - Presupuesto de capital: Evaluar proyectos de inversión utilizando métodos de programación matemática para maximizar el valor presente neto (VPN) o minimizar el costo de capital.

- Gestión de Inventarios y Tesorería
  - Optimización de inventarios: Aplicar modelos de control de inventarios para optimizar el nivel de inventario y reducir costos asociados a la falta o exceso de inventario.
  - Gestión de tesorería: Utilizar modelos de optimización para gestionar el flujo de efectivo de manera eficiente y asegurar la liquidez necesaria para operaciones diarias.

#### Ejemplo 1. Punto de equilibrio
Se usará el taller de reparación de relojes de Bill Pritchett como ejemplo para demostrar el uso de los modelos matemáticos. La compañía de Bill, Relojería Fina de Pritchett, compra, vende y repara relojes antiguos y sus partes. Bill vende resortes reconstruidos a un precio de $10 por unidad. El costo fijo del equipo para construir los resortes es de $1,000. El costo variable por unidad es de $5 por el material del resorte. Construye un modelo de punto de equilibrio.

#### Solución 1.
Desglose de la fórmula de punto de equilibrio en esta hoja de [Miro](https://miro.com/app/board/uXjVK2RSouM=/?share_link_id=255419322371).

#### Tarea 1. 
De acuerdo al problema planteado en el [caso de estudio](https://drive.google.com/file/d/1Eu70fLs6btTwRNv2CdLOAp0JvtlhQO4G/view?usp=sharing) sobre los alimentos y bebidas en el estadio de futbol universitario, contesta las preguntas planteadas. Con esas respuestas, elabora un reporte para presentar tus recomendaciones utilizando [Google Looker Studio](https://lookerstudio.google.com/).

### Sesión 2 [09/07/2024]. Introducción a la Programación Lineal

#### Introducción

En esta sesión presentamos una introducción a la programación lineal.

Muchas decisiones administrativas implican tratar de hacer un uso más eficaz de los recursos de una organización. En general, los recursos incluyen maquinaria, mano de obra, dinero, tiempo, espacio de almacenamiento y materia prima. Tales recursos se utilizan para elaborar productos (como maquinaria, mobiliario, alimentos o ropa) o servicios (como horarios para aerolíneas o producción, políticas de publicidad o decisiones de inversión). La **programación lineal** (PL) es una técnica de modelado matemático ampliamente utilizada, que está diseñada para ayudar a los gerentes en la planeación y toma de decisiones respecto a la asignación de recursos. Se dedican este capítulo y el siguiente para demostrar cómo y por qué funciona la programación lineal.

A pesar de su nombre, la PL y la categoría más general de técnicas llamada programación “matemática” tienen poco que ver con la programación por computadora. En el mundo de la ciencia de la administración, programar se refiere a modelar y resolver matemáticamente un problema. Desde luego, la programación por computadora ha jugado un rol importante en el avance y uso de la PL. Los problemas reales de la PL son demasiado engorrosos para resolverlos a mano o con una calculadora. Así, presentaremos ejemplos de lo valioso que puede ser un software en la solución de un problema de PL.

Un problema de PL tiene las siguientes propiedades:

1. Una función objetivo
2. Una o más restricciones
3. Cursos de acción alternativos
4. La función objetivo y las restricciones son lineales: proporcionalidad y divisibilidad
5. Certeza
6. Divisibilidad
7. Variables no negativas

La formulación de un programa lineal implica el desarrollo de un modelo matemático que represente el problema administrativo. Por lo tanto, para formular un programa lineal, es necesario entender cabalmente el problema administrativo al que se enfrenta. Una vez que se haya entendido, es posible comenzar a desarrollar la formulación matemática del problema. Los pasos en la formulación de un programa lineal son los siguientes:
1. Entender cabalmente el problema administrativo que se enfrenta.
2. Identificar el objetivo y las restricciones.
3. Definir las variables de decisión.
4. Utilizar las variables de decisión para escribir expresiones matemáticas de la función objetivo y de las restricciones.

Una de las aplicaciones más comunes de la PL es el problema de la mezcla de productos. Con
frecuencia dos o más productos se fabrican con recursos limitados, como personal, máquinas, mate- ria prima, etcétera. La utilidad que la empresa busca maximizar se basa en la contribución a la utilidad por unidad de cada producto.

#### Ejemplo 1.
La compañía Muebles Troncoso fabrica mesas y sillas de bajo precio. El proceso de fabricación de cada una es similar, ya que ambas requieren cierto número de horas de trabajo de carpintería, así como cierto número de horas de trabajo en el departamento de pintura y barnizado. Cada mesa requiere de 4 horas de carpintería y 2 horas en el taller de pintura y barnizado. Cada silla requiere de 3 horas de carpintería, y 1 hora en la pintura y barnizado. Durante el periodo de producción actual, están disponibles 240 horas de tiempo de carpintería, así como 100 horas de tiempo de pintura y barnizado. Cada mesa vendida genera una utilidad de $70; cada silla fabricada se vende con una utilidad de $50.
El problema de Flair Furniture es determinar la mejor combinación posible de mesas y sillas a fabricar, con la finalidad de alcanzar la utilidad máxima. 

Trabajaremos en el archivo de [Google Sheets](https://docs.google.com/spreadsheets/d/1fCO89NuAsVOjitelD0jaTXCqhn9fbdsF61Y46rj12oQ/edit?usp=sharing) los primeros modelos.

Para graficar usamos [GeoGebra](https://www.geogebra.org/classroom/msuxdfmr).

Para resolver usando Python usamos ([Google Colab](https://colab.research.google.com/drive/1oNDR4TsuWjz3ZwCf7wpvZ79RkCU2zMDc?usp=sharing))

#### Ejercicio 1.
La corporación Electrocomp fabrica dos productos eléctricos: acondicionadores de aire y ventiladores de gran tamaño. El proceso de ensamblado para cada uno es similar en tanto que requieren una cierta cantidad de ca- bleado y de perforación. Cada acondicionador de aire tarda 3 horas de cableado y 2 horas de perforación. Cada ventilador tiene que pasar por 2 horas de cableado y 1 hora de perforación. En el siguiente periodo de producción, están disponibles 240 horas de tiempo de ca- bleado y hasta 140 horas de tiempo de perforación que se pueden utilizar. Cada aparato de acondicionador de aire vendido genera una utilidad de $25. Cada ventilador ensamblado se puede vender con una utilidad de $15. Formule y resuelva esta situación de la mezcla producción de PL para encontrar la mejor combinación de acondicionadores de aire y ventiladores que genera la mayor utilidad. Use el método gráfico de punto esquina.

