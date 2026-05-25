<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Notas de Crédito · Documentos Fiscales</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Archivo técnico electrónico en formato XML para validación fiscal ante SUNAT. Contiene la información estructurada de la nota de crédito en formato legible por sistemas automatizados.</span>

<alert type="info">
  El XML es <strong>obligatorio para fines fiscales</strong>. SUNAT lo requiere para validar la nota de crédito. El sistema lo procesa automáticamente: decodifica base64, descomprime ZIP y extrae el XML. Funciona <strong>idénticamente</strong> al de facturas y boletas.
</alert>

---

## Ubicación del XML

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Posición</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">En la <strong>tabla de notas de crédito</strong>, columna "XML". Enlace azul <strong>"Ver XML"</strong>. Si no hay XML disponible, se muestra un guion <strong>"-"</strong> en gris.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Identificación visual</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="color:#3B82F6;font-weight:500;">"Ver XML"</span> enlace azul (XML disponible)</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="color:#86868b;">"-"</span> guion gris (XML no disponible)</p>
</div>
</div>

</div>
<div>

<div style="background:#FFFFFF;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;box-shadow:0 1px 3px rgba(0,0,0,0.05);">
<div style="display:flex;align-items:center;gap:0.75rem;margin-bottom:0.75rem;">
<svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M14 2H6C4.89543 2 4 2.89543 4 4V20C4 21.1046 4.89543 22 6 22H18C19.1046 22 20 21.1046 20 20V8L14 2Z" stroke="#3B82F6" stroke-width="1.5"/><path d="M14 2V8H20" stroke="#3B82F6" stroke-width="1.5"/><path d="M9 15L11 17L15 13" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
<span style="font-size:12px;font-weight:600;color:#121212;">Columna XML</span>
</div>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="background:#EFF6FF;border:1px solid #BFDBFE;border-radius:0.375rem;padding:0.5rem;">
<p style="font-size:12px;color:#1D4ED8;margin:0;font-weight:500;">Ver XML</p>
<p style="font-size:10px;color:#3B82F6;margin:0.25rem 0 0;">Descarga automática</p>
</div>
<div style="background:#F9FAFB;border:1px solid #E5E7EB;border-radius:0.375rem;padding:0.5rem;">
<p style="font-size:12px;color:#9CA3AF;margin:0;">-</p>
<p style="font-size:10px;color:#9CA3AF;margin:0.25rem 0 0;">XML no disponible</p>
</div>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Búsqueda previa</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Usa el <strong>buscador</strong> o <strong>filtro de fechas</strong> para localizar la nota de crédito específica antes de descargar su XML.</p>
</div>

</div>
</div>

---

## Cómo Descargar el XML

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso de descarga</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Localiza la <span style="font-weight:600;color:#121212;">nota de crédito</span> en la tabla</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#E5E5E5;color:#6B6B6B;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Busca columna <span style="font-weight:600;color:#121212;">"XML"</span></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz clic en enlace <strong>"Ver XML"</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">04</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Sistema <strong>procesa automáticamente</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">05</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Archivo se <strong>descarga</strong> a tu computadora</span></div>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Proceso técnico automático</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Decodifica base64</strong> → Formato normal</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Descomprime ZIP</strong> → Extrae archivo</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• <strong>Entrega XML</strong> → Listo para usar</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">• Tiempo: <strong>~segundos</strong> (depende de conexión)</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Archivo resultante</p>
<div style="background:#ffffff;border:1px solid #E5E5E5;border-radius:0.5rem;padding:0.75rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Ubicación:</strong> Carpeta de descargas predeterminada</p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Formato:</strong> <code style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#F5F5F5;padding:0.1rem 0.3rem;border-radius:3px;">nota-credito-{serie}.xml</code></p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Ejemplo:</strong> <code style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#F5F5F5;padding:0.1rem 0.3rem;border-radius:3px;">nota-credito-BC01-0000001.xml</code></p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Mensaje:</strong> "XML descargado exitosamente"</p>
</div>
</div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">¿Por qué está comprimido?</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">El XML se transmite en <strong>ZIP</strong> para ahorrar espacio y transferir más rápido. El sistema lo descomprime automáticamente. Es estándar en sistemas fiscales.</p>
</div>

</div>
</div>

---

## XML vs PDF

