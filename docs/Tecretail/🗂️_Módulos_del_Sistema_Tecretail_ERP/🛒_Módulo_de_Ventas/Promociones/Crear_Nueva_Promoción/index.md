
<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Promociones · Creación</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Formulario de creación de promociones con soporte para descuentos porcentuales, montos fijos y comisiones asociadas a vendedores. Configuración de fechas de vigencia y estado activo/inactivo.</span>

<alert type="warning">
  Si eliges tipo <strong>"Comisionado"</strong>, debes completar obligatoriamente los campos <strong>"Nombre"</strong> y <strong>"Usuario"</strong>. El nombre sirve como <strong>clave en localStorage</strong> y el usuario se guarda en el navegador para asociar la promoción al vendedor.
</alert>

---

## Cómo Iniciar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Localiza botón <strong>"+ Nueva Promoción"</strong> (arriba a la derecha)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz <strong>clic</strong> en el botón verde</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <strong>modal</strong> con el formulario</span></div>
</div>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ubicación</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Arriba a la <strong>derecha</strong> de la página</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Botón <strong>verde</strong> con icono <strong>(+)</strong></p>
</div>

</div>
</div>

---

## Completar el Formulario

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Datos básicos</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Nombre</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Identificador de la promoción. <strong>Obligatorio si es Comisionado</strong> (sirve como clave en localStorage).</p>
<p style="font-size:11px;color:#86868b;margin:0.2rem 0 0;line-height:1.4;">Ej: "Descuento de Verano", "Oferta Black Friday"</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Descripción</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;"><strong>Opcional</strong> pero recomendado. Explica qué incluye el descuento.</p>
<p style="font-size:11px;color:#86868b;margin:0.2rem 0 0;line-height:1.4;">Ej: "10% de descuento en toda la orden"</p>
</div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Tipo de promoción</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Selecciona de lista desplegable:</p>
</div>
<div style="display:flex;flex-direction:column;gap:0.3rem;margin-top:0.5rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="background:#3B82F6;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Porcentual</span> Descuento % (10%, 20%)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="background:#8B5CF6;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Numérico</span> Monto fijo (S/. 50, S/. 100)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="background:#F59E0B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Comisionado</span> Asociado a vendedor</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Fechas de vigencia</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Fecha de Inicio</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Clic en campo → se abre calendario → selecciona día. La promoción estará activa desde esta fecha.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Fecha de Fin</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Clic en campo → calendario → selecciona día. Debe ser <strong>posterior</strong> a fecha inicio.</p>
<p style="font-size:11px;color:#86868b;margin:0.2rem 0 0;line-height:1.4;">Si no seleccionas, la promoción no tiene fin.</p>
</div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campo especial: Usuario</p>
<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">Solo aparece cuando seleccionas tipo <strong>"Comisionado"</strong>.</p>
<p style="font-size:12px;color:#92400E;margin:0.25rem 0 0;line-height:1.5;"><strong>Obligatorio.</strong> Nombre o código del vendedor. Se guarda en localStorage.</p>
<p style="font-size:11px;color:#92400E;margin:0.25rem 0 0;line-height:1.4;">Ej: "juan.perez", "vendedor01"</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Valor y Estado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Valor:</strong> Según tipo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0 1rem;line-height:1.5;">- Porcentual: 10, 20 (sin %)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0 1rem;line-height:1.5;">- Numérico: 50, 100 (puede usar decimales)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0 1rem;line-height:1.5;">- Comisionado: según configuración</p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Estado:</strong> <span style="background:#22C55E;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Vigente</span> (por defecto) o <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Vencido</span></p>
</div>
</div>

</div>
</div>

---

## Guardar o Cancelar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Guardar promoción</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Revisa <strong>todos los campos</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <strong>"Guardar Promoción"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Botón muestra <strong>"Guardando..."</strong></span></div>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Éxito:</strong> "¡Promoción guardada exitosamente!" → Modal cierra → Aparece en listado → Si es comisionado, se guarda en localStorage.</p>
<p style="font-size:11px;color:#86868b;margin:0.25rem 0 0;line-height:1.4;"><strong>Error:</strong> "Error al guardar la promoción" → Modal permanece abierto → Corrige y reintenta.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cancelar</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <strong>"Cancelar"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal se <strong>cierra</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Ningún cambio se <strong>guarda</strong></span></div>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;">Usar cuando: no quieres crear la promoción, detectas error antes de guardar, o quieres empezar de nuevo.</p>
</div>

</div>
</div>

---

