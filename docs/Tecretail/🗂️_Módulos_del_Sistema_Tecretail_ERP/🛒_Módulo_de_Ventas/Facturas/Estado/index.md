<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Facturas · Estados Fiscales</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Indicadores visuales del estado de validación de facturas ante SUNAT, determinando validez fiscal y operativa de cada documento emitido.</span>

<alert type="info">
  Los estados son <strong>críticos para fines fiscales</strong>. Solo envía facturas al cliente cuando estén <span style="color:#065F46;font-weight:600;">Aceptadas</span>. Los estados se actualizan automáticamente por respuesta de SUNAT, con opción de corrección manual si hay discrepancias.
</alert>

---

## Estados Disponibles

<div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:1rem;margin:1.25rem 0;">
<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#22C55E;color:#FFFFFF;font-weight:600;">Aceptado</span>
</div>
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Válido</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">SUNAT validó la factura. Documento fiscalmente válido para envío al cliente y registro contable.</p>
</div>

<div style="background:#DBEAFE;border:1px solid #BFDBFE;border-radius:0.75rem;padding:1rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#3B82F6;color:#FFFFFF;font-weight:600;">En Proceso</span>
</div>
<p style="font-size:11px;font-weight:600;color:#1E40AF;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Pendiente</p>
<p style="font-size:12px;color:#1E40AF;margin:0;line-height:1.5;">Factura enviada a SUNAT, en espera de respuesta. No enviar al cliente hasta cambio de estado.</p>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<div style="display:flex;align-items:center;gap:0.5rem;margin-bottom:0.75rem;">
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#EF4444;color:#FFFFFF;font-weight:600;">Anulado</span>
</div>
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Inválido</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">Factura cancelada. No válida fiscalmente. Enviar nota de crédito generada automáticamente.</p>
</div>
</div>

---

## Visualización

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">En tabla</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Columna "Estado" con badge coloreado. Colores: <span style="color:#22C55E;font-weight:600;">● Verde</span>, <span style="color:#3B82F6;font-weight:600;">● Azul</span>, <span style="color:#EF4444;font-weight:600;">● Rojo</span>.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">En detalle</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Modal muestra badge, fecha de estado y descripción. Sección de información claramente identificada.</p>
</div>

</div>
<div>

<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;box-shadow:0 1px 3px rgba(0,0,0,0.05);">
<div style="display:flex;justify-content:space-between;align-items:center;">
<span style="font-size:12px;color:#6B6B6B;">F001-0001234</span>
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#22C55E;color:#FFFFFF;font-weight:600;">Aceptado</span>
</div>
</div>

<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;box-shadow:0 1px 3px rgba(0,0,0,0.05);">
<div style="display:flex;justify-content:space-between;align-items:center;">
<span style="font-size:12px;color:#6B6B6B;">F001-0001235</span>
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#3B82F6;color:#FFFFFF;font-weight:600;">En Proceso</span>
</div>
</div>

<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;box-shadow:0 1px 3px rgba(0,0,0,0.05);">
<div style="display:flex;justify-content:space-between;align-items:center;">
<span style="font-size:12px;color:#6B6B6B;">F001-0001236</span>
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#EF4444;color:#FFFFFF;font-weight:600;">Anulado</span>
</div>
</div>

</div>
</div>

---

## Actualización de Estados

### Automática

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Flujo normal</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:center;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#3B82F6;color:#FFFFFF;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Emisión: <span style="color:#3B82F6;font-weight:600;">En Proceso</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:center;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">→</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">SUNAT procesa (minutos-horas)</span></div>
<div style="display:flex;gap:0.75rem;align-items:center;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#22C55E;color:#FFFFFF;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Respuesta: <span style="color:#22C55E;font-weight:600;">Aceptado</span></span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Por anulación</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:center;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#22C55E;color:#FFFFFF;flex-shrink:0;">●</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Factura <span style="color:#22C55E;font-weight:600;">Aceptado</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:center;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">→</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Función "Anular Factura"</span></div>
<div style="display:flex;gap:0.75rem;align-items:center;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#EF4444;color:#FFFFFF;flex-shrink:0;">●</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Cambia a <span style="color:#EF4444;font-weight:600;">Anulado</span> automático</span></div>
</div>
</div>

</div>
</div>

---

### Manual (corrección)

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Método</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Proceso</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Uso</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Edición inline</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en celda "Estado" → Seleccionar nuevo estado → Enter</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Cambio rápido individual</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Edición modal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Menú → Editar Factura → Cambiar estado → Guardar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Corrección con revisión completa</td></tr>
</tbody>
</table>

---

## Impacto por Estado

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">✓ Aceptado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><strong>Envío:</strong> PDF válido para cliente</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><strong>Contabilidad:</strong> Cuenta como venta</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><strong>Cobranza:</strong> Debe pagar</p>
</div>
</div>

<div style="background:#DBEAFE;border:1px solid #BFDBFE;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#1E40AF;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">⏳ En Proceso</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#1E40AF;margin:0;line-height:1.5;"><strong>Envío:</strong> Esperar validación SUNAT</p>
<p style="font-size:12px;color:#1E40AF;margin:0;line-height:1.5;"><strong>Contabilidad:</strong> Pendiente de confirmación</p>
<p style="font-size:12px;color:#1E40AF;margin:0;line-height:1.5;"><strong>Cobranza:</strong> Generalmente no se cobra aún</p>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">✗ Anulado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Envío:</strong> NO enviar, usar nota de crédito</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Contabilidad:</strong> NO cuenta, se resta</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Cobranza:</strong> NO debe pagar, devolver si pagó</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Acciones recomendadas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="color:#22C55E;font-weight:600;">●</span> Enviar PDF, archivar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="color:#3B82F6;font-weight:600;">●</span> Esperar, verificar después</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="color:#EF4444;font-weight:600;">●</span> Enviar nota de crédito</p>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Siempre "En Proceso"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">SUNAT no respondió, error de sincronización</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Esperar, verificar conexión, contactar soporte si persiste. Cambiar manualmente si tienes confirmación SUNAT.</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Estado incorrecto</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Error de sistema, cambio manual previo</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verificar estado real con SUNAT. Corregir manualmente vía edición inline o modal si es necesario.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">No puedo cambiar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Sin permisos, factura bloqueada</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verificar permisos de usuario. Intentar desde modal. Contactar soporte si persiste.</td></tr>
</tbody>
</table>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Verificación</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Revisa regularmente</strong> estados de facturas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Actúa rápido</strong> si "En Proceso" dura horas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Documenta cambios</strong> manuales (razón)</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Mantenimiento</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Esperar respuesta SUNAT antes de manual</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Confirmar con SUNAT antes de corregir</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Usar función "Anular" en lugar de cambiar estado</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Auditoría</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Mantener historial de cambios de estado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Documentar razones de correcciones manuales</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verificar consistencia con registros SUNAT</p>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Importante</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">Solo envía facturas al cliente cuando estén <span style="color:#22C55E;font-weight:600;">Aceptadas</span>. Las <span style="color:#3B82F6;font-weight:600;">En Proceso</span> pueden tener rechazo posterior.</p>
</div>

</div>
</div>

<alert type="warning">
  Los estados son <strong>críticos para cumplimiento fiscal</strong>. Verifica siempre antes de enviar al cliente. Si hay discrepancias entre sistema y SUNAT, corrige manualmente con <strong>confirmación oficial</strong>. No cambies estados sin respaldo de SUNAT.
</alert>