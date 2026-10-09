# Aviso de privacidad integral de Photo Review

**Fecha de entrada en vigor:** 8 de octubre de 2026

> **Borrador para revisión y publicación.** Este aviso se elaboró con base en el código de Photo Review disponible al 6 de octubre de 2026. Antes de publicarlo, confirme los datos de producción de los proveedores, las prácticas de consentimiento publicitario y las declaraciones de privacidad de App Store. Este texto no sustituye la revisión de un profesional en privacidad y protección de datos.

## 1. Responsable del tratamiento y contacto

El responsable del tratamiento de los datos personales relacionados con Photo Review es **Mauricio Zárate Barrera**, con domicilio en **Grand Masters 48, Fracc. Junto al Río, Temixco, Morelos, México** y correo para asuntos de privacidad **morrisgrill@hotmail.com** (en adelante, el “Responsable”).

Photo Review es una aplicación para iPhone de público general; no está diseñada ni se promociona específicamente para niños. Permite explorar categorías y álbumes de la fototeca, revisar fotos y videos, conservarlos o marcarlos para eliminarlos, administrar los elementos pendientes y consultar ofertas de suscripción. Se planea distribuirla en **México, Estados Unidos y Canadá** y ofrecer el aviso en español e inglés. La aplicación se ofrece por **Mauricio Zárate Barrera**.

Para cualquier pregunta, solicitud o queja sobre este aviso o el tratamiento de datos, puede escribir a **morrisgrill@hotmail.com**, canal de contacto del Responsable.

## 2. Alcance del aviso

Este aviso explica qué información procesa Photo Review, para qué la utiliza, dónde se conserva, cuándo intervienen proveedores como Apple o Google y qué opciones tiene el usuario. Comprende el uso de la aplicación en iOS, incluidos sus permisos de Fotos, la revisión de elementos, la lista de pendientes, la publicidad integrada y las compras de suscripción.

El aviso no sustituye los avisos de privacidad de Apple, Google, los anunciantes ni los sitios externos que se abran desde un anuncio. Cada proveedor es responsable de sus propias prácticas de privacidad.

## 3. Información relacionada con la fototeca

Photo Review utiliza PhotoKit, el marco de iOS para consultar y modificar la fototeca, únicamente después de que el usuario otorgue el permiso solicitado por iOS. Según el permiso concedido, la aplicación puede consultar fotos y videos disponibles, categorías inteligentes —por ejemplo, favoritos, recientes, videos, capturas de pantalla, selfies y otros grupos ofrecidos por Fotos— y, con acceso completo, álbumes creados por el usuario.

Para mostrar y ordenar los elementos, la aplicación puede utilizar en el dispositivo:

- El identificador local que iOS asigna a cada elemento de Fotos.
- El tipo de medio —imagen o video— y la fecha de creación que proporciona Fotos.
- El identificador y nombre de una categoría o álbum.
- Una miniatura que PhotoKit entrega para representar la foto o el video en pantalla.

La aplicación procesa esta información para construir las categorías, mostrar las tarjetas, recordar el progreso y ejecutar las decisiones de conservación o eliminación. La aplicación no incorpora reconocimiento facial, identificación de personas, OCR ni búsqueda por el contenido de las imágenes en la versión descrita por este aviso.

**Las fotos, los videos y sus miniaturas no se cargan a servidores de Photo Review ni se adjuntan a solicitudes publicitarias realizadas por la aplicación.** El código revisado no utiliza un servidor propio, una cuenta de usuario ni un backend para almacenar el contenido de la fototeca.

Si una foto o un video está optimizado en iCloud y el sistema necesita obtenerlo para mostrarlo, PhotoKit puede solicitarlo a los servicios de Apple/iCloud conforme a los ajustes de Fotos y iCloud del usuario. Esa transferencia la gestiona el sistema operativo y Apple; no equivale a una carga del contenido a servidores del Responsable.

Las fotos pueden contener información que el usuario considere privada o sensible. Photo Review no extrae ni clasifica intencionalmente rostros, ubicación u otros atributos sensibles para publicidad o perfiles. El usuario controla qué elementos permite ver a la aplicación mediante el permiso de Fotos de iOS.

## 4. Permisos de Fotos y control del usuario

La aplicación solicita permiso de lectura y modificación de la fototeca cuando es necesario para mostrar los elementos y permitir la eliminación confirmada. iOS puede conceder acceso completo, acceso limitado a elementos seleccionados, o denegarlo. Con acceso limitado, Photo Review solo puede utilizar los elementos que iOS permita ver; algunas categorías o álbumes pueden no estar disponibles.

