<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Notas de Crédito · Edición Completa</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Formulario completo de edición en modal dedicado para modificar múltiples campos simultáneamente con revisión previa y confirmación explícita de cambios.</span>

<alert type="info">
  La edición desde modal es <strong>idéntica</strong> a la de facturas y boletas. Es ideal para <strong>cambios complejos o críticos</strong> donde necesitas ver el contexto completo. Recuerda que <strong>Serie Relacionada</strong> y <strong>Correlativo Relacionado</strong> <strong>no son editables</strong> (son vínculos automáticos al documento original).
</alert>

---

## Cómo Abrir el Modal de Edición

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Localiza la <span style="font-weight:600;color:#121212;">nota de crédito</span> en la tabla</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">menú (⋮)</span> al final de la fila</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>"Editar Nota de Crédito"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <strong>modal de edición</strong> con todos los campos</span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Búsqueda previa</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Usa el <strong>buscador</strong> o <strong>filtro de fechas</strong> para localizar la nota antes de editar.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estructura del modal</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong style="color:#121212;">Encabezado:</strong> Título "Editar Nota de Crédito" + número + botón X</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong style="color:#121212;">Cuerpo:</strong> Formulario con todos los campos organizados en secciones</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong style="color:#121212;">Pie:</strong> Botón "Cancelar" (secundario) + "Guardar" (primario)</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Datos precargados</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Todos los campos del formulario ya contienen los <strong>datos actuales</strong> de la nota. Puedes modificar los que necesites.</p>
</div>

</div>
</div>

---

## Campos del Formulario

### Datos Editables

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Datos del cliente</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Tipo de documento</span> (DNI, RUC, etc.)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Número de documento</span> (DNI/RUC)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Nombre del cliente</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Email</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Dirección</span></p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Datos de la nota</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Moneda</span> (PEN, USD)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Monto</span> de la nota</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Serie</span> (BC01, FC01)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Número</span> correlativo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Motivo</span> (razón de corrección)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Estado</span> (Completado, En Proceso, Anulado)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Fecha</span> de emisión</p>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos NO editables</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>ID de la nota</strong> (identificador interno)</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Enlaces PDF/XML</strong> (generados automáticamente)</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Serie Relacionada</strong> (referencia al doc. original)</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Correlativo Relacionado</strong> (referencia al doc. original)</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Datos técnicos</strong> (campos internos del sistema)</p>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Importante</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">Los campos de <strong>referencia al documento original</strong> no se pueden editar porque la vinculación es <strong>permanente</strong>. Si hay error en el documento relacionado, contacta a soporte.</p>
</div>

</div>
</div>

---

## Cómo Usar el Modal

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Modificar campos</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Texto (cliente, motivo)</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Clic en campo → borra si es necesario → escribe nuevo valor → cualquier texto</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Número (monto, correlativo)</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Clic en campo → borra si es necesario → escribe número → punto decimal para centavos</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Selección (tipo doc, moneda, estado)</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Clic en campo → se abre lista → selecciona opción → lista se cierra automáticamente</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Fecha</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Clic en campo → se abre calendario → navega y selecciona día → fecha se llena</p>
</div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Guardar cambios</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modifica los <span style="font-weight:600;color:#121212;">campos necesarios</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <strong>"Guardar"</strong> (primario)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Botón muestra <strong>"Guardando..."</strong></span></div>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Éxito</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Mensaje: "Nota de crédito actualizada exitosamente"</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Modal se <strong>cierra automáticamente</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Tabla se <strong>actualiza</strong> con nuevos datos</p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Error</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Mensaje: "Error al actualizar la nota de crédito"</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Modal <strong>permanece abierto</strong></p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• Corrige y <strong>vuelve a intentar</strong></p>
</div>
</div>

</div>
</div>

---

## Cancelar vs Guardar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cancelar</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <strong>"Cancelar"</strong> (secundario)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal se <strong>cierra</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Ningún cambio se <strong>guarda</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Tabla <strong>permanece igual</strong></span></div>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;">Usar cuando: no quieres hacer cambios, detectas error antes de guardar, o quieres empezar de nuevo.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ventaja: Confirmación explícita</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">A diferencia de la edición inline, aquí tienes que hacer clic deliberadamente en <strong>"Guardar"</strong>. Esto reduce el riesgo de cambios accidentales y te permite <strong>revisar todo antes de confirmar</strong>.</p>
</div>

</div>
</div>

---

