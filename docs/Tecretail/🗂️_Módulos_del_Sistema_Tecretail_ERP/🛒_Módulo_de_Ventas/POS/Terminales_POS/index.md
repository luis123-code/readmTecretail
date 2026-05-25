<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Terminales POS · Puntos de Venta</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Gestión de terminales físicos y virtuales asociados a tiendas, con configuración individual, acceso directo a interfaz de ventas y visualización en cuadrícula responsive.</span>

<alert type="info">
  Cada terminal pertenece a <strong>una sola tienda</strong> de forma permanente. La relación no se puede modificar. Una tienda puede tener <strong>múltiples terminales</strong> con diferentes modos de operación.
</alert>

---

## Información del Terminal

### Campos Principales

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.4rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Campo</th>
<th style="text-align:left;padding:0.4rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Tipo</th>
<th style="text-align:left;padding:0.4rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Descripción</th>
<th style="text-align:left;padding:0.4rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Obligatorio</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;">Nombre</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Texto</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Identificador del terminal</td><td style="padding:0.3rem 0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;">Sí</span></td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;">Email</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Texto</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Correo asociado</td><td style="padding:0.3rem 0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;">No</span></td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;">Clave POS</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Texto</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Clave de acceso</td><td style="padding:0.3rem 0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;">No</span></td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;">IP</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Texto</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Dirección IP</td><td style="padding:0.3rem 0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;">No</span></td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;">Puerto</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Texto</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Puerto conexión</td><td style="padding:0.3rem 0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;">No</span></td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;">Modo</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Número</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">0=Normal, 1=Fácil</td><td style="padding:0.3rem 0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;">Sí</span></td></tr>
<tr><td style="padding:0.3rem 0.5rem;font-size:13px;font-weight:500;color:#121212;">Tienda</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">Número</td><td style="padding:0.3rem 0.5rem;font-size:13px;color:#6B6B6B;">ID tienda asociada</td><td style="padding:0.3rem 0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;">Sí</span></td></tr>
</tbody>
</table>

---

## Visualización en Tarjetas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;margin:1.25rem 0;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:1rem;padding:1rem;box-shadow:0 1px 3px rgba(0,0,0,0.05);">
<div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:0.75rem;">
<div style="display:flex;align-items:center;gap:0.75rem;">
<div style="width:40px;height:40px;border-radius:50%;background:#F5F5F5;display:flex;align-items:center;justify-content:center;">
<svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M4.8 21.6H19.2C20.19 21.6 21 20.79 21 19.8V4.8C21 3.81 20.19 3 19.2 3H9L3 9V19.8C3 20.79 3.81 21.6 4.8 21.6Z" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3V9H3" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
</div>
<span style="font-size:15px;font-weight:600;color:#1d1d1f;">Caja Principal</span>
</div>
<span style="font-size:10px;font-weight:600;padding:0.2rem 0.5rem;border-radius:4px;background:#E5E5E5;border:1px solid #D4D4D4;color:#374151;text-transform:uppercase;letter-spacing:0.05em;">Normal</span>
</div>
<p style="font-size:13px;color:#86868b;margin:0 0 1rem;">IP: 192.168.1.100</p>
<div style="height:1px;background:#E5E5E5;margin:0 -1rem 1rem;"></div>
<div style="display:flex;justify-content:center;">
<div style="padding:0.5rem 1rem;border:1px solid #E5E5E5;border-radius:0.5rem;background:#FFFFFF;display:flex;align-items:center;gap:0.5rem;cursor:pointer;">
<span style="font-size:12px;color:#6B6B6B;">Acceder al POS</span>
<svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M7 17L17 7" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 7H17V17" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
</div>
</div>
</div>

<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:1rem;padding:1rem;box-shadow:0 1px 3px rgba(0,0,0,0.05);">
<div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:0.75rem;">
<div style="display:flex;align-items:center;gap:0.75rem;">
<div style="width:40px;height:40px;border-radius:50%;background:#F5F5F5;display:flex;align-items:center;justify-content:center;">
<svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M4.8 21.6H19.2C20.19 21.6 21 20.79 21 19.8V4.8C21 3.81 20.19 3 19.2 3H9L3 9V19.8C3 20.79 3.81 21.6 4.8 21.6Z" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3V9H3" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
</div>
<span style="font-size:15px;font-weight:600;color:#1d1d1f;">Caja Express</span>
</div>
<span style="font-size:10px;font-weight:600;padding:0.2rem 0.5rem;border-radius:4px;background:#DBEAFE;border:1px solid #BFDBFE;color:#1E40AF;text-transform:uppercase;letter-spacing:0.05em;">Fácil</span>
</div>
<p style="font-size:13px;color:#86868b;margin:0 0 1rem;">IP: No asignada</p>
<div style="height:1px;background:#E5E5E5;margin:0 -1rem 1rem;"></div>
<div style="display:flex;justify-content:center;">
<div style="padding:0.5rem 1rem;border:1px solid #E5E5E5;border-radius:0.5rem;background:#FFFFFF;display:flex;align-items:center;gap:0.5rem;cursor:pointer;">
<span style="font-size:12px;color:#6B6B6B;">Acceder al POS</span>
<svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M7 17L17 7" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 7H17V17" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
</div>
</div>
</div>
</div>

