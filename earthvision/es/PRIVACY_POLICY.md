---
title: EarthVision — Política de privacidad
permalink: /earthvision/es/PRIVACY_POLICY.html
---

[Français](../PRIVACY_POLICY.html) · [English](../en/PRIVACY_POLICY.html) · **Español**

# Política de privacidad — EarthVision

_Última actualización: 1 de octubre de 2026_

Esta política explica cómo la aplicación **EarthVision** («la Aplicación», «nosotros») recopila, usa y protege la información cuando la utilizas en Android o iOS.

EarthVision muestra en un globo **webcams públicas en directo** que pertenecen a terceros (canales de YouTube, servicios de transporte, oficinas de turismo…). No grabamos, no almacenamos ni retransmitimos nada: la Aplicación muestra la señal que ofrece el propietario de cada cámara.

---

## 1. Editor

La Aplicación la publica **EarthVision**, con quien puedes contactar en **simondouz81150@gmail.com**.

## 2. Datos que tratamos

EarthVision está diseñada para recopilar lo mínimo. Esta es la lista completa.

### 2.1 Identificador anónimo
- **Qué:** un identificador técnico aleatorio creado en el primer inicio (inicio de sesión anónimo). Sin nombre, correo ni número de teléfono.
- **Para qué:** vincular tus favoritos a tu dispositivo y sincronizarlos.
- **Dónde:** Supabase (alojado en la Unión Europea, Irlanda).
- **Cuánto tiempo:** hasta que borres tus datos (ver sección 6).

### 2.2 Favoritos
- **Qué:** la lista de cámaras que has guardado en favoritos.
- **Para qué:** mostrártelas y calcular la clasificación anónima «Favoritos de la gente» (número de favoritos por cámara, nunca quién guardó qué).
- **Dónde:** en tu dispositivo y en Supabase.

### 2.3 Valoraciones y reportes
- **Valoraciones:** si valoras la app dentro de la Aplicación, la valoración (de 1 a 5 estrellas) se guarda con tu identificador anónimo para ayudarnos a mejorarla.
- **Reportes:** si reportas una cámara, guardamos el identificador de la cámara y la fecha.

### 2.4 Ubicación
- **Cuándo:** **solo** cuando la pides («Ubicarme», la pestaña «Cerca de aquí», alertas de pasos de la ISS) y aceptas el permiso. Nunca en segundo plano sin tu consentimiento, nunca un seguimiento continuo.
- **Para qué:** centrar el globo en ti, ordenar las cámaras por distancia y, si activas las alertas de pasos de la ISS o de auroras (EarthVision+), calcular lo que será visible sobre ti.
- **Dónde:** **solo en tu dispositivo.** Para las alertas, se guarda allí una posición **redondeada a unos 10 km**, que se actualiza al abrir la Aplicación. **Nunca se envía a nuestros servidores.**

### 2.5 Notificaciones y alertas
- **Notificaciones de descubrimiento:** **dos por semana** como mucho (una puesta de sol, un lugar por descubrir).
- **Alertas de EarthVision+ (si las activas):** puesta de sol en uno de tus favoritos (una al día como mucho), pasos visibles de la ISS, noches de auroras.
- **100 % locales:** las programa la Aplicación en tu dispositivo, sin servidor. Para las auroras, la Aplicación consulta más o menos cada hora la previsión pública del índice Kp de la NOAA (ver sección 3): no se envía ningún dato sobre ti, salvo la dirección IP propia de cualquier conexión.
- **Desactivarlas:** en la Aplicación (Perfil, Favoritos) o en los ajustes del teléfono.

### 2.6 Widget de pantalla de inicio
- El widget muestra la imagen del momento de la cámara que elijas. Tu elección y la imagen se guardan **en tu dispositivo**; la imagen se descarga directamente del proveedor de la cámara.

### 2.7 Preferencias
- Idioma, tipos de cámaras mostradas, ajustes de las alertas: se guardan **solo en tu dispositivo**.

### 2.8 Suscripción EarthVision+
- El pago lo gestiona **Google Play** o el **App Store**: nunca recibimos tu medio de pago, tu nombre ni tu correo.
- El estado de tu suscripción lo gestiona **RevenueCat**, que recibe de la tienda el recibo de compra (producto, fecha, renovación) asociado a un identificador de usuario anónimo creado por la Aplicación.

### 2.9 Lo que NO recopilamos
Nombre, correo, dirección, fecha de nacimiento, contactos, fotos, historial de navegación, identificador publicitario. **Ningún seguimiento publicitario.** Por ahora, ninguna estadística de uso ni informe de errores.

## 3. Servicios de terceros

