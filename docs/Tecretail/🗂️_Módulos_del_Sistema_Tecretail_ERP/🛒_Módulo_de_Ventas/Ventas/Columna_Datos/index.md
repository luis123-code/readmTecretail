
# <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="vertical-align:middle;margin-right:0.5rem;display:inline;"><g clip-path="url(#h1)"><path d="M19 8C20.66 8 22 6.66 22 5C22 3.34 20.66 2 19 2C17.34 2 16 3.34 16 5C16 6.66 17.34 8 19 8Z" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 13H12" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 17H16" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14 2H9C4 2 2 4 2 9v6c0 5 2 7 7 7h6c5 0 7-2 7-7v-5" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="h1"><rect width="24" height="24" fill="white"/></clipPath></defs></svg> Columnas de Datos — Página de Ventas

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:17px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Referencia completa de las 18 columnas de la tabla de órdenes de venta: datos, interacciones y configuración.</span>

<div style="display:flex;gap:0.5rem;flex-wrap:wrap;margin:1rem 0 1.5rem;">
<span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:11px;color:#065F46;font-weight:500;">18 columnas</span>
<span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #BFDBFE;background:#DBEAFE;font-size:11px;color:#1E40AF;">5 editables</span>
<span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#F5F5F5;font-size:11px;color:#6B6B6B;">6 ocultables</span>
</div>

---

## Resumen de Columnas

| # | Columna | Clave | Editable | Ocultable |
|---|---------|-------|----------|-----------|
| 1 | ID Venta | `OrdenVenta_id` | — | — |
| 2 | Fecha | `fecha` | ✓ doble clic | — |
| 3 | Hora | `Hora` | — | ✓ |
| 4 | Cliente | `Contactx` | ✓ clic | — |
| 5 | Resumen | `produc` | — | — |
| 6 | Total con Descuento | `totalConDescuento` | — | — |
| 7 | Movimientos | `Movimiento` | — | — |
| 8 | Saldo Adeudado | `saldoAdeudado` | — | ✓ |
| 9 | Estado | `StatusVent` | ✓ doble clic | — |
| 10 | Estado Interno | `SelectInterno` | ✓ doble clic | ✓ |
| 11 | Estado Interno 2 | `SelectInterno2` | ✓ doble clic | ✓ |
| 12 | Estado Interno 3 | `SelectInterno3` | ✓ doble clic | ✓ |
| 13 | Boletas | `Boletas` | — | — |
| 14 | Facturas | `Facturas` | — | — |
| 15 | CxC | `CuentasPorCobrar` | — | — |
| 16 | Envíos | `OrdenEnvio` | — | — |
| 17 | Canal | `Canal` | — | ✓ |
| 18 | Order ID | `SagaOrderId` | — | ✓ |

---

## Columnas de Identificación y Tiempo

<tabs>
  <tab title="ID Venta">

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1rem 0;">
<div>

**Clave:** `OrdenVenta_id`

Número identificador único de la orden de venta. A la izquierda del número aparece un botón de expansión **(chevron ▶)** para mostrar las líneas de la orden.

**Interacciones:**
- Clic en **▶** expande las líneas de producto
- Muestra spinner mientras carga los datos
- Al expandir cambia a **▼**

</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:500;">Características:</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#121212;">
<span>→ Tipo: <strong>Número</strong></span>
<span>→ Editable: <span style="color:#DC2626;">No</span></span>
<span>→ Ocultable: <span style="color:#DC2626;">No</span></span>
<span>→ Ejemplo: <code>1234</code>, <code>5678</code></span>
</div>
</div>
</div>

  </tab>
  <tab title="Fecha">

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1rem 0;">
<div>

**Clave:** `fecha`

Fecha de emisión de la orden. Muestra un ícono de calendario a la izquierda del valor formateado.

**Interacciones:**
- **Doble clic** abre un selector de fecha (DatePicker)
- Selecciona la nueva fecha
- Se guarda automáticamente

</div>
<div style="background:#F0FDF4;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#065F46;margin:0 0 0.5rem;font-weight:500;">Características:</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#065F46;">
<span>→ Tipo: <strong>Fecha</strong></span>
<span>→ Formato: <code>DD/MM/AAAA</code></span>
<span>→ Editable: <span style="color:#249F65;font-weight:600;">Sí</span></span>
<span>→ Ocultable: <span style="color:#DC2626;">No</span></span>
</div>
</div>
</div>

  </tab>
  <tab title="Hora">

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1rem 0;">
<div>

