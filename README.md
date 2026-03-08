"LorHels Project Viewer":

🛠️ La Arquitectura (El Motor)
Tecnología: Es una Single Page Application (SPA) súper rápida. No necesita recargar la página para navegar.

Diseño: Construida con Tailwind CSS para ser 100% responsiva (se ve perfecta en celulares, tablets y computadoras) y usa íconos modernos de Phosphor.

Base de Datos y Seguridad: Conectada en tiempo real a Firebase. Tiene reglas de seguridad estrictas: nadie puede ver la información si no ha iniciado sesión.

👥 Sistema de Usuarios y Roles
Tienes un sistema cerrado y seguro con dos tipos de cuentas:

Administrador (El Estudio): Tiene el control total.

Cliente: Solo ve lo que el administrador le asigna.

Nota técnica genial que logramos: Usamos un "truco de app secundaria" para que el Administrador pueda registrar nuevos clientes desde su panel sin que Firebase le cierre su propia sesión.

🎛️ El Panel de Administrador (Tu Centro de Mando)
Cuenta con estadísticas en tiempo real y tres pestañas principales:

Proyectos: Puedes crear y editar proyectos. Tienes control de: título, cliente asignado, estado (En diseño, revisión, aprobado), descripción, imagen de portada personalizada, y múltiples fotos de antes/después.

Clientes: Un directorio para registrar nuevos clientes y ver cuántos proyectos tiene cada uno.

Solicitudes (Sistema de Tickets): Un panel centralizado donde caen todas las peticiones de tus clientes. Puedes leerlas, cambiarles el estado (Pendiente, En proceso, Listo) y responderles directamente.

🛋️ La Experiencia del Cliente
Dashboard Privado: Al iniciar sesión, el cliente ve una cuadrícula elegante con las portadas de sus proyectos y su estado actual.

Visor del Proyecto (La joya de la corona):

Visor 3D: Soporta la inserción (Embed) de modelos interactivos reales desde plataformas como Sketchfab, ocupando todo el ancho disponible. (Y si no hay modelo, muestra un visor 3D básico de prueba).

Galería Interactiva: Dos secciones separadas ("Estado Anterior" y "Resultado Final") que soportan múltiples imágenes a través de enlaces de Cloudinary. Tienen un efecto hover y, al hacer clic, se abren en un Lightbox (pantalla completa oscurecida).

Chat / Solicitudes: Un panel lateral donde el cliente puede pedir cambios. Él puede ver en tiempo real si su petición está pendiente, en proceso, o si el estudio ya le respondió y la marcó como "Lista".
