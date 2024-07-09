# Modelos Cuantitativos e Investigación de Operaciones
Curso de Modelos Cuantitativos e Investigación de Operaciones para alumnos de la Maestría en Finanzas del IEE 2024

## Ligas de interés
- Link de las sesiones en [Google Meet](https://meet.google.com/uyo-dtks-qta)
- [Temario del curso](https://drive.google.com/file/d/1xe8BHi05IHPSS84VSQ_zUyRYaNNox6GI/view?usp=drive_link)


## Sesiones
### Sesión 1 [02/07/2024]. Introducción a la Investigación de Operaciones en Finanzas

Ver el contenido de la [primera sesión](https://github.com/intelica-learning/iee-io/blob/f773b1bc6979d815bbc461f6ab5d7a4974306333/sesion1.md)

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







