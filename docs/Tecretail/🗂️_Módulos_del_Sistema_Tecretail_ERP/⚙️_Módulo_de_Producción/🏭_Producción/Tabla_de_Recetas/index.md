<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Producción · Recetas</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Gestiona y visualiza todas las recetas de producción del sistema. Cada receta define los ingredientes, cantidades y parámetros para fabricar un producto específico.</span>

---

## Columnas de la tabla

| Columna | Descripción |
|---|---|
| **RECETA** | Código único de la receta (ej. REC-001, REC-002) |
| **PRODUCTO RESULTANTE** | Producto final que se obtiene de la receta |
| **COMPONENTES** | Ingredientes/materiales con badges de colores y abreviaturas |
| **CANTIDAD** | Cantidad base del lote de producción |
| **ESTADO** | Estado de la receta con badge de color (Activo/Inactivo) |
| **ACCIONES** | Botón de menú (tres puntos) para opciones adicionales |

---

## Funcionalidades

<Cards>
  <Card title="Crear nueva receta" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><g clip-path='url(#clip0_4418_169797)'><path d='M22 6V8.42C22 10 21 11 19.42 11H16V4.01C16 2.9 16.91 2 18.02 2C19.11 2.01 20.11 2.45 20.83 3.17C21.55 3.9 22 4.9 22 6Z' stroke='#249F65' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M2 7V21C2 21.83 2.94001 22.3 3.60001 21.8L5.31 20.52C5.71 20.22 6.27 20.26 6.63 20.62L8.28999 22.29C8.67999 22.68 9.32001 22.68 9.71001 22.29L11.39 20.61C11.74 20.26 12.3 20.22 12.69 20.52L14.4 21.8C15.06 22.29 16 21.82 16 21V4C16 2.9 16.9 2 18 2H7H6C3 2 2 3.79 2 6V7Z' stroke='#249F65' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M6.25 10H11.75' stroke='#249F65' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M9 12.75V7.25' stroke='#249F65' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></g><defs><clipPath id='clip0_4418_169797'><rect width='24' height='24' fill='white'/></clipPath></defs></svg>" href="#" tags="Formulario, Código, Componentes, Parámetros">
    Haz clic en **Nueva Receta** (arriba a la derecha). Completa: código, descripción, producto final, componentes/ingredientes, cantidades, parámetros de proceso, costo estimado y rendimiento estimado.
  </Card>
  <Card title="Buscar recetas" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><g clip-path='url(#clip0_4418_9554)'><path d='M11.5 21C16.7467 21 21 16.7467 21 11.5C21 6.25329 16.7467 2 11.5 2C6.25329 2 2 6.25329 2 11.5C2 16.7467 6.25329 21 11.5 21Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M21.02 2.47998C21.32 4.58998 21.62 6.69998 21.92 8.80998' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M18.85 5.41016L21.92 2.48016L21.01 1.57016' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></g><defs><clipPath id='clip0_4418_9554'><rect width='24' height='24' fill='white'/></clipPath></defs></svg>" href="#" tags="Código, Descripción, Producto Final">
    Búsqueda en tiempo real por código, descripción o producto final. Los resultados aparecen automáticamente al escribir.
  </Card>
  <Card title="Ver detalles de receta" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><g clip-path='url(#clip0_4418_9532)'><path d='M15.58 11.9999C15.58 13.9799 13.98 15.5799 12 15.5799C10.02 15.5799 8.42004 13.9799 8.42004 11.9999C8.42004 10.0199 10.02 8.41992 12 8.41992C13.98 8.41992 15.58 10.0199 15.58 11.9999Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M12 20.2707C15.53 20.2707 18.82 18.1907 21.11 14.5907C22.01 13.1807 22.01 10.8107 21.11 9.4007C18.82 5.8007 15.53 3.7207 12 3.7207C8.46997 3.7207 5.17997 5.8007 2.88997 9.4007C1.98997 10.8107 1.98997 13.1807 2.88997 14.5907C5.17997 18.1907 8.46997 20.2707 12 20.2707Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></g><defs><clipPath id='clip0_4418_9532'><rect width='24' height='24' fill='white'/></clipPath></defs></svg>" href="#" tags="Modal, Componentes, Parámetros, Costo">
    Haz clic en cualquier receta para abrir el modal con: código, descripción, producto resultante, lista completa de componentes con cantidades, parámetros de proceso, costo y rendimiento estimados.
  </Card>
  <Card title="Editar receta" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><g clip-path='url(#clip0_4418_169799)'><path d='M6.73 19.7C7.55 18.82 8.8 18.89 9.52 19.85L10.53 21.2C11.34 22.27 12.65 22.27 13.46 21.2L14.47 19.85C15.19 18.89 16.44 18.82 17.26 19.7C19.04 21.6 20.49 20.97 20.49 18.31V7.04C20.5 3.01 19.56 2 15.78 2H8.22C4.44 2 3.5 3.01 3.5 7.04V18.3C3.5 20.97 4.96 21.59 6.73 19.7Z' stroke='#1E40AF' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M8.09607 11H8.10505' stroke='#1E40AF' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'/><path d='M10.8984 11H16.3984' stroke='#1E40AF' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M8.09607 7H8.10505' stroke='#1E40AF' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'/><path d='M10.8984 7H16.3984' stroke='#1E40AF' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M18.42 11C20.1 11 21.5 9.6 21.5 7.92C21.5 6.24 20.1 4.84 18.42 4.84C16.74 4.84 15.34 6.24 15.34 7.92C15.34 9.6 16.74 11 18.42 11Z' stroke='#1E40AF' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M18.42 4.83984V2.83984' stroke='#1E40AF' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M18.42 12.959V10.959' stroke='#1E40AF' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></g><defs><clipPath id='clip0_4418_169799'><rect width='24' height='24' fill='white'/></clipPath></defs></svg>" href="#" tags="Modificación, Componentes, Estado">
    Click en los tres puntos (⋮) → **Editar Receta**. Puedes cambiar: descripción, producto final, componentes y cantidades, parámetros de proceso, costo, rendimiento y estado.
  </Card>
