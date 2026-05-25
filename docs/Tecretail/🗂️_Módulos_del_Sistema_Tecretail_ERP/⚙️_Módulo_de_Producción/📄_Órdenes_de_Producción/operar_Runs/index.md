<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Producción · Operar Runs</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Gestiona el ciclo de vida de cada run de producción de una orden directamente, sin salir del módulo de Órdenes.</span>

---

## Cómo abrirlo

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin:1.25rem 0;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">Haz clic en los <span style="font-weight:600;color:#121212;">tres puntos ⋯</span> de la orden → selecciona <span style="font-weight:600;color:#121212;">Operar Runs</span>.</p>
</div>

---

## Qué muestra

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>
<p style="font-size:13px;color:#6B6B6B;line-height:1.7;margin-bottom:1rem;">Al abrir, aparece la lista de todos los runs asociados a la orden, cada uno con su nombre, etapa y estado actual.</p>
<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.75rem;">Estados disponibles</p>
<div style="display:flex;flex-direction:column;gap:0.4rem;">
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;flex-shrink:0;">En Cola</span><span style="font-size:12px;color:#6B6B6B;">El run está esperando para iniciar</span></div>
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#DBEAFE;border:1px solid #BFDBFE;color:#1E40AF;font-weight:600;flex-shrink:0;">En Proceso</span><span style="font-size:12px;color:#6B6B6B;">El run está siendo ejecutado</span></div>
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;flex-shrink:0;">Terminado</span><span style="font-size:12px;color:#6B6B6B;">El run concluyó correctamente</span></div>
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;color:#991B1B;font-weight:600;flex-shrink:0;">En Problema</span><span style="font-size:12px;color:#6B6B6B;">El run tiene una incidencia</span></div>
</div>
</div>
</div>
<div>
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778658479/image_v4zv31.png" alt="Lista de runs de la orden" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
</div>
</div>

---

## Acciones disponibles por run

### Iniciar un Run

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">• El run debe estar en estado <span style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#F3F4F6;padding:0.1rem 0.3rem;border-radius:3px;border:1px solid #E5E7EB;color:#6B7280;">En Cola</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">• Si el run ya tiene <span style="font-weight:500;color:#121212;">materiales asignados</span> → cambia directamente a <span style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#DBEAFE;padding:0.1rem 0.3rem;border-radius:3px;border:1px solid #BFDBFE;color:#1E40AF;">En Proceso</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">• Si <span style="font-weight:500;color:#121212;">no tiene materiales</span> → el sistema despliega un formulario para asignarlos antes de iniciar</p>
</div>

### Asignar Materiales e Iniciar

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.75rem;">Cuando un run no tiene materiales asignados</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Busca y selecciona el <span style="font-weight:500;color:#121212;">material</span> de la receta</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Elige el <span style="font-weight:500;color:#121212;">inventario</span> (almacén) del que se extrae</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Ingresa la <span style="font-weight:500;color:#121212;">cantidad a extraer</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#065F46;">Asignar y Arrancar</span></span></div>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.6;">✅ El sistema automáticamente <span style="font-weight:600;">descuenta el stock</span>, registra el movimiento en el Kardex y cambia el run a <span style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#DBEAFE;padding:0.1rem 0.3rem;border-radius:3px;border:1px solid #BFDBFE;color:#1E40AF;">En Proceso</span>.</p>
</div>

### Terminar un Run

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin:1.25rem 0;">
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;line-height:1.6;">• El run debe estar en estado <span style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#DBEAFE;padding:0.1rem 0.3rem;border-radius:3px;border:1px solid #BFDBFE;color:#1E40AF;">En Proceso</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;line-height:1.6;">• Ingresa la <span style="font-weight:500;color:#121212;">cantidad producida</span> <span style="color:#249F65;font-size:10px;">obligatorio</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;line-height:1.6;">• Ingresa el <span style="font-weight:500;color:#121212;">scrap</span> o merma <span style="font-size:11px;color:#9CA3AF;">(opcional)</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">• Haz clic en <span style="font-weight:600;color:#121212;">Terminar Run</span></p>
</div>

<div style="background:#EDE9FE;border:1px solid #DDD6FE;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#4C1D95;margin:0;line-height:1.6;">✅ El sistema automáticamente <span style="font-weight:600;">ingresa el producto fabricado</span> al inventario, calcula el <span style="font-weight:600;">costo unitario</span> según los materiales usados y registra el movimiento de entrada en el Kardex.</p>
</div>

---

## Qué hace el sistema al terminar un run

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin:1.25rem 0;">
<div style="display:grid;grid-template-columns:1fr 1fr;gap:0.75rem;">
<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;margin:0 0 0.3rem;">📦 Actualiza inventario de salida</p>
<p style="font-size:11px;color:#7F1D1D;margin:0;line-height:1.4;">Descuenta los materiales usados</p>
</div>
<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;margin:0 0 0.3rem;">📥 Actualiza inventario de entrada</p>
<p style="font-size:11px;color:#047857;margin:0;line-height:1.4;">Agrega el producto fabricado con la cantidad producida</p>
</div>
<div style="background:#DBEAFE;border:1px solid #BFDBFE;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#1E40AF;margin:0 0 0.3rem;">🧮 Calcula costo unitario</p>
<p style="font-size:11px;color:#1E40AF;margin:0;line-height:1.4;">Basado en costo total de materiales ÷ lo producido</p>
</div>
<div style="background:#EDE9FE;border:1px solid #DDD6FE;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#5B21B6;margin:0 0 0.3rem;">📝 Registra en Kardex</p>
<p style="font-size:11px;color:#4C1D95;margin:0;line-height:1.4;">Crea movimiento de entrada del producto final</p>
</div>
</div>
<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.5rem;padding:0.75rem;margin-top:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;margin:0 0 0.3rem;">🔄 Cambia estado del run</p>
<p style="font-size:11px;color:#92400E;margin:0;line-height:1.4;">De <span style="font-family:'JetBrains Mono',monospace;font-size:10px;">En Proceso</span> a <span style="font-family:'JetBrains Mono',monospace;font-size:10px;">Terminado</span></p>
</div>
</div>

<div style="display:flex;flex-direction:column;gap:0.75rem;margin-top:1.25rem;">
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778658496/image_mmnlav.png" alt="Formulario asignar materiales" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778658532/image_dh6wyb.png" alt="Run en proceso" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778658575/image_dakfve.png" alt="Formulario terminar run" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
</div>