# Taller06

## Construcción de programas usando estructuras de selección simple y compuesta

* En su asignatura ***Fundamentos computacionales***, resolvió *(análisis, diseño de algoritmos, flujograma, prueba de escritorio, etc.)*, algunos problemas con estructuras de control selectivas básicas, dobles y anidadas. El objetivo a continuación es codificar similares algoritmos, pero en el lenguaje de programación de alto nivel **JAVA**. 
* Programar/codificar en el lenguaje de alto nivel Java *(en el IDE NetBeans)*, sus soluciones a cada uno de los problemas listados a continuación dadas las siguientes instrucciones: 
    1. Clone este repositorio en su **PC** local `git clone URL_del_repo` 
    2. En su ***IDE*** cree un nuevo proyecto de tipo ***Java Application*** con el siguiente nombre: ***Proyect-APEB1-Taller06*** eligiendo como localización del proyecto, el repositorio *(carpeta)* clonada localmente en el *paso anterior*.
    3. Para cada problema, genere una clase/programa java independiente pero dentro del único proyecto (*Java App* creado en el *paso anterior*). No olvide nombrar cada clase con el número del problema y un nombre representativo de la solución. Ejemplo: ***Ejercicio01_Facturacion***
    4. Finalizado el taller *(o cada ejercicio)*, sincronice los cambios de su **PC** local a este repositorio remoto de **GitHub**, con los comandos: `git add .` `git commit -m "Mensaje de la versión"` `git push`
* Verifique sus soluciones con las técnicas de compilación, ejecución y depurado de programas.
* Documente las soluciones con los bloques: (1.-) ***Documentación del problema***, y (2.-) ***Evidencia del funcionamiento y resultados***. Para ello, al inicio y final como parte de la codificación (en comentarios /*** ), copiar y pegar el enunciado del problema, y al final, los resultados obtenidos de consola **RUN**. Ejemplo: 

```java
/**
 * Ejercicio 01: "Texto del enunciado del ejercicio/problema...."
 * @author NombreAutor
 * @version 1.0
 */

public class Ejercicio01_Facturacion {
    //AQUÍ AGREGUE TODO SU CÓDIGO...
}

/***
 * EVIDENCIA DEL RUN:
 * Pegue aquí la evidencia de la ejecución del .java
 */
 ```



### Listado de problemáticas:

### Problema-1
> **Facturación de 2 productos:** La empresa Amazon.com le contrata como desarrollador de Sistemas Informáticos para programar su sistema de compras online, el cual calcule el precio total de la compra para un cliente. Para ello, se necesita utilizar estructuras secuenciales y de selección (if simple, doble y/o anidadas), sin aplicar ciclos repetitivos.
> 
> Requisitos:
> 
> 1.	La empresa inicialmente venderá solo 2 tipos de productos distintos, a costos variantes. 
> 2.	Al costo total de la factura, se debe incluir los gastos por concepto de transporte/envío del paquete, del cual no se aplican ningún tipo de descuentos o impuestos dada la excepción descrita en el punto 3.b. 
> 3.	El objetivo es presentar al usuario los detalles de su compra: costos, impuestos, descuentos, monto final dadas las siguientes condiciones: 
> 	a.	Si el subtotal de la compra (sin descuentos o gastos de envío), supera los $1000, se le otorga un 20% de descuento; y si es al menos los $1000 el descuento es como mínimo 5%.
> 	b.	Adicional, si la compra es mayor a $5000, el envío será gratuito. 
> 	c.	El IVA del 15% se debe aplicar a todos los artículos antes de agregar cualquier tipo de descuesto o promoción. 


### Problema-2
> **Clasificación de un triángulo** Dado tres valores que representan las longitudes de los lados de un triángulo, determinar su tipo. Las reglas son:
> 
> - Si todos los lados son iguales, mostrar "Triángulo equilátero".
> - Si dos lados son iguales, mostrar "Triángulo isósceles".
> - Si todos los lados son diferentes, mostrar "Triángulo escaleno".
> - Si la suma de dos lados no es mayor que el tercer lado, mostrar "No es un triángulo".

### Problema-3
> **Costo de envío de paquetes** Un servicio de envío cobra diferentes tarifas según la región y el peso del paquete. Si el peso es menor de 5 kg y la región es "local", el costo es de $5. Si pesa entre 5 y 10 kg, el costo es de $10 para la región "nacional". Para cualquier otro caso, el costo es de $15.

### Problema-4
> **Convertir un número de mes a nombre.** Dado un número del 1 al 12, que representa un mes del año, muestra el nombre del mes correspondiente. Por ejemplo, si el usuario ingresa 1, debe mostrar "Enero"; si ingresa 2, debe mostrar "Febrero", y así sucesivamente.

### Problema-5
> **Determinar el tipo de operación matemática.** Dado un número del 1 al 4 que representa una operación matemática básica (suma, resta, multiplicación, división), muestra el nombre de la operación correspondiente. Por ejemplo, si el usuario ingresa 1, debe mostrar "Suma"; si ingresa 2, debe mostrar "Resta", y así sucesivamente.

**Mucho aprendizaje en este taller 6**
