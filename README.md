# Décimo Dia Pa roma

## Métodos de Strings en Python
- **_endswith_**(Acaba con): Verifica si una cadena termina en una subcadena dada.
  ```python
  texto = "Quiere Coco Channel"
  t = texto.endswith("Channel")  # True
  f = texto.endswith("Coco")  # False
  ```

- **_startswith_**(Empieza con): Verifica si una cadena empieza en una subcadena dada.
  ```python
  texto = "Ron pa todo el mundo, que invita Pipe Daza."
  t = texto.startswith("Ron")  # True
  f = texto.endswith("Guaro")  # False
  ```

- **_isalpha_** (Es Alfabeto): Verifica si todos los caracteres son del alfabeto.
  ```python
  texto = "MuchosLosLlamadosDocelosEscogidos"
  t = texto.isalpha()  # True
  ```
  ```python
  texto = "MuchosLosLlamados12losEscogidos" #Tiene números
  f = texto.isalpha()  # False
  ```
  
- **_isalnum_**(Son Alfanuméricos) Verifica si todos los caracteres de la cadena son alfanuméricos.
  ```python
  texto = "ALas3SeVaPalBiutiALas4VaPlaMolPaEsoDeLas5EstaVapol"
  t = texto.isalnum()  # True
  ```
  ```python
  texto = "ALas3S eVaPalBiuti,ALas4 VaPlaMol,PaEsoDeLas5 EstaVapol" #Tiene comas y espacios
  f = texto.isalnum()  # False
  ```

- **_isdigit_**(Es dígito/número): Verifica si todos los caracteres de la cadena son dígitos.
  ```python
  texto = "1599333"
  t = texto.isdigit()  # True
  ```
  ```python
  texto = "15.99.3:33" #Tiene puntos.
  f = texto.isdigit()  # False
  ```

- **_isspace_**(Es espacio): Verifica si la cadena está compuesta de solo espacios.
  ```python
  texto = "   "
  resultado = texto.isspace()  # True

- **istitle:** Verifica si la cadena está en formato título (la primera letra de cada palabra es mayúscula).
  ```python
  texto = "Hola, Soy Homero Hincha Del Deportes Iquique"
  t = texto.istitle()  # True

  ```python
  texto = "Hola, soy Homero hincha del Deportes Iquique" #Hay dos palabras que no tienen formato de Título.
  f = texto.istitle()  # False

- **islower:** Verifica si todos los caracteres de la cadena están en minúsculas.
  ```python
  texto = "arremangala arrepújala"
  t = texto.islower()  # True
  ```
- **isupper:** Verifica si todos los caracteres de la cadena están en mayúsculas.
  ```python
  texto = "¿QUÉ TU HARÍA SI FUERA PRESIDENTE DE LA REPÚBLICA DOMINICANA?" #FUTBOL EN PAZ
  t = texto.isupper()  # True
  ```
