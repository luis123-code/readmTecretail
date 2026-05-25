<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Notas de Crédito · Listado Principal</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Tabla principal de registro de notas de crédito emitidas para corrección o anulación de facturas y boletas, con trazabilidad al documento original mediante el campo Comprobante.</span>

<alert type="info">
  Cada nota de crédito está <strong>vinculada a un documento original</strong> (factura o boleta). El campo <strong>"Comprobante"</strong> muestra qué documento corrige. Revisa siempre esta referencia para mantener trazabilidad de correcciones.
</alert>

---

## Estructura del Listado

### Columnas de la Tabla

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Columna</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Muestra</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Tipo de dato</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Tipo Doc.</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">DNI, RUC, Carnet</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Texto</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Cliente</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Nombre completo</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Texto editable</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Comprobante</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">F001-0001234, B001-0005678</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Texto (referencia)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Serie</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">BC01, FC01</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Texto editable</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Correlativo</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">0001234, 0005678</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Número editable</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Moneda</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">PEN, USD</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Selector editable</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Monto</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">S/. 100.00, $ 50.00</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Número editable</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Motivo</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Devolución de producto</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Texto editable</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Estado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;"><span style="color:#22C55E;font-weight:600;">● Completado</span> <span style="color:#3B82F6;font-weight:600;">● En Proceso</span> <span style="color:#EF4444;font-weight:600;">● Anulado</span></td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Selector editable</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Fecha</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">DD/MM/AAAA</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Fecha editable</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">PDF / XML</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Ver PDF / Ver XML</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Enlaces</td></tr>
</tbody>
</table>

---

## Funcionamiento del Listado

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Carga automática</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Al entrar a la página, el sistema carga las primeras <strong>200 notas</strong> automáticamente. Las notas más recientes aparecen primero (ordenadas por fecha descendente).</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Paginación</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Si hay más de 200 notas, aparecen controles de paginación para navegar entre páginas. Cada página muestra hasta 200 registros.</p>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Badges de Estado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><span style="color:#22C55E;font-weight:600;">● Completado</span> (Verde) - Procesada y aceptada</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><span style="color:#3B82F6;font-weight:600;">● En Proceso</span> (Azul) - En tramite</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><span style="color:#EF4444;font-weight:600;">● Anulado</span> (Rojo) - Nota no válida</p>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Montos</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;"><strong>Positivo</strong> (verde): Montos normales<br><strong>Negativo</strong> (rojo): Devoluciones o anulaciones</p>
</div>

</div>
</div>

---

## Acciones Disponibles

### Ver Detalle

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción A: Clic en fila</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">cualquier parte</span> de la fila</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <strong>modal con detalle</strong> completo</span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción B: Menú acciones</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">menú (...)</span> al final de fila</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>"Ver Detalle"</strong></span></div>
</div>
</div>

</div>
</div>

---

### Editar Nota

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Edición rápida (inline)</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz <span style="font-weight:600;color:#121212;">clic directo</span> en celda a modificar</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Celda se <span style="font-weight:600;color:#121212;">transforma en campo</span> editable</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modifica y presiona <strong>Enter</strong> o clic fuera</span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos editables inline</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Tipo documento, Número documento</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cliente, Email</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Serie, Correlativo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Moneda, Monto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Motivo, Estado, Fecha</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Edición completa (modal)</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">menú (...)</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>"Editar Nota de Crédito"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal con <strong>todos los campos</strong> editable</span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cuál usar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Inline:</strong> Cambios simples de un campo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Modal:</strong> Ediciones complejas, múltiples campos</p>
</div>
</div>

</div>
</div>

---

### Descargar Documentos

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ver PDF</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Ver PDF"</span> en columna PDF</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre en <strong>nueva pestaña</strong> (imprimir/guardar)</span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Descargar XML</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Ver XML"</span> en columna XML</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Archivo se <strong>descarga automáticamente</strong></span></div>
</div>
</div>

</div>
</div>

---

## Campo Comprobante

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">¿Qué muestra?</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Documento original que corrige la nota: <strong>F001-0001234</strong> (factura) o <strong>B001-0005678</strong> (boleta). Se calcula automáticamente desde "Serie Relacionada" + "Correlativo Relacionado".</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Importancia</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Trazabilidad:</strong> Saber qué documento corrige</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Auditoría:</strong> Facilita conciliación</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Referencia:</strong> Vínculo con factura/boleta</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Reportes:</strong> Rastreo de correcciones</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">No editable</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Los campos "Serie Relacionada" y "Correlativo Relacionado" se llenan <strong>automáticamente</strong> al crear la nota y no se editan manualmente. Garantizan integridad del vínculo.</p>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Diferencia clave</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">Las notas de crédito tienen <strong>referencia</strong> a factura/boleta original. Las facturas/boletas no tienen documento relacionado (son originales).</p>
</div>

</div>
</div>

---

## VS Facturas y Boletas

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Aspecto</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Facturas / Boletas</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Notas de Crédito</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Origen</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Desde orden de venta</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Desde factura/boleta existente</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Tipo</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Documento de venta original</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Documento correctivo</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Referencia</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Orden de venta</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Factura/Boleta original (campo Comprobante)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Anulación</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Solo 6 días; después usar nota de crédito</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Sin restricción de tiempo</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Envío SUNAT</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Comprobante de venta</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Anulación/corrección a SUNAT</td></tr>
</tbody>
</table>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para encontrar rápido</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Usa buscador</strong> (más rápido que paginación)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Filtra por fechas</strong> si sabes el período</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Busca por comprobante</strong> si conoces factura/boleta original</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Combina filtros:</strong> fecha + búsqueda</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para revisar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Clic en fila:</strong> Ver detalle completo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Revisa estado:</strong> Debe estar <span style="color:#22C55E;font-weight:600;">● Completado</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Verifica comprobante:</strong> Documento correcto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Descarga PDF:</strong> Para copia de respaldo</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para corregir errores</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Error simple:</strong> Usa edición inline</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Error complejo:</strong> Usa edición modal</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Anular:</strong> Menú → Anular Nota de Crédito</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Verificar:</strong> Confirma comprobante correcto</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Verificación crítica</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Siempre revisa que el campo <strong>Comprobante</strong> muestre la factura o boleta correcta. Este vínculo es fundamental para auditorías y trazabilidad de correcciones.</p>
</div>

</div>
</div>

<alert type="warning">
  El campo <strong>"Comprobante"</strong> es clave: muestra qué factura o boleta corrige cada nota. Verifica siempre esta referencia. Las notas de crédito <strong>siempre</strong> están vinculadas a un documento original. Usa el <strong>buscador por comprobante</strong> para rastrear correcciones específicas.
</alert>