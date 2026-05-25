<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Facturación · Facturas</span>


<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:17px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Consulta y audita facturas filtrando por fecha de emisión con rango inclusivo.</span>

<div style="display:flex;gap:0.5rem;flex-wrap:wrap;margin:1rem 0 1.5rem;">
<span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#F5F5F5;font-size:11px;color:#6B6B6B;font-weight:500;">Aplicación manual</span>
<span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #BFDBFE;background:#DBEAFE;font-size:11px;color:#1E40AF;">Rango inclusivo</span>
<span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:11px;color:#065F46;">Combinable con filtros de columna</span>
</div>

---

## ¿Qué es el Filtro por Fecha en Facturas?

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

Permite ver solo las facturas emitidas dentro de un rango de fechas específico. Es como decirle al sistema: **"Muéstrame las facturas de enero"** o **"Muéstrame las de los últimos 7 días"**.

A diferencia de otros filtros del sistema, este **requiere confirmar con el botón "Aplicar"**. El rango es **inclusivo** en ambos extremos: desde las 00:00:00 hasta las 23:59:59 UTC de las fechas seleccionadas.

</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">

**Ubicación en pantalla**

<div style="margin-top:0.75rem;display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;align-items:center;gap:0.5rem;font-size:13px;color:#121212;">
<span style="width:20px;height:20px;border-radius:50%;background:#DBEAFE;border:1px solid #BFDBFE;display:inline-flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:#1E40AF;flex-shrink:0;">1</span>
Página de <strong>Facturas</strong>
</div>
<div style="display:flex;align-items:center;gap:0.5rem;font-size:13px;color:#121212;">
<span style="width:20px;height:20px;border-radius:50%;background:#DBEAFE;border:1px solid #BFDBFE;display:inline-flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:#1E40AF;flex-shrink:0;">2</span>
Esquina superior izquierda del panel blanco
</div>
<div style="display:flex;align-items:center;gap:0.5rem;font-size:13px;color:#121212;">
<span style="width:20px;height:20px;border-radius:50%;background:#DBEAFE;border:1px solid #BFDBFE;display:inline-flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:#1E40AF;flex-shrink:0;">3</span>
Campos <strong>"Desde"</strong> y <strong>"Hasta"</strong>
</div>
<div style="display:flex;align-items:center;gap:0.5rem;font-size:13px;color:#121212;">
<span style="width:20px;height:20px;border-radius:50%;background:#DBEAFE;border:1px solid #BFDBFE;display:inline-flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:#1E40AF;flex-shrink:0;">4</span>
Botón negro <strong>"Aplicar"</strong> + botón <strong>"Limpiar"</strong>
</div>
</div>

</div>
</div>

---

## Elementos del Filtro

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin:1.25rem 0;">
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#el1)"><path d="M8 2V5" stroke="#6B7280" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M16 2V5" stroke="#6B7280" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M3.5 9.09H20.5" stroke="#6B7280" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M21 8.5V17C21 20 19.5 22 16 22H8C4.5 22 3 20 3 17V8.5C3 5.5 4.5 3.5 8 3.5H16C19.5 3.5 21 5.5 21 8.5Z" stroke="#6B7280" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="el1"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
<span style="font-size:13px;font-weight:600;color:#374151;">Campo "Desde"</span>
</div>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Fecha de <strong>inicio</strong> del rango</span>
<span>→ Etiqueta con ícono de calendario</span>
<span>→ Placeholder: <code>dd/mm/aaaa</code></span>
<span>→ Al seleccionar muestra <code>DD/MM/AAAA</code></span>
<span>→ Filtra: fecha <strong>≥</strong> seleccionada (desde 00:00:00 UTC)</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#el2)"><path d="M8 2V5" stroke="#6B7280" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M16 2V5" stroke="#6B7280" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M3.5 9.09H20.5" stroke="#6B7280" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M21 8.5V17C21 20 19.5 22 16 22H8C4.5 22 3 20 3 17V8.5C3 5.5 4.5 3.5 8 3.5H16C19.5 3.5 21 5.5 21 8.5Z" stroke="#6B7280" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="el2"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
<span style="font-size:13px;font-weight:600;color:#374151;">Campo "Hasta"</span>
</div>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Fecha de <strong>fin</strong> del rango</span>
<span>→ Etiqueta sin ícono adicional</span>
<span>→ Placeholder: <code>dd/mm/aaaa</code></span>
<span>→ Al seleccionar muestra <code>DD/MM/AAAA</code></span>
<span>→ Filtra: fecha <strong>≤</strong> seleccionada (hasta 23:59:59 UTC)</span>
</div>
</div>
<div style="background:#121212;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#fff;margin:0 0 0.6rem;">Botón "Aplicar"</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#D1D5DB;line-height:1.5;">
<span>→ Color negro · texto blanco · bordes redondeados</span>
<span>→ <strong>Obligatorio</strong> — el filtro no actúa sin este clic</span>
<span>→ Se deshabilita mientras procesa</span>
<span>→ Semitransparente mientras carga</span>
</div>
</div>
<div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#DC2626;margin:0 0 0.6rem;">Botón "Limpiar"</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Ícono <strong>X</strong> (XCircle) + texto "Limpiar"</span>
<span>→ <strong>Solo visible</strong> cuando hay fechas seleccionadas</span>
<span>→ Borra fechas y restaura la vista</span>
<span>→ Mantiene otros filtros de columna activos</span>
</div>
</div>
</div>