## Ejemplos Prácticos

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 1: Descuento porcentual</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: 20% de descuento para verano</p>
<div style="display:flex;flex-direction:column;gap:0.2rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Nombre:</strong> "Descuento de Verano"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Descripción:</strong> "20% de descuento en toda la orden"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Fecha Inicio:</strong> 1 de enero 2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Fecha Fin:</strong> 31 de marzo 2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Tipo:</strong> Porcentual</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Valor:</strong> 20</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Estado:</strong> Vigente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>→ Guardar</strong></p>
</div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 2: Descuento numérico</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: S/. 50 en productos seleccionados</p>
<div style="display:flex;flex-direction:column;gap:0.2rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Nombre:</strong> "Oferta Especial"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Descripción:</strong> "S/. 50 de descuento en productos seleccionados"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Fecha Inicio:</strong> 1 de febrero 2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Fecha Fin:</strong> 28 de febrero 2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Tipo:</strong> Numérico</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Valor:</strong> 50</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Estado:</strong> Vigente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>→ Guardar</strong></p>
</div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 3: Promoción comisionada</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;font-weight:600;">Situación: Comisión para vendedor Juan Pérez</p>
<div style="display:flex;flex-direction:column;gap:0.2rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Nombre:</strong> "Comisión Juan Pérez" <span style="color:#EF4444;">*</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Descripción:</strong> "Comisión del vendedor Juan Pérez"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Fecha Inicio:</strong> 1 de enero 2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Fecha Fin:</strong> 31 de diciembre 2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Tipo:</strong> Comisionado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Usuario:</strong> juan.perez <span style="color:#EF4444;">*</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Valor:</strong> 10 (porcentaje comisión)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Estado:</strong> Vigente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>→ Guardar</strong></p>
</div>
<p style="font-size:11px;color:#EF4444;margin:0.5rem 0 0;line-height:1.4;"><span style="color:#EF4444;">*</span> Obligatorio para comisionado</p>
</div>
</div>

</div>
</div>

---

## Validaciones del Sistema

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para tipo Comisionado</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#ffffff;border:1px solid #FECACA;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.3rem;">Nombre obligatorio</p>
<p style="font-size:11px;color:#991B1B;margin:0;line-height:1.4;">Mensaje: "En comisionado, indica también el nombre de la promoción (sirve de clave en localStorage)"</p>
<p style="font-size:11px;color:#991B1B;margin:0.2rem 0 0;line-height:1.4;">No puedes guardar sin nombre.</p>
</div>
<div style="background:#ffffff;border:1px solid #FECACA;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.3rem;">Usuario obligatorio</p>
<p style="font-size:11px;color:#991B1B;margin:0;line-height:1.4;">Mensaje: "En comisionado, indica el usuario (userName) para guardarlo en el navegador"</p>
<p style="font-size:11px;color:#991B1B;margin:0.2rem 0 0;line-height:1.4;">No puedes guardar sin usuario.</p>
</div>
</div>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">¿Por qué son obligatorios?</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• El <strong>nombre</strong> sirve como <strong>clave en localStorage</strong></p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• El <strong>usuario</strong> se guarda en el navegador</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Necesario para <strong>asociar</strong> la promoción al vendedor</p>
</div>
</div>

</div>
</div>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Antes de crear</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Define el tipo:</strong> ¿Porcentual, Numérico o Comisionado?</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Calcula el valor:</strong> Asegúrate que el descuento sea correcto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Define las fechas:</strong> Establece el período de vigencia</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Escribe nombre claro:</strong> Fácil de identificar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">5. <strong>Agrega descripción:</strong> Para detalles adicionales</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Al completar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Usa nombres <strong>descriptivos:</strong> "Descuento de Verano" mejor que "Promo1"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Sé <strong>específico</strong> en descripción: "10% en toda la orden" mejor que "Descuento"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verifica <strong>fechas:</strong> Fecha fin debe ser posterior a inicio</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Selecciona <strong>tipo correcto:</strong> No confundas porcentual con numérico</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Para comisionado: Completa <strong>nombre y usuario</strong> obligatoriamente</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Después de crear</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Verifica en el listado:</strong> Confirma que aparezca</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Revisa los datos:</strong> Abre el detalle para verificar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Verifica el estado:</strong> Debe estar "Vigente"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Prueba en venta:</strong> Asegúrate que funcione correctamente</p>
</div>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">"En comisionado, indica también el nombre"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Tipo Comisionado sin completar campo Nombre</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Completa el campo "Nombre". Reintenta guardar.</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">"En comisionado, indica el usuario"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Tipo Comisionado sin completar campo Usuario</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Completa el campo "Usuario". Reintenta guardar.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">"Error al guardar la promoción"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Problema de conexión, error servidor, datos inválidos</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica internet. Revisa todos los campos. Reintenta. Contacta soporte si persiste.</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Iniciar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botón "+ Nueva Promoción"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Abre formulario en modal</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Completar nombre</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Campo "Nombre" (obligatorio si comisionado)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Identificador de la promoción</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Completar descripción</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Campo "Descripción" (opcional)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Detalles de la promoción</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Seleccionar fechas</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Selector calendario (Inicio/Fin)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Período de vigencia definido</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Seleccionar tipo</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Lista desplegable</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Porcentual / Numérico / Comisionado</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Completar usuario</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Campo "Usuario" (solo si comisionado)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Vendedor asociado (guardado en localStorage)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Completar valor</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Campo numérico</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Monto o porcentaje del descuento</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Seleccionar estado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Lista desplegable</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Vigente (por defecto) / Vencido</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Guardar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botón "Guardar Promoción"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Promoción creada y aparece en listado</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Cancelar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botón "Cancelar"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">No se crea nada, modal cierra</td></tr>
</tbody>
</table>

<alert type="warning">
  Al crear una promoción, presta especial atención al <strong>tipo</strong> que seleccionas. Si eliges <strong>"Comisionado"</strong>, debes completar obligatoriamente <strong>"Nombre"</strong> y <strong>"Usuario"</strong>. El nombre sirve como <strong>clave en localStorage</strong> y el usuario se guarda en el <strong>navegador</strong>. Las <strong>fechas de inicio y fin</strong> controlan la vigencia, pero el estado puede requerir <strong>actualización manual</strong>. Siempre verifica los datos después de crear para asegurarte que todo esté correcto.
</alert>
```