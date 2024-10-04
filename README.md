<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">    
</head>
<body>
    <h1>Proyecto_MadaInfusiones</h1> 
<h2></h2>
  <h2>Fase 1: Planificación y Análisis</h2>
  <h3>1. Definición de Requisitos</h3>

 <h4>1.1 Reunión Inicial con el Cliente</h4>  

<h5>Objetivo:</h5>
 <ul>
 <li>Entender las necesidades y expectativas del cliente.</li>    
 </ul>
 
 <h5>Acciones:</h5>
 <ul>
    <li>Entrevista con el dueño de la empresa.</li>
    <li>Identificación de procesos actuales y desafíos.</li>
    <li>Discusión de funcionalidades deseadas.</li>
 </ul>
<h4>1.2 Documentación de Requisitos:</h4>

<h5>Objetivo:</h5>
<ul>
   <li>Crear un documento claro y detallado.</li>
</ul>
<h4>Contenido:</h4>
<ul>
   <li>Descripción general del sistema.</li>
   <li>Funcionalidades principales y secundarias.</li>
   <li>Casos de uso detallados.</li>
   <li>Requisitos no funcionales (rendimiento, seguridad, etc.).</li>
</ul>
<h3>2. Especificación de Requisitos</h3>
 
 <h4>2.1 Identificación de Roles de Usuario:</h4>  

<h5>Administrador:</h5>
<ul>
    <li>Gestión completa del sistema.</li>
</ul>
<h5>Vendedor:</h5>
<ul>
    <li>Gestión de ventas y atención al cliente.</li>
</ul>
<h5>Cliente:</h5>
<ul>
    <li>Realización de compras online.</li>
</ul>
<h4>2.2 Elaboración de Historias de Usuario:</h4>
<ul>
    <li>Ejemplo: “Como administrador, quiero gestionar el inventario para mantener un control de stock eficiente.”</li>
    <li>Ejemplo: “Como cliente, quiero poder buscar y comprar productos fácilmente en la tienda online.”</li>
</ul>

<h3>3. Investigación y Selección de Tecnologías</h3>
 
<h4>3.1 Evaluación de Lenguajes y Frameworks:</h4>
<ul>
    <li>Backend: Node.js con Express, Django, Ruby on Rails.</li>
    <li>Frontend: React, Angular, Vue.js.</li>
    <li>Base de Datos: MySQL, PostgreSQL, MongoDB.</li>
</ul>
<h4>3.2 Selección de Herramientas:</h4>

<ul>
    <li>Control de Versiones: Git.</li>
    <li>Repositorios: GitHub, GitLab.</li>
</ul>
<h2>Fase 2: Diseño</h2> 
<h3>4. Diseño de la Arquitectura del Sistema</h3> 
<h4>4.1 Diseño de la Base de Datos:</h4>
<ul>
    <li>Tablas: Productos, Clientes, Proveedores, Ventas, Compras, Usuarios.</li>
    <li>Relaciones: Definición de claves primarias y foráneas.</li>
</ul>
<h4>4.2 Definición de la Arquitectura:</h4>
<ul>
    <li>Modelo MVC: Separación de modelos, vistas y controladores.</li>
    <li>APIs RESTful: Para comunicación entre frontend y backend.</li>
</ul>
<h3>5. Wireframes y Prototipos</h3>
 
<h4>5.1 Creación de Wireframes:</h4>
<ul>
    <li>Herramientas: Figma, Adobe XD, Sketch.</li>
    <li>Páginas: Inicio, Listado de Productos, Detalle de Producto, Carrito de Compras, Panel de Administración.</li>
</ul>
<h4>5.2 Prototipos Interactivos:</h4>
<ul>
    <li>Simulación: Navegación y flujo de usuario.</li>
    <li>Feedback: Revisión con el cliente para ajustes.</li>
</ul>

<h2>Fase 3: Desarrollo</h2> 
<h3>6. Configuración del Entorno de Desarrollo</h3> 
<h4>6.1 Instalación de Herramientas:</h4>
<ul>
    <li>IDE: Visual Studio Code, IntelliJ IDEA.</li>
    <li>Dependencias: npm/yarn para Node.js, pip para Python.</li>
</ul>
<h4>6.2 Configuración de Control de Versiones:</h4>
<ul>
    <li>Repositorio Git: Creación y configuración.</li>
