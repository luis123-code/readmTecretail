<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Facturas · Listado y Gestión</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Tabla principal de facturas emitidas con visualización de 200 registros por página, filtros de fecha, búsqueda avanzada y acciones directas sobre cada documento.</span>

<alert type="info">
  Listado con carga automática de últimas 200 facturas, ordenamiento fijo por fecha descendente, edición inline y descarga de documentos PDF/XML. No permite eliminar facturas (solo anular dentro de 6 días).
</alert>

---

## Información Visualizada

### Columnas del Listado

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.4rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Grupo</th>
<th style="text-align:left;padding:0.4rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Campo</th>
<th style="text-align:left;padding:0.4rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Descripción</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;" rowspan="4">Cliente</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Tipo Doc.</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">RUC, DNI, Carnet extranjería</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Nro. Doc.</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Número de documento</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Cliente</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Nombre empresa o persona</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Email</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Correo electrónico</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;" rowspan="5">Factura</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Moneda</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">PEN (Soles) o USD (Dólares)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Monto</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Total de la factura</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Serie</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">F001, B001, etc.</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Número</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Correlativo (0001234)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Descripción</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Breve descripción de venta</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;">Estado</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Estado</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Aceptado, En Proceso, Anulado</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;">Fecha</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Fecha</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Fecha de emisión</td></tr>
<tr><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;" rowspan="2">Documentos</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">PDF</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Enlace para ver documento</td></tr>
<tr><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">XML</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Enlace para descargar archivo</td></tr>
</tbody>
</table>

---

## Funcionalidades del Listado

### 1. Ver Detalle de Factura

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción A: Clic en fila</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">cualquier parte de la fila</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal se abre con <strong>detalle completo</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción B: Menú de acciones</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">menú (...)</span> al final de fila</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>"Ver Detalle"</strong></span></div>
</div>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Información mostrada</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Datos completos del cliente</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Detalle de productos/servicios</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Totales e impuestos</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Estado y observaciones</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Carga automática</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Máximo <strong>200 facturas</strong> por página</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ordenamiento <strong>fijo por fecha</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Más recientes primero</p>
</div>
</div>

</div>
</div>

---

### 2. Editar Factura

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Edición Rápida (Inline)</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz <span style="font-weight:600;color:#121212;">clic directo</span> en la celda</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Celda se convierte en <strong>campo editable</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modifica el valor</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Presiona <strong>Enter</strong> o clic fuera</span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Edición Completa (Modal)</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Menú de acciones → <span style="font-weight:600;color:#121212;">"Editar Factura"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal con <strong>todos los campos</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modifica y haz clic en <strong>"Guardar"</strong></span></div>
</div>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cambio automático</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">En edición inline, el cambio se guarda <strong>automáticamente</strong> al presionar Enter o hacer clic fuera del campo.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos editables</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Datos del cliente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Descripción de ítems</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Observaciones</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Campos según permisos</p>
</div>
</div>

</div>
</div>

---

### 3. Descargar Documentos

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ver PDF</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Busca columna <span style="font-weight:600;color:#121212;">"PDF"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Ver PDF"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre en <strong>nueva pestaña</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Descargar XML</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Busca columna <span style="font-weight:600;color:#121212;">"XML"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Ver XML"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Archivo se <strong>descarga automáticamente</strong></span></div>
</div>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">PDF</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Visualización en navegador</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Opción de imprimir</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Opción de guardar localmente</p>
</div>
</div>

<div style="background:#DBEAFE;border:1px solid #BFDBFE;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#1E40AF;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">XML</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#1E40AF;margin:0;line-height:1.5;">• Descarga directa</p>
<p style="font-size:12px;color:#1E40AF;margin:0;line-height:1.5;">• Formato para SUNAT</p>
<p style="font-size:12px;color:#1E40AF;margin:0;line-height:1.5;">• Almacenamiento en carpeta de descargas</p>
</div>
</div>

</div>
</div>

---

## Filtros y Búsqueda

### Filtro por Fechas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Aplicar filtro</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <span style="font-weight:600;color:#121212;">"Desde"</span> (fecha inicio)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <span style="font-weight:600;color:#121212;">"Hasta"</span> (fecha fin)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <strong>"Aplicar"</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Quitar filtro</p>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">→</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <strong>"Limpiar"</strong> para ver todas las facturas</span></div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplos de uso</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Facturas de <strong>enero 2024</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ventas de <strong>esta semana</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Documentos del <strong>último mes</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Período <strong>específico</strong> para reporte</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Combinable</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">El filtro de fechas se puede combinar con la búsqueda de texto para resultados más precisos.</p>
</div>

