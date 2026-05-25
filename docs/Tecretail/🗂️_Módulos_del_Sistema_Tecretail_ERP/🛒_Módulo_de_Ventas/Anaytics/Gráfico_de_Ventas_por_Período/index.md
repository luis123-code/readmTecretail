<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Analytics · Visualización Temporal</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Visualización interactiva que muestra la evolución de ventas a lo largo del tiempo. Soporta diferentes granularidades (años, meses, días, personalizado) y múltiples series comparativas (ventas, facturas, boletas, cantidad de productos) para análisis de tendencias y patrones estacionales.</span>

<alert type="info">
  Usa <strong>períodos largos</strong> (años, meses) para ver <strong>tendencias de largo plazo</strong> y <strong>períodos cortos</strong> (días) para monitoreo diario. Activa <strong>múltiples series</strong> para comparar ventas con facturación. El <strong>switch de combinación</strong> de documentos simplifica la visualización mostrando facturación total. Este gráfico muestra <strong>datos agregados por período</strong>, no transacciones individuales.
</alert>

---

## Ubicación y Elementos

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ubicación visual</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• En la página de <strong>Analytics</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Sección <strong>principal de gráficos</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Gráfico más <strong>grande y destacado</strong></p>
</div>
</div>

</div>
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Elementos visibles</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Gráfico</strong> de líneas o barras</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Controles</strong> de período (tipo y cantidad)</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Checkboxes</strong> para mostrar/ocultar series</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Switch</strong> para combinar documentos</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Leyenda</strong> con colores por serie</p>
</div>
</div>

</div>
</div>

---

## Tipos de Período

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Años</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ventas por <strong>año</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Últimos <strong>N años</strong> (3, 5, 10)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cada punto = un <strong>año</strong></p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar para:</strong> tendencias anuales, comparar años, análisis de largo plazo.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Meses</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ventas por <strong>mes</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Últimos <strong>N meses</strong> (12, 24)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cada punto = un <strong>mes</strong></p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar para:</strong> tendencias mensuales, comparar meses, análisis de mediano plazo.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Días</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ventas por <strong>día</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Últimos <strong>N días</strong> (30, 60, 90)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cada punto = un <strong>día</strong></p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar para:</strong> tendencias diarias, patrones semanales, análisis de corto plazo.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Personalizado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Rango de <strong>fechas específico</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Desde</strong> fecha hasta <strong>fecha</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cada punto = un <strong>día</strong></p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar para:</strong> períodos específicos, eventos especiales, auditorías.</p>
</div>

</div>
</div>

---

