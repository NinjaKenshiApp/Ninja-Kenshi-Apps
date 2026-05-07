# Política de Privacidad — MAIA POS

**Última actualización:** 6 de mayo de 2026  
**Versión:** 1.0  
**Desarrollador:** NinjaKenshiApp  
**Contacto:** elninjakenshi.app@gmail.com

---

## 1. Introducción y Alcance

La presente Política de Privacidad describe cómo **NinjaKenshiApp** (en adelante "nosotros", "el desarrollador" o "el proveedor") recopila, utiliza, almacena, protege y eventualmente elimina la información personal de los usuarios (en adelante "el usuario" o "usted") que instalan y utilizan la aplicación **MAIA POS** (en adelante "la aplicación" o "el software") en plataformas Windows y/o Android.

Al instalar, registrarse o utilizar MAIA POS, usted acepta los términos descritos en esta política. Si no está de acuerdo con alguna de las prácticas aquí descriptas, le solicitamos que se abstenga de utilizar la aplicación.

Esta política cumple con:
- La **Ley N° 25.326 de Protección de Datos Personales** de la República Argentina y sus disposiciones complementarias emitidas por la Agencia de Acceso a la Información Pública (AAIP).
- El **Reglamento General de Protección de Datos (GDPR)** de la Unión Europea, en tanto usuarios europeos puedan acceder al servicio.
- Las políticas de privacidad de **Google Play Store** para aplicaciones Android.
- Las directrices de privacidad de **Microsoft** para aplicaciones de escritorio Windows.

---

## 2. Información que Recopilamos

### 2.1 Información que usted nos proporciona directamente

| Dato | Finalidad | Obligatoriedad |
|------|-----------|----------------|
| **Dirección de email** | Autenticación mediante OTP (código de un solo uso). Comunicaciones sobre la cuenta y la suscripción. | Obligatorio |
| **Información de pago** | Procesada exclusivamente por MercadoPago. MAIA POS nunca accede ni almacena datos de tarjetas de crédito/débito. | Al contratar un plan pago |

### 2.2 Información recopilada automáticamente

| Dato | Descripción | Finalidad |
|------|-------------|-----------|
| **ID de dispositivo** | Identificador único anonimizado generado a partir del hardware del dispositivo. No contiene información personal identificable. | Gestión del límite de dispositivos por suscripción (máximo 3). |
| **Nombre del dispositivo** | Nombre asignado al equipo por el sistema operativo (ej. "PC-ESCRITORIO"). | Visualización en el panel de dispositivos del usuario. |
| **Sesión de autenticación** | Token de sesión cifrado generado por Supabase Auth. | Mantener la sesión activa y validar el acceso a la aplicación. |
| **Datos de uso de licencia** | Plan activo, fecha de inicio, fecha de vencimiento, estado de la suscripción. | Validar el acceso a las funciones de la aplicación. |

### 2.3 Información que NO recopilamos

MAIA POS **no** recopila ni almacena en servidores propios:
- Datos de ventas, productos, clientes, inventario u operaciones del negocio.
- Información financiera o contable del negocio del usuario.
- Registros de actividad dentro de la aplicación (logs de uso).
- Datos de geolocalización.
- Información biométrica.
- Datos de contactos del dispositivo.
- Fotos, videos u otros archivos del dispositivo.

---

## 3. Datos Almacenados Localmente en el Dispositivo

La mayor parte de los datos operativos de MAIA POS —ventas, productos, clientes, inventario, reportes, configuración del negocio— se almacenan de forma **exclusivamente local** en el dispositivo del usuario, utilizando **IndexedDB** (base de datos del navegador/WebView).

**Esto significa:**
- Dichos datos **no se transmiten** a nuestros servidores.
- El usuario tiene control total sobre sus propios datos operativos.
- La eliminación de la aplicación borrará irrecuperablemente todos los datos locales, a menos que el usuario haya realizado una copia de seguridad manual a través de las herramientas provistas en la app.
- No tenemos acceso a los datos del negocio del usuario.

---

## 4. Cómo Usamos la Información

Usamos la información recopilada exclusivamente para los siguientes fines:

1. **Autenticación y acceso seguro**: Verificar la identidad del usuario mediante OTP y gestionar la sesión de forma segura.
2. **Gestión de suscripción y licencia**: Activar, renovar, suspender o cancelar el acceso a las funciones de la aplicación según el plan contratado.
3. **Control de dispositivos**: Verificar que el usuario no supere el límite de 3 dispositivos activos por suscripción.
4. **Comunicaciones esenciales**: Enviar correos transaccionales relativos a la cuenta (código OTP, confirmación de suscripción, alertas de vencimiento). No realizamos envío de publicidad salvo que el usuario haya dado consentimiento explícito.
5. **Soporte técnico**: Si el usuario se contacta con nosotros, podemos usar su email para responder consultas.
6. **Mejora del servicio**: Análisis agregados y anonimizados para entender el uso general del producto y mejorar funcionalidades.

**No vendemos, arrendamos ni cedemos datos personales a terceros** con fines comerciales.

---

## 5. Base Legal para el Tratamiento de Datos

El tratamiento de sus datos personales se realiza bajo las siguientes bases legales:

- **Ejecución de contrato**: Para prestar los servicios solicitados (autenticación, licencia, suscripción).
- **Interés legítimo**: Para prevenir fraudes, garantizar la seguridad del sistema y cumplir el límite de dispositivos por licencia.
- **Obligación legal**: Para cumplir con requerimientos legales aplicables.
- **Consentimiento**: Para comunicaciones de marketing, cuando aplique (con posibilidad de revocación en cualquier momento).

---

## 6. Compartición de Datos con Terceros

MAIA POS utiliza los siguientes proveedores de servicios terceros, quienes pueden procesar datos en nombre del desarrollador:

### 6.1 Supabase (Auth y Base de Datos de Licencias)
- **Proveedor**: Supabase, Inc.
- **Ubicación de servidores**: Estados Unidos de América
- **Datos procesados**: Email del usuario, ID de sesión, datos de suscripción/licencia, ID de dispositivo.
- **Política de privacidad**: [https://supabase.com/privacy](https://supabase.com/privacy)
- **Propósito**: Autenticación segura, almacenamiento y validación de licencias.

### 6.2 MercadoPago (Procesamiento de Pagos)
- **Proveedor**: MercadoLibre S.R.L.
- **Ubicación**: Argentina (con operaciones en Latinoamérica)
- **Datos procesados**: Email del usuario, información de pago (procesada directamente por MercadoPago, nunca por MAIA POS).
- **Política de privacidad**: [https://www.mercadopago.com.ar/privacidad](https://www.mercadopago.com.ar/privacidad)
- **Propósito**: Cobro de suscripciones mensuales y anuales.

### 6.3 Proveedores de Email Transaccional
- Los correos OTP y de notificaciones pueden ser enviados a través de proveedores de email transaccional (como Resend o servicios de Supabase). Solo se transmite el email del destinatario y el contenido del mensaje.

**No compartimos datos con:**
- Redes de publicidad o plataformas de marketing de terceros.
- Brokers de datos o empresas de analítica de datos personales.
- Agencias gubernamentales, salvo requerimiento legal expreso.

---

## 7. Retención de Datos

| Tipo de dato | Período de retención |
|--------------|----------------------|
| Email del usuario | Mientras la cuenta esté activa + 1 año tras la baja |
| Datos de suscripción | 5 años desde la última transacción (obligación fiscal) |
| ID de dispositivo | Mientras el dispositivo esté activo en la cuenta. Se elimina al desvincularlo. |
| Tokens de sesión | Expiran automáticamente (sesión temporal: al cerrar app; sesión persistente: 30 días con renovación automática) |
| Registros de pagos | 10 años (obligación fiscal argentina, Ley N° 20.628 y normas AFIP) |

Transcurridos los plazos indicados, los datos serán eliminados o anonimizados de forma irreversible.

---

## 8. Seguridad de la Información

Implementamos medidas técnicas y organizativas apropiadas para proteger la información personal contra acceso no autorizado, pérdida, alteración o divulgación:

- **Cifrado en tránsito**: Todas las comunicaciones entre la aplicación y los servidores se realizan mediante HTTPS/TLS.
- **Cifrado en reposo**: Los datos almacenados en Supabase se cifran en reposo.
- **Autenticación sin contraseña**: El sistema OTP elimina los riesgos asociados al robo de contraseñas.
- **Tokens de sesión cifrados**: Los tokens JWT están firmados con claves privadas y expiran automáticamente.
- **Principio de mínimo privilegio**: Las funciones del backend solo acceden a los datos estrictamente necesarios para su operación.
- **Validación criptográfica de licencias**: Las licencias se validan mediante HMAC-SHA256, previniendo falsificaciones.

A pesar de estas medidas, ningún sistema es 100% seguro. En caso de una brecha de seguridad que afecte datos personales, notificaremos a los usuarios afectados dentro de las 72 horas de detectada la incidencia.

---

## 9. Derechos del Usuario

De conformidad con la Ley N° 25.326 (Argentina) y el GDPR (para usuarios de la UE), usted tiene los siguientes derechos:

- **Acceso**: Conocer qué datos personales tenemos sobre usted.
- **Rectificación**: Corregir datos inexactos o desactualizados.
- **Supresión ("derecho al olvido")**: Solicitar la eliminación de sus datos personales, sujeto a obligaciones legales de retención.
- **Oposición**: Oponerse al tratamiento de sus datos para determinados fines.
- **Portabilidad**: Recibir sus datos en un formato estructurado y legible.
- **Revocación del consentimiento**: Retirar el consentimiento otorgado en cualquier momento, sin afectar la licitud del tratamiento previo.
- **No ser objeto de decisiones automatizadas**: No tomamos decisiones que le afecten significativamente basadas exclusivamente en tratamiento automatizado.

Para ejercer cualquiera de estos derechos, envíe un correo a **elninjakenshi.app@gmail.com** con el asunto "Derechos ARCO – MAIA POS" e indicando su dirección de email registrada. Responderemos en un plazo máximo de **30 días hábiles**.

Si considera que sus derechos han sido vulnerados, puede presentar una reclamación ante la **Agencia de Acceso a la Información Pública (AAIP)** de Argentina: [https://www.argentina.gob.ar/aaip](https://www.argentina.gob.ar/aaip).

---

## 10. Transferencias Internacionales de Datos

Sus datos pueden ser transferidos y almacenados en servidores ubicados fuera de la República Argentina (principalmente en Estados Unidos, donde opera Supabase Inc.). Estas transferencias se realizan bajo acuerdos que garantizan un nivel de protección adecuado, incluyendo:

- Cláusulas contractuales tipo aprobadas.
- Certificaciones o marcos de adecuación reconocidos.

Al utilizar la aplicación, usted consiente expresamente esta transferencia internacional de datos.

---

## 11. Menores de Edad

MAIA POS es una aplicación destinada a usuarios mayores de 18 años o a personas menores que cuenten con la supervisión y autorización de un adulto responsable del negocio. No recopilamos intencionalmente información personal de menores de 13 años.

Si descubrimos que hemos recopilado información de un menor sin el consentimiento verificable de un padre o tutor, procederemos a eliminar dichos datos de inmediato. Si usted cree que esto ha ocurrido, contáctenos en elninjakenshi.app@gmail.com.

---

## 12. Cookies y Tecnologías Similares

MAIA POS es una aplicación nativa de escritorio/móvil y **no utiliza cookies de navegador web**. Sin embargo, se utilizan tecnologías de almacenamiento local equivalentes:

- **LocalStorage** del WebView: Para persistir la preferencia de sesión del usuario ("Mantener sesión iniciada").
- **IndexedDB**: Para el almacenamiento local de datos operativos (no transmitidos a terceros).
- **Tokens JWT**: Almacenados de forma segura para gestionar la sesión autenticada.

---

## 13. Cambios en esta Política

Nos reservamos el derecho de actualizar esta Política de Privacidad en cualquier momento. Cuando lo hagamos:

1. Actualizaremos la fecha de "Última actualización" al inicio del documento.
2. Notificaremos a los usuarios activos mediante un aviso en la aplicación y/o por correo electrónico si los cambios son materiales.
3. Los cambios entrarán en vigencia **15 días después** de su publicación.

El uso continuado de la aplicación después de la entrada en vigencia de los cambios implica la aceptación de la nueva política. Le recomendamos revisar esta página periódicamente.

---

## 14. Contacto y Responsable del Tratamiento

**Responsable del tratamiento de datos:**

- **Nombre/Razón social**: NinjaKenshiApp
- **País**: República Argentina
- **Email de contacto**: elninjakenshi.app@gmail.com
- **Instagram**: [@elninjakenshi.app](https://www.instagram.com/elninjakenshi.app)

Para consultas, ejercicio de derechos o cualquier cuestión relacionada con el tratamiento de sus datos personales, puede contactarnos en cualquier momento a través del email indicado.

---

*MAIA POS © 2024–2026 NinjaKenshiApp. Todos los derechos reservados.*
