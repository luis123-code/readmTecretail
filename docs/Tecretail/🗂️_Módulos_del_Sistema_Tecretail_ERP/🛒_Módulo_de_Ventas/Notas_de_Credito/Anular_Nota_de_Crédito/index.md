<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Notas de Crédito · Anulación</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Proceso de cancelación definitiva de notas de crédito con envío fiscal a SUNAT. Acción irreversible que invalida la nota fiscalmente y actualiza el estado en el sistema.</span>

<alert type="warning">
  La anulación de notas de crédito es <strong>diferente</strong> a facturas/boletas: <strong>no tiene restricción de tiempo</strong> (se puede anular en cualquier momento) y envía la anulación <strong>directamente a SUNAT</strong>. Es un proceso fiscal oficial <strong>irreversible</strong>.
</alert>

---

## Diferencias con Anular Facturas/Boletas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Facturas/Boletas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Restricción de tiempo:</strong> Solo primeros 6 días</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Después de 6 días: <strong>no se puede anular</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Alternativa: Usar <strong>nota de crédito</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Anulación: <strong>interna</strong> al sistema</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Genera nota de crédito <strong>automáticamente</strong></p>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Notas de Crédito</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Sin restricción de tiempo:</strong> Anulable en cualquier momento</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Envío a <strong>SUNAT (API externa)</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Actualiza <strong>estado en base de datos</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Proceso fiscal <strong>oficial</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Irreversible</strong></p>
</div>
</div>

</div>
</div>

---

## Cómo Anular una Nota de Crédito

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Localiza la <span style="font-weight:600;color:#121212;">nota de crédito</span> en la tabla</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">menú (⋮)</span> al final de la fila</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>"Anular Nota de Crédito"</strong> (icono basura rojo)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <strong>modal de confirmación</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Búsqueda previa</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Usa el <strong>buscador</strong> o <strong>filtro de fechas</strong> para localizar la nota. Recuerda: <strong>no hay límite de tiempo</strong> para anular notas antiguas.</p>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Modal de confirmación</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;"><strong>Información mostrada:</strong></p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Serie y número de la nota</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Monto de la nota</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Cliente</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Motivo original</p>
<p style="font-size:12px;color:#92400E;margin:0.5rem 0 0;line-height:1.5;"><strong>Advertencia:</strong> "¿Estás seguro? Esta acción enviará la anulación a SUNAT. No se puede deshacer."</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opciones</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#6B6B6B;margin:0 0 0.3rem;">Cancelar</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Modal cierra. No se realiza acción. Nota permanece igual.</p>
</div>
<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.3rem;">Confirmar / Anular</p>
<p style="font-size:11px;color:#991B1B;margin:0;line-height:1.4;">Sistema procesa anulación. Envía a SUNAT. Actualiza estado.</p>
</div>
</div>
</div>

</div>
</div>

---

## Qué Pasa al Confirmar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">1. Envío a SUNAT</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">El sistema prepara <strong>payload de anulación</strong>:</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Token de autenticación</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Tipo documento: <strong>07</strong> (Nota de Crédito)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Serie y número</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Fecha de emisión</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Motivo de anulación</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;">Envía a <strong>API externa de SUNAT</strong> y espera respuesta.</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Si SUNAT acepta</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Recibe confirmación positiva. Continúa con actualización en base de datos.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">2. Actualización en BD</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Estado cambia a <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Anulado</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Badge se vuelve <strong>rojo</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Se guarda en base de datos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Nota ya <strong>no es válida</strong> fiscalmente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Se mantiene <strong>registro histórico</strong></p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Si hay error</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Mensaje: "Error al anular la nota de crédito"</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Modal <strong>permanece abierto</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Verifica conexión y <strong>reintenta</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Contacta soporte si persiste</p>
</div>

</div>
</div>

---

## Mensajes de Confirmación

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Éxito</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• "Nota de crédito anulada exitosamente en el sistema externo"</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• "Estado de la nota de crédito actualizado a anulado"</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Modal se <strong>cierra</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Tabla se <strong>actualiza</strong> (badge rojo)</p>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Error de SUNAT</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• SUNAT puede <strong>rechazar</strong> la anulación</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Causas: Nota ya procesada, datos no coinciden, problema fiscal</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Verifica estado en portal SUNAT</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Contacta soporte si no puedes resolver</p>
</div>
</div>

</div>
</div>

---

