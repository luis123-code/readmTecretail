<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Flujo de Crear POS · Guía de Usuario</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Guía completa para agregar nuevos terminales POS a una tienda, incluyendo configuración de modo, credenciales y conexión.</span>

<alert type="info">
  Flujo de creación con tienda preasignada automáticamente, valores por defecto configurables y validación de campos obligatorios. El POS aparece inmediatamente bajo la tienda al guardar.
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
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Abre el menú contextual de la tienda para acceder a opciones de gestión, incluyendo la creación de nuevos terminales POS.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cómo hacerlo</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Ubica la <span style="font-weight:600;color:#121212;">tienda deseada</span> en el listado</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">tres puntos (...)</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Menú desplegable aparece</span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opciones del menú</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Ver Tienda</span> — Consultar información</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Editar Tienda</span> — Modificar datos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Crear POS</span> — Agregar terminal (nuevo)</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cuándo usarlo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Para agregar caja adicional a tienda</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Para configurar terminal de venta</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Para expandir puntos de venta físicos</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Pre-asignación automática</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">La tienda se selecciona automáticamente desde la que abriste el menú. No necesitas buscarla.</p>
</div>

</div>
</div>

---

### 2. Abrir Modal de Creación

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Icono</p>
<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#ico_pos)"><path d="M4.8 21.6H19.2C20.19 21.6 21 20.79 21 19.8V4.8C21 3.81 20.19 3 19.2 3H9L3 9V19.8C3 20.79 3.81 21.6 4.8 21.6Z" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3V9H3" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M16 14H8" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M16 18H8" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M10 10H8" stroke="#121212" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><defs><clipPath id="ico_pos"><rect width="24" height="24" fill="white"/></clipPath></defs></svg>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Qué hace</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Abre el modal "Crear Nuevo POS" con formulario para configurar el terminal, tienda pre-asignada automáticamente.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cómo hacerlo</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">En el menú, selecciona <span style="font-weight:600;color:#121212;">"Crear POS"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal "Crear Nuevo POS" se abre</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Campos cargados con <strong>valores por defecto</strong></span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estructura del modal</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Título:</span> "Crear Nuevo POS"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Subtítulo:</span> "Agrega un nuevo terminal..."</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Ancho:</span> 560px máximo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Layout:</span> Grid 4 columnas</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Valores por defecto</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">email</span> = "tecretail.org"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">clavePOS</span> = "0"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Puerto</span> = "3000"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">EasyMode</span> = 0 (Normal)</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Botones</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Cancelar:</span> Outline gris</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Guardar POS:</span> Primario verde</p>
</div>
</div>

</div>
</div>

---

### 3. Configurar Campos del POS

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campo obligatorio: Nombre</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>ID:</strong> pos-nombre</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Tipo:</strong> Texto libre</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Ejemplos:</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;padding-left:0.5rem;">• "Caja 1"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;padding-left:0.5rem;">• "Terminal Principal"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;padding-left:0.5rem;">• "POS Recepción"</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campos de conexión</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">IP:</span> "192.168.1.100"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Puerto:</span> "3000" (default)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Email:</span> "tecretail.org"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Clave:</span> "0" (default)</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campo obligatorio: Modo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>ID:</strong> EasyMode</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Tipo:</strong> Selector numérico</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;">0</span> = Modo Normal</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#DBEAFE;border:1px solid #BFDBFE;color:#1E40AF;font-weight:600;">1</span> = Modo Fácil</p>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Validaciones obligatorias</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Nombre:</strong> "El nombre del POS es obligatorio"</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Tienda:</strong> Pre-asignada automáticamente</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;"><strong>Bloqueo:</strong> No guarda si falta nombre</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Diferencias de modo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Normal (0):</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;padding-left:0.5rem;">Interfaz completa con todas las funcionalidades</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-weight:500;color:#121212;">Fácil (1):</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;padding-left:0.5rem;">Interfaz simplificada para operaciones rápidas</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Campo oculto</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Tiend</span> = ID de tienda pre-asignado</p>
<p style="font-size:11px;color:#86868b;margin:0.25rem 0 0;line-height:1.5;">Se envía como array: <span style="font-family:monospace;">[id_tienda]</span></p>
</div>

</div>
</div>

---

