<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Catálogo · Sincronización</span>



<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Actualiza automáticamente el stock y precio de venta de productos desde un almacén específico hacia los canales de venta.</span>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<p style="font-size:13px;color:#6B6B6B;line-height:1.7;margin-bottom:1rem;">Esta función actualiza el <span style="font-weight:500;color:#121212;">stock</span> y el <span style="font-weight:500;color:#121212;">precio de venta</span> de los productos seleccionados tomando como fuente los datos registrados en un almacén específico.</p>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.75rem;">¿Qué hace exactamente?</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0.5rem;line-height:1.5;">Por cada producto seleccionado, el sistema:</p>
<div style="display:flex;flex-direction:column;gap:0.4rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">1</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Busca el inventario del producto en el <span style="font-weight:500;color:#121212;">almacén elegido</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">2</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Hace un <span style="font-weight:500;color:#121212;">refresco de stock</span> (suma 1 y luego resta 1) para forzar la actualización en los canales</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">3</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Si el inventario tiene un <span style="font-weight:500;color:#121212;">precio registrado</span>, actualiza el PVENTA del producto automáticamente</span></div>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;color:#065F46;margin:0;line-height:1.6;">💡 Si un producto <span style="font-weight:600;">no tiene inventario</span> en el almacén seleccionado, se omite sin generar error.</p>
</div>

</div>
<div style="display:flex;flex-direction:column;gap:0.75rem;">
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778649697/image_oms9nl.png" alt="Barra de acciones masivas con sincronizar" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778649720/image_svgugv.png" alt="Modal selección de almacén fuente" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
</div>
</div>

---

## Pasos para sincronizar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>
<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;flex-shrink:0;">1</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;"><span style="font-weight:500;color:#121212;">Seleccionar</span> uno o varios productos marcando sus casillas en la tabla</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;flex-shrink:0;">2</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en el botón <span style="font-weight:600;color:#121212;">Sincronizar inventario</span> dentro de la barra de acciones masivas</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;flex-shrink:0;">3</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abrirá un modal para seleccionar el <span style="font-weight:500;color:#121212;">almacén fuente</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#121212;color:#fff;font-weight:600;flex-shrink:0;">4</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Elige el almacén desde el cual se tomará la información de stock y precio</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#249F65;color:#fff;font-weight:600;flex-shrink:0;">5</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Confirma la operación</span></div>
</div>
</div>
<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;font-weight:600;color:#065F46;margin:0 0 0.4rem;">Resultado</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• ✅ Cantidad de productos sincronizados correctamente</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• ❌ Cantidad de productos que presentaron errores</p>
</div>
</div>
<div>
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778649753/image_qsgoan.png" alt="Modal confirmación sincronización" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
</div>
</div>

<alert type="warning">
  ⚠️ Durante la sincronización <span style="font-weight:600;">no cierres ni recargues</span> la página. El proceso se ejecuta producto por producto y puede tardar unos segundos dependiendo de la cantidad seleccionada.
</alert>