---

## ¿Cómo Usar el Filtro?

<tabs>
  <tab title="Paso 1 · Desde">

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1rem 0;">
<div>

**Seleccionar la fecha inicial:**

1. Haz clic en el campo **"Desde"** (muestra `dd/mm/aaaa`)
2. Se abre un calendario emergente
3. Navega con las flechas al mes y año
4. Haz clic en el día de inicio
5. El calendario se cierra y aparece la fecha

</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:500;">Puedes dejarlo vacío si:</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#121212;">
<span>→ Solo quieres filtrar <strong>hasta</strong> una fecha</span>
<span>→ Quieres todo el historial hasta cierta fecha</span>
<span>→ El sistema tomará desde el inicio del registro</span>
</div>
</div>
</div>

  </tab>
  <tab title="Paso 2 · Hasta">

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1rem 0;">
<div>

**Seleccionar la fecha final:**

1. Haz clic en el campo **"Hasta"** (muestra `dd/mm/aaaa`)
2. Se abre un calendario emergente
3. Navega al mes y año que necesitas
4. Haz clic en el día de fin
5. El calendario se cierra con la fecha seleccionada

<alert type="warning">
  <svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="display:inline;vertical-align:middle;margin-right:0.3rem;"><g clip-path="url(#wr1)"><path d="M19 8C20.66 8 22 6.66 22 5C22 3.34 20.66 2 19 2C17.34 2 16 3.34 16 5C16 6.66 17.34 8 19 8Z" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14.02 2.2C13.36 2.07 12.69 2 12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 11.32 21.93 10.65 21.8 10.01" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="wr1"><rect width="24" height="24" fill="white"/></clipPath></defs></svg> **"Desde"** debe ser anterior o igual a **"Hasta"**, de lo contrario no aparecerán resultados.
</alert>

</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:500;">Puedes dejarlo vacío si:</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#121212;">
<span>→ Solo quieres filtrar <strong>desde</strong> una fecha</span>
<span>→ Quieres ver todo a partir de cierta fecha</span>
<span>→ El sistema tomará hasta el día de hoy</span>
</div>
</div>
</div>

  </tab>
  <tab title="Paso 3 · Aplicar">

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1rem 0;">
<div>

**Ejecutar el filtro:**

1. Haz clic en el botón negro **"Aplicar"**
2. El sistema procesa la consulta
3. La tabla se actualiza con las facturas del rango
4. El contador de registros se actualiza

</div>
<div style="background:#FFFBEB;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#92400E;margin:0 0 0.5rem;font-weight:600;">Diferencia clave con otros filtros</p>
<p style="font-size:12px;color:#78350F;line-height:1.5;margin:0;">Este filtro <strong>no se aplica automáticamente</strong>. Siempre debes confirmar con el botón <strong>"Aplicar"</strong>. Sin este clic, la tabla no cambia.</p>
</div>
</div>

  </tab>
  <tab title="Paso 4 · Limpiar">

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1rem 0;">
<div>

**Quitar el filtro de fecha:**

1. Haz clic en el botón **"Limpiar"** (ícono X + texto)
2. Las fechas se borran de ambos campos
3. La tabla vuelve a mostrar todas las facturas
4. El botón "Limpiar" desaparece hasta la próxima selección