## Impacto Después de Anular

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estado de la nota</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cambia a <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Anulado</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Badge <strong>rojo</strong> en tabla</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Sigue <strong>visible</strong> en tabla (registro histórico)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ya <strong>no es válida</strong> para fines fiscales</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Documento original</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• La <strong>factura o boleta original</strong> mantiene su estado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Sigue siendo <strong>válida</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• La <strong>referencia</strong> a la nota permanece</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• La nota anulada <strong>no afecta</strong> los montos</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Monto neto</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;margin-bottom:0.5rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Ejemplo:</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0.25rem 0 0;line-height:1.5;">Factura: <strong>S/. 1000</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Nota: <strong>S/. 200</strong> (anulada)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Neto: <strong>S/. 1000</strong> (la nota anulada no resta)</p>
</div>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">El sistema <strong>recalcula</strong> automáticamente.</p>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Historial</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Queda <strong>registro de la anulación</strong> útil para auditorías y trazabilidad de qué notas se anularon.</p>
</div>

</div>
</div>

---

## Cuándo Usar Anular

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ideal para</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Errores en la nota:</strong> Emitida por error, duplicado</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Correcciones mayores:</strong> Nota original incorrecta, anular y crear nueva</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Cancelaciones:</strong> Cliente canceló devolución, ya no aplica corrección</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Revertir:</strong> Necesitas deshacer la nota completamente</p>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">No ideal para</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Correcciones parciales:</strong> Solo ajustar el monto → Usa <strong>edición</strong></p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Cambios simples:</strong> Error menor → Usa <strong>edición inline o modal</strong></p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Anular vs Crear Nueva</p>
<table style="width:100%;border-collapse:collapse;font-size:11px;">
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.2rem 0;color:#6B6B6B;">Plazo de tiempo</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Sin límite</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Sin límite</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.2rem 0;color:#6B6B6B;">Tipo de acción</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Cancela nota</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Crea nueva corrección</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.2rem 0;color:#6B6B6B;">Estado nota</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Cambia a Anulado</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Permanece igual</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.2rem 0;color:#6B6B6B;">Envío SUNAT</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Sí (anulación)</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Sí (nueva nota)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.2rem 0;color:#6B6B6B;">Reversibilidad</td><td style="padding:0.2rem 0;color:#991B1B;font-weight:500;">No reversible</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Se puede crear otra</td></tr>
<tr><td style="padding:0.2rem 0;color:#6B6B6B;">Uso recomendado</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Errores en nota</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Correcciones adicionales</td></tr>
</table>
</div>

</div>
</div>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Antes de anular</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Verifica la nota:</strong> Confirma que sea la correcta</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Revisa el motivo:</strong> Asegúrate que realmente necesites anular</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Verifica documento original:</strong> Confirma la relación</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Ten documentación:</strong> Guarda respaldos de por qué anulas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">5. <strong>Comunícate con cliente:</strong> Infórmale sobre la anulación</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Al confirmar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Sé <strong>rápido:</strong> La anulación debe procesarse rápidamente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verifica la <strong>respuesta:</strong> Confirma que SUNAT aceptó</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Documenta el proceso:</strong> Guarda registro de la anulación</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Después de anular</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Verifica el estado:</strong> Confirme que esté "Anulado"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Revisa documento original:</strong> Que no se vea afectado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Actualiza reportes:</strong> Confirma montos correctos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Archiva:</strong> Guarda registro de la anulación</p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Si anulaste por error</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>No se puede deshacer</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Debes <strong>crear una nueva nota</strong> si es necesario</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Documenta el error para <strong>auditorías</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Contacta a <strong>soporte</strong> si es crítico</p>
</div>

</div>
</div>

---

## Solución de Problemas

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Error</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Causa</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Solución</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">"Error al anular"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Problema conexión SUNAT, error payload, SUNAT rechaza</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica internet. Reintenta. Verifica datos nota sean correctos. Contacta soporte si persiste.</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">SUNAT rechaza</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Nota ya procesada, datos no coinciden, problema fiscal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica estado en portal SUNAT. Corrige datos si necesario. Contacta soporte.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">No se puede deshacer</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Anulación es irreversible por diseño</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Crea nueva nota si necesitas. Documenta error. Contacta soporte si es crítico.</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Abrir anulación</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Menú → Anular Nota de Crédito</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Modal de confirmación con datos</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Revisar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verificar información en modal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Confirmar nota correcta</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Confirmar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botón "Confirmar" / "Anular"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Envía anulación a SUNAT</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Esperar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Sistema procesa</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">SUNAT acepta o rechaza</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver resultado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Mensaje de éxito/error</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Estado actualizado o error mostrado</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver estado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Badge en tabla</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;"><span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Anulado</span> (nota invalidada)</td></tr>
</tbody>
</table>

<alert type="warning">
  La anulación de notas de crédito es <strong>diferente</strong> a facturas/boletas: <strong>sin restricción de tiempo</strong> y envío <strong>directo a SUNAT</strong>. Es un proceso fiscal oficial e <strong>irreversible</strong>. Una vez anulada, no puede reactivarse. Si necesitas corregir, considera: <strong>anular y crear nueva</strong> (si error es grave) o <strong>editar</strong> (si cambio es menor). Siempre verifica que <strong>SUNAT acepte</strong> la anulación antes de considerar el proceso completo.
</alert>