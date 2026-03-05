# Nombre del proyecto
Gestión de Inventario
# Descripción del proyecto
Gestión de Inventario es una aplicación web diseñada para digitalizar y optimizar el control de existencias en pequeñas y medianas empresas (PYMES). Su propósito principal es eliminar la dependencia de registros manuales o hojas de cálculo obsoletas, reduciendo así los errores humanos y los costes operativos derivados de una mala administración del stock.
La plataforma está dirigida tanto a dueños de negocios como a encargados de almacén que necesitan una herramienta ágil para monitorizar sus productos en tiempo real. Al centralizar la información, el sistema permite evitar la pérdida de ventas por falta de stock y ayuda a identificar productos de baja rotación, optimizando el flujo de caja y garantizando la trazabilidad de cada artículo.

## Estructura del Prototipo
El prototipo se divide en tres vistas principales que permiten un flujo de trabajo intuitivo:

    index.html: Actúa como la puerta de acceso al sistema mediante un formulario de inicio de sesión, garantizando que solo el personal autorizado pueda gestionar los recursos de la empresa.
    panel-control.html: Es el núcleo de la aplicación. Utiliza una interfaz basada en pestañas (tabs) que permite al usuario añadir nuevos artículos, dar de baja stock existente o acceder a la edición, además de incluir la opción de cierre de sesión.
    editar.html: Una vista especializada para la modificación detallada de los artículos, permitiendo ajustar parámetros críticos como el precio y las especificaciones del producto seleccionado.

## Tecnologías Utilizadas

    HTML5: Estructuración semántica del contenido y uso de formularios avanzados.
    CSS3: Diseño visual, maquetación de la interfaz y lógica de navegación mediante estados.

## Enfoque Técnico
El desarrollo se ha centrado en crear una herramienta funcional utilizando únicamente tecnologías de cliente (Frontend):

    Lógica sin JavaScript: Se implementó el sistema de navegación entre pestañas del panel de control utilizando selectores de estado como :checked y el combinador de hermanos adyacentes (~), permitiendo una experiencia de usuario fluida sin sobrecarga de scripts.
    Maquetación Dinámica: Uso de propiedades display para el control de visibilidad de vistas y position para la organización de elementos como la sidebar y el contenido principal.
    Personalización de Componentes: Limpieza de estilos nativos en inputs de tipo número y radio para lograr una estética profesional y minimalista.
## Autor
    https://github.com/0-frank


## Proximas mejoras
    Para convertir este prototipo en una solución integral de gestión, se planean las siguientes implementaciones:
 ## Escáner de Código de Barras/QR
    Integración mediante la API de la cámara para agilizar la entrada y salida de mercancía sin necesidad de teclado.
## Gestión Inteligente de Stock
    Alertas de Stock Bajo: Sistema de notificaciones automáticas cuando un producto llegue a un nivel crítico.
## Análisis de Rotación: 
    Identificación de productos "estrella" y artículos con exceso de stock para optimizar el capital inmovilizado.
## Módulo de Proveedores
    Base de datos vinculada a cada artículo para automatizar las órdenes de compra.
## Generación de Reportes
    Exportación de inventarios y valor total del almacén en formatos PDF y Excel para auditorías contables.
## Multi-sucursal
    Capacidad para gestionar inventarios en diferentes ubicaciones físicas desde una sola cuenta administrativa.