**Clave:** `Hora`

Hora de creación de la orden en formato `HH:MM`. Si no existe hora registrada muestra `—`. Se presenta en texto pequeño y gris.

</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:500;">Características:</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#121212;">
<span>→ Tipo: <strong>Texto</strong></span>
<span>→ Formato: <code>HH:MM</code></span>
<span>→ Editable: <span style="color:#DC2626;">No</span></span>
<span>→ Ocultable: <span style="color:#249F65;font-weight:600;">Sí</span></span>
</div>
</div>
</div>

  </tab>
</tabs>

---

## Columnas de Cliente y Productos

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div style="background:#EFF6FF;border:1px solid #BFDBFE;border-radius:0.75rem;padding:1.25rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#cl1)"><path d="M12 12C14.7614 12 17 9.76142 17 7C17 4.23858 14.7614 2 12 2C9.23858 2 7 4.23858 7 7C7 9.76142 9.23858 12 12 12Z" stroke="#1E40AF" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M20.59 22C20.59 18.13 16.74 15 12 15C7.26 15 3.41 18.13 3.41 22" stroke="#1E40AF" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="cl1"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
<span style="font-size:13px;font-weight:600;color:#1E40AF;">Cliente</span>
<code style="font-size:10px;background:#DBEAFE;padding:0.1rem 0.4rem;border-radius:4px;color:#1E40AF;margin-left:auto;">Contactx</code>
</div>
<div style="display:flex;flex-direction:column;gap:0.4rem;font-size:12px;color:#1E3A5F;line-height:1.5;">
<span>→ Nombre capitalizado en <strong>badge azul</strong></span>
<span>→ Sin cliente: badge gris "Cliente no definido"</span>
<span>→ <strong>Clic</strong> abre mini editor de contacto</span>
<span>→ Editable: nombre, email, RUC/DNI, teléfono, dirección, empresa</span>
</div>
<div style="margin-top:0.75rem;display:flex;gap:0.35rem;flex-wrap:wrap;">
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#DBEAFE;border:1px solid #BFDBFE;font-size:10px;color:#1E40AF;">Editable</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;font-size:10px;color:#DC2626;">No ocultable</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#pr1)"><path d="M19 8C20.66 8 22 6.66 22 5C22 3.34 20.66 2 19 2C17.34 2 16 3.34 16 5C16 6.66 17.34 8 19 8Z" stroke="#6B7280" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 13H12" stroke="#6B7280" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 17H16" stroke="#6B7280" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14 2H9C4 2 2 4 2 9v6c0 5 2 7 7 7h6c5 0 7-2 7-7v-5" stroke="#6B7280" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="pr1"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
<span style="font-size:13px;font-weight:600;color:#374151;">Resumen (Productos)</span>
<code style="font-size:10px;background:#F5F5F5;padding:0.1rem 0.4rem;border-radius:4px;color:#6B7280;margin-left:auto;">produc</code>
</div>
<div style="display:flex;flex-direction:column;gap:0.4rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Botón <strong>"Ver detalles (N)"</strong></span>
<span>→ Dropdown: imagen, nombre, SKU, cantidad × precio, subtotal, total, nota</span>
<span>→ Clic en producto abre detalle completo</span>
<span>→ "Ocultar detalles" cierra el dropdown</span>
</div>
<div style="margin-top:0.75rem;display:flex;gap:0.35rem;flex-wrap:wrap;">
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#F5F5F5;border:1px solid #E5E5E5;font-size:10px;color:#6B7280;">No editable</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;font-size:10px;color:#DC2626;">No ocultable</span>
</div>
</div>
</div>

---