</ul>
<h3>7. Desarrollo del Backend</h3>
 
<h4>7.1 Configuración de la Base de Datos:</h4>
<ul>
    <li>Creación de Esquemas y Tablas.</li>
    <li>Migrations: Herramientas como Sequelize, Alembic.</li>
</ul>
<h4>7.2 Desarrollo de APIs:</h4>
<ul>
    <li>Endpoints CRUD: Productos, Clientes, Ventas, Compras.</li>
    <li>Autenticación: JWT, OAuth</li>
</ul>

<h3>8. Desarrollo del Frontend</h3> 
<h4>8.1 Creación de Componentes:</h4>
<ul>
    <li>Catálogo de Productos.</li>
    <li>Formulario de Compra.</li>
    <li>Panel de Administración.</li>
</ul>
<h4>8.2 Integración con Backend:</h4>
<ul>
    <li>Fetch/Axios: Para llamadas a la API.</li>
    <li>Estado Global: Redux, Context API.</li>
</ul>

<h3>9. Integración de Funcionalidades</h3>
 
<h4>9.1 Pruebas de Integración:</h4>
<ul>
    <li>Verificación de Flujo Completo: Desde la gestión de stock hasta la compra online.</li>
    <li>Resolución de Conflictos: Bugs y ajustes.</li>
</ul>
<h2>Fase 4: Pruebas</h2> 
<h3>10. Pruebas Unitarias y de Integración</h3>
 
<h4>10.1 Desarrollo de Pruebas Unitarias:</h4>
<ul>
    <li>Backend: Jest, Mocha.</li>
    <li>Frontend: React Testing Library, Cypress.</li>
</ul>
<h4>10.2 Pruebas de Integración:</h4>
<ul>
    <li>Escenarios Complejos: Procesos completos de negocio.</li>
    <li>Automatización: CI/CD para ejecutar pruebas automáticamente.</li>
</ul>

<h3>11. Pruebas de Usuario</h3> 
<h4>11.1 Feedback de Usuarios Reales:</h4>
<ul>
    <li>Pruebas Beta: Usuarios seleccionados.</li>
    <li>Revisión y Ajustes: Basados en el feedback recibido.</li>
</ul>
<h2>Fase 5: Implementación</h2>
<h3>12. Despliegue</h3>
<h4>12.1 Preparación del Entorno de Producción:</h4>
<ul>
    <li>Servidor: Heroku, AWS, DigitalOcean.</li>
    <li>Seguridad: Certificados SSL, HTTPS.</li>
</ul>
<h4>12.2 Despliegue Continuo:</h4>
<ul>
    <li>CI/CD Pipelines: Jenkins, GitHub Actions.</li>
</ul>
<h3>13. Mantenimiento</h3>
<h4>13.1 Monitoreo y Soporte:</h4>
<ul>
    <li>Monitoreo: Herramientas como New Relic, Datadog.</li>
    <li>Soporte Técnico: Resolución de problemas y actualizaciones.</li>
</ul>
<h4>13.2 Mejoras Continuas:</h4>
<ul>
    <li>Feedback Constante: Encuestas y revisiones periódicas.</li>
    <li>Actualizaciones: Nuevas funcionalidades y mejoras de UX.</li>
</ul>

<h2>Sugerencias Adicionales</h2> 
<h5>Seguridad:</h5>
<ul>
    <li>Autenticación y Autorización: Implementación robusta.</li>
    <li>Encriptación de Datos: Sensibles en la base de datos.</li>
</ul>
<h5>Escalabilidad:</h5>
<ul>
    <li>Microservicios: Considerar si la empresa crece.</li>
    <li>Optimización de Consultas: SQL y NoSQL.</li>    
</ul>
<h5>Experiencia de Usuario (UX):</h5>
<ul>
    <li>Diseño Intuitivo: Facilitar la navegación.</li>
    <li>Accesibilidad: Asegurarse de que sea usable para todos los usuarios.</li>
</ul>
<h5>Documentación:</h5>
<ul>
    <li>Código: Comentarios claros y concisos.</li>
    <li>Manual de Usuario: Guía para los usuarios finales.</li>
</ul>
<h5>Funcionalidades Adicionales</h5>
<ul>
    <li>Notificaciones: Emails y SMS: Alertas sobre pedidos, stock bajo, etc.</li>
</ul>
</body>
</html>