</div>
<div style="background:#F0FDF4;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#065F46;margin:0 0 0.5rem;font-weight:500;">Qué se mantiene al limpiar:</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#065F46;">
<span>✓ Filtros de columna del DataTable</span>
<span>✓ Búsqueda activa (si la hay)</span>
<span>✗ Fechas seleccionadas (se borran)</span>
<span>✗ Condiciones de fecha en la consulta</span>
</div>
</div>
</div>

  </tab>
</tabs>

---

## Ejemplos de Uso

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.75rem;">Facturas de hoy</p>
<div style="background:#fff;border-radius:0.5rem;padding:0.75rem;font-size:12px;color:#121212;display:flex;flex-direction:column;gap:0.3rem;border:1px solid #E5E5E5;">
<span><strong>Desde:</strong> hoy</span>
<span><strong>Hasta:</strong> hoy</span>
<span style="color:#249F65;margin-top:0.25rem;">→ Solo emisiones del día actual</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.75rem;">Mes completo</p>
<div style="background:#fff;border-radius:0.5rem;padding:0.75rem;font-size:12px;color:#121212;display:flex;flex-direction:column;gap:0.3rem;border:1px solid #E5E5E5;">
<span><strong>Desde:</strong> 01/03/2024</span>
<span><strong>Hasta:</strong> 31/03/2024</span>
<span style="color:#249F65;margin-top:0.25rem;">→ Todo marzo de 2024</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.75rem;">Desde una fecha en adelante</p>
<div style="background:#fff;border-radius:0.5rem;padding:0.75rem;font-size:12px;color:#121212;display:flex;flex-direction:column;gap:0.3rem;border:1px solid #E5E5E5;">
<span><strong>Desde:</strong> 15/01/2024</span>
<span><strong>Hasta:</strong> <em>(vacío)</em></span>
<span style="color:#249F65;margin-top:0.25rem;">→ Todo desde esa fecha hasta hoy</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.75rem;">Hasta una fecha específica</p>
<div style="background:#fff;border-radius:0.5rem;padding:0.75rem;font-size:12px;color:#121212;display:flex;flex-direction:column;gap:0.3rem;border:1px solid #E5E5E5;">
<span><strong>Desde:</strong> <em>(vacío)</em></span>
<span><strong>Hasta:</strong> 28/02/2024</span>
<span style="color:#249F65;margin-top:0.25rem;">→ Todo el historial hasta esa fecha</span>
</div>
</div>
</div>

---

## Combinación con Otros Filtros

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.5rem;">+ Filtros de columna (DataTable)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.75rem;line-height:1.5;">Trabajan en conjunto. El filtro de fecha se envía como condición adicional (<code>additionalWhereConditions</code>).</p>
<div style="background:#F9FAFB;border-radius:0.5rem;padding:0.75rem;font-size:12px;color:#121212;line-height:1.5;">
<strong>Ej:</strong> Marzo 2024 + columna Estado = <span style="display:inline-flex;padding:0.1rem 0.4rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;font-size:10px;color:#065F46;">Aceptado</span> → facturas aceptadas de marzo
</div>
</div>
<div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.5rem;">+ Búsqueda general</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.75rem;line-height:1.5;">Búsqueda y filtro de fecha <strong>no son simultáneos</strong>. Al aplicar fecha con búsqueda activa, la búsqueda se desactiva.</p>
<div style="background:#FFFBEB;border-radius:0.5rem;padding:0.75rem;font-size:12px;color:#78350F;line-height:1.5;">
<strong>Prioridad:</strong> El filtro de fecha tiene prioridad sobre la búsqueda activa.
</div>
</div>
</div>

---

## Cuándo Usar el Filtro

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.75rem;">Cierre mensual</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Filtra por el mes a cerrar</span>
<span>→ Revisa todas las facturas del período</span>
<span>→ Verifica totales y estados</span>
<span>→ Exporta si es necesario</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.75rem;">Declaración de impuestos</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Filtra por el período fiscal</span>
<span>→ Revisa facturas aceptadas</span>
<span>→ Verifica montos y documentos</span>
<span>→ Prepara la declaración</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.75rem;">Auditoría</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Filtra por el rango solicitado</span>
<span>→ Revisa facturas del período</span>
<span>→ Verifica que todo esté en orden</span>
<span>→ Documenta hallazgos</span>
</div>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
<p style="font-size:13px;font-weight:600;color:#121212;margin:0 0 0.75rem;">Monitoreo diario</p>
<div style="display:flex;flex-direction:column;gap:0.35rem;font-size:12px;color:#6B6B6B;line-height:1.5;">
<span>→ Filtra por el día de hoy</span>
<span>→ Revisa facturas emitidas</span>
<span>→ Verifica estados</span>
<span>→ Identifica problemas</span>
</div>
</div>
</div>