## Columnas Financieras

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div style="background:#F0FDF4;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1.25rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#fi1)"><path d="M19.3 7.92V13.07C19.3 16.15 17.54 17.47 14.9 17.47H6.11C5.66 17.47 5.23 17.43 4.83 17.34C4.58 17.3 4.34 17.23 4.12 17.15C2.62 16.59 1.71 15.29 1.71 13.07V7.92C1.71 4.84 3.47 3.52 6.11 3.52H14.9C17.14 3.52 18.75 4.47 19.18 6.64C19.25 7.04 19.3 7.45 19.3 7.92Z" stroke="#249F65" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M22.3 10.92V16.07C22.3 19.15 20.54 20.47 17.9 20.47H9.11C8.37 20.47 7.7 20.37 7.12 20.15C5.93 19.71 5.12 18.8 4.83 17.34C5.23 17.43 5.66 17.47 6.11 17.47H14.9C17.54 17.47 19.3 16.15 19.3 13.07V7.92C19.3 7.45 19.26 7.03 19.18 6.64C21.08 7.04 22.3 8.38 22.3 10.92Z" stroke="#249F65" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M10.5 13.14C11.96 13.14 13.14 11.96 13.14 10.5C13.14 9.04 11.96 7.86 10.5 7.86C9.04 7.86 7.86 9.04 7.86 10.5C7.86 11.96 9.04 13.14 10.5 13.14Z" stroke="#249F65" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="fi1"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
<span style="font-size:13px;font-weight:600;color:#065F46;">Total con Descuento</span>
<code style="font-size:10px;background:#D1FAE5;padding:0.1rem 0.4rem;border-radius:4px;color:#065F46;margin-left:auto;">totalConDescuento</code>
</div>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#065F46;line-height:1.5;">
<span>→ Monto total aplicando descuentos de promociones</span>
<span>→ <strong style="color:#249F65;">Verde</strong> si positivo · <strong style="color:#DC2626;">Rojo</strong> si negativo</span>
<span>→ Se calcula automáticamente</span>
<span>→ No editable · No ocultable</span>
</div>
</div>
<div style="background:#EFF6FF;border:1px solid #BFDBFE;border-radius:0.75rem;padding:1.25rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#fi2)"><path d="M22 12C22 17.52 17.52 22 12 22C6.48 22 2 17.52 2 12C2 6.48 6.48 2 12 2C17.52 2 22 6.48 22 12Z" stroke="#1E40AF" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M15.71 15.18L12.61 13.33C12.07 13.01 11.63 12.24 11.63 11.61V7.51" stroke="#1E40AF" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="fi2"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
<span style="font-size:13px;font-weight:600;color:#1E40AF;">Movimientos</span>
<code style="font-size:10px;background:#DBEAFE;padding:0.1rem 0.4rem;border-radius:4px;color:#1E40AF;margin-left:auto;">Movimiento</code>
</div>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#1E3A5F;line-height:1.5;">
<span>→ Suma de pagos + cantidad de movimientos</span>
<span>→ Ejemplo: <code>+S/ 500.00 (2 movimientos)</code></span>
<span>→ Egresos se restan del total</span>
<span>→ Chevron para expandir detalle</span>
</div>
</div>
<div style="background:#FFF5F5;border:1px solid #FECACA;border-radius:0.75rem;padding:1.25rem;grid-column:span 2;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#fi3)"><path d="M19.3 7.92V13.07C19.3 16.15 17.54 17.47 14.9 17.47H6.11C5.66 17.47 5.23 17.43 4.83 17.34C4.58 17.3 4.34 17.23 4.12 17.15C2.62 16.59 1.71 15.29 1.71 13.07V7.92C1.71 4.84 3.47 3.52 6.11 3.52H14.9C17.14 3.52 18.75 4.47 19.18 6.64C19.25 7.04 19.3 7.45 19.3 7.92Z" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M22.3 10.92V16.07C22.3 19.15 20.54 20.47 17.9 20.47H9.11C8.37 20.47 7.7 20.37 7.12 20.15C5.93 19.71 5.12 18.8 4.83 17.34C5.23 17.43 5.66 17.47 6.11 17.47H14.9C17.54 17.47 19.3 16.15 19.3 13.07V7.92C19.3 7.45 19.26 7.03 19.18 6.64C21.08 7.04 22.3 8.38 22.3 10.92Z" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M10.5 13.14C11.96 13.14 13.14 11.96 13.14 10.5C13.14 9.04 11.96 7.86 10.5 7.86C9.04 7.86 7.86 9.04 7.86 10.5C7.86 11.96 9.04 13.14 10.5 13.14Z" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="fi3"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
<span style="font-size:13px;font-weight:600;color:#DC2626;">Saldo Adeudado</span>
<code style="font-size:10px;background:#FEE2E2;padding:0.1rem 0.4rem;border-radius:4px;color:#DC2626;margin-left:auto;">saldoAdeudado</code>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#F5F5F5;border:1px solid #E5E5E5;font-size:10px;color:#6B7280;margin-left:0.5rem;">Ocultable</span>
</div>
<div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;">
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#991B1B;line-height:1.5;">
<span>→ <strong>Total con descuento − Suma de movimientos</strong></span>
<span>→ <strong style="color:#1E40AF;">Azul</strong> si positivo (hay deuda pendiente)</span>
<span>→ <strong style="color:#DC2626;">Rojo</strong> si negativo (exceso de pago)</span>
</div>
<div style="background:#FEE2E2;border-radius:0.5rem;padding:0.5rem 0.75rem;font-size:12px;color:#991B1B;display:flex;flex-direction:column;gap:0.25rem;">
<span>No editable</span>
<span>Ocultable vía configuración</span>
<span>Fuente en negrita</span>
</div>
</div>
</div>
</div>

