🏗️ LorHels Project Viewer
Plataforma B2B de Visualización 3D y Gestión de Clientes

Es una aplicación web dinámica (SPA) diseñada a medida para estudios de arquitectura y diseño de interiores. Su objetivo principal es centralizar la presentación de propuestas visuales y agilizar la comunicación con los clientes en un entorno privado, elegante y en tiempo real.

Tecnologías clave utilizadas: Vanilla JavaScript, Tailwind CSS, Firebase (Auth & Firestore) y Three.js.

✨ Características Principales:
🔐 Sistema de Roles Cerrado: * Administrador: Tiene el control total. Es el único que puede invitar clientes, crear proyectos y gestionar los accesos, garantizando la privacidad del estudio.

Cliente: Accede a un entorno seguro y personalizado donde solo visualiza los proyectos que se le han asignado.

🎛️ Panel de Administración (Centro de Mando):

Gestión de Proyectos: Permite crear y editar propuestas definiendo título, cliente, estado (En diseño, En revisión, Aprobado), descripción y portada.

Gestión de Solicitudes (Ticketing): Un panel centralizado que captura los comentarios de los clientes y permite al estudio responder y cambiar el estado de la tarea (Pendiente, En proceso, Listo) en tiempo real.

🖼️ Experiencia de Visualización Premium:

Visor 3D Embebido: Capacidad de inyectar recorridos virtuales y modelos 3D interactivos desde plataformas profesionales (como Sketchfab, Kuula o Matterport) ocupando el espacio central del proyecto.

Galerías Comparativas: Secciones divididas de "Estado Anterior" y "Resultado Final" que soportan múltiples imágenes.

Lightbox Integrado: Al hacer clic en cualquier imagen de la galería, esta se amplía en pantalla completa oscureciendo el fondo para una experiencia inmersiva.

💬 Comunicación en Tiempo Real: * Un panel de comentarios lateral impulsado por la base de datos reactiva de Firebase. El cliente y el administrador pueden interactuar instantáneamente sin necesidad de recargar la página, eliminando la dependencia de correos o mensajes de WhatsApp desorganizados.
