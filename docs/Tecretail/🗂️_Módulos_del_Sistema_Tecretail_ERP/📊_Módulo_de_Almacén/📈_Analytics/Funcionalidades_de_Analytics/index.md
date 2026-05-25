<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Inventario · Dashboard</span>

## 📊 Dashboard de Inventario

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<div style="display:flex;align-items:center;gap:0.625rem;margin-bottom:0.4rem;">
<span style="font-family:'JetBrains Mono',monospace;font-size:11px;padding:0.15rem 0.4rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;">1</span>
<p style="font-size:12px;font-weight:600;color:#121212;margin:0;">Cálculo de Valor Total del Inventario</p>
</div>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">Suma el valor económico de todos los registros de inventario activos multiplicando el <span style="font-weight:500;color:#121212;">stock actual</span> de cada ítem por su <span style="font-weight:500;color:#121212;">costo unitario</span>. El resultado se muestra en <span style="font-family:'JetBrains Mono',monospace;">S/.</span> en el KPI superior. Permite saber cuánto capital está inmovilizado en stock.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<div style="display:flex;align-items:center;gap:0.625rem;margin-bottom:0.4rem;">
<span style="font-family:'JetBrains Mono',monospace;font-size:11px;padding:0.15rem 0.4rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;">2</span>
<p style="font-size:12px;font-weight:600;color:#121212;margin:0;">Identificación de Stock Bajo</p>
</div>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">Cuenta automáticamente cuántos ítems tienen el <span style="font-weight:500;color:#121212;">stock actual por debajo del mínimo</span> definido. Se muestra como KPI en la parte superior para saber de inmediato cuántos productos necesitan reposición.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<div style="display:flex;align-items:center;gap:0.625rem;margin-bottom:0.4rem;">
<span style="font-family:'JetBrains Mono',monospace;font-size:11px;padding:0.15rem 0.4rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;">3</span>
<p style="font-size:12px;font-weight:600;color:#121212;margin:0;">Ranking de Productos por Valor</p>
</div>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">Genera un <span style="font-weight:500;color:#121212;">gráfico de barras</span> con los productos que mayor valor económico concentran en el inventario. Permite identificar qué productos representan la mayor inversión en stock y priorizarlos en decisiones de compra, reposición o venta.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<div style="display:flex;align-items:center;gap:0.625rem;margin-bottom:0.4rem;">
<span style="font-family:'JetBrains Mono',monospace;font-size:11px;padding:0.15rem 0.4rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;">4</span>
<p style="font-size:12px;font-weight:600;color:#121212;margin:0;">Análisis de Solicitudes de Abastecimiento</p>
</div>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">Toma todas las solicitudes de abastecimiento registradas y las <span style="font-weight:500;color:#121212;">agrupa por estado</span>: <span style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#FEF3C7;padding:0.1rem 0.3rem;border-radius:3px;border:1px solid #FDE68A;color:#92400E;">Pendiente</span>, <span style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#D1FAE5;padding:0.1rem 0.3rem;border-radius:3px;border:1px solid #A7F3D0;color:#065F46;">Aprobado</span>, <span style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#FEE2E2;padding:0.1rem 0.3rem;border-radius:3px;border:1px solid #FECACA;color:#991B1B;">Rechazado</span>, <span style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#DBEAFE;padding:0.1rem 0.3rem;border-radius:3px;border:1px solid #BFDBFE;color:#1E40AF;">Completado</span>. Muestra el resultado en un <span style="font-weight:500;color:#121212;">gráfico de torta</span>.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<div style="display:flex;align-items:center;gap:0.625rem;margin-bottom:0.4rem;">
<span style="font-family:'JetBrains Mono',monospace;font-size:11px;padding:0.15rem 0.4rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;">5</span>
<p style="font-size:12px;font-weight:600;color:#121212;margin:0;">Comparación de Volumen Operativo</p>
</div>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">Enfrenta en un <span style="font-weight:500;color:#121212;">gráfico de barras</span> el número de <span style="font-weight:500;color:#121212;">solicitudes de abastecimiento</span> contra el número de <span style="font-weight:500;color:#121212;">órdenes de transferencia</span> generadas. Permite evaluar si el flujo de reposición interno está siendo atendido de forma proporcional a la demanda.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<div style="display:flex;align-items:center;gap:0.625rem;margin-bottom:0.4rem;">
<span style="font-family:'JetBrains Mono',monospace;font-size:11px;padding:0.15rem 0.4rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;">6</span>
<p style="font-size:12px;font-weight:600;color:#121212;margin:0;">Conteo de Almacenes Activos</p>
</div>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.6;">Consulta en tiempo real cuántos almacenes tienen estado <span style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#D1FAE5;padding:0.1rem 0.3rem;border-radius:3px;border:1px solid #A7F3D0;color:#065F46;">Activo</span> y lo muestra como KPI. Sirve para tener contexto operativo al interpretar los demás indicadores.</p>
</div>

<div style="background:#EDE9FE;border:1px solid #DDD6FE;border-radius:0.75rem;padding:1rem;">
<div style="display:flex;align-items:center;gap:0.625rem;margin-bottom:0.4rem;">
<span style="font-family:'JetBrains Mono',monospace;font-size:11px;padding:0.15rem 0.4rem;border-radius:4px;background:#5B21B6;color:#fff;font-weight:600;">7</span>
<p style="font-size:12px;font-weight:600;color:#5B21B6;margin:0;">Carga de Datos en Tiempo Real</p>
</div>
<p style="font-size:12px;color:#4C1D95;margin:0;line-height:1.6;">Al entrar al módulo, todos los indicadores y gráficos se consultan <span style="font-weight:600;">simultáneamente desde el servidor</span> para garantizar que la información siempre refleje el estado actual del sistema sin necesidad de refrescar manualmente.</p>
</div>

</div>
<div style="display:flex;flex-direction:column;gap:0.75rem;">
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778618157/image_yyoi39.png" alt="KPIs del dashboard de inventario" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778618172/image_csedwv.png" alt="Gráfico ranking de productos" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778618186/image_pzdf3n.png" alt="Gráficos de solicitudes y transferencias" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
</div>
</div>