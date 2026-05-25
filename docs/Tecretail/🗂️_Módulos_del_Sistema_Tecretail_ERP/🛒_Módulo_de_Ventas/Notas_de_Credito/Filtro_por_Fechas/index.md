<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Notas de Crédito · Filtrado Temporal</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Herramienta de filtrado por rango de fechas para visualizar notas de crédito emitidas en períodos específicos, compatible con combinación de búsqueda y reinicio automático de paginación.</span>

<alert type="info">
  El filtro por fechas funciona <strong>idénticamente</strong> a los módulos de facturas y boletas. Selecciona al menos una fecha (<strong>Desde</strong> o <strong>Hasta</strong>) para filtrar. El botón <strong>"Limpiar"</strong> solo aparece cuando hay filtro activo.
</alert>

---

## Ubicación del Filtro

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Posición</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Arriba de la tabla de notas de crédito, a la <strong>izquierda</strong> del título "Gestión de Notas de Crédito". Recuadro blanco con controles de fecha.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Elementos</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Icono calendario</span> (indicador visual)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Desde:</span> Campo fecha inicial</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Hasta:</span> Campo fecha final</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Aplicar:</span> Botón negro</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Limpiar:</span> Botón X (cuando hay filtro)</p>
</div>
</div>

</div>
<div>

<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;box-shadow:0 1px 3px rgba(0,0,0,0.05);">
<div style="display:flex;align-items:center;gap:0.75rem;margin-bottom:0.75rem;">
<svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><rect x="3" y="4" width="18" height="18" rx="2" stroke="#6B6B6B" stroke-width="1.5"/><path d="M16 2V6" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round"/><path d="M8 2V6" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round"/><path d="M3 10H21" stroke="#6B6B6B" stroke-width="1.5"/></svg>
<span style="font-size:12px;font-weight:600;color:#6B6B6B;">Filtrar por Fechas</span>
</div>
<div style="display:flex;gap:0.5rem;margin-bottom:0.75rem;">
<div style="flex:1;background:#F9FAFB;border:1px solid #E5E7EB;border-radius:0.375rem;padding:0.5rem;">
<p style="font-size:10px;color:#6B7280;margin:0 0 0.25rem;">Desde</p>
<p style="font-size:12px;color:#374151;margin:0;">01/01/2024</p>
</div>
<div style="flex:1;background:#F9FAFB;border:1px solid #E5E7EB;border-radius:0.375rem;padding:0.5rem;">
<p style="font-size:10px;color:#6B7280;margin:0 0 0.25rem;">Hasta</p>
<p style="font-size:12px;color:#374151;margin:0;">31/01/2024</p>
</div>
</div>
<div style="display:flex;gap:0.5rem;">
<button style="background:#121212;color:#fff;padding:0.4rem 1rem;border-radius:0.375rem;font-size:12px;border:none;flex:1;">Aplicar</button>
<button style="background:#fff;color:#6B6B6B;padding:0.4rem 0.75rem;border-radius:0.375rem;font-size:12px;border:1px solid #E5E5E5;">✕</button>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Comportamiento</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Al aplicar el filtro, la <strong>paginación se reinicia</strong> a página 1 y el total de registros se actualiza al conteo del rango filtrado.</p>
</div>

</div>
</div>

---

## Cómo Usar el Filtro

### 1. Seleccionar Fecha "Desde"

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en campo <span style="font-weight:600;color:#121212;">"Desde"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <span style="font-weight:600;color:#121212;">calendario</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Navega a <span style="font-weight:600;color:#121212;">mes y año</span> deseados</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en el <strong>día</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">05</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Campo se <strong>completa automáticamente</strong></span></div>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Significado</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">Fecha <strong>inicial</strong> del rango. Muestra notas de crédito <strong>desde</strong> esta fecha en adelante (inclusive).</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Seleccionas <strong>01/01/2024</strong> en "Desde"</p>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;">Resultado: Sistema muestra todas las notas de crédito emitidas desde el 1 de enero de 2024 en adelante.</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Solo "Desde" (sin "Hasta")</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Muestra notas desde esa fecha <strong>hasta hoy</strong>. Útil para ver notas recientes desde un punto específico.</p>
</div>

</div>
</div>

---

### 2. Seleccionar Fecha "Hasta"

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en campo <span style="font-weight:600;color:#121212;">"Hasta"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <span style="font-weight:600;color:#121212;">calendario</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Navega a <span style="font-weight:600;color:#121212;">mes y año</span> deseados</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en el <strong>día</strong></span></div>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Significado</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">Fecha <strong>final</strong> del rango. Muestra notas de crédito <strong>hasta</strong> esta fecha (inclusive).</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Seleccionas <strong>31/01/2024</strong> en "Hasta"</p>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;">Resultado: Sistema muestra todas las notas de crédito emitidas hasta el 31 de enero de 2024 (desde el inicio de registros).</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Solo "Hasta" (sin "Desde")</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Muestra notas desde el <strong>inicio de registros</strong> hasta esa fecha. Útil para ver notas antiguas hasta un punto específico.</p>
</div>

