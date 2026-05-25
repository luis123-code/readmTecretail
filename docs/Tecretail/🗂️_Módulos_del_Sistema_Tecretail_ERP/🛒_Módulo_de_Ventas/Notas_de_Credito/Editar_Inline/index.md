<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Notas de Crédito · Edición Rápida</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Modificación directa de datos de notas de crédito en la tabla sin abrir modales. Permite edición rápida de campos específicos con guardado automático mediante Enter o clic fuera.</span>

<alert type="info">
  La edición inline funciona <strong>idénticamente</strong> a facturas y boletas. Es ideal para <strong>cambios rápidos y simples</strong>. Las celdas <strong>"Comprobante"</strong>, <strong>"Serie Relacionada"</strong> y <strong>"Correlativo Relacionado"</strong> <strong>no son editables</strong> (son referencias calculadas al documento original).
</alert>

---

## Cómo Funciona

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">1. Hacer clic en celda</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Busca la <span style="font-weight:600;color:#121212;">celda</span> a modificar en la tabla</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic <strong>directamente</strong> en la celda</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se convierte en <strong>campo de entrada</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos editables</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Tipo documento</span> (DNI, RUC)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Cliente</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Serie</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Correlativo</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Moneda</span> (PEN, USD)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Monto</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Motivo</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Estado</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Fecha</span></p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">2. Modificar valor</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Según <span style="font-weight:600;color:#121212;">tipo de campo</span>, modifica el valor</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Texto: <strong>Escribe</strong> directamente</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Número: <strong>Dígitos</strong> y punto decimal</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selección: <strong>Lista desplegable</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">05</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Fecha: <strong>Selector calendario</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">3. Guardar cambio</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">A</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Presiona <strong>Enter</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">B</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic <strong>fuera</strong> de la celda</span></div>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;">El cambio se guarda <strong>automáticamente</strong> en la base de datos.</p>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos NO editables</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• PDF, XML (enlaces)<br>• Comprobante (calculado)<br>• Serie Relacionada, Correlativo Relacionado (referencias)</p>
</div>

</div>
</div>

---

## Resultado del Guardado

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Éxito</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Mensaje: "Nota de crédito actualizada exitosamente"</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Celda muestra <strong>nuevo valor</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Cambio es <strong>inmediato</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Se guarda en <strong>base de datos</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Otros usuarios ven <strong>cambio actualizado</strong></p>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Error</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Mensaje: "Error al actualizar la nota de crédito"</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Celda <strong>vuelve al valor original</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Cambio se <strong>revierte automáticamente</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Verifica conexión e <strong>intenta nuevamente</strong></p>
</div>
</div>

</div>
</div>

---

## Ejemplos Prácticos

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Corregir nombre de cliente</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: Nombre mal escrito</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Clic en celda <strong>"Cliente"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Borra nombre incorrecto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Escribe nombre correcto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Enter</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">5. Nombre actualizado ✓</p>
</div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cambiar estado</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: "En Proceso" → "Completado"</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Clic en celda <strong>"Estado"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Se abre <strong>lista desplegable</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Selecciona <strong>"Completado"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. Clic fuera</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">5. Estado cambia a <span style="background:#22C55E;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Completado</span> ✓</p>
</div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Corregir monto</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: Monto incorrecto</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Clic en celda <strong>"Monto"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Borra monto incorrecto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Escribe <strong>150.00</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Enter</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">5. Monto actualizado ✓</p>
</div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cambiar fecha</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: Fecha de emisión incorrecta</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Clic en celda <strong>"Fecha"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Se abre <strong>calendario</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Navega y selecciona día</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. Clic fuera</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">5. Fecha actualizada ✓</p>
</div>
</div>
</div>

</div>
</div>

---

## Ventajas y Limitaciones

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ventajas</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#ffffff;border:1px solid #A7F3D0;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#065F46;margin:0 0 0.3rem;">Rapidez</p>
<p style="font-size:11px;color:#047857;margin:0;line-height:1.4;">No abres modales. Cambio directo. Guardado automático.</p>
</div>
<div style="background:#ffffff;border:1px solid #A7F3D0;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#065F46;margin:0 0 0.3rem;">Simplicidad</p>
<p style="font-size:11px;color:#047857;margin:0;line-height:1.4;">Clic y editas. Sin formularios complejos. Intuitivo.</p>
</div>
<div style="background:#ffffff;border:1px solid #A7F3D0;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#065F46;margin:0 0 0.3rem;">Eficiencia</p>
<p style="font-size:11px;color:#047857;margin:0;line-height:1.4;">Editas varias celdas seguidas. Ves resultado inmediato. Menos clics.</p>
</div>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Limitaciones</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#ffffff;border:1px solid #FECACA;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.3rem;">Una celda a la vez</p>
<p style="font-size:11px;color:#991B1B;margin:0;line-height:1.4;">Solo puedes editar una celda simultáneamente. Guarda antes de editar otra.</p>
</div>
<div style="background:#ffffff;border:1px solid #FECACA;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.3rem;">Sin deshacer manual</p>
<p style="font-size:11px;color:#991B1B;margin:0;line-height:1.4;">Una vez guardado, no hay botón deshacer. El sistema revierte automáticamente si hay error.</p>
</div>
<div style="background:#ffffff;border:1px solid #FECACA;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.3rem;">No para cambios complejos</p>
<p style="font-size:11px;color:#991B1B;margin:0;line-height:1.4;">Si necesitas modificar muchos campos o validar antes, usa edición desde modal.</p>
</div>
</div>
</div>

</div>
</div>

---

## Cuándo Usar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ideal para</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Correcciones simples:</strong> Errores de ortografía, números incorrectos, estados desactualizados</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Cambios rápidos:</strong> Actualizar estado de varias notas, corregir montos levemente</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Ediciones frecuentes:</strong> Muchos cambios pequeños, revisión y corrección de datos</p>
</div>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">No ideal para</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Cambios complejos:</strong> Modificar muchos campos, necesitar contexto completo, validar antes de guardar</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Cambios críticos:</strong> Afectan cálculos importantes, implicaciones fiscales, necesitan revisión previa</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Alternativa:</strong> Usa <strong>edición desde modal</strong> para mayor control</p>
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
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Solución</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Clic accidental en celda</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Haz clic fuera. No se guarda nada. Celda vuelve a estado original.</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Valor incorrecto guardado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic nuevamente en celda. Corrige valor. Enter. Se actualiza.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Sistema no guarda (error)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica conexión a internet. Intenta nuevamente. Contacta soporte si persiste.</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Editar celda</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en celda editable</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Se convierte en campo de entrada</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Modificar valor</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Escribir, seleccionar, o usar calendario</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Valor cambiado (no guardado aún)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Guardar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Enter o clic fuera</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Guardado automático en base de datos</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Cancelar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic fuera sin modificar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">No se guarda nada</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Error</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Sistema detecta error</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Revierte a valor original automáticamente</td></tr>
</tbody>
</table>

<alert type="warning">
  La edición inline es <strong>idéntica</strong> a la de facturas y boletas. Es perfecta para <strong>cambios rápidos y simples</strong>. Recuerda que <strong>no puedes editar</strong> celdas de referencia al documento original (Comprobante, Serie Relacionada, Correlativo Relacionado) porque son <strong>campos calculados</strong>. Para cambios <strong>complejos o críticos</strong>, usa la <strong>edición desde modal</strong> para tener más control.
</alert>