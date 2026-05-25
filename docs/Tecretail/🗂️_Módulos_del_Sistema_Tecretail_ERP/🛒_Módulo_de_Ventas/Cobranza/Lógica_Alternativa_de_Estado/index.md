<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Cuentas por Cobrar · Configuración Avanzada</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Switch configurable para alternar entre dos formas de calcular el estado de cuentas por cobrar. Permite adaptar el sistema a criterios de negocio específicos sin modificar los datos subyacentes.</span>

<alert type="warning">
  <strong>Funcionalidad avanzada.</strong> Por defecto usa la <strong>lógica estándar</strong>. Solo activa la alternativa si tienes <strong>criterios especiales de negocio</strong> que la estándar no cubre. Los montos y fechas no cambian, solo la <strong>interpretación del estado</strong>.
</alert>

---

## Ubicación del Switch

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ubicación visual</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Arriba de la <strong>tabla de cuentas</strong> por cobrar</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Cerca de los <strong>filtros</strong> de la tabla</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Interruptor con etiqueta <strong>"Lógica Alternativa de Estado"</strong></span></div>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;">Por defecto está <strong>desactivado</strong> (apagado). Al activarse, el switch se ilumina/enciende.</p>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Acción rápida</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Haz <strong>clic</strong> en el interruptor para alternar entre:</p>
<p style="font-size:12px;color:#047857;margin:0.5rem 0 0;line-height:1.5;">• <strong>Apagado:</strong> Lógica estándar</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Encendido:</strong> Lógica alternativa</p>
<p style="font-size:11px;color:#065F46;margin:0.5rem 0 0;line-height:1.4;"><strong>Resultado inmediato:</strong> El sistema <strong>recalcula todos los estados</strong> y la tabla se actualiza.</p>
</div>

</div>
</div>

---

## Comparativa de Lógicas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Lógica estándar (por defecto)</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Pendiente</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">La cuenta <strong>no tiene ningún pago</strong>.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Cobrado Parcial</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Tiene <strong>pagos</strong> pero <strong>no el total</strong>.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Cobrado Total</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;"><strong>Monto pagado = Monto total</strong>.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Vencido</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Fecha de vencimiento <strong>pasó</strong> y no está pagada completamente.</p>
</div>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Ideal para:</strong> Criterios de cobranza simples, sin reglas especiales, mayoría de casos.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Lógica alternativa</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Criterios personalizables</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Usa <strong>reglas diferentes</strong> según configuración de negocio.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Factores adicionales</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Puede considerar <strong>variables adicionales</strong> en el cálculo.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Adaptación específica</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Configurada según <strong>necesidades particulares</strong> de cada empresa.</p>
</div>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Ideal para:</strong> Criterios complejos, reglas especiales de negocio, casos donde la estándar no aplica.</p>
</div>

</div>
</div>

---

## Ejemplos de Diferencias

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Caso: Cuenta con pago parcial</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;">Datos: Monto S/. 1000, Pagado S/. 500</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Estándar:</strong> <span style="background:#F59E0B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Parcial</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Alternativa (ejemplo):</strong> <span style="background:#6B6B6B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Pendiente</span> (si el criterio exige 100% para ser considerado parcial)</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Caso: Cuenta vencida</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;">Datos: Monto S/. 1000, Pagado S/. 0, Vencimiento: Ayer</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Estándar:</strong> <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Vencido</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Alternativa (ejemplo):</strong> <span style="background:#6B6B6B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Pendiente</span> (si el criterio no considera fecha de vencimiento)</p>
</div>
</div>

</div>
</div>

---

## Impacto en el Sistema

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Qué cambia</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Estados</strong> de las cuentas (badges de colores)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Métricas</strong> de clientes en panel lateral</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Métricas</strong> de vendedores en panel lateral</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Cantidad</strong> de cuentas por estado</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Qué NO cambia</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Montos:</strong> Total, pagado, por cobrar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Fechas:</strong> Emisión, vencimiento</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Datos de cuenta:</strong> Código, concepto, cliente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Nombres:</strong> Clientes, vendedores</p>
</div>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Efecto en reportes</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Los <strong>reportes</strong> que dependen del estado mostrarán datos diferentes</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Las <strong>métricas de cobranza</strong> cambian según la lógica activa</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• El <strong>dashboard</strong> de CxC refleja la interpretación alternativa</p>
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
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Entiende</strong> la diferencia entre lógicas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Revisa</strong> estados actuales como referencia</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Considera</strong> impacto en reportes</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Comunica</strong> al equipo si trabajas colaborativamente</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Al cambiar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Activa el <strong>switch</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Verifica</strong> que los estados sean correctos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Revisa</strong> métricas de paneles laterales</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Documenta</strong> cuándo y por qué cambiaste</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Después de cambiar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Verifica <strong>consistencia</strong> de los estados</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Revisa que <strong>reportes</strong> sean correctos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Monitorea</strong> por posibles problemas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Vuelve a estándar</strong> si hay inconsistencias</p>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Los estados no cambian</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Switch no se activó correctamente o error al recalcular</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica que el switch esté activado. <strong>Recarga la página</strong> e intenta nuevamente.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Los estados son incorrectos</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Lógica alternativa no se adapta a tus necesidades o error en configuración</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Revisa si la alternativa es correcta para tu negocio. Si no, <strong>vuelve a lógica estándar</strong>. Contacta soporte si necesitas configuración personalizada.</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Activar lógica alternativa</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en switch</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Usa lógica personalizada, recalcula estados</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Desactivar lógica alternativa</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en switch</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Vuelve a lógica estándar, recalcula estados</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver estados actuales</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Revisar tabla</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Estados según lógica activa</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Comparar lógicas</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Activar/desactivar switch</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Ver diferencias entre cálculos</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Revertir cambio</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Desactivar switch</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Vuelve a estados originales (estándar)</td></tr>
</tbody>
</table>

<alert type="warning">
  La lógica alternativa es una funcionalidad <strong>avanzada</strong>. Por defecto usa la <strong>lógica estándar</strong>. Solo activa la alternativa si tienes <strong>criterios especiales</strong> que la estándar no cubre. Siempre <strong>verifica los cambios</strong> después de activar el switch para asegurarte de que los estados sean correctos. Si no estás seguro, mantén el switch <strong>desactivado</strong> (lógica estándar).
</alert>