</div>
</div>

---

### Búsqueda Avanzada

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos de búsqueda</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">ID Venta</span> — Número de orden</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Nro. Documento</span> — RUC o DNI</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Cliente</span> — Nombre</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Email</span> — Correo</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cómo buscar</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona el <span style="font-weight:600;color:#121212;">campo</span> a buscar</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Escribe el <span style="font-weight:600;color:#121212;">término</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Tabla se <strong>actualiza automáticamente</strong></span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo práctico</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Búsqueda: "Cliente" = "Juan"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Resultado: Todas las facturas de clientes que contienen "Juan" en el nombre (Juan Pérez, Juanita García, etc.)</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Búsqueda parcial</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">El sistema busca coincidencias parciales. No necesitas escribir el nombre completo.</p>
</div>

</div>
</div>

---

## Estados y Badges

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Estado</th>
<th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Badge</th>
<th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Significado</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Aceptado</td><td style="padding:0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;">Aceptado</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Factura aceptada por SUNAT</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">En Proceso</td><td style="padding:0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#DBEAFE;border:1px solid #BFDBFE;color:#1E40AF;font-weight:600;">En Proceso</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Pendiente de respuesta SUNAT</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Anulado</td><td style="padding:0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;color:#991B1B;font-weight:600;">Anulado</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Factura anulada, no válida</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Monto Positivo</td><td style="padding:0.5rem;font-size:12px;color:#059669;font-weight:600;">S/. 100.00</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Venta normal</td></tr>
<tr><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Monto Negativo</td><td style="padding:0.5rem;font-size:12px;color:#dc2626;font-weight:600;">-S/. 50.00</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Devolución o nota de crédito</td></tr>
</tbody>
</table>

---

## Paginación

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Controles disponibles</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Anterior:</span> Página previa</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Siguiente:</span> Página siguiente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Número:</span> Ir a página específica</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Información mostrada</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;font-family:monospace;">"Mostrando 1-200 de 500"</p>
<p style="font-size:11px;color:#86868b;margin:0.25rem 0 0;">Primeras 200 de 500 facturas totales</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Registros por página</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Máximo:</strong> 200 facturas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Si hay más:</strong> Se activa paginación</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Orden:</strong> Fecha descendente (fijo)</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Orden fijo</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">El ordenamiento por fecha es <strong>inmutable</strong>. Las más recientes siempre aparecen primero para mantener consistencia en reportes.</p>
</div>

</div>
</div>

---

## Limitaciones y Restricciones

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Restricción</th>
<th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Detalle</th>
<th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Alternativa</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Eliminar facturas</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">No permitido</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-weight:500;color:#121212;">Anular</span> (solo 6 días)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Cambiar orden</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">No permitido (fijo por fecha)</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Usar <span style="font-weight:500;color:#121212;">filtros de fecha</span></td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Más de 200 por página</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">No permitido</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Usar <span style="font-weight:500;color:#121212;">paginación</span></td></tr>
<tr><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Exportar a Excel</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">No disponible directamente</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Descargar <span style="font-weight:500;color:#121212;">PDF/XML</span> individuales</td></tr>
</tbody>
</table>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para encontrar facturas rápido</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Usa el <strong>buscador</strong> (más rápido que páginas)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Filtra por <strong>fechas</strong> si conoces el período</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Combina</strong> filtros para precisión</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para revisar facturas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Clic en <strong>fila</strong> para detalle completo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verifica estado <strong>"Aceptado"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Descarga <strong>PDF</strong> para copia física</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para corregir errores</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Menor a 6 días:</strong> Anular factura</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Mayor a 6 días:</strong> Crear nota de crédito</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Error simple:</strong> Edición inline</p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Anulación: 6 días</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">La función <strong>"Anular Factura"</strong> solo está disponible dentro de los primeros <strong>6 días</strong> de la emisión. Después de ese plazo, usa nota de crédito.</p>
</div>

</div>
</div>

<alert type="warning">
  El ordenamiento por fecha es <strong>fijo e inmutable</strong> para mantener consistencia en reportes. No se puede eliminar facturas, solo <strong>anular</strong> (dentro de 6 días) o crear <strong>notas de crédito</strong>. La edición inline guarda cambios <strong>automáticamente</strong> al salir del campo.
</alert>