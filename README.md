# Farmacias-Guadalajara:

![image](https://github.com/user-attachments/assets/4585c19e-bf4f-47ac-a781-99c1d7c26fb7)

### :page_facing_up: *Documentación utilizada:* 
- Dirección del servidor: https://www.farmaciasguadalajara.com/
- Requisitos: No hay requisitos
  
### 🛠️ *Lenguajes y herramientas utilizadas:*
<div id="header" align="left">

- Navegador web: Para la ejecución de las pruebas.
- DevTools (F12): Para inspeccionar elementos, ver errores en consola, y monitorear solicitudes de red.
- Jira: Registro y seguimiento de errores.
- MS Office: Documentación de las pruebas.

</a>
<img decoding="async" src="https://img.shields.io/badge/WEB-purple?style=for-the-badge&logo=Web&logoColor=white" alt="Web"/>
<img decoding="async" src="https://img.shields.io/badge/DevTools-D80B01?style=for-the-badge&logo=Devtools&logoColor=white" alt="DevTools"/>
<img decoding="async" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white" alt="Jira"/>
<img decoding="async" src="https://img.shields.io/badge/Microsoft_Office-D86B01?style=for-the-badge&logo=microsoft-office&logoColor=white" alt="microsoft-office"/>
</a>

### :fireworks: *Descripción del Aplicativo Farmacias Guadalajara*
#### 1. Exploración de Pedidos en Farmacias Guadalajara:
Este plan de pruebas sencillo ayudará a explorar la funcionalidad de pedidos en la aplicación de Farmacias Guadalajara. 
#### El objetivo principal: 
es identificar cualquier problema básico o comportamiento inesperado durante el proceso de compra.
 
#### 2. Alcance de la Prueba:
- Aplicación a probar: La aplicación web de Farmacias Guadalajara en su versión de escritorio.
- Funcionalidad principal: Proceso de realización de pedidos, desde la búsqueda de productos, adición al carrito hasta la confirmación de la orden.
- Tipo de prueba: Exploratoria, enfocada en la usabilidad y flujo general.

#### 3. Entorno de Prueba
Navegador(es) recomendado(s): Chrome, Firefox, Edge (utilizaremos Chrome para las pruebas).
Configuración: (Navegador Chrome Versión 137.0.7151.104 (Build oficial) (64 bits)).
Sistema operativo: (SO Windows 10, 64 bits), resolución 1920x1080.).
Conexión a internet: Estable.
Credenciales de usuario: Se recomienda tener al menos una cuenta de usuario registrada y, si es posible, una cuenta nueva para probar el registro.

#### 4. Listas de Comprobación (Exploratorios)
#### - Acceso y Navegación
Acceso a la web: Verificar que se puede acceder a la URL principal de Farmacias Guadalajara.
Comprobar la carga inicial de la página.
- Inicio de sesión/Registro:
Intentar iniciar sesión con credenciales válidas e inválidas.
Revisar el flujo de registro de un nuevo usuario (solo hasta el punto de verificar la creación de la cuenta, sin necesidad de completar todo el proceso si es muy largo).
Verificar la opción "Olvidé mi contraseña".
- Navegación general:
Explorar el menú principal y las categorías de productos.
Verificar que los enlaces principales funcionan y dirigen a las páginas correctas.
#### - Búsqueda de Productos
Búsqueda simple:
Buscar productos por nombre exacto (ej. "Paracetamol", "Bebidas").
Buscar productos con nombres parciales o errores tipográficos comunes.
- Búsqueda avanzada/Filtros:
Si existen, utilizar filtros por categoría, precio, marca, etc.
Verificar que los resultados se actualizan correctamente al aplicar filtros.
- Resultados de la búsqueda:
Comprobar la presentación de los resultados (imágenes, precios, disponibilidad).
Verificar el comportamiento cuando no hay resultados para una búsqueda.
#### - Adición de Productos al Carrito
- Página de producto:
Navegar a la página de un producto específico.
Verificar que se muestra la información relevante del producto (descripción, precio, imágenes, disponibilidad).
- Agregar al carrito:
Agregar una unidad de un producto al carrito.
Agregar múltiples unidades del mismo producto.
Agregar diferentes productos al carrito.
Intentar agregar un producto sin stock (si la aplicación lo permite mostrar).
- Visualización del carrito:
Verificar que el ícono del carrito o la sección del carrito se actualiza correctamente.
Navegar a la página del carrito de compras.
#### - Proceso de Checkout (Caja)
- Página del carrito:
Verificar que los productos y cantidades en el carrito son correctos.
Intentar modificar cantidades de productos directamente en el carrito.
Intentar eliminar productos del carrito.
Verificar que los totales (subtotal, envío, total) se actualizan correctamente.
- Selección de envío/Recolección:
- En esta sección solo se llena el formulario con los datos de envío, pero no se verifica el flujo del mis mo por ser demasiado largo para nuestras pruebas y no se completara el pago de una compra real.
Explorar las opciones de envío a domicilio y/o recolección en tienda.
Si aplica, verificar la entrada de dirección de envío y validación.
- Métodos de pago:(solo se agregara el pago sin revisar todo el flujo y datos)
Explorar los métodos de pago disponibles (tarjeta de crédito/débito, efectivo, etc.).
No es necesario completar una compra real, pero verificar que se puede avanzar hasta el punto de la introducción de los datos de pago.
- Revisión y confirmación del pedido:
Verificar que se muestra un resumen claro del pedido antes de la confirmación final.
Simular el clic en el botón de "Confirmar pedido" para ver la respuesta (si no se requiere un pago real).

