<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Facturas · Edición Completa</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Formulario completo en modal para modificar múltiples campos de factura simultáneamente, con revisión previa y confirmación explícita de cambios.</span>

<alert type="info">
  Modal con todos los campos de factura precargados. Ideal para <strong>cambios complejos</strong> que afectan múltiples datos. Revisa antes de guardar. Los cambios son inmediatos tras confirmar.
</alert>

---

## Acceder al Modal

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Ubica la <span style="font-weight:600;color:#121212;">factura</span> en la tabla</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">menú (...)</span> al final de la fila</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>"Editar Factura"</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Resultado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Modal grande con <strong>todos los campos</strong> de la factura precargados con datos actuales, organizados en secciones claras.</p>
</div>

</div>
<div>

<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;box-shadow:0 1px 3px rgba(0,0,0,0.05);">
<div style="display:flex;align-items:center;gap:0.75rem;margin-bottom:0.75rem;">
<svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M2 12H4" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M20 12H22" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M12 2V4" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M12 20V22" stroke="#6B6B6B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
<span style="font-size:13px;font-weight:600;color:#121212;">Modal de Edición</span>
</div>
<p style="font-size:11px;color:#86868b;margin:0 0 0.5rem;">Editar Factura · F001-0001234</p>
<div style="height:1px;background:#E5E5E5;margin:0.5rem 0;"></div>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Formulario completo con campos organizados en secciones: Cliente, Factura, Detalle.</p>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estructura</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Encabezado:</strong> Título y número de factura</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Cuerpo:</strong> Formulario con todos los campos</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Pie:</strong> Botones Cancelar y Guardar</p>
</div>
</div>

</div>
</div>

---

## Campos Editables

### Datos del Cliente y Factura

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cliente</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Tipo documento (RUC, DNI, etc.)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Número documento</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Nombre / Razón social</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Email</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Dirección</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Factura</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Moneda (PEN/USD)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Monto total</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Serie (F001, B001)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Número correlativo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Descripción</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Estado (badge)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Fecha emisión</p>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">No editables</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• ID interno de factura</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Enlaces PDF/XML (generados auto)</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Campos técnicos del sistema</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Tipos de campo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Texto:</strong> Edición libre</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Número:</strong> Solo dígitos y punto decimal</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Selector:</strong> Lista desplegable</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Fecha:</strong> Calendario desplegable</p>
</div>
</div>

</div>
</div>

---

## Guardar o Cancelar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Guardar cambios</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modifica los <span style="font-weight:600;color:#121212;">campos necesarios</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Guardar"</span> (botón primario)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Botón muestra <strong>"Guardando..."</strong> mientras procesa</span></div>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Éxito</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><strong>Mensaje:</strong> "Factura actualizada exitosamente"</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><strong>Modal:</strong> Cierra automáticamente</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><strong>Tabla:</strong> Se actualiza inmediatamente</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cancelar</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Cancelar"</span> (botón secundario)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal se <strong>cierra</strong> sin guardar</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Tabla permanece <strong>sin cambios</strong></span></div>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Error</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Mensaje:</strong> "Error al actualizar la factura"</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Modal:</strong> Permanece abierto con valores ingresados</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Acción:</strong> Corrige y reintenta</p>
</div>
</div>

</div>
</div>

---

## VS Edición Inline

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Aspecto</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Edición Inline</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Edición Modal</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Campos visibles</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Uno a la vez</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Todos simultáneamente</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Velocidad</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Rápida</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Moderada</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Control</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Limitado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Total (revisión previa)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Contexto</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Celda individual</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Factura completa</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ideal para</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Cambios simples</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Cambios complejos/críticos</td></tr>
</tbody>
</table>

---

## Cuándo Usar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">✓ Usar Modal</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Cambios en <strong>múltiples campos</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Modificaciones <strong>críticas</strong> (montos, datos fiscales)</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Correcciones que requieren <strong>contexto completo</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Cambios con <strong>implicaciones en reportes</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Auditorías</strong> y revisiones formales</p>
</div>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">✗ Usar Inline</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Correcciones <strong>puntuales</strong> de un solo campo</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Cambios <strong>simples</strong> y rápidos</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Actualizaciones <strong>frecuentes</strong> menores</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplos Modal</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cambiar moneda + monto + fecha</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Corregir nombre + dirección + email</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Actualizar estado + descripción</p>
</div>
</div>

</div>
</div>

<alert type="warning">
  Usa el modal para cambios que requieren <strong>revisión previa</strong> o afectan múltiples datos. La edición inline es más eficiente para correcciones <strong>puntuales simples</strong>. Los cambios en el modal son <strong>inmediatos y permanentes</strong> tras guardar.
</alert>