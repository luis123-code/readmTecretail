<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Cuentas por Cobrar · Gestión de Estado</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Función para modificar manualmente el estado de una cuenta (Pendiente, Cobrado Parcial, Cobrado Total, Vencido). Útil cuando el cálculo automático no refleja la situación real o se necesita actualización manual inmediata.</span>

<alert type="warning">
  El cambio de estado <strong>afecta métricas</strong> de clientes y vendedores, así como <strong>cálculos generales</strong>. Solo cambia el estado cuando el cálculo automático no refleja la realidad o cuando necesitas corregir un error. Si el cálculo automático es correcto, <strong>no es necesario</strong> cambiar manualmente.
</alert>

---

## Cómo Cambiar el Estado

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Localiza la <strong>cuenta</strong> en la tabla (usa filtros si es necesario)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz <strong>clic</strong> en el <strong>badge de estado CxC</strong> de la fila</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <strong>modal de confirmación</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>nuevo estado</strong> de la lista desplegable</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">05</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <strong>"Confirmar"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">06</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal cierra + tabla se <strong>actualiza</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Información del modal</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Cuenta seleccionada:</strong> Identificador de la cuenta</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Estado actual:</strong> Estado previo al cambio</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Nuevo estado:</strong> Lista desplegable con opciones</p>
</div>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ubicación</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Columna <strong>"Estado CxC"</strong> de la tabla</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Badge</strong> clickeable con estado actual</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Botones del modal</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Confirmar</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Guarda el cambio. Sistema actualiza estado y cierra modal.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Cancelar</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Cierra modal sin guardar. El estado permanece igual.</p>
</div>
</div>
</div>

</div>
</div>

---

## Estados Disponibles

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Pendiente</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Badge:</strong> <span style="background:#6B6B6B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Pendiente</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Significado:</strong> La cuenta no tiene pagos registrados. Está pendiente de cobro.</p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Usar cuando:</strong> cuenta recién creada, aún no cobrada, sin pagos.</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cobrado Parcial</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Badge:</strong> <span style="background:#F59E0B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Parcial</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Significado:</strong> Tiene pagos parciales. Falta pagar el resto.</p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Usar cuando:</strong> cliente pagó una parte, faltan pagos adicionales.</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cobrado Total</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Badge:</strong> <span style="background:#22C55E;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Total</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Significado:</strong> Cuenta pagada completamente. No hay saldo pendiente.</p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Usar cuando:</strong> cliente pagó todo el monto, sin saldo por cobrar.</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Vencido</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Badge:</strong> <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Vencido</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Significado:</strong> Fecha de vencimiento pasó. Cliente no pagó a tiempo.</p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Usar cuando:</strong> fecha de vencimiento expiró, cuenta no pagada.</p>
</div>
</div>

</div>
</div>

---