El usuario puede cambiar o revocar el permiso desde **Configuración de iOS > Privacidad y seguridad > Fotos > Photo Review**. Al revocar el acceso, las categorías y tarjetas que dependan de la fototeca pueden dejar de estar disponibles.

Marcar un elemento con el gesto o botón de eliminación **no lo elimina de inmediato**. La aplicación conserva su identificador en la lista local de pendientes, donde puede deshacerse la marca. La modificación de la fototeca se solicita únicamente cuando el usuario elige **Eliminar seleccionadas**. iOS puede mostrar su propia confirmación o autorización. Los elementos eliminados quedan sujetos a las funciones y plazos de recuperación de la aplicación Fotos, incluida la carpeta **Eliminado recientemente**, si iOS los coloca allí.

## 5. Información que se guarda en el dispositivo

Photo Review conserva en el almacenamiento privado de la aplicación los datos mínimos necesarios para mantener la lista de pendientes y reanudar la revisión. En particular, SwiftData puede guardar:

- El identificador local de cada foto o video marcado para eliminación.
- El identificador y el nombre de la categoría o álbum de origen.
- La fecha en que se marcó el elemento, el estado de una solicitud de eliminación y, si ocurre un error, el texto de error necesario para mostrar o reintentar la operación.
- El punto de revisión por categoría: clase e identificador de la colección, nombre mostrado, identificador del último elemento cuya decisión se guardó y fecha de actualización.

La aplicación no guarda los archivos multimedia, copias de las fotos, videos, miniaturas ni objetos de PhotoKit en SwiftData. La base local se configura sin sincronización de CloudKit ni backend de Photo Review.

También pueden conservarse en las preferencias locales de iOS el idioma elegido y un contador de uso para espaciar la presentación de anuncios. El contador se reinicia cuando se consume un intervalo de anuncios. No se usa como identificador de cuenta.

Los datos anteriores se utilizan en el propio dispositivo. El sistema operativo puede incluir datos de aplicaciones en copias de seguridad del dispositivo, de acuerdo con los ajustes de respaldo elegidos por el usuario. El Responsable no recibe esas copias.

## 6. Publicidad y Google Mobile Ads

La versión revisada integra el SDK de Google Mobile Ads para cargar anuncios nativos dentro del flujo de revisión. La configuración del código establece un intervalo de ocho fotos revisadas: cuando corresponde y existe otra foto por revisar, se inserta una tarjeta publicitaria. La aplicación no solicita esos anuncios cuando detecta una suscripción activa. La frecuencia o disponibilidad final también puede depender de la configuración de anuncios y de la respuesta del proveedor.

Las solicitudes de anuncios limitan el contenido a la clasificación general de Google. Esta clasificación limita el tipo de contenido publicitario; no significa que se envíe a Google una edad verificada ni que la configuración por sí sola resuelva las reglas de privacidad aplicables a menores.

El SDK puede tratar automáticamente información necesaria para entregar, medir, proteger y diagnosticar anuncios. De acuerdo con la documentación de Google Mobile Ads para iOS, esta información puede incluir dirección IP, identificadores del dispositivo o publicitarios disponibles, datos sobre publicidad y las interacciones con ella, registros de fallos y métricas de rendimiento o diagnóstico. Google puede usar estos datos conforme a sus propios avisos, herramientas, ajustes del dispositivo y requisitos legales. El SDK puede comunicarse con Google y con proveedores de publicidad participantes.

La aplicación no envía a Google fotos, videos, miniaturas ni identificadores locales de la fototeca como parámetros de solicitud publicitaria. Si el usuario toca elementos interactivos de un anuncio, utiliza el gesto de interacción configurado por el SDK o abre el destino del anuncio, Google, el anunciante y el sitio o aplicación de destino pueden recibir información sobre esa interacción y tratarla conforme a sus propios avisos.

Los anuncios se identifican dentro de la interfaz. El usuario puede omitir la tarjeta con el botón o gesto disponible. Una interacción hacia la derecha está configurada como gesto de clic personalizado para el SDK y puede registrarse como interacción publicitaria; el comportamiento final y el destino dependen del anuncio servido.