---

## Columna Estado

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

**Clave:** `StatusVent` · **Editable con doble clic**

Muestra el estado actual de la orden como un badge con color semántico. Al hacer doble clic se abre un dropdown con todas las opciones disponibles. El cambio se guarda automáticamente.

</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:500;">Estados disponibles:</p>
<div style="display:flex;flex-wrap:wrap;gap:0.3rem;">
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#F5F5F5;border:1px solid #E5E5E5;font-size:10px;color:#6B7280;">Pendiente</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#EDE9FE;border:1px solid #DDD6FE;font-size:10px;color:#5B21B6;">Por fabricar</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#FEF3C7;border:1px solid #FDE68A;font-size:10px;color:#92400E;">Por enviar</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#DBEAFE;border:1px solid #BFDBFE;font-size:10px;color:#1E40AF;">Procesado</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;font-size:10px;color:#065F46;">Completada</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;font-size:10px;color:#065F46;">Enviado</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#F0FDF4;border:1px solid #A7F3D0;font-size:10px;color:#065F46;">Ahorro</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;font-size:10px;color:#DC2626;">Desaprobado</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;font-size:10px;color:#DC2626;">Cancelado</span>
<span style="display:inline-flex;padding:0.1rem 0.5rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;font-size:10px;color:#DC2626;">Anulada</span>
</div>
</div>
</div>

---

## Estados Internos Personalizables

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

Las columnas **Estado Interno**, **Estado Interno 2** y **Estado Interno 3** son totalmente personalizables por empresa: el nombre de la columna, las opciones disponibles y los colores se configuran según el negocio.

**Comportamiento común:**
- **Doble clic** para editar
- Badge con color de fondo según configuración
- Sin valor muestra `"Sin estado"` en gris
- Todas son **ocultables** vía configuración

</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:500;">Las tres columnas:</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;align-items:center;justify-content:space-between;font-size:12px;color:#121212;">
<span><strong>Estado Interno</strong></span>
<code style="font-size:10px;background:#F5F5F5;padding:0.1rem 0.4rem;border-radius:4px;color:#6B7280;">SelectInterno</code>
</div>
<div style="display:flex;align-items:center;justify-content:space-between;font-size:12px;color:#121212;">
<span><strong>Estado Interno 2</strong></span>
<code style="font-size:10px;background:#F5F5F5;padding:0.1rem 0.4rem;border-radius:4px;color:#6B7280;">SelectInterno2</code>
</div>
<div style="display:flex;align-items:center;justify-content:space-between;font-size:12px;color:#121212;">
<span><strong>Estado Interno 3</strong></span>
<code style="font-size:10px;background:#F5F5F5;padding:0.1rem 0.4rem;border-radius:4px;color:#6B7280;">SelectInterno3</code>
</div>
</div>
</div>
</div>

---

