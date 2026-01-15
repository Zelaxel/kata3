# Kata3
Continuación de la kata 2. Implementación de histogramas para un dataset con diseño limpio en java.
## Objetivos
- **Inyección de dependencias para la selección del atributo**. Implementar un mecanismo que permita seleccionar dinámicamente el atributo sobre el que se generará el histograma. Esta selección se realizará mediante inyección de dependencias, por ejemplo, pasando una expresión lambda o referencia a método que obtenga el valor del atributo desde cada objeto. El diseño debe ser genérico y reutilizable, sin depender de un atributo específico (como “año” o “duración”).
- **Creación de la clase view model Histogram**. Implementar una clase llamada Histogram que actúe como view model para representar el histograma generado en memoria. La clase debe contener métodos para añadir o actualizar frecuencias, métodos para obtener los valores y frecuencias
- **Generación del histograma en memoria**. A partir de la colección de objetos cargados y del atributo seleccionado mediante la lambda, construir una instancia de Histogram que contenga las frecuencias de los valores observados.
## Implementación
Planteamos una clase Histogram e HistogramBuilder. La primera representa un histograma de tipo variable y la segunda devuelve instancias de la anterior.
## Fuentes
- Archivo de los mounstruos.
  [monsters.json](https://github.com/CrimsonNynja/monster-hunter-DB/blob/master/monsters.json)
- Librería de maven.
  [org.json](https://mvnrepository.com/artifact/org.json/json/20251224)
