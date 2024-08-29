![Tec de Monterrey](images/logotecmty.png)
# Act 1.3 - Actividad Integral de Conceptos Básicos y Algoritmos Fundamentales (Evidencia Competencia)

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
En este repositorio encontrarás los archivos de entrada, así como las salidas esperadas que podrás usar para probar tu implementación. También encontrarás un archivo "main.cpp". Ahí deberás implementar tu solución. En el archivo deberás colocar en la parte superior, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: main.cpp
// Author: Edward Elric - A00123456
// Date: 01/01/2021
// =========================================================
```
<span style="text-decoration: underline;">De manera individual</span>, desarrolla la solución del siguiente problema:

Una medida de "desorden" en una secuencia es el número de pares de entradas que están desordenadas entre sí. Por ejemplo, en la secuencia de letras “DAABEC”, esta medida es 5, ya que D es mayor que cuatro letras a su derecha y E es mayor que una letra a su derecha. Esta medida se llama el número de inversiones en la secuencia. La secuencia "AACEDGG" tiene solo una inversión (E y D), está casi ordenada, mientras que la secuencia "ZWQM" tiene 6 inversiones (es tan desordenada como puede ser, exactamente lo contrario de ordenada).

Eres responsable de catalogar una secuencia de cadenas de ADN (secuencias que contienen solo las cuatro letras A, C, G y T). Sin embargo, desea catalogarlos, no en orden alfabético, sino en orden de "clasificación", de "más ordenados" a "menos ordenados". Todas las cuerdas son de la misma longitud.

## <span style="color: rgb(26, 99, 169);">**Entrada**</span>
La primera línea de la entrada es un entero M, luego una línea en blanco seguida de M conjuntos de datos. Hay una línea en blanco entre los conjuntos de datos. La primera línea de cada conjunto de datos contiene dos enteros: un entero positivo n (0 < n ≤ 50) que indica la longitud de las cadenas; y un entero positivo m (0 < m ≤ 100) que indica la cantidad de cadenas. A continuación, aparecen m líneas, cada una de las cuales contiene una cadena de longitud n.

## <span style="color: rgb(26, 99, 169);">**Salida**</span>
Genera la lista de cadenas de entrada, ordenadas de "más ordenadas" a "menos ordenadas". Si dos o más cadenas están igualmente ordenadas, enumérelas en el mismo orden en que están en el archivo de entrada.

## <span style="color: rgb(26, 99, 169);">**Ejemplo de entrada**</span>
```
1

10 6
AACATGAAGG
TTTTGGCCAA
TTTGGCCAAA
GATCAGATTT
CCCGGGGGGA
ATCGATGCAT
```

## <span style="color: rgb(26, 99, 169);">**Ejemplo de salida**</span>
```
CCCGGGGGGA
AACATGAAGG
GATCAGATTT
ATCGATGCAT
TTTTGGCCAA
TTTGGCCAAA
```

Para probar tu implementación, compila tu programa con el comando:
```
g++ -std=c++11 main.cpp -o app
```
Posteriormente, prueba con cada uno de los archivos de entrada de prueba que encontrarás en este repositorio (input1.txt, input2.txt, input3.txt, input4.txt). Los resultados que debes obtener se encuentran en los archivos llamados output1.txt, output1.txt, output1.txt y output1.txt. Para realizar las pruebas, puedes usar las siguientes líneas de código. Por ejemplo, si queremos probar con el archivo de prueba "input1.txt".
```
./app < input1.txt > mysolution1.txt
diff mysolution1.txt output1.txt
```
Si el segundo comando no tenga ninguna salida, sabrás que los resultados que obtuviste son los esperados. 

Por último, realiza una investigación y reflexión en forma individual de la importancia y eficiencia del uso de los diferentes algoritmos de ordenamiento y búsqueda en una situación problema de esta naturaleza, generando un documento llamado **"ReflexAct1.3.pdf"**

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **70%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (70%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (55%)** - pasa correctamente el 75% de los casos de prueba.
    - **Bien (35%)** - pasa correctamente el 50% de los casos de prueba.
    - **Insuficiente (17%)** - pasa correctamente menos del 50% de los casos de prueba.


- **15%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](https://github.com/Manchas2k4/tc1031)</span>
- **15%** - Se respetenan los nombres de las funciones en la aplicación.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Esta actividad forma parte tanto de tu calificación final del curso, así como del portafolio de evidencias de las competencias a desarrollar del curso, por lo que se te pide que en forma individual:
* Realices una entrega de  los archivos correspondientes de los algoritmos de ordenamiento y búsqueda, en la sección correspondiente dentro de esta plataforma, así como el documento de reflexión individual (**ReflexAct1.3.pdf**).
* Generes una carpeta en forma personal llamada **TC1031(Portafolio_Final)** que servirá como preparación para la entrega del portafolio de competencias que se realizará al final del curso, esta carpeta debe contener 5 carpetas:
    * **Act1.3** - coloca aquí tus archivos que solucionaron la <span style="text-decoration: underline;">actividad 1.3</span> así como el documento de reflexión individual (**ReflexAct1.3.pdf**).
    * Act2.3
    * Act3.4
    * Act4.3
    * Act5.2
 
[Fuente](https://onlinejudge.org/external/6/612.pdf)
