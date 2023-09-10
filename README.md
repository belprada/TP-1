
# TP-1

### Consignas
Debe entregar un único script que resuelva los siguientes puntos
> a. Reemplace cada punto del archivo “breve_historia.txt” por punto y salto de línea generando un nuevo archivo.
> 
> b. Borre todas las líneas en blanco.
> 
> c. Cree un nuevo archivo: “breve_historia_2.txt” con el
> resultado de las operaciones a y b (redireccionamiento de la salida estándar).
> 
> d. Del archivo “breve_historia.txt”, liste todas las
> oraciones que contengan la palabra “independencia” sin distinguir mayúsculas y minúsculas.
> 
> e. Muestre las líneas que empiecen con “El” y terminen con “.” del archivo “breve_historia.txt”.
> 
> f. Sobre el mismo archivo del punto anterior, Indique en cuántas oraciones aparece la palabra “peronismo”. Puede usar la opción -c para contar.
> 
> g. Muestre la cantidad de oraciones que contienen la palabra “Sarmiento” y la palabra “Rosas”.
> 
> h. Muestre las oraciones que tengan fechas referidas al siglo XIX.
> 
> i. Borre la primera palabra de cada línea. Utilice substitución con sed. La sintaxis para sustituir la primera palabra de cada línea por “nada” sería: $sed `“s/^[[a-zA-Z]]*\b//g”` nombre_archivo (La “s” indica sustitución; entre los dos primeros /.../ está la expresión regular que queremos reemplazar, en este caso `“/^[[a-zA-Z]]*\b”` entre el segundo y el tercer “//” se indica la expresión por la cual será reemplazada, en este caso por la palabra vacía. Finalmente la “g” indica que el cambio será en todo el archivo.
> 
> j. Escriba un comando que enumere todos los archivos de una carpeta que contengan extensión “.txt”. (tip: pipe con el comando ls).

Investigue y explique, dando ejemplos cómo se utilizan los siguientes elementos en bash
> - Variables.
> - Sentencias condicionales.
> - Sentencias cíclicas.
> - Subprogramas
De ejemplos de cada una.

### Condiciones de entrega
La entrega del trabajo se debe realizar el 5/10 por GitHub institucional en una carpeta
llamada “TP 1” dentro del repositorio del grupo. La carpeta debe contener:
- Informe en PDF con carátula indicando: legajo, nombre, apellido, correo institucional,
usuario gitHub de cada integrante y link al repositorio.
- Casos de prueba (ejecuciones, pueden ser capturas de pantalla de la salida de
consola luego de la ejecución.
- Soluciones en uno o más scripts sh.
