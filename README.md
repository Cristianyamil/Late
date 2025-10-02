PASTELERIA_LATE - Sitio web (versión entregable)
Archivos incluidos:
- index.html          -> Página principal (carrusel, productos, footer).
- contacto.html       -> Página de contacto y formulario (envía por fetch a contact.php).
- styles.css          -> Estilos compartidos.
- contact.php         -> Script PHP (usa mail()). Cambia la variable $to por tu correo.
- images/             -> Carpeta sugerida para tus imágenes (no incluida).
- README.md           -> Este archivo.

INSTRUCCIONES RÁPIDAS:
1) Sube la carpeta al hosting donde tengas soporte PHP (por ejemplo: /public_html/pasteleria).
2) Edita contact.php y reemplaza 'tupasteleria@tudominio.com' por tu correo real.
3) Asegúrate de que el servidor permita la función mail() o configura SMTP (PHPMailer).
4) Abre contacto.html en tu navegador (vía HTTPS) y prueba el formulario.

NOTAS:
- Si tu hosting no soporta mail(), puedo incluir una versión SMTP usando PHPMailer. Necesitarás instalar dependencias (composer) o subir la carpeta vendor de PHPMailer.
- Las imágenes (images/*.png) no están incluidas: coloca tus imágenes en la carpeta 'images' junto a los .html.
