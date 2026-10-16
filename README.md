# ARAPORA PS-FBO — sitio web

Sitio estático en HTML, preparado para publicar con GitHub Pages.

## Funcionalidades incluidas
- Navegación por secciones y menú móvil.
- Enlaces directos para llamar, enviar correo y contactar por WhatsApp.
- Formulario con validación del navegador que prepara una solicitud completa en WhatsApp.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub, por ejemplo `arapora-ps-fbo`.
2. Sube `index.html`, `DESIGN.md` y `README.md` a la raíz del repositorio.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
6. Espera la publicación y abre la URL que GitHub Pages muestre en esa pantalla.

## Importante sobre el formulario
El formulario no almacena ni envía automáticamente los datos a un servidor. Abre WhatsApp con el mensaje ya redactado y la persona debe pulsar **Enviar**. Para recibir solicitudes por correo automáticamente, se deberá integrar después un servicio de formularios o un backend y configurar sus credenciales de forma segura.

## Recursos externos
El HTML carga fuentes, iconos, Tailwind CSS e imágenes desde servicios externos. Es necesaria una conexión a Internet para que esos recursos se muestren correctamente.
