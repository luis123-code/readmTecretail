<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Notas de Crédito · Visualización</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Vista completa de información de nota de crédito en modal dedicado, incluyendo datos del cliente, montos de corrección, documento original relacionado y acceso a documentos asociados.</span>

<alert type="info">
  El detalle de nota de crédito es <strong>idéntico</strong> al de facturas y boletas, pero incluye la <strong>referencia al documento original</strong> (factura o boleta) que la nota corrige. Esta vinculación es <strong>fundamental</strong> para trazabilidad de correcciones.
</alert>

---

## Cómo Abrir el Detalle

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción 1: Clic en fila</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Localiza la <span style="font-weight:600;color:#121212;">nota de crédito</span> en la tabla</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <strong>cualquier parte</strong> de la fila</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <strong>modal de detalle</strong></span></div>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Opción 2: Menú de acciones</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en <span style="font-weight:600;color:#121212;">menú (⋮)</span> al final de la fila</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>"Ver Detalle"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre el <strong>mismo modal</strong></span></div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estructura del modal</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong style="color:#121212;">Encabezado:</strong> Título + número de nota + botón X</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong style="color:#121212;">Cuerpo:</strong> Secciones organizadas con scroll si es necesario</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong style="color:#121212;">Pie:</strong> Botón Cerrar + acciones disponibles</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cerrar el modal</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Botón X:</strong> Esquina superior derecha</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Botón Cerrar:</strong> Parte inferior</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Clic fuera:</strong> Fuera del modal</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Tecla ESC:</strong> En teclado</p>
</div>
</div>

</div>
</div>

---

## Información del Modal

### Datos del Cliente y de la Nota

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Información del cliente</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Nombre completo</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Tipo de documento</span> (DNI, RUC, etc.)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Número de documento</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Dirección</span> completa</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Teléfono</span> (si disponible)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Email</span></p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Información de la nota</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Serie</span> (BC01, FC01)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Número</span> correlativo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Fecha de emisión</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Moneda</span> (PEN o USD)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Monto</span> de la nota</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Motivo</span> (razón de corrección)</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Referencia al documento original</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Serie relacionada</span> (del documento original)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Correlativo relacionado</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Tipo de documento</span> (factura o boleta)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Comprobante completo</span> (F001-0001234)</p>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Importancia</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">La <strong>referencia al documento original</strong> es única de notas de crédito. Permite verificar qué factura o boleta corrige esta nota. Fundamental para <strong>trazabilidad</strong> y auditorías.</p>
</div>

</div>
</div>

---

### Detalles de Corrección y Estado

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Detalles de la corrección</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Tipo de corrección:</span> Devolución, descuento, error</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Monto original:</span> Del documento relacionado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Monto de la nota:</span> Corrección aplicada</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Monto neto:</span> Diferencia post-corrección</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estado de la nota</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Estado actual:</span> <span style="background:#22C55E;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Completado</span> <span style="background:#3B82F6;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">En Proceso</span> <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Anulado</span></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Fecha de estado:</span> Último cambio</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Descripción:</span> Explicación del estado</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Documentos relacionados</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">PDF:</span> Enlace para ver documento</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">XML:</span> Enlace para descargar archivo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Documento original:</span> Enlace a factura/boleta relacionada</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Información adicional</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Historial de cambios:</span> Creación, modificaciones</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Referencias:</span> Orden de venta, guías relacionadas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Observaciones:</span> Notas internas, comentarios</p>
</div>
</div>

</div>
</div>

---

## Acciones desde el Detalle

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ver documentos</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">PDF</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Haz clic en enlace. Se abre en nueva pestaña. Puedes imprimir o guardar.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">XML</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Haz clic en enlace. Se descarga automáticamente. Guarda en computadora.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Documento original</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Si hay enlace, clic para ver factura/boleta que corrige. Útil para verificar relación.</p>
</div>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Operaciones disponibles</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Editar nota</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Si hay botón "Editar", clic para abrir formulario. Modifica y guarda.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Imprimir</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Botón "Imprimir" o abre PDF e imprime desde ahí.</p>
</div>
<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;font-weight:600;color:#121212;margin:0 0 0.3rem;">Anular nota</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.4;">Botón "Anular". Sistema envía a SUNAT. Estado cambia a "Anulado".</p>
</div>
</div>
</div>

</div>
</div>

---

## Cuándo Usar el Detalle

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para verificación</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Antes de <strong>enviar al cliente</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verificar <strong>datos correctos</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Revisar <strong>montos y cálculos</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Confirmar <strong>documento original</strong> relacionado</p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Qué revisar antes de enviar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Nombre del cliente ✓</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• DNI/RUC correcto ✓</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Monto correcto ✓</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Motivo claro y específico ✓</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Documento original correcto ✓</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Estado actual ✓</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para auditoría</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Auditorías fiscales</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Responder a <strong>contabilidad</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verificar <strong>discrepancias</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Rastrear <strong>correcciones</strong></p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para soporte al cliente</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Revisar información</strong> para responder preguntas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verificar <strong>estado</strong> para actualizaciones</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Descargar PDF</strong> si cliente lo perdió</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Verificar <strong>documento original</strong> para explicar corrección</p>
</div>
</div>

</div>
</div>

---

## Importancia de la Referencia al Documento Original

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Trazabilidad</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Permite saber <strong>qué documento corrige</strong> la nota</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Facilita <strong>auditorías</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Ayuda a <strong>conciliar cuentas</strong></p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Validación</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Confirma vinculación al <strong>documento correcto</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Evita <strong>errores en correcciones</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Permite verificar <strong>consistencia</strong></p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Reportes</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Calcula <strong>montos netos</strong> correctamente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Genera <strong>reportes de correcciones</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Análisis de <strong>devoluciones</strong></p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Verificación crítica</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">Siempre revisa que la <strong>serie y correlativo relacionado</strong> correspondan al documento correcto. Una vinculación incorrecta es <strong>difícil de corregir</strong>.</p>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Modal no se abre</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Error del sistema, datos incompletos, conexión</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Recarga página, reintenta clic. Contacta soporte si persiste</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Falta información en detalle</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Nota incompleta, falta datos en sistema</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica qué falta, usa edición para completar. Contacta soporte si no editable</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Documento original incorrecto</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Error al seleccionar documento en creación</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica serie/correlativo. Contacta soporte. Puede requerir nueva nota</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Abrir detalle</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en fila o menú → "Ver Detalle"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Modal con información completa</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver datos cliente</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Sección "Cliente" en modal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Nombre, DNI, dirección, contacto</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver montos</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Sección "Detalles de corrección"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Monto original, nota, neto</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver documento original</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Sección "Referencia"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Serie, correlativo, tipo (factura/boleta)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Descargar PDF/XML</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Enlaces en modal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Acceso a documentos</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Editar/Anular</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Botones en pie del modal (si disponibles)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Formulario de edición o anulación</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Cerrar modal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">X, botón Cerrar, clic fuera, ESC</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Vuelve a tabla</td></tr>
</tbody>
</table>

<alert type="warning">
  El detalle de nota de crédito es <strong>idéntico</strong> al de facturas y boletas, pero incluye la <strong>referencia al documento original</strong>. Siempre revisa el detalle antes de enviar al cliente para confirmar que: (1) el <strong>documento original relacionado</strong> es el correcto, (2) el <strong>motivo</strong> es claro, y (3) los <strong>datos</strong> están precisos. La vinculación al documento original es <strong>permanente</strong> y fundamental para trazabilidad.
</alert>