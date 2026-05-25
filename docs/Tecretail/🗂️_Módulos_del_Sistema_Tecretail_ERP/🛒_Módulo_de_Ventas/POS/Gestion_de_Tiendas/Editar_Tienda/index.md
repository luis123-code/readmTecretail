<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Flujo de Editar Tienda · Guía de Usuario</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Guía detallada para modificar la información de una tienda existente, incluyendo validaciones, proceso de guardado y manejo de errores.</span>

<alert type="info">
  Flujo de edición con formulario precargado, campos obligatorios validados y actualización inmediata en el listado. El nombre es el único campo requerido.
</alert>

---

## Acciones disponibles

### 1. Acceder al Menú de Acciones

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Icono</p>
<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#ico_menu)"><path d="M12 8C13.1 8 14 7.1 14 6C14 4.9 13.1 4 12 4C10.9 4 10 4.9 10 6C10 7.1 10.9 8 12 8Z" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M12 20C13.1 20 14 19.1 14 18C14 16.9 13.1 16 12 16C10.9 16 10 16.9 10 18C10 19.1 10.9 20 12 20Z" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M12 14C13.1 14 14 13.1 14 12C14 10.9 13.1 10 12 10C10.9 10 10 10.9 10 12C10 13.1 10.9 14 12 14Z" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="ico_menu"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Qué hace</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Abre el menú contextual con opciones de gestión para la tienda seleccionada.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cómo hacerlo</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Ubica la tienda en el <span style="font-weight:600;color:#121212;">listado principal</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">tres puntos (...)</span> junto al nombre</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Menú desplegable aparece con opciones</span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opciones disponibles</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Ver Tienda</span> — Consultar información</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Editar Tienda</span> — Modificar datos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Crear POS</span> — Agregar terminal</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cuándo usarlo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Para corregir información de la tienda</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Para cambiar estado operativo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Para actualizar horarios de atención</p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Importante</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">Necesitas permisos de edición para ver esta opción en el menú.</p>
</div>

</div>
</div>

---

### 2. Abrir el Modal de Edición

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Icono</p>
<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#ico_edit)"><path d="M20.5 11.3V7.04C20.5 3.01 19.56 2 15.78 2H8.22C4.44 2 3.5 3.01 3.5 7.04V18.3C3.5 20.96 4.96 21.59 6.73 19.69L6.74 19.68C7.56 18.81 8.81 18.88 9.52 19.83L10.53 21.18" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M8 7H16" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 11H15" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M18.211 14.77L14.671 18.31C14.531 18.45 14.401 18.71 14.371 18.9L14.181 20.25C14.111 20.74 14.451 21.08 14.941 21.01L16.291 20.82C16.481 20.79 16.751 20.66 16.881 20.52L20.421 16.98C21.031 16.37 21.321 15.66 20.421 14.76C19.531 13.87 18.821 14.16 18.211 14.77Z" stroke="#121212" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M17.699 15.28C17.999 16.36 18.839 17.2 19.919 17.5" stroke="#121212" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="ico_edit"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Qué hace</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Abre el modal de edición con formulario precargado con los datos actuales de la tienda.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cómo hacerlo</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">En el menú, selecciona <span style="font-weight:600;color:#121212;">"Editar Tienda"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal "Editar Tienda" se abre</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Campos precargados automáticamente</span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estructura del modal</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Título:</span> "Editar Tienda"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Ancho:</span> 560px máximo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Layout:</span> Grid 4 columnas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Gap:</span> 24px entre filas</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Botones del pie</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Cancelar:</span> Estilo outline gris</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Actualizar Tienda:</span> Estilo primario verde</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Datos precargados</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Todos los campos muestran los valores actuales. ID de tienda se envía internamente (no visible).</p>
</div>

</div>
</div>

---

### 3. Modificar Campos del Formulario

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campo obligatorio: Nombre</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>ID:</strong> edit-nombre</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Tipo:</strong> Texto libre</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Ejemplo:</strong> "Tienda Centro" → "Tienda Norte"</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos opcionales</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Teléfono</span> — Cualquier formato</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Dirección</span> — Texto libre largo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Hora Inicio</span> — "8 am", "09:00"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Hora Fin</span> — "10 pm", "22:00"</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campo obligatorio: Estado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>ID:</strong> edit-estado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Tipo:</strong> Selector</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Opciones:</strong> "abierto" | "cerrado"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Por defecto:</strong> Valor actual</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estilos de campos</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Bordes:</span> Grises, redondeados</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Focus:</span> Borde verde primario</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Etiquetas:</span> Derecha, alineadas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Gap:</span> 16px etiqueta-campo</p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Validación nombre</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Obligatorio:</strong> Sí</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Error:</strong> "El nombre es obligatorio"</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Momento:</strong> Al hacer clic en guardar</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">• <strong>Bloqueo:</strong> No guarda si está vacío</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos no editables</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• ID de tienda (envío interno)</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Terminales POS (gestión separada)</p>
</div>
</div>