</Cards>

---

## Estados de las recetas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;font-weight:600;color:#065F46;margin:0 0 0.5rem;">Activo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<div style="display:flex;gap:0.75rem;align-items:center;"><span style="width:10px;height:10px;border-radius:50%;background:#249F65;display:inline-block;"></span><span style="font-size:12px;color:#047857;">Color verde</span></div>
<div style="display:flex;gap:0.75rem;align-items:center;"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="vertical-align:middle;display:inline;"><g clip-path="url(#clip0_4418_9540)"><path d="M10.49 2.23055L5.50003 4.11055C4.35003 4.54055 3.41003 5.90055 3.41003 7.12055V14.5505C3.41003 15.7305 4.19003 17.2805 5.14003 17.9905L9.44003 21.2005C10.85 22.2605 13.17 22.2605 14.58 21.2005L18.88 17.9905C19.83 17.2805 20.61 15.7305 20.61 14.5505V7.12055C20.61 5.89055 19.67 4.53055 18.52 4.10055L13.53 2.23055C12.68 1.92055 11.32 1.92055 10.49 2.23055Z" stroke="#249F65" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9.05005 11.8697L10.66 13.4797L14.96 9.17969" stroke="#249F65" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="clip0_4418_9540"><rect width="24" height="24" fill="white"/></clipPath></defs></svg><span style="font-size:12px;color:#047857;">Disponible para usar en producción</span></div>
<div style="display:flex;gap:0.75rem;align-items:center;"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="vertical-align:middle;display:inline;"><g clip-path="url(#clip0_4418_9540)"><path d="M10.49 2.23055L5.50003 4.11055C4.35003 4.54055 3.41003 5.90055 3.41003 7.12055V14.5505C3.41003 15.7305 4.19003 17.2805 5.14003 17.9905L9.44003 21.2005C10.85 22.2605 13.17 22.2605 14.58 21.2005L18.88 17.9905C19.83 17.2805 20.61 15.7305 20.61 14.5505V7.12055C20.61 5.89055 19.67 4.53055 18.52 4.10055L13.53 2.23055C12.68 1.92055 11.32 1.92055 10.49 2.23055Z" stroke="#249F65" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9.05005 11.8697L10.66 13.4797L14.96 9.17969" stroke="#249F65" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="clip0_4418_9540"><rect width="24" height="24" fill="white"/></clipPath></defs></svg><span style="font-size:12px;color:#047857;">Puede seleccionarse al crear nuevos runs</span></div>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.5rem;">Inactivo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<div style="display:flex;gap:0.75rem;align-items:center;"><span style="width:10px;height:10px;border-radius:50%;background:#DC2626;display:inline-block;"></span><span style="font-size:12px;color:#991B1B;">Color rojo</span></div>
<div style="display:flex;gap:0.75rem;align-items:center;"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="vertical-align:middle;display:inline;"><g clip-path="url(#clip0_4418_9665)"><path d="M13.39 17.3594L10.64 14.6094" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M13.36 14.6406L10.61 17.3906" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M8.80994 2L5.18994 5.63" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M15.1899 2L18.8099 5.63" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M2 7.84961C2 5.99961 2.99 5.84961 4.22 5.84961H19.78C21.01 5.84961 22 5.99961 22 7.84961C22 9.99961 21.01 9.84961 19.78 9.84961H4.22C2.99 9.84961 2 9.99961 2 7.84961Z" stroke="#DC2626" stroke-width="1.5"/><path d="M3.5 10L4.91 18.64C5.23 20.58 6 22 8.86 22H14.89C18 22 18.46 20.64 18.82 18.76L20.5 10" stroke="#DC2626" stroke-width="1.5" stroke-linecap="round"/></g><defs><clipPath id="clip0_4418_9665"><rect width="24" height="24" fill="white"/></clipPath></defs></svg><span style="font-size:12px;color:#991B1B;">No disponible temporalmente</span></div>
<div style="display:flex;gap:0.75rem;align-items:center;"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="vertical-align:middle;display:inline;"><g clip-path="url(#clip0_4418_9665)"><path d="M13.39 17.3594L10.64 14.6094" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M13.36 14.6406L10.61 17.3906" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M8.80994 2L5.18994 5.63" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M15.1899 2L18.8099 5.63" stroke="#DC2626" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M2 7.84961C2 5.99961 2.99 5.84961 4.22 5.84961H19.78C21.01 5.84961 22 5.99961 22 7.84961C22 9.99961 21.01 9.84961 19.78 9.84961H4.22C2.99 9.84961 2 9.99961 2 7.84961Z" stroke="#DC2626" stroke-width="1.5"/><path d="M3.5 10L4.91 18.64C5.23 20.58 6 22 8.86 22H14.89C18 22 18.46 20.64 18.82 18.76L20.5 10" stroke="#DC2626" stroke-width="1.5" stroke-linecap="round"/></g><defs><clipPath id="clip0_4418_9665"><rect width="24" height="24' fill='white'/></clipPath></defs></svg><span style="font-size:12px;color:#991B1B;">No debería usarse en nuevos runs</span></div>
</div>
</div>