---

## Diseño Responsive

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Layout de cuadrícula</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Pequeño (sm):</span> 1 columna</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Mediano (lg):</span> 2 columnas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Grande (xl):</span> 3 columnas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Extra grande:</span> 4 columnas</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Espaciado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Gap tarjetas:</span> 16px (gap-4)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Padding:</span> 16px (p-4)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Borde:</span> Gris claro</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Radio:</span> 1rem</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Efectos hover</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Sombra: <span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">hover:shadow-md</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Borde: <span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">hover:border-primary/50</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Transición: <span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">transition-all</span></p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Menú de acciones</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Ubicación:</strong> Esquina superior derecha</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Icono:</strong> Tres puntos (MoreHorizontal)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Tamaño:</strong> 24px (h-6 w-6)</p>
</div>
</div>

</div>
</div>

---

## Acciones Disponibles

### Editar Terminal

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cómo acceder</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">menú (...)</span> del terminal</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Seleccionar <span style="font-weight:600;color:#121212;">"Editar POS"</span></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos editables</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Nombre</span> — Identificador</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Email</span> — Correo asociado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Clave POS</span> — Clave acceso</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">IP</span> — Dirección IP</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Puerto</span> — Puerto conexión</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Modo</span> — EasyMode (0/1)</p>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">No modificable</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Tienda asignada</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">La relación tienda-POS es permanente. No se puede cambiar al editar.</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Resultado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Mensaje: "POS actualizado correctamente"</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Listado se actualiza automáticamente</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Badge de modo se actualiza visualmente</p>
</div>
</div>

</div>
</div>

---

### Acceso Directo al POS

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cómo acceder</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Identifica el <span style="font-weight:600;color:#121212;">botón de acceso</span> en la tarjeta</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en el <span style="font-weight:600;color:#121212;">icono de enlace</span></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">URL construida</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;font-family:monospace;font-size:11px;color:#6B6B6B;line-height:1.6;">
{posUrl}?id={terminal.POS_id}
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;">Ejemplo: https://pos.tecretail.org?id=123</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Comportamiento</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Abre en <strong>nueva pestaña</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">target="_blank"</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">rel="noopener noreferrer"</span></p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Resultado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Interfaz POS carga con ID del terminal</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Operación independiente del sistema</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Modo de operación aplicado automáticamente</p>
</div>
</div>

</div>
</div>

---

## Relación con Tiendas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Asociación</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cada terminal: <strong>una sola tienda</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Una tienda: <strong>múltiples terminales</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Relación establecida al <strong>crear</strong> el POS</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Campo <span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Tiend</span> = array[ID]</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Filtrado automático</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Terminales agrupados por tienda</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Filtro por <span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Tiendas_id</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Solo visibles los de la tienda actual</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Conteo en tienda</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Se muestra en <strong>detalle de tienda</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cálculo: filtrar por ID de tienda</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Actualización automática</p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Permanente</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">La relación tienda-POS <strong>no se puede cambiar</strong> después de la creación. Es permanente.</p>
</div>

</div>
</div>

---

## Estados del Terminal

<table style="width:100%;border-collapse:collapse;">
<thead><tr style="border-bottom:1px solid #E5E5E5;"><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Estado</th><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Visual</th><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Significado</th></tr></thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Modo Normal</td><td style="padding:0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#E5E5E5;border:1px solid #D4D4D4;color:#374151;font-weight:600;">Normal</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Interfaz completa (EasyMode=0)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Modo Fácil</td><td style="padding:0.5rem;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#DBEAFE;border:1px solid #BFDBFE;color:#1E40AF;font-weight:600;">Fácil</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Interfaz simplificada (EasyMode=1)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">IP Asignada</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">IP: 192.168.x.x</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Configuración de red completa</td></tr>
<tr><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">IP No Asignada</td><td style="padding:0.5rem;font-size:12px;color:#9CA3AF;">No asignada</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Falta configuración de red</td></tr>
</tbody>
</table>

<alert type="warning">
  La <strong>relación tienda-POS es permanente</strong> y no se puede modificar. El <strong>acceso directo</strong> abre el POS en nueva pestaña con ID del terminal. La <strong>cuadrícula es responsive</strong> adaptándose al tamaño de pantalla. No hay <strong>función de eliminar</strong> terminal en la interfaz actual.
</alert>