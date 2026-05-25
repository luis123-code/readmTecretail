<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Cuentas por Cobrar · Organización de Listas</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Funcionalidad para organizar listas de clientes y vendedores en paneles laterales según diferentes criterios (cantidad de cuentas, montos totales, pagados, por cobrar) en orden ascendente o descendente. Facilita priorización y análisis de cobranza.</span>

<alert type="info">
  El ordenamiento solo afecta la <strong>lista lateral</strong> (clientes o vendedores), no la tabla principal de cuentas. Usa el criterio que mejor se adapte a tu objetivo: <strong>"Por Cobrar" descendente</strong> para priorizar cobranza, <strong>"Pagado" descendente</strong> para evaluar desempeño.
</alert>

---

## Ubicación del Ordenamiento

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ubicación visual</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• En los <strong>paneles laterales</strong> (clientes / vendedores)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Arriba</strong> de cada lista lateral</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Selector desplegable con etiqueta <strong>"Ordenar por"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Botón <strong>flecha arriba/abajo</strong> para cambiar dirección</p>
</div>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Indicador visual</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Flecha hacia arriba:</strong> Ascendente (menor a mayor)</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Flecha hacia abajo:</strong> Descendente (mayor a menor)</p>
</div>
</div>

</div>
</div>

---

## Criterios de Ordenamiento

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para Lista de Clientes</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Cuentas:</span> Cantidad de CxC del cliente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Monto:</span> Total de cuentas del cliente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Pagado:</span> Total cancelado por cliente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Por Cobrar:</span> Total pendiente por cliente</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para Lista de Vendedores</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Cuentas:</span> Cantidad de CxC del vendedor</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Monto:</span> Total de cuentas del vendedor</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Pagado:</span> Total cancelado del vendedor</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Por Cobrar:</span> Total pendiente del vendedor</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ascendente (Menor → Mayor)</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Ejemplo: Ordenar por Monto</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Cliente A: S/. 100</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Cliente B: S/. 500</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Cliente C: S/. 1000</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar:</strong> ver clientes con menos deuda primero, identificar cuentas pequeñas.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Descendente (Mayor → Menor)</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Ejemplo: Ordenar por Monto</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Cliente C: S/. 1000</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Cliente B: S/. 500</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Cliente A: S/. 100</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar:</strong> ver clientes con más deuda primero, priorizar cobranza de montos mayores.</p>
</div>

</div>
</div>

---

## Cómo Usar el Ordenamiento

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Cambia a vista <strong>"client"</strong> o <strong>"vendedor"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz <strong>clic</strong> en selector <strong>"Ordenar por"</strong> en panel lateral</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>criterio</strong> (Cuentas/Monto/Pagado/Por Cobrar)</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz <strong>clic</strong> en <strong>flecha arriba/abajo</strong> para dirección</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">05</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">La <strong>lista se reordena</strong> automáticamente</span></div>
</div>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ventajas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Priorización:</strong> Identifica clientes/vendedores más importantes</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Eficiencia:</strong> Organiza lista según criterio, ahorra tiempo</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Análisis:</strong> Detecta patrones y tendencias</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Evaluación:</strong> Compara montos pagados, mide desempeño</p>
</div>
</div>

</div>
</div>

---

## Cuándo Usar Cada Criterio

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ordenar por Cuentas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Cuándo usarlo:</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ver quién tiene <strong>más cuentas</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Identificar <strong>muchas deudas pequeñas</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Evaluar <strong>volumen de transacciones</strong></p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Ideal para:</strong> gestión de volumen, clientes frecuentes, evaluar actividad de vendedores.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ordenar por Monto</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Cuándo usarlo:</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ver quién tiene <strong>más deuda total</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Identificar <strong>cuentas grandes</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Priorizar cobranza por <strong>monto</strong></p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Ideal para:</strong> priorización de cobranza, identificar grandes deudores, gestión de riesgo.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ordenar por Pagado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Cuándo usarlo:</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ver quién ha <strong>pagado más</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Identificar <strong>buenos pagadores</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Evaluar <strong>desempeño de cobranza</strong></p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Ideal para:</strong> evaluación de pagadores, análisis de desempeño, identificar clientes leales.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ordenar por Por Cobrar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Cuándo usarlo:</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ver quién tiene <strong>más pendiente</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Identificar <strong>cuentas por cobrar</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Priorizar <strong>cobranza pendiente</strong></p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Ideal para:</strong> priorización de cobranza, identificar deudores, gestión de flujo de caja.</p>
</div>

</div>
</div>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para priorizar cobranza</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Ordena por <strong>"Por Cobrar" (descendente)</strong> → quién debe más</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Ordena por <strong>"Monto" (descendente)</strong> → deudas más grandes</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Ordena por <strong>"Cuentas" (descendente)</strong> → quién tiene más deudas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Combina criterios</strong> según necesidad</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para análisis</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Ordena por <strong>"Pagado" (descendente)</strong> → mejores pagadores</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Ordena por <strong>"Monto" (ascendente)</strong> → deudas pequeñas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Compara criterios</strong>: cambia entre diferentes ordenamientos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Documenta hallazgos:</strong> anota patrones que encuentres</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para gestión</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Ordena según tu objetivo:</strong> usa criterio más relevante</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Cambia dirección:</strong> entre ascendente/descendente para diferentes perspectivas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Combina con búsqueda:</strong> busca cliente específico + ordena</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Revisa regularmente:</strong> los datos cambian con el tiempo</p>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">La lista no se reordena</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">No seleccionaste criterio, error en sistema</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica que hayas <strong>seleccionado un criterio</strong>. Intenta otro criterio. <strong>Recarga la página</strong> si es necesario.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ordenamiento no es el esperado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Estás en ascendente cuando quieres descendente, o criterio no es adecuado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Cambia entre <strong>ascendente/descendente</strong> (flecha). Prueba <strong>otro criterio</strong>. Verifica que el criterio sea el correcto.</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Seleccionar criterio</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Dropdown "Ordenar por"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Criterio seleccionado, lista reordena</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ordenar por cuentas</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Seleccionar "Cuentas"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Ordena por cantidad de CxC</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ordenar por monto</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Seleccionar "Monto"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Ordena por monto total</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ordenar por pagado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Seleccionar "Pagado"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Ordena por monto pagado</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ordenar por por cobrar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Seleccionar "Por Cobrar"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Ordena por monto pendiente</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Cambiar a ascendente</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Flecha hacia arriba</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Menor a mayor</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Cambiar a descendente</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Flecha hacia abajo</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Mayor a menor</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver resultado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Lista se reordena</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Nuevo orden aplicado en panel lateral</td></tr>
</tbody>
</table>

<alert type="info">
  El ordenamiento es una herramienta muy útil para gestionar cobranza de manera <strong>eficiente</strong>. Usa el criterio que mejor se adapte a tu objetivo: <strong>"Por Cobrar" descendente</strong> para priorizar cobranza; <strong>"Pagado" descendente</strong> para evaluar desempeño. Puedes cambiar entre <strong>ascendente y descendente</strong> para ver diferentes perspectivas. Recuerda que solo afecta la <strong>lista lateral</strong>, no la tabla principal. <strong>Combina con búsqueda</strong> para encontrar rápidamente clientes o vendedores específicos.
</alert>