## Series Disponibles

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ventas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Monto total de <strong>ventas</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Color: <strong>Azul (#1e40af)</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Línea en el gráfico</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar para:</strong> rendimiento comercial, tendencias de ventas, comparar períodos.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Facturas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Monto total <strong>facturado</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Color: <strong>Púrpura (#7c3aed)</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Línea en el gráfico</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar para:</strong> ver facturación, comparar con ventas, evaluar conversión.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Boletas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Monto total <strong>boleteado</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Color: <strong>Verde azulado (#0f766e)</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Línea en el gráfico</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar para:</strong> ver boletación, comparar con ventas, evaluar conversión.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Documentos</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Suma</strong> de Facturas + Boletas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Color: <strong>Azul cielo (#0ea5e9)</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Aparece con <strong>switch de combinación</strong></p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar para:</strong> simplificar visualización, facturación total, análisis consolidado.</p>
</div>

</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin:1.25rem 0;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cantidad de Productos</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Cantidad</strong> de productos vendidos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Color: <strong>Naranja (#f59e0b)</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Métrica de <strong>cantidad</strong>, no de monto</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar para:</strong> ver volumen de productos, comparar con montos, análisis de ticket promedio.</p>
</div>

---

## Cómo Usar el Gráfico

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Paso 1: Tipo de período</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Dropdown: <strong>Años, Meses, Días, Personalizado</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Por defecto: <strong>Años</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Clic en dropdown → selecciona opción</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Gráfico se <strong>actualiza automáticamente</strong></p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Paso 2: Cantidad de períodos</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Campo <strong>numérico</strong> o dropdown</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Por defecto: <strong>3 (años), 12 (meses), 30 (días)</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ejemplos: Años (3, 5, 10), Meses (6, 12, 24), Días (7, 30, 90)</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Paso 3: Fechas (solo Personalizado)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Aparecen dos <strong>selectores de fecha</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>"Desde":</strong> Fecha inicial del rango</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>"Hasta":</strong> Fecha final del rango</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Gráfico se <strong>actualiza automáticamente</strong></p>
</div>
</div>

</div>
</div>

---

## Control de Series

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Mostrar/Ocultar Series</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cada serie tiene un <strong>checkbox</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Por defecto activas: <strong>Ventas, Facturas, Boletas</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Inactivas por defecto: <strong>Documentos, Cantidad de productos</strong></p>
</div>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;margin-top:0.5rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0;"><strong>Ejemplos:</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0.2rem 0 0;line-height:1.5;">• Solo <strong>Ventas</strong> para ver solo ventas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Ventas + Facturas</strong> para comparar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Todas</strong> para ver todo</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Combinar Documentos (Switch)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Etiqueta: <strong>"Combinar Documentos"</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Activa serie <strong>"Documentos"</strong> (Facturas + Boletas)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Por defecto: <strong>Desactivado</strong></p>
</div>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;margin-top:0.5rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0;"><strong>Cuándo usar:</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0.2rem 0 0;line-height:1.5;">• Simplificar <strong>visualización</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ver <strong>facturación total</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Análisis <strong>consolidado</strong></p>
</div>
</div>

</div>
</div>

---

## Ejemplos de Uso

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 1: Últimos 12 meses</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Situación:</strong> Ver evolución de ventas último año</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Tipo: <strong>Meses</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Cantidad: <strong>12</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Series: <strong>Ventas</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">→ Gráfico muestra <strong>ventas últimos 12 meses</strong></p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 2: Comparar Ventas y Facturación</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Situación:</strong> Comparar ventas con facturación</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Tipo: <strong>Meses</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Cantidad: <strong>12</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Series: <strong>Ventas + Facturas</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">→ Gráfico muestra <strong>ambas líneas para comparar</strong></p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 3: Período específico</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Situación:</strong> Ver ventas de enero 2024</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Tipo: <strong>Personalizado</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Desde: <strong>1 ene 2024</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Hasta: <strong>31 ene 2024</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. Series: <strong>Ventas</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">→ Gráfico muestra <strong>ventas de enero</strong></p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo 4: Tendencia anual</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:11px;color:#6B6B6B;margin:0 0 0.5rem;"><strong>Situación:</strong> Ver tendencia últimos 5 años</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Tipo: <strong>Años</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Cantidad: <strong>5</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Series: <strong>Ventas</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">→ Gráfico muestra <strong>tendencia de 5 años</strong></p>
</div>
</div>

</div>
</div>

---

## Interacción con el Gráfico

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Tooltip</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Al pasar <strong>mouse</strong> sobre un punto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Muestra <strong>información detallada</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Incluye valores de <strong>todas las series activas</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Formato: <strong>Fecha + Valores (S/. X,XXX.XX)</strong></p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Zoom (si disponible)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Permite <strong>ampliar</strong> sección del gráfico</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Útil para ver <strong>detalles</strong> de período específico</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Clic y <strong>arrastra</strong> para seleccionar rango</p>
</div>
</div>

</div>
</div>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Análisis de tendencias</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">1. Usa <strong>períodos largos</strong> (años, meses)</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">2. <strong>Compara series</strong> (Ventas vs Facturación)</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">3. Identifica <strong>patrones</strong> (estacionalidad, crecimiento)</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">4. <strong>Documenta</strong> hallazgos</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Monitoreo diario</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Usa <strong>días</strong> para tendencias diarias</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Compara</strong> con ayer</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Identifica <strong>anomalías</strong> (días atípicos)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. Toma <strong>acciones</strong> según resultados</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para comparación</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Activa <strong>múltiples series</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Usa <strong>colores</strong> para identificar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Compara <strong>períodos</strong> (años, meses)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Documenta</strong> diferencias</p>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Gráfico no se actualiza</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Error en carga de datos, filtros mal aplicados</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica <strong>tipo de período</strong> seleccionado. Intenta cambiar a otro tipo y vuelve al original. Si persiste, <strong>recarga la página</strong>.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">No aparecen datos</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">No hay datos en período seleccionado, rango incorrecto</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica que el <strong>período tenga datos</strong>. <strong>Amplía el rango</strong> de fechas. Prueba con otro período. Si persiste, contacta <strong>soporte</strong>.</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Seleccionar tipo período</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Dropdown (Años/Meses/Días/Personalizado)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Cambia tipo de gráfico</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Seleccionar cantidad</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Selector numérico</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Cambia cantidad de períodos mostrados</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Seleccionar fechas</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Selectores Desde/Hasta (personalizado)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Define rango personalizado</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Activar serie</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Checkbox</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Muestra serie en gráfico</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Desactivar serie</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Checkbox</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Oculta serie en gráfico</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Combinar documentos</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Switch</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Activa serie "Documentos" (Facturas + Boletas)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver tooltip</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Mouse sobre punto</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Información detallada del período</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Comparar series</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Activar múltiples series</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Comparación visual entre series</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver tendencia</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Período largo (años/meses)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Tendencia temporal clara</td></tr>
</tbody>
</table>

<alert type="info">
  El gráfico de ventas por período es tu herramienta principal para <strong>analizar tendencias temporales</strong>. Usa el <strong>tooltip</strong> para ver valores detallados de cada período. <strong>Compara diferentes períodos</strong> para identificar patrones estacionales y tendencias de crecimiento. Para ver <strong>detalles de transacciones individuales</strong>, usa el <strong>módulo de Ventas</strong>.
</alert>