---

## Referencia Rápida

| Elemento | Descripción |
|----------|-------------|
| **Campo "Desde"** | Fecha de inicio · filtra ≥ fecha seleccionada |
| **Campo "Hasta"** | Fecha de fin · filtra ≤ fecha seleccionada |
| **Botón "Aplicar"** | Obligatorio — ejecuta el filtro manualmente |
| **Botón "Limpiar"** | Visible solo con fechas activas · quita solo el filtro de fecha |
| **Campo filtrado** | `fecha` — fecha de emisión de la factura |
| **Rango inclusivo** | Ambos extremos incluidos (00:00:00 a 23:59:59 UTC) |
| **Con búsqueda** | La fecha tiene prioridad, desactiva la búsqueda |
| **Con columnas** | Trabajan en conjunto como condición adicional |

---

## Errores Comunes

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin:1.25rem 0;">
<div>

<alert type="warning">
  <svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="display:inline;vertical-align:middle;margin-right:0.3rem;"><g clip-path="url(#ew1)"><path d="M19 8C20.66 8 22 6.66 22 5C22 3.34 20.66 2 19 2C17.34 2 16 3.34 16 5C16 6.66 17.34 8 19 8Z" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14.02 2.2C13.36 2.07 12.69 2 12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 11.32 21.93 10.65 21.8 10.01" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="ew1"><rect width="24" height="24" fill="white"/></clipPath></defs></svg> **"Selecciona al menos una fecha"** — Hiciste clic en "Aplicar" sin seleccionar ninguna fecha. Selecciona al menos un campo antes de aplicar.
</alert>

</div>
<div>

<alert type="warning">
  <svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="display:inline;vertical-align:middle;margin-right:0.3rem;"><g clip-path="url(#ew2)"><path d="M19 8C20.66 8 22 6.66 22 5C22 3.34 20.66 2 19 2C17.34 2 16 3.34 16 5C16 6.66 17.34 8 19 8Z" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14.02 2.2C13.36 2.07 12.69 2 12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 11.32 21.93 10.65 21.8 10.01" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="ew2"><rect width="24" height="24" fill="white"/></clipPath></defs></svg> **No aparecen resultados** — No hay facturas en ese rango, o la combinación con otros filtros es muy restrictiva. Amplía el rango o limpia otros filtros.
</alert>

</div>
<div style="grid-column:span 2;">

<alert type="warning">
  <svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="display:inline;vertical-align:middle;margin-right:0.3rem;"><g clip-path="url(#ew3)"><path d="M19 8C20.66 8 22 6.66 22 5C22 3.34 20.66 2 19 2C17.34 2 16 3.34 16 5C16 6.66 17.34 8 19 8Z" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14.02 2.2C13.36 2.07 12.69 2 12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 11.32 21.93 10.65 21.8 10.01" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="ew3"><rect width="24" height="24" fill="white"/></clipPath></defs></svg> **"Desde" mayor que "Hasta"** — La fecha inicial es posterior a la final. Verifica que el rango sea cronológicamente correcto y haz clic en "Aplicar" nuevamente.
</alert>

</div>
</div>

---

<alert type="info">
  <svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="display:inline;vertical-align:middle;margin-right:0.3rem;"><g clip-path="url(#ai1)"><path d="M19 8C20.66 8 22 6.66 22 5C22 3.34 20.66 2 19 2C17.34 2 16 3.34 16 5C16 6.66 17.34 8 19 8Z" stroke="#047857" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 13H12" stroke="#047857" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 17H16" stroke="#047857" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14 2H9C4 2 2 4 2 9v6c0 5 2 7 7 7h6c5 0 7-2 7-7v-5" stroke="#047857" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="ai1"><rect width="24" height="24" fill="white"/></clipPath></defs></svg> Este filtro actúa sobre el campo <code>fecha</code> (fecha de emisión). **Siempre haz clic en "Aplicar"** — el filtro no se ejecuta automáticamente. Verifica el contador de registros después de aplicar para confirmar que el filtro se ejecutó correctamente.
</alert>