Puede consultar la información de privacidad de Google en [Política de privacidad de Google](https://policies.google.com/privacy) y la descripción de datos del SDK en [Divulgación de datos de Google Mobile Ads para iOS](https://developers.google.com/admob/ios/privacy/data-disclosure). La información de anuncios y los controles publicitarios disponibles pueden variar según el país, el sistema operativo, la configuración del dispositivo y las tecnologías de consentimiento que se implementen.

## 7. Compras y suscripciones

La aplicación ofrece compras de suscripción renovable semanal y anual mediante StoreKit, el sistema de compras de Apple. Antes de una compra, Apple muestra el precio, la moneda, el periodo, los impuestos y las condiciones aplicables en el storefront correspondiente.

Apple procesa el pago y administra la transacción, la renovación, la cancelación y la restauración de compras. Photo Review consulta a StoreKit si existe una suscripción activa para dejar de mostrar anuncios. El Responsable no recibe ni almacena el número completo de tarjeta ni las credenciales de pago. Apple puede tratar información de cuenta, pago y transacción conforme a sus avisos y condiciones.

El usuario puede administrar o cancelar una suscripción en los ajustes de su cuenta de Apple/App Store y restaurar compras elegibles desde la aplicación. Los enlaces disponibles son **[Administrar suscripciones de Apple](https://apps.apple.com/account/subscriptions)** y **[Condiciones estándar de Apple para servicios multimedia](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)**. La disponibilidad, el precio, la renovación y los reembolsos están sujetos a las condiciones de Apple y del storefront.

## 8. Finalidades y decisiones del usuario

La información se utiliza para las siguientes finalidades:

1. **Proveer la función principal:** consultar las categorías y álbumes autorizados, presentar fotos y videos, recordar dónde se quedó el usuario y conservar sus decisiones pendientes.
2. **Ejecutar acciones solicitadas:** quitar elementos de la lista de pendientes o solicitar a iOS que elimine en lote solo aquellos que el usuario confirmó.
3. **Administrar la suscripción:** consultar con StoreKit la compra y vigencia necesarias para activar la experiencia sin anuncios.
4. **Mostrar y medir publicidad:** cargar anuncios, limitar su frecuencia, registrar interacciones publicitarias mediante el SDK y financiar el acceso gratuito.
5. **Mantener preferencias:** conservar localmente el idioma elegido y el estado mínimo necesario para la frecuencia de anuncios.
6. **Atender incidencias:** mostrar errores de Photos, StoreKit o del SDK en la aplicación y permitir reintentar operaciones cuando corresponda.

El acceso a Fotos solo ocurre después de que el usuario concede el permiso correspondiente en iOS. Cuando Google UMP determina que se requiere una decisión de privacidad para anuncios, la aplicación solicita esa decisión antes de iniciar Google Mobile Ads. Las compras se procesan cuando el usuario confirma la operación a través de Apple. La aplicación no solicita una fecha de nacimiento ni crea una cuenta de usuario.

## 9. Transferencias y proveedores

Photo Review no mantiene un backend propio ni envía al Responsable una copia de la fototeca. Para operar determinadas funciones, puede haber comunicación directa con:

- **Apple**, por los permisos y servicios del sistema Fotos/iCloud, la distribución de la aplicación, StoreKit, la validación de compras y la administración de suscripciones.
- **Google y participantes de su servicio publicitario**, por la carga, medición, protección y diagnóstico de anuncios y las interacciones con ellos.
- **Anunciantes y destinos externos**, cuando el usuario interactúe con un anuncio y se abra un enlace o aplicación de terceros.

Estos proveedores pueden tratar información en países distintos del país del usuario conforme a sus propios avisos, contratos y mecanismos de transferencia. Para la publicación, el Responsable debe confirmar las entidades proveedoras que correspondan a las cuentas y acuerdos reales de Apple y Google, así como las transferencias internacionales aplicables.

No se venden los identificadores locales de Fotos ni se entregan fotos o videos a anunciantes desde Photo Review. El código revisado no incluye integración con una plataforma propia de analítica, CRM, registro de cuentas o publicidad de terceros distinta de Google Mobile Ads.

## 10. Conservación y eliminación de datos

Los identificadores de elementos pendientes permanecen en el almacenamiento local hasta que el usuario quite la marca o hasta que Fotos confirme la eliminación y la aplicación retire la entrada. Si la operación falla, la aplicación puede conservar el elemento pendiente y el error para permitir un reintento.

El punto de revisión se conserva localmente para permitir continuar una categoría y se elimina o actualiza cuando se termina o reinicia su sesión. Las preferencias permanecen en el dispositivo mientras no se cambien o eliminen los datos de la aplicación. El Responsable no conserva estos registros en un servidor central.

Desinstalar Photo Review normalmente elimina sus datos locales de la aplicación, sin perjuicio de copias de seguridad del dispositivo o de datos que deban conservar Apple, Google u otros proveedores conforme a sus propias políticas. Desinstalar la aplicación no cancela una suscripción de Apple; el usuario debe cancelarla en su cuenta.

## 11. Seguridad

La aplicación usa el almacenamiento privado de iOS y limita la información local a identificadores y estado de revisión necesarios para sus funciones. El acceso a la fototeca se controla mediante los permisos del sistema operativo. El Responsable no opera una base central de fotos ni una cuenta de usuario para esta versión.

Ninguna medida puede garantizar seguridad absoluta. El usuario debe proteger el acceso al dispositivo, mantener actualizado iOS, revisar los permisos de Fotos y evitar compartir el dispositivo con personas no autorizadas. Apple y Google aplican sus propias medidas a los servicios que administran.

## 12. Derechos y opciones del usuario

El usuario puede:

- Conceder, limitar o revocar el permiso de Fotos desde Configuración de iOS.
- Revisar, deshacer o retirar de la lista local las marcas de eliminación antes de confirmar el lote.
- Confirmar la eliminación y administrarla después desde Fotos, incluida la carpeta **Eliminado recientemente** cuando aplique.
- Cambiar el idioma en la aplicación.
- Administrar, cancelar o restaurar compras a través de Apple.
- Solicitar información sobre el tratamiento de datos personales del que sea responsable el Responsable, así como ejercer los derechos de acceso, rectificación, cancelación u oposición (ARCO), revocar consentimientos cuando proceda o limitar el uso o divulgación, conforme a la legislación aplicable.

Para ejercer derechos o formular una solicitud, escriba a **morrisgrill@hotmail.com** e indique su nombre, un medio para recibir respuesta, el derecho que desea ejercer y la información que permita localizar los datos relacionados. Si actúa en representación de otra persona, indique esa relación. El Responsable podrá solicitar la información estrictamente necesaria para verificar la identidad o representación conforme a la legislación aplicable. No envíe por correo fotos, contraseñas, números de tarjeta ni otros datos sensibles innecesarios.

Algunos registros solo existen en el dispositivo y el Responsable no puede consultarlos remotamente. Para eliminarlos, el usuario puede retirar marcas dentro de la app, gestionar el elemento en Fotos, cambiar permisos o desinstalar la aplicación. Las solicitudes relativas a compras, identificadores publicitarios o información que Apple o Google administren deberán dirigirse también a esos proveedores mediante sus canales oficiales.

## 13. Menores de edad

Photo Review es de público general y no está diseñada ni se promociona específicamente para niños. La aplicación no crea cuentas ni solicita la edad de quien la usa. La fototeca puede contener imágenes de menores; estas se muestran localmente solo dentro del permiso otorgado y no se envían a servidores de Photo Review ni a solicitudes de anuncios creadas por la aplicación. Las solicitudes publicitarias limitan el contenido a la clasificación general de Google y UMP presenta las opciones de privacidad que correspondan según la región. La aplicación no envía la edad del usuario ni configura las solicitudes como dirigidas específicamente a niños. El uso por menores y el tratamiento de datos asociado están sujetos a las leyes aplicables y a la configuración de edad y controles parentales del dispositivo y de la cuenta de Apple.

Si el Responsable detecta que ha recibido información personal de un menor de forma incompatible con la ley aplicable, tomará las medidas correspondientes, que pueden incluir su eliminación cuando sea posible.

## 14. Cambios a este aviso

El Responsable puede actualizar este aviso cuando cambien la aplicación, los proveedores, las finalidades o las obligaciones legales. La versión vigente indicará la fecha de actualización y estará disponible en [https://morrisgrill33.github.io/photo-review-ios-public/](https://morrisgrill33.github.io/photo-review-ios-public/). Si un cambio requiere consentimiento nuevo, se solicitará mediante la aplicación u otro medio permitido por la legislación aplicable antes de aplicar el tratamiento correspondiente.

## 15. Autoridad de protección de datos

Si el usuario considera que su solicitud no fue atendida adecuadamente, puede acudir a la autoridad competente en materia de protección de datos personales de su jurisdicción. En México, puede consultar a la **Secretaría Anticorrupción y Buen Gobierno** y el procedimiento de protección de derechos previsto en la [Ley Federal de Protección de Datos Personales en Posesión de los Particulares](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf). La información oficial de la Secretaría está disponible en [gob.mx/BuenGobierno](https://www.gob.mx/buengobierno).
