# Simplificador y Visualizador de Expresiones Booleanas

La aplicación acepta de 2 a 4 expresiones booleanas o tablas de verdad como entrada, las simplifica usando el método de Quine–McCluskey y muestra la forma de simplificación con mapas de Karnaugh a todo color. :contentReference[oaicite:0]{index=0}

* La entrada se puede introducir en la GUI de dos maneras:  
  * Escribiendo en el campo de texto, por ejemplo: `A.B'.C + A.B.C'` (forma de suma de productos).  
  * Generando una tabla de verdad de tamaño 2, 3 o 4 y luego editándola.  
* También se puede importar la entrada desde un archivo:  
  * Archivo con extensión `.be`, escrito así:  
    ```  
    A.B.C + A'.B'.C  
    ```  
  * Archivo con extensión `.tt`, con formato:  
    ```  
    A,B;F  
    0,0;0  
    0,1;1  
    1,0;1  
    1,1;0  
    ```  
* **Características extra:**  
  * Importación de archivos.  
  * Cambio de tema (modo claro/oscuro).  
* **Errores conocidos:**  
  * No puede resolver formas incompletas como `A.B + B'.C`.  
  * No valida correctamente las entradas con valor `1`.  

## Acerca de

Simplificador y visualizador de expresiones booleanas con interfaz gráfica.  

### Temas

`karnaugh-map` · `boolean-expression` · `truth-table` · `logic-design`  

### Recursos

– Este mismo README.  

### Licencia

Licencia MIT