### :page_facing_up: *Resumen Lista de Comprobación de Pruebas:*  
- Acceso y navegación general: Verificación de la carga de la página, inicio de sesión/registro y exploración de menús.
- Búsqueda de productos: Pruebas con nombres exactos, parciales y el uso de filtros si están disponibles.
- Adición de productos al carrito: Añadir unidades individuales, múltiples y variados productos, observando la actualización del carrito.
- Proceso de checkout: Revisión de productos en el carrito, modificación de cantidades,
  opciones de envío/recolección y exploración de métodos de pago (sin completar una compra real).

#### 5. Estrategia de Pruebas
Se adoptará una estrategia de pruebas basada en el riesgo, enfocándose primero en las funcionalidades de mayor impacto para el negocio y la experiencia del usuario.

- Pruebas Exploratorias: Inicialmente, se realizarán pruebas exploratorias para entender el comportamiento del sistema y descubrir posibles fallas inesperadas,
  dada la falta de requisitos.
- Pruebas Funcionales: Se validará que cada componente del flujo de compra y las funcionalidades clave operen según lo esperado desde la perspectiva del usuario.

### 🧪 *Resultados de las pruebas:* 
 La documentación de las pruebas se desarrollaro en los siguientes archivos disponibles.
#### :file_folder: Documentación para el aplicativo Web:
 
  - Lista de comprobación: https://docs.google.com/spreadsheets/d/1wNr76IR04i3inApwY4HMgmSqtH7gfUmH9-g2oOTaCvo/edit?usp=sharing
  - Reporte y seguimiento de errores:https://arqkarvga.atlassian.net/browse/FAR

### :page_facing_up: *Informe resumen:* 
 - Informe del producto:
 1. Se ha recorrido el flujo completo de pedido al menos una vez, desde la búsqueda hasta la simulación de confirmación.
 2. Se ha verificado el proceso de registro de una cuenta nueva, incluyendo la adición de datos de envío.
 3. Se ha probado la funcionalidad de inicio de sesión con una cuenta existente para asegurar el acceso al flujo de pedido.
 4. Se han identificado las funcionalidades principales y su comportamiento general.
 5. Se han anotado al menos 3-5 posibles áreas de mejora o defectos obvios.
 6. Esta estrategia de pruebas se centra en una exploración ágil y sencilla de la aplicación web de Farmacias Guadalajara para escritorio,
 específicamente en el proceso de pedidos.

#### Defecto Crítico en el Proceso de Pago: Artículos "Disponibles en la Zona de Entrega" Bloquean la Compra.
Durante las pruebas exploratorias, se identificó un defecto crítico en el proceso de pago. El problema principal es que no es posible finalizar la compra de ningún artículo que muestre la notificación "#Disponibles en la zona de entrega#", incluso si la dirección y el código postal coinciden con nuestra área de servicio (MDVDM).
Esto significa que ninguna compra en línea para entrega a domicilio puede ser concretada en el área MDVDM debido a este bug. La falla representa un inconveniente altamente importante para nuestro comercio y tienda en línea, ya que afecta directamente la función principal de la plataforma, lo que se traduce en pérdidas monetarias significativas.
La existencia de este bug fue verificada adicionalmente a través de una llamada telefónica, confirmando su impacto.