</div>
</div>

---

## Información de los componentes

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Visualización</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Círculos de colores: cada material tiene un color único</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Abreviaturas: Si es número → "Ma" + número (ej. Ma123)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Si es texto → Primeras letras (ej. "Tomate" → "TO")</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Tamaño: círculos pequeños (7x7)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Hover: muestra nombre completo y cantidad</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ejemplo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Material</span> — Tomate Rojo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Badge</span> — Círculo rojo con "TO"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Hover</span> — "Tomate Rojo - 5 kg"</p>
</div>
</div>

</div>
</div>

---

## Cómo usar la tabla

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para crear producción</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Busca la receta del producto que quieres fabricar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verifica que esté en estado "Activo"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Revisa los componentes para asegurar disponibilidad</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Usa la receta al crear un nuevo run</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para consultar información</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Click en la receta para ver detalles completos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Revisa componentes y cantidades</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Consulta parámetros de proceso</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verifica costo y rendimiento estimados</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para modificar recetas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Click en el menú de acciones (⋮)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Selecciona "Editar Receta"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Modifica los datos necesarios</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Guarda los cambios</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Funcionalidades de la tabla</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ordenamiento: click en encabezado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Búsqueda: código, descripción, producto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Paginación: configurable (default: 200)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Filtros: estado, producto resultante</p>
</div>
</div>

</div>
</div>

<alert type="info">
  Los componentes se muestran de forma compacta con badges de colores. Cada material tiene un color único para fácil identificación. La cantidad de lote base define el tamaño estándar de producción. Los parámetros de proceso definen cómo fabricar el producto.
</alert>