<table style="width:100%;border-collapse:collapse;">
<thead>
<tr style="border-bottom:1px solid #E5E5E5;">
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">Característica</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">XML</th>
<th style="text-align:left;padding:0.3rem 0.5rem;font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;">PDF</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Lectura</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Máquinas / sistemas</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Humanos</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Uso principal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">SUNAT / fiscal</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Cliente / archivo</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Formato</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Código estructurado (XML)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Documento visual</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Obligatoriedad</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;"><strong>Obligatorio</strong> (SUNAT)</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Recomendado (cliente)</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Comprensión</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Difícil para humanos</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Fácil de entender</td></tr>
</tbody>
</table>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;margin:1.25rem 0;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Necesitas ambos</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;"><strong>XML</strong> para SUNAT (obligatorio fiscal). <strong>PDF</strong> para el cliente (comprobante visual). Siempre descarga <strong>ambos</strong> para cada nota de crédito.</p>
</div>

---

## Importancia del XML en Notas de Crédito

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para SUNAT (crítico)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Obligatorio</strong> para validación fiscal</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Documento fiscal <strong>oficial</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Sin XML, la nota <strong>no es válida</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Requerido para <strong>correcciones</strong> y devoluciones</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para contabilidad</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Respaldo</strong> fiscal oficial</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Conciliación</strong> de correcciones</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Facilita <strong>auditorías</strong></p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cuándo archivar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Siempre</strong> junto con el PDF</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Carpeta del <strong>mes</strong> correspondiente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Junto con <strong>factura/boleta original</strong></p>
</div>
</div>

<div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#065F46;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Uso como respaldo</p>
<p style="font-size:12px;color:#047857;margin:0;line-height:1.5;">Si pierdes el PDF, el XML contiene toda la información técnica. Es la <strong>fuente oficial</strong> para recuperar datos si hay discrepancias o fallas del sistema.</p>
</div>

</div>
</div>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Al descargar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. <strong>Verifica descarga:</strong> Confirma que se completó</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. <strong>Revisa nombre:</strong> Debe seguir formato estándar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. <strong>Verifica contenido:</strong> Abre y confirma no esté vacío</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Guarda con PDF:</strong> Mantén ambos juntos</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para archivo</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Organiza por fecha:</strong> Carpetas por mes/año</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Nombres consistentes:</strong> Misma estructura que PDF</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Ambos documentos:</strong> XML + PDF de misma nota</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Respaldos:</strong> Más de un lugar (local + nube)</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Para envío a SUNAT</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Generalmente automático:</strong> El sistema lo envía</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Si es manual:</strong> Sube al portal de SUNAT</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Verifica respuesta:</strong> SUNAT confirma recepción</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Guarda comprobante:</strong> Si envías manualmente</p>
</div>
</div>

<div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#991B1B;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Nota importante</p>
<p style="font-size:12px;color:#991B1B;margin:0;line-height:1.5;">No necesitas <strong>entender el contenido</strong> del XML (es código técnico). Solo necesitas <strong>guardarlo correctamente</strong> para cumplimiento fiscal.</p>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Muestra guion "-"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">XML no generado o en proceso</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Si estado es "En Proceso", espera. Si es "Completado", contacta soporte</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">"No se encontró archivo XML en ZIP"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">ZIP corrupto o sin XML válido</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Reintenta descarga. Si persiste, solicita regeneración a soporte</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">"Error al descargar XML"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Problema de conexión o servidor</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Verifica internet, recarga página, reintenta. Contacta soporte si persiste</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Archivo descargado vacío</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Descarga interrumpida o error servidor</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Descarga nuevamente, verifica contenido. Contacta soporte si sigue vacío</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Descargar XML</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en "Ver XML"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Archivo descarga automáticamente (proceso base64 + ZIP transparente)</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Verificar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Revisar carpeta descargas</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Archivo <code style="font-family:'JetBrains Mono',monospace;font-size:11px;background:#F5F5F5;padding:0.1rem 0.3rem;border-radius:3px;">nota-credito-{serie}.xml</code></td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Enviar a SUNAT</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Generalmente automático</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Validación fiscal de la nota</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Archivar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Guardar en carpeta organizada</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Respaldo fiscal completo</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Usar como respaldo</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Guardar junto con PDF</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Recuperación de datos si falla sistema</td></tr>
</tbody>
</table>

<alert type="warning">
  El XML es <strong>obligatorio para SUNAT</strong> y funciona idénticamente al de facturas y boletas. No necesitas entender su contenido técnico, pero sí <strong>guardarlo correctamente</strong>. Es especialmente crítico en notas de crédito porque SUNAT requiere validación de todas las <strong>correcciones y devoluciones</strong>. Siempre descarga XML junto con PDF para respaldo completo.
</alert>