</div>
</div>

---

### 3. Aplicar y Limpiar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Aplicar filtro</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona al menos <span style="font-weight:600;color:#121212;">una fecha</span> (Desde o Hasta)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <strong>"Aplicar"</strong> (botón negro)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Botón muestra <strong>indicador de carga</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Tabla se <strong>actualiza</strong> con resultados</span></div>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Resultado del filtrado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Tabla muestra solo notas del rango</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Total de registros se <strong>recalcula</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Paginación <strong>reinicia</strong> a página 1</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Limpiar filtro</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Limpiar"</span> (botón X)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Campos de fecha se <strong>vacían</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Vuelven <strong>todas las notas</strong> sin filtro</span></div>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Error común</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">Si intentas aplicar sin seleccionar ninguna fecha: <strong>"Selecciona al menos una fecha para filtrar"</strong>.</p>
</div>

</div>
</div>

---

## Combinaciones de Filtro

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Modo</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Configuración</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Resultado</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Rango completo</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Desde + Hasta</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Notas entre ambas fechas (inclusive)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Desde fecha</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Solo "Desde"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Notas desde esa fecha hasta hoy</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Hasta fecha</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Solo "Hasta"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Notas desde inicio hasta esa fecha</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Sin fechas</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Ambos vacíos</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Error: requiere al menos una fecha</td></tr>
</tbody>
</table>

---

## Ejemplos Prácticos

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Notas de este mes</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Enero 2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Desde:</strong> 01/01/2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Hasta:</strong> 31/01/2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Resultado:</strong> Solo notas de enero</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Notas de esta semana</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Últimos 7 días</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Desde:</strong> [Hace 7 días]</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Hasta:</strong> Hoy</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Resultado:</strong> Notas de la semana</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Notas de año completo</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">2023</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Desde:</strong> 01/01/2023</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Hasta:</strong> 31/12/2023</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Resultado:</strong> Todas las notas de 2023</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Notas recientes</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Desde mitad de mes</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Desde:</strong> 15/[mes actual]</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Hasta:</strong> [vacío - hasta hoy]</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Resultado:</strong> Notas desde el 15 en adelante</p>
</div>
</div>

</div>
</div>

---

## Integración con Otros Filtros

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Con buscador</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Si el filtro de fecha está <strong>activo</strong>, el buscador busca <strong>dentro</strong> de las notas filtradas por fecha.</p>
<p style="font-size:12px;color:#047857;margin:0.5rem 0 0;line-height:1.5;"><strong>Ejemplo:</strong> Filtro enero + buscar "Juan" = Notas de enero de clientes "Juan".</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Sin filtro de fecha</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Al limpiar, el buscador opera sobre <strong>todas</strong> las notas de crédito del sistema.</p>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Impacto en paginación</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">Al aplicar filtro, la paginación <strong>siempre reinicia</strong> a página 1. El total de registros muestra el conteo del rango filtrado (ej: de 500 totales a 50 filtradas).</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Uso recomendado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Reportes mensuales:</strong> Rango mes completo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Auditorías:</strong> Período específico a auditar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Conciliación:</strong> Rango de fechas contables</p>
</div>
</div>

</div>
</div>

---

## Solución de Problemas

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Problema</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Causa</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Solución</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">"Selecciona al menos una fecha"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Intentaste aplicar sin fechas</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Selecciona Desde o Hasta (o ambas)</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Sin resultados</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">No hay notas en el rango seleccionado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica fechas, amplía rango, o limpia filtro</td></tr>
</tbody>
</table>

---

## Resumen

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Acción</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Cómo</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Resultado</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Filtrar rango</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Desde + Hasta + Aplicar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Notas entre fechas</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Filtrar desde</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Solo Desde + Aplicar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Notas desde fecha hasta hoy</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Filtrar hasta</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Solo Hasta + Aplicar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Notas desde inicio hasta fecha</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Limpiar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botón Limpiar (X)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Quita filtro, muestra todo</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Combinar con búsqueda</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Filtro fecha + buscador</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Búsqueda dentro del rango</td></tr>
</tbody>
</table>

<alert type="warning">
  El filtro por fechas es <strong>idéntico</strong> al de facturas y boletas. Requiere <strong>al menos una fecha</strong> para funcionar. Al aplicar, la <strong>paginación reinicia</strong> y el total de registros se actualiza. Combínalo con el <strong>buscador</strong> para filtrar por contenido dentro de un período específico.
</alert>
```