</div>
</div>

---

### 4. Guardar o Cancelar Cambios

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción A: Cancelar</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Cancelar"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal se cierra</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Cambios <strong>NO</strong> se guardan</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Vuelves al listado</span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción B: Actualizar</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Actualizar Tienda"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Sistema valida campos</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Si hay errores, muestra mensaje</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Si todo OK, procede al guardado</span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Datos enviados al servidor</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">ID_UPDATE</span> — ID interno tienda</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">nombre</span> — Nombre de tienda</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">telefono</span> — Teléfono</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">direccion</span> — Dirección</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">horaApert</span> — Hora apertura</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">horaCierre</span> — Hora cierre</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Estador606</span> — Estado</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estado de carga</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Botón muestra: "Actualizando..."</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Botón se <strong>deshabilita</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cursor: not-allowed</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Opacidad: 50%</p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Importante</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">No hay "Guardar borrador". Solo guardado definitivo. Una vez actualizado, los cambios son inmediatos.</p>
</div>

</div>
</div>

---

### 5. Resultado del Guardado

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">✓ Escenario: Éxito</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">01</span><span style="font-size:12px;color:#047857;line-height:1.5;">Mensaje: <strong>"Tienda actualizada correctamente"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#047857;line-height:1.5;">Modal se cierra <strong>automáticamente</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#047857;line-height:1.5;">Listado se <strong>actualiza</strong> con nuevos datos</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#047857;line-height:1.5;">Badge de estado cambia si se modificó</span></div>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Flujo completado</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">La tienda está actualizada. Los cambios son inmediatos y visibles en todo el sistema.</p>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">✗ Escenario: Error</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#FECACA;color:#991B1B;flex-shrink:0;">01</span><span style="font-size:12px;color:#991B1B;line-height:1.5;">Mensaje: <strong>"Error al actualizar la tienda"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#FECACA;color:#991B1B;flex-shrink:0;">02</span><span style="font-size:12px;color:#991B1B;line-height:1.5;">Modal <strong>permanece abierto</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#FECACA;color:#991B1B;flex-shrink:0;">03</span><span style="font-size:12px;color:#991B1B;line-height:1.5;">Campos mantienen <strong>valores ingresados</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#FECACA;color:#991B1B;flex-shrink:0;">04</span><span style="font-size:12px;color:#991B1B;line-height:1.5;">Botón vuelve a <strong>habilitado</strong></span></div>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">¿Qué hacer?</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">Verifica tu conexión, revisa que el nombre no esté vacío, e intenta nuevamente. Si persiste, contacta soporte.</p>
</div>

</div>
</div>

---

## Estados del Modal

<table style="width:100%;border-collapse:collapse;">
<thead><tr style="border-bottom:1px solid #E5E5E5;"><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Estado</th><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Descripción</th><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Visual</th></tr></thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Inicial</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Modal cerrado</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">—</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Cargado</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Campos precargados, botones habilitados</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#DBEAFE;border:1px solid #BFDBFE;color:#1E40AF;font-weight:600;">Listo</span></td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Guardando</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Esperando respuesta del servidor</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#FEF3C7;border:1px solid #FDE68A;color:#92400E;font-weight:600;">Actualizando...</span></td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Éxito</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Modal cierra, mensaje toast, listado actualiza</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;">✓ OK</span></td></tr>
<tr><td style="padding:0.5rem;font-size:12px;font-weight:500;color:#121212;">Error</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Modal abierto, mensaje toast error, botones habilitados</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;color:#991B1B;font-weight:600;">✗ Error</span></td></tr>
</tbody>
</table>

<alert type="warning">
  El <strong>nombre</strong> es el único campo obligatorio. Los <strong>terminales POS</strong> no se pueden modificar desde este modal (gestión separada). Los cambios son <strong>inmediatos</strong> al guardar. En caso de error, el modal permanece abierto para corregir sin perder datos ingresados.
</alert>