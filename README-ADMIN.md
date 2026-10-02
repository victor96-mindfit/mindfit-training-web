# MindFit Training — edición de la web sin tocar código

## Lo importante
La web incluye un panel privado en `/admin/`. Una vez conectada a vuestro GitHub y publicado el sitio, podréis editar desde el navegador:
- textos de portada y filosofía;
- servicios (crear, borrar, reordenar y cambiar textos/etiquetas);
- teléfonos, WhatsApp, email e Instagram;
- artículos de **MindFit Ciencia**: título, categoría, fecha, introducción, secciones, ideas clave, referencia y DOI.

## Activación inicial (solo una vez)
1. Crear un repositorio de GitHub propiedad de MindFit y subir esta carpeta.
2. En `admin/config.yml`, cambiar `TU_USUARIO/TU_REPOSITORIO` por el repositorio real.
3. Cambiar `TU-DOMINIO.es` por vuestro dominio real.
4. Publicar el repositorio en Netlify (o alojamiento compatible).
5. Configurar la autenticación OAuth de GitHub que usa Decap CMS. El hosting/repositorio deben ser vuestros; no entreguéis la propiedad a un tercero.

## Uso diario
1. Entrar en `https://vuestro-dominio.es/admin/`.
2. Iniciar sesión.
3. Abrir **Editar web → Textos, servicios y contacto**.
4. Cambiar lo que necesitéis.
5. Guardar/publicar. El cambio queda versionado en GitHub y el hosting vuelve a desplegar la web.

## Publicar un artículo científico
Dentro de **Artículos de MindFit Ciencia**, pulsar **Añadir** y completar los campos. El artículo aparecerá automáticamente en la portada y tendrá su propia página.

Narrativa recomendada: pregunta clara → qué investigaron → resultado principal → explicación sencilla → qué NO demuestra → aplicación práctica → ideas clave → referencia/DOI.

## Seguridad editorial
MindFit Ciencia es divulgación. Evitad promesas de curación, causalidad cuando el estudio solo muestre asociación y sustitución de atención sanitaria individual. En salud mental o patologías, mantened siempre el aviso de que el contenido no sustituye valoración profesional.

## Copias y recuperación
Cada publicación queda registrada como un cambio en GitHub. Si se publica algo por error, se puede volver a una versión anterior del repositorio/despliegue.
