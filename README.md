# Prueba de Carga

Autor:  Angie Alvarado



## Prerrequisitos

La herramientas utilizadas para la creación de este proyecto son:

- Apache Jmeter  5.6.3
- Java 17




---

## Ejecución de pruebas

### Opcion Interfaz Grafica

Abrir el archivo .jmx desde Jmeter y ejecutar  

### Ejecutar por console

#### Generar archivo jtl

 ```
 jmeter -n -t "<Ruta-archivo.jmx>" -l "<Ruta/NombreArchivo.jtl>"  
 ```       
#### Crear reporte html    
 ``` 
 jmeter -g "Ruta-archivo.jtl" -o "<Carpeta-reporte>"
 ```
Nota: La carpeta para crear el reporte debe encontrarse vacia sin ningun archihvo