## Ventajas de Edición desde Modal

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Control completo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Ves <strong>todos los campos</strong> a la vez</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Puedes <strong>revisar antes de guardar</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Más <strong>contexto</strong> de la nota</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Menos propenso a <strong>errores</strong> por clics accidentales</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Visibilidad</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Toda la información en <strong>un solo lugar</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Puedes <strong>comparar valores</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Identificas <strong>inconsistencias</strong> fácilmente</p>
</div>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Seguridad</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Confirmación <strong>explícita</strong> con "Guardar"</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Puedes <strong>cancelar</strong> si cambias de opinión</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Menos riesgo de cambios <strong>accidentales</strong></p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Revisión</strong> antes de confirmar</p>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ideal para</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Cambios que afectan <strong>múltiples campos</strong></p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Correcciones importantes</strong></p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Modificaciones que requieren <strong>validación</strong></p>
</div>
</div>

</div>
</div>

---

## Cuándo Usar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ideal para (usa modal)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Cambios complejos:</strong> Múltiples campos relacionados</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Cambios críticos:</strong> Afectan montos importantes</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Correcciones importantes:</strong> Errores en datos del cliente</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Implicaciones fiscales:</strong> Necesitan revisión</p>
</div>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">No ideal para (usa inline)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Cambios simples:</strong> Solo un campo menor</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Cambios rápidos:</strong> No necesitas contexto completo</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Ediciones frecuentes:</strong> Correcciones menores</p>
</div>
</div>

</div>
</div>

---

## Ejemplos Prácticos

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 1: Datos completos del cliente</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: Cliente cambió nombre y dirección</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Menú → <strong>"Editar Nota de Crédito"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Modifica <strong>nombre</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Modifica <strong>dirección</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. Modifica <strong>email</strong> si aplica</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">5. <strong>Guardar</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">6. Todos los cambios <strong>juntos</strong> ✓</p>
</div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 2: Cambiar moneda y monto</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: Soles → Dólares</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Menú → <strong>"Editar Nota de Crédito"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Cambia <strong>moneda</strong> PEN → USD</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Actualiza <strong>monto</strong> con tipo de cambio</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Revisa</strong> ambos campos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">5. <strong>Guardar</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">6. Nota actualizada ✓</p>
</div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 3: Fecha y estado</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: Fecha incorrecta + estado desactualizado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Menú → <strong>"Editar Nota de Crédito"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Corrige <strong>fecha</strong> de emisión</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Cambia <strong>estado</strong> En Proceso → Completado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Revisa</strong> ambos cambios</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">5. <strong>Guardar</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">6. Ambos cambios <strong>juntos</strong> ✓</p>
</div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Diferencias con edición inline</p>
<table style="width:100%;border-collapse:collapse;font-size:11px;">
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.2rem 0;color:#6B6B6B;">Campos visibles</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Uno vs Todos</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.2rem 0;color:#6B6B6B;">Contexto</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Limitado vs Completo</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.2rem 0;color:#6B6B6B;">Velocidad</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Más rápido vs Más lento</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.2rem 0;color:#6B6B6B;">Control</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Menos vs Más</td></tr>
<tr><td style="padding:0.2rem 0;color:#6B6B6B;">Riesgo error</td><td style="padding:0.2rem 0;color:#121212;font-weight:500;">Mayor vs Menor</td></tr>
</table>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Campo obligatorio vacío</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Falta completar campo requerido</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Completa el campo. Intenta guardar nuevamente.</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Valor inválido</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Tipo de dato incorrecto (ej: letras en numérico)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Corrige el valor al tipo correcto. Reintenta.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">No se pudo guardar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Problema de conexión o servidor</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica internet. Reintenta. Contacta soporte si persiste.</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Abrir modal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Menú → Editar Nota de Crédito</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Modal con todos los campos precargados</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Modificar campos</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en campo → editar valor</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Valor modificado (pendiente de guardar)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Revisar cambios</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Ver todos los campos antes de guardar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Contexto completo para validación</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Guardar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botón "Guardar" (primario)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Todos los cambios guardados, modal cierra</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Cancelar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botón "Cancelar" (secundario)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Ningún cambio guardado, modal cierra</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Error</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Sistema detecta error</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Modal permanece abierto, corrige y reintenta</td></tr>
</tbody>
</table>

<alert type="warning">
  La edición desde modal es <strong>idéntica</strong> a la de facturas y boletas. Es ideal para <strong>cambios complejos o críticos</strong> donde necesitas ver el contexto completo y revisar antes de guardar. Para cambios <strong>simples y rápidos</strong>, usa la <strong>edición inline</strong>. Los campos <strong>Serie Relacionada</strong> y <strong>Correlativo Relacionado</strong> <strong>no son editables</strong> (vínculos permanentes al documento original).
</alert>