## Columnas de Documentos y Relaciones

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin:1.25rem 0;">
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.6rem;">Boletas <code style="font-size:10px;background:#F5F5F5;padding:0.1rem 0.3rem;border-radius:4px;color:#6B7280;font-weight:400;">Boletas</code></p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Miniatura de documento</span>
<span>→ <code>+N</code> si hay más de una · <code>—</code> si no hay</span>
<span>→ Clic abre pestaña de documentos</span>
<span>→ Chevron expande lista completa</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.6rem;">Facturas <code style="font-size:10px;background:#F5F5F5;padding:0.1rem 0.3rem;border-radius:4px;color:#6B7280;font-weight:400;">Facturas</code></p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Miniatura de documento</span>
<span>→ <code>+N</code> si hay más de una · <code>—</code> si no hay</span>
<span>→ Clic abre pestaña de documentos</span>
<span>→ Chevron expande lista completa</span>
</div>
</div>
<div style="background:#FFFBEB;border:1px solid #FDE68A;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#92400E;margin:0 0 0.6rem;">CxC <code style="font-size:10px;background:#FEF3C7;padding:0.1rem 0.3rem;border-radius:4px;color:#92400E;font-weight:400;">CuentasPorCobrar</code></p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#78350F;line-height:1.5;">
<span>→ Badge ámbar con código y monto</span>
<span>→ Ejemplo: <code>CXC-001 S/. 500.00</code></span>
<span>→ Ícono <strong>$</strong> para mostrar · <code>—</code> si no hay</span>
<span>→ Chevron expande si hay varias</span>
</div>
</div>
<div style="background:#F5F3FF;border:1px solid #DDD6FE;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#5B21B6;margin:0 0 0.6rem;">Envíos <code style="font-size:10px;background:#EDE9FE;padding:0.1rem 0.3rem;border-radius:4px;color:#5B21B6;font-weight:400;">OrdenEnvio</code></p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#4C1D95;line-height:1.5;">
<span>→ Badge púrpura con <code>OE-{id}</code></span>
<span>→ Badge adicional con estado del envío</span>
<span>→ Clic abre pestaña de envíos · <code>—</code> si no hay</span>
<span>→ Chevron expande si hay varios</span>
</div>
</div>
</div>

---

## Columnas de Canal y Marketplace

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<span style="font-size:13px;font-weight:600;color:#374151;">Canal</span>
<code style="font-size:10px;background:#F5F5F5;padding:0.1rem 0.4rem;border-radius:4px;color:#6B7280;margin-left:auto;">Canal</code>
<span style="display:inline-flex;padding:0.1rem 0.4rem;border-radius:9999px;background:#F5F5F5;border:1px solid #E5E5E5;font-size:10px;color:#6B7280;">Ocultable</span>
</div>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Canal de venta de la orden</span>
<span>→ Badge con color personalizado por canal</span>
<span>→ Ejemplos: <code>Tienda</code>, <code>Online</code>, <code>Mercado Libre</code>, <code>Falabella</code></span>
<span>→ <code>—</code> si no tiene canal asignado</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<span style="font-size:13px;font-weight:600;color:#374151;">Order ID</span>
<code style="font-size:10px;background:#F5F5F5;padding:0.1rem 0.4rem;border-radius:4px;color:#6B7280;margin-left:auto;">SagaOrderId</code>
<span style="display:inline-flex;padding:0.1rem 0.4rem;border-radius:9999px;background:#F5F5F5;border:1px solid #E5E5E5;font-size:10px;color:#6B7280;">Ocultable</span>
</div>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ ID de la orden en marketplace externo</span>
<span>→ Falabella: muestra <code>SagaOrderId</code></span>
<span>→ Otros: muestra <code>CanalId</code></span>
<span>→ Texto en fuente monoespaciada · <code>—</code> si no hay</span>
</div>
</div>
</div>

---

<alert type="info">
  <svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="display:inline;vertical-align:middle;margin-right:0.3rem;"><g clip-path="url(#ai1)"><path d="M19 8C20.66 8 22 6.66 22 5C22 3.34 20.66 2 19 2C17.34 2 16 3.34 16 5C16 6.66 17.34 8 19 8Z" stroke="#047857" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 13H12" stroke="#047857" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 17H16" stroke="#047857" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14 2H9C4 2 2 4 2 9v6c0 5 2 7 7 7h6c5 0 7-2 7-7v-5" stroke="#047857" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="ai1"><rect width="24" height="24" fill="white"/></clipPath></defs></svg> La visibilidad de las **6 columnas ocultables** (Hora, Saldo Adeudado, Estado Interno 1-3, Canal, Order ID) se guarda en <code>localStorage</code> del navegador y se mantiene entre sesiones. Los **estados internos** son completamente configurables por empresa: nombres, opciones y colores se definen según tu negocio.
</alert>
```