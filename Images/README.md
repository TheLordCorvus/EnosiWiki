# Images

Carpeta para las ilustraciones de la wiki.

- Formatos: `.png`, `.jpg`, `.jpeg`, `.webp`, `.gif`, `.avif`.
- Nombres sin espacios ni acentos: `espada-cromatica.png`.

## Cómo usarlas en la wiki

1. Copia el archivo a esta carpeta y súbelo al repo (`git add`, `commit`, `push`).
2. En la ficha del nodo: **Editar → Usar ruta** y escribe el nombre del archivo,
   por ejemplo `espada-cromatica.png`. La ficha guardará `Images/espada-cromatica.png`
   y la imagen no ocupará espacio en el navegador.
3. En el texto también puedes escribir:

   ```
   ![Espada](Images/espada-cromatica.png|izq|50%)
   ```

   Opciones: `izq`, `der`, `centro` y un ancho en % (por defecto, tamaño natural).

Las imágenes subidas con «Añadir imagen» siguen guardándose en el navegador (base64).
Las de esta carpeta se publican con la web y las ve todo el mundo.