## Ejemplos de Situaciones

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 1: Marcar como Cobrado Total</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Situación:</strong> Cliente pagó todo el monto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Clic en estado actual (ej: <span style="background:#6B6B6B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Pendiente</span>)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Selecciona <span style="background:#22C55E;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Total</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Confirmar → Estado cambia a verde</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 2: Marcar como Cobrado Parcial</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Situación:</strong> Cliente pagó una parte</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Clic en estado actual (ej: <span style="background:#6B6B6B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Pendiente</span>)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Selecciona <span style="background:#F59E0B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Parcial</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Confirmar → Estado cambia a amarillo</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 3: Marcar como Vencido</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Situación:</strong> Fecha de vencimiento pasó, no pagó</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Clic en estado actual (ej: <span style="background:#6B6B6B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Pendiente</span>)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Selecciona <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Vencido</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Confirmar → Estado cambia a rojo</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 4: Corregir estado incorrecto</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Situación:</strong> Marcado como vencido pero ya pagó</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Clic en estado actual (<span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Vencido</span>)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Selecciona <span style="background:#22C55E;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Total</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Confirmar → Estado corregido</p>
</div>
</div>

</div>
</div>

---

## ¿Cuándo Cambiar Manualmente?

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cálculo automático incorrecto</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Hubo un <strong>error</strong> en el registro de pagos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cálculo automático no refleja la <strong>realidad</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Necesitas <strong>corregir</strong> el estado manualmente</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Correcciones</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Hubo un <strong>error</strong> en el estado asignado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Estado fue asignado <strong>incorrectamente</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Necesitas <strong>corregir</strong> el error</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Actualización rápida</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cliente pagó y necesitas <strong>reflejar</strong> inmediatamente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• No quieres esperar el <strong>cálculo automático</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Necesitas <strong>reflejar el cambio</strong> ya</p>
</div>
</div>

</div>
</div>

---

## Impacto del Cambio

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Qué cambia</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Badge de estado:</strong> Cambia de color y texto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Métricas:</strong> Se recalculan en tiempo real</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Paneles laterales:</strong> Métricas de clientes/vendedores se actualizan</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Cantidad de cuentas:</strong> Por estado cambia</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Qué NO cambia</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Montos:</strong> Total, pagado, por cobrar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Fechas:</strong> Emisión, vencimiento</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Datos de cuenta:</strong> Código, concepto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Clientes/vendedores:</strong> Nombres, datos</p>
</div>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Efecto en reportes</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Los <strong>reportes</strong> que dependen del estado mostrarán datos diferentes</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• El <strong>dashboard</strong> de CxC se actualiza</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Las <strong>métricas de cobranza</strong> cambian según nuevo estado</p>
</div>
</div>

</div>
</div>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Antes de cambiar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Verifica</strong> estado actual (¿es incorrecto?)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Revisa</strong> los pagos (¿son correctos?)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Verifica</strong> fechas (¿son correctas?)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Considera</strong> impacto en métricas</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Al cambiar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Selecciona</strong> estado correcto (apropiado)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Confirma</strong> (revisa antes de aceptar)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Verifica</strong> resultado (¿se aplicó?)</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Después de cambiar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Verifica</strong> consistencia (¿todo coherente?)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Revisa</strong> métricas (¿cálculos correctos?)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Documenta</strong> (¿por qué cambiaste?)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Comunica</strong> (infórmalo al equipo)</p>
</div>
</div>

</div>
</div>

---

## Comparativa: Manual vs Automático

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cálculo automático</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Cómo:</strong> Basado en pagos registrados y fechas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Ventajas:</strong> Sin intervención, siempre actualizado, menos errores</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Desventajas:</strong> Puede no reflejar situaciones especiales, depende de pagos correctos</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cambio manual</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Cómo:</strong> Tú seleccionas el estado directamente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Ventajas:</strong> Corrige errores, refleja situaciones especiales, control total</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Desventajas:</strong> Requiere intervención, posibles errores humanos, necesita verificación</p>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">El estado no cambia</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">No confirmaste en modal, error al guardar, modal cerró sin confirmar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Asegúrate de hacer clic en <strong>"Confirmar"</strong>. Verifica que el modal se cierre correctamente. Si hay error, reintenta.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Estado incorrecto</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Seleccionaste estado equivocado, no revisaste antes de confirmar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Vuelve a abrir el modal. Selecciona el <strong>estado correcto</strong>. Confirma el cambio.</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Abrir modal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en badge estado CxC</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Modal de confirmación</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver estado actual</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Revisar en modal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Estado previo al cambio</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Seleccionar nuevo estado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Lista desplegable</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Nuevo estado seleccionado</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Confirmar cambio</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botón "Confirmar"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Estado actualizado, tabla recalcula</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Cancelar cambio</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botón "Cancelar"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Modal cierra, no guarda nada</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver resultado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Badge cambia color</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Nuevo estado visible en tabla</td></tr>
</tbody>
</table>

<alert type="warning">
  Cambiar el estado requiere <strong>confirmación</strong>. Siempre verifica que el estado seleccionado sea el <strong>correcto</strong> antes de confirmar. El cambio <strong>afecta métricas</strong> de clientes y vendedores. Si el cálculo automático es correcto, <strong>no necesitas</strong> cambiar manualmente. Si necesitas criterios diferentes de cálculo automático, usa la <strong>"Lógica Alternativa de Estado"</strong> en lugar de cambiar manualmente cada cuenta.
</alert>