### 4. Guardar o Cancelar

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción A: Cancelar</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Cancelar"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Modal se cierra</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Cambios <strong>NO</strong> se guardan</span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción B: Guardar POS</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">"Guardar POS"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Sistema valida campos</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Si OK, procede a guardar</span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Payload enviado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">nombre</span> — Nombre del POS</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">email</span> — Email asociado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">clavePOS</span> — Clave de acceso</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">IP</span> — Dirección IP</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Puerto</span> — Puerto de conexión</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">EasyMode</span> — 0 o 1</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><span style="font-family:monospace;background:#E5E5E5;padding:0.1rem 0.3rem;border-radius:3px;font-size:11px;">Tiend</span> — [ID tienda]</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estado de carga</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Botón muestra: "Guardando..."</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Botón <strong>deshabilitado</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cursor: not-allowed</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Opacidad: 50%</p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Sin borrador</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">No hay opción "Guardar borrador". Solo guardado definitivo inmediato.</p>
</div>

</div>
</div>

---

### 5. Resultado y Visualización

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">✓ Éxito al guardar</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">01</span><span style="font-size:12px;color:#047857;line-height:1.5;">Mensaje: <strong>"POS creado correctamente"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#047857;line-height:1.5;">Modal cierra <strong>automáticamente</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#047857;line-height:1.5;">Listado se <strong>actualiza</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#047857;line-height:1.5;">POS aparece <strong>bajo la tienda</strong></span></div>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Tarjeta del POS creado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Icono:</strong> Laptop</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Nombre:</strong> Como lo ingresaste</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Badge modo:</strong> "Fácil" (azul) o "Normal" (gris)</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>IP:</strong> Mostrada o "No asignada"</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Acceso:</strong> Botón enlace externo</p>
</div>
</div>

</div>
<div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">✗ Error al guardar</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#FECACA;color:#991B1B;flex-shrink:0;">01</span><span style="font-size:12px;color:#991B1B;line-height:1.5;">Mensaje: <strong>"Error al crear el POS"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#FECACA;color:#991B1B;flex-shrink:0;">02</span><span style="font-size:12px;color:#991B1B;line-height:1.5;">Modal <strong>permanece abierto</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#FECACA;color:#991B1B;flex-shrink:0;">03</span><span style="font-size:12px;color:#991B1B;line-height:1.5;">Campos mantienen <strong>valores</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#FECACA;color:#991B1B;flex-shrink:0;">04</span><span style="font-size:12px;color:#991B1B;line-height:1.5;">Botón vuelve a <strong>habilitado</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Acceso inmediato</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">El botón de acceso al POS está disponible inmediatamente en la tarjeta. Puedes entrar al terminal desde el listado.</p>
</div>

</div>
</div>

---

## Resumen de campos

<table style="width:100%;border-collapse:collapse;">
<thead><tr style="border-bottom:1px solid #E5E5E5;"><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Campo</th><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Tipo</th><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Obligatorio</th><th style="text-align:left;padding:0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Default</th></tr></thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-weight:500;color:#121212;">Nombre</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Texto</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;">Sí</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">—</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-weight:500;color:#121212;">Email</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Texto</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;">No</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">"tecretail.org"</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-weight:500;color:#121212;">Clave POS</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Texto</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;">No</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">"0"</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-weight:500;color:#121212;">IP</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Texto</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;">No</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">—</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-weight:500;color:#121212;">Puerto</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Texto</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#F3F4F6;border:1px solid #E5E7EB;color:#6B7280;font-weight:600;">No</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">"3000"</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-weight:500;color:#121212;">Modo</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Número</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;">Sí</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">0 (Normal)</td></tr>
<tr><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-weight:500;color:#121212;">Tienda</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Número</td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;"><span style="font-size:11px;padding:0.15rem 0.5rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;">Sí</span></td><td style="padding:0.5rem;font-size:12px;color:#6B6B6B;">Preasignado</td></tr>
</tbody>
</table>

<alert type="warning">
  La <strong>tienda se pre-asigna automáticamente</strong> desde la que abriste el menú y <strong>no se puede cambiar</strong> al editar. El <strong>nombre es obligatorio</strong>. El <strong>acceso al POS es inmediato</strong> tras guardar. No hay <strong>borrador</strong>: guardado es definitivo. <strong>Modo Fácil (1)</strong> simplifica la interfaz para operaciones rápidas.
</alert>