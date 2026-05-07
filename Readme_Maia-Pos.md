# MAIA POS — Sistema de Punto de Venta Profesional

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.8-blue?style=for-the-badge" alt="Versión" />
  <img src="https://img.shields.io/badge/plataforma-Windows%20%7C%20Android-green?style=for-the-badge" alt="Plataformas" />
  <img src="https://img.shields.io/badge/licencia-SaaS-orange?style=for-the-badge" alt="Licencia" />
  <img src="https://img.shields.io/badge/estado-producción-brightgreen?style=for-the-badge" alt="Estado" />
</p>

---

## ¿Qué es MAIA POS?

**MAIA POS** es un sistema de punto de venta (POS) multiplataforma diseñado para pequeños negocios y emprendedores que necesitan una solución ágil, moderna y completa para gestionar sus operaciones diarias.

Disponible para **Windows** (aplicación de escritorio nativa vía Electron) y **Android** (aplicación móvil nativa vía Capacitor), MAIA POS ofrece una experiencia fluida, minimalista y de alto rendimiento tanto en mostrador como en dispositivos móviles.

---

## Módulos y Funcionalidades

### 🛒 Punto de Venta (POS)
- Carrito de compra con búsqueda instantánea de productos.
- Soporte de múltiples métodos de pago (efectivo, tarjeta, transferencia, MercadoPago).
- Descuentos por ítem y por venta global.
- Cálculo automático de vuelto.
- Historial de ventas con filtros avanzados por fecha, método de pago y estado.
- Reapertura y anulación de ventas.
- Impresión de comprobantes (modo thermal y normal).

### 📦 Inventario
- Alta, edición y eliminación de productos.
- Categorías personalizables con colores e íconos.
- Control de stock con alertas de bajo inventario.
- Historial de movimientos de stock (entradas/salidas manuales).
- Kit de embalaje: agrupación de productos en combos vendibles.
- Gestión de insumos y materias primas para producción.
- Importación y exportación de productos en lote.

### 🧪 Recetas, Insumos y Producción
- Creación de recetas para productos gastronómicos y no gastronómicos.
- Definición de insumos, consumos y costos por receta.
- Producción por lote con descuento automático de stock de insumos.
- Gestión de presentaciones por unidad, peso o volumen.
- Estructuras de producto terminado a partir de materias primas.

### ⚖️ Venta por Peso y por Unidades
- Productos configurables para venta por unidad, kilo, gramo, litro o fracción.
- Cálculo automático de precio según cantidad y unidad de medida.
- Conversión de unidades para operaciones de venta y stock.

### 📦 Embalajes y Kits
- Creación de embalajes y combinaciones de venta.
- Armado de kits/combos con impacto automático en el inventario.
- Reglas de contenido por paquete para estandarizar despachos.

### 👥 Clientes
- Base de datos de clientes con historial de compras.
- Búsqueda rápida por nombre, teléfono o DNI/CUIL.
- Registro de deudas y pagos a cuenta.
- Etiquetas y notas personalizadas por cliente.

### 💰 Finanzas
- Registro de ingresos y egresos.
- Caja diaria con apertura y cierre.
- Resumen de rentabilidad por período.
- Integración con ventas del POS.

### 📊 Reportes
- Resumen de ventas por día, semana, mes y período personalizado.
- Productos más vendidos.
- Medios de pago más usados.
- Exportación de reportes a PDF.
- Gráficos de tendencias.

### 🔧 Herramientas
- Copia de seguridad y restauración de datos local.
- Importación/exportación de base de datos.
- Configuración avanzada de la empresa (logo, datos fiscales, impresoras).
- Calculadora integrada.
- Conversor de unidades.

### 🔐 Configuración y Licencia
- Gestión de suscripción desde dentro de la app.
- Información de plan activo, días restantes y dispositivos vinculados.
- Inicio de sesión seguro mediante OTP (código de un solo uso) por email.
- Soporte para hasta **3 dispositivos** por suscripción activa.

---

## Planes y Precios

| Plan | Precio | Descripción |
|------|--------|-------------|
| 🆓 **Prueba gratuita** | $0 por 14 días | Acceso completo a todas las funcionalidades |
| 📅 **Mensual** | $10.000 ARS / mes | Facturación mensual, renovación automática |
| 📆 **Anual** | $60.000 ARS / año | 50% de descuento respecto al plan mensual |

> Los precios pueden actualizarse. Se notificará a los suscriptores activos con anticipación.

---

## Plataformas Soportadas

| Plataforma | Tecnología | Requisito mínimo |
|------------|-----------|------------------|
| **Windows** | Electron (app de escritorio) | Windows 10 / 11, 64-bit |
| **Android** | Capacitor (app nativa) | Android 8.0 (API 26) o superior |

---

## Seguridad y Privacidad

- **Autenticación**: Login sin contraseña mediante OTP enviado al email registrado. No se almacenan contraseñas.
- **Datos locales**: La información operativa (ventas, productos, clientes) se almacena de forma local en el dispositivo usando **IndexedDB**, garantizando disponibilidad sin conexión.
- **Datos en la nube**: Solo se sincroniza información de licencia y autenticación con **Supabase** (infraestructura segura, servers en USA).
- **Privacidad**: No se venden ni comparten datos personales con terceros. Ver [Política de Privacidad](./PRIVACIDAD.md).
- **Licencias**: El sistema valida las licencias de forma criptográfica mediante HMAC-SHA256.
- **Dispositivos**: Cada suscripción admite hasta 3 dispositivos únicos identificados por un ID de hardware anonimizado.

---

## Tecnología

MAIA POS está construido con tecnologías modernas de primer nivel:

- **Frontend**: React 19 + Vite + TypeScript
- **Estilos**: Tailwind CSS + Framer Motion
- **Estado**: Zustand + TanStack Query
- **Base de datos local**: IndexedDB (via Dexie.js)
- **Backend / Auth / Licencias**: Supabase (PostgreSQL + Edge Functions)
- **Desktop (Windows)**: Electron
- **Mobile (Android)**: Capacitor
- **Pagos**: MercadoPago (Argentina)

---

## Política de Uso

El uso de MAIA POS está sujeto a los siguientes documentos legales:

- 📄 [Términos de Servicio](./TERMINOS.md)
- 🔒 [Política de Privacidad](./PRIVACIDAD.md)

---

## Soporte y Contacto

| Canal | Información |
|-------|------------|
| 📧 Email | elninjakenshi.app@gmail.com |
| 📸 Instagram | [@elninjakenshi.app](https://www.instagram.com/elninjakenshi.app) |

---

## Desarrollador

**NinjaKenshiApp**  
Desarrollo de software independiente · Argentina  
Especializado en aplicaciones multiplataforma para comercios de cercanía y emprendedores.

---

<p align="center">
  <strong>MAIA POS © 2024–2026 NinjaKenshiApp. Todos los derechos reservados.</strong>
</p>
