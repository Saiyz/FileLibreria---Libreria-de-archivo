# FileLibreria---Libreria-de-archivo
FileLibreria es una sencilla librería en Java que te permite realizar operaciones comunes de manejo de archivos, como leer, escribir, copiar, mover y borrar archivos. Esta librería puede ser útil en tus proyectos de Java cuando necesites interactuar con archivos en el sistema de archivos local.


# Uso
Para utilizar FileLibreria en tu proyecto Java, sigue estos pasos:

- Copia la clase FileLibreria.java en tu proyecto. Asegúrate de que esté en el paquete FileLibreria o ajusta el nombre del paquete según tu proyecto.

- Importa la clase FileLibreria en tu código donde desees utilizar sus funcionalidades.
```java
import FileLibreria.FileLibreria;
```
Utiliza los métodos proporcionados por FileLibreria para realizar operaciones de manejo de archivos. Aquí hay algunos ejemplos:
```java

FileLibreria.CrearArchivo("miarchivo.txt", "Contenido del archivo"); // Crear un archivo

FileLibreria.leerArchivo("miarchivo.txt"); // Leer un archivo

FileLibreria.copiarArchivo("miarchivo.txt", "copia_de_miarchivo.txt"); // Copiar un archivo

FileLibreria.MoverArchivo("miarchivo.txt", "nueva_ruta/miarchivo.txt"); // Mover un archivo

FileLibreria.EscribirArchivo("miarchivo.txt", "Nuevos datos"); // Escribir en un archivo existente

FileLibreria.borrarArchivo("miarchivo.txt"); // // Borrar un archivo

//Asegúrate de ajustar las rutas de archivo y nombres de archivo según las necesidades de tu proyecto.
```

# Nota
Esta libreria está en su fase beta, por lo tanto, puede presentar algunos problemas, si te ocurre esto no dudes en contactarme para hacerle reparaciones.





