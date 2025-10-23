# avance-2-estadistica

DICCIONARIO
| **Variable** | **Descripción** | **Tipo de variable** | **Valores o categorías** |
|---------------|-----------------|----------------------|---------------------------|
| **DOMINIO** | Región o zona geográfica de residencia del hogar | Categórica | Costa Norte, Costa Sur, Sierra Centro, Sierra Sur, Selva, etc. |
| **UBIGEO** | Código geográfico del hogar según ubicación departamental, provincial y distrital | Numérica (categórica codificada) | Códigos oficiales del INEI |
| **CONGLOME** | Número de conglomerado o zona de muestreo utilizada por la ENAHO | Numérica | Valores enteros |
| **VIVIENDA** | Identificador de la vivienda en la muestra | Numérica | Valores enteros |
| **HOGAR** | Identificador del hogar dentro de la vivienda | Numérica | Valores enteros |
| **TuvoTrabajo** | Indica si la persona tuvo trabajo fijo la semana pasada | Binaria (dependiente) | 1 = Sí tuvo trabajo, 0 = No tuvo trabajo |
| **Educacion** | Nivel educativo alcanzado por la persona | Ordinal | Primaria incompleta/completa, Secundaria incompleta/completa, Superior no universitaria, Superior universitaria |
| **Sexo** | Sexo del entrevistado | Binaria | Hombre = 1, Mujer = 0 |
| **Edad** | Edad en años cumplidos del entrevistado | Cuantitativa continua | 15 a 80 años (según muestra) |
| **TrabajaPerú** | Indica si el entrevistado fue beneficiario del programa Trabaja Perú | Binaria (independiente principal) | 1 = Beneficiario, 0 = No beneficiario |
| **FACTOR07** | Factor de expansión muestral de la ENAHO (pondera los casos para representar a la población nacional) | Numérica continua | > 0 (según diseño muestral) |
| **Situación de Vulnerabilidad** | Condición socioeconómica del entrevistado o del hogar | Categórica (control) | Pobre Extremo, Pobre No Extremo, Vulnerable No Pobre, No Pobre |