| Servicio | Función | Datos implicados |
|---|---|---|
| **Supabase** (Supabase Inc., servidores en Irlanda) | Base de datos, inicio de sesión anónimo, lista de cámaras | Identificador anónimo, favoritos, valoraciones, reportes, dirección IP (registros técnicos) |
| **RevenueCat** (RevenueCat Inc., Estados Unidos) | Gestión de la suscripción EarthVision+ | Identificador de compra anónimo, recibos de compra enviados por la tienda, dirección IP ([política de RevenueCat](https://www.revenuecat.com/privacy)) |
| **Mapbox** (Mapbox Inc., Estados Unidos) | Mapa y globo | Dirección IP, datos técnicos y telemetría anónima del SDK ([política de Mapbox](https://www.mapbox.com/legal/privacy)) |
| **YouTube** (Google) | Reproducción de directos de YouTube | Datos recopilados por el reproductor de YouTube cuando ves un vídeo ([política de privacidad de Google](https://policies.google.com/privacy)) |
| **Windy** y otros **proveedores de cámaras** (TfL, Fintraffic, departamentos de transporte…) | Envío de imágenes y vídeos | Dirección IP, como en cualquier página web que visites |
| **MET Norway** (Instituto Meteorológico de Noruega) | Tiempo mostrado en la página de una cámara | Coordenadas **de la cámara** (no las tuyas), dirección IP |
| **Wikipedia** (Wikimedia Foundation) | Tarjeta «Sobre este lugar» | Coordenadas **de la cámara**, dirección IP |
| **NOAA** (agencia de EE. UU., previsiones de meteorología espacial) | Previsión de auroras | Solo la dirección IP |
| **Google Play / App Store** | Descargas, valoraciones, compras | Según sus propias políticas |

Algunos datos pueden tratarse fuera de la Unión Europea (RevenueCat, Mapbox, Google), con las garantías adecuadas (Marco de Privacidad de Datos UE-EE. UU. o cláusulas contractuales tipo).

## 4. Base jurídica

- **Ejecución del servicio:** identificador anónimo, favoritos, suscripción, ubicación a petición.
- **Interés legítimo:** valoraciones, reportes, registros técnicos (seguridad, mejora de la app).
- **Consentimiento:** ubicación y notificaciones (permisos del sistema, que puedes retirar en cualquier momento).

## 5. Tarea en segundo plano

Para las alertas de auroras y el widget, la Aplicación ejecuta más o menos una vez por hora una breve tarea en segundo plano (programada por Android, solo con conexión a Internet): consulta la previsión de la NOAA y recarga la imagen del widget. No envía ningún dato personal.

## 6. Tus derechos (RGPD / CCPA)

Puedes acceder a tus datos, rectificarlos, borrarlos, oponerte a su tratamiento o pedir su portabilidad.

- **Borrado inmediato:** en la Aplicación, **Perfil → Borrar mis datos**. Tu identificador anónimo, tus favoritos y tus valoraciones se borran de nuestros servidores y de tu dispositivo.
- **Por correo:** **simondouz81150@gmail.com**. Respuesta en **30 días como máximo**. Consulta también la [página de borrado de datos](./DATA_DELETION.html).
- Puedes presentar una reclamación ante tu autoridad de protección de datos (en España, la **AEPD**, aepd.es).

## 7. Conservación

- Identificador anónimo, favoritos, valoraciones: hasta que borres tus datos.
- Reportes: se conservan sin ningún vínculo contigo tras borrar tus datos.
- Datos de suscripción en RevenueCat: el tiempo necesario para gestionar la suscripción y cumplir las obligaciones legales.
- Datos en el dispositivo (preferencias, posición redondeada, widget): se borran al desinstalar la Aplicación.
- Registros técnicos: unos días, según la política de cada proveedor.

## 8. Seguridad

Todas las comunicaciones con nuestros servidores están cifradas (**HTTPS / TLS**). El acceso a la base de datos está protegido por reglas de seguridad por fila: cada usuario solo puede leer y modificar sus propios favoritos.

## 9. Menores

Las webcams muestran lugares públicos en directo, sin moderación previa. La Aplicación está destinada a usuarios de **13 años o más**. No recopilamos a sabiendas datos de menores de 13 años.

## 10. Personas grabadas

Las cámaras graban lugares públicos y pertenecen a sus operadores. Si crees que una cámara invade tu privacidad, usa «Reportar un problema» en el reproductor o escríbenos: la retiramos de la Aplicación en un plazo de **7 días**.

## 11. Cambios

Esta política puede cambiar (por ejemplo, cuando lleguen los anuncios). La fecha del principio indica la última versión; los cambios importantes se anunciarán en la Aplicación.

## 12. Ley aplicable y contacto

Esta política se rige por la ley **francesa**. Para cualquier pregunta: **simondouz81150@gmail.com**.
