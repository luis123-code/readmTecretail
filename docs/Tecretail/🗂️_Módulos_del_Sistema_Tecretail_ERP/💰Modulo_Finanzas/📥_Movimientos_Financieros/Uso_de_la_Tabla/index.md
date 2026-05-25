## Referencia visual de columnas

### Código de movimiento

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>
<p style="font-size:13px;color:#6B6B6B;line-height:1.7;margin-bottom:1rem;">Cada movimiento tiene un código con color según su tipo. Pasa el cursor sobre el código para ver el texto completo en tooltip.</p>
<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.75rem;">Colores por prefijo</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;font-family:'JetBrains Mono',monospace;flex-shrink:0;">PAY</span><span style="font-size:12px;color:#6B6B6B;">Pagos — badge verde</span></div>
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#DBEAFE;border:1px solid #BFDBFE;color:#1E40AF;font-weight:600;font-family:'JetBrains Mono',monospace;flex-shrink:0;">REC</span><span style="font-size:12px;color:#6B6B6B;">Recepciones — badge azul</span></div>
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;color:#991B1B;font-weight:600;font-family:'JetBrains Mono',monospace;flex-shrink:0;">EXP</span><span style="font-size:12px;color:#6B6B6B;">Expensas — badge rojo</span></div>
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#EDE9FE;border:1px solid #DDD6FE;color:#5B21B6;font-weight:600;font-family:'JetBrains Mono',monospace;flex-shrink:0;">TRF</span><span style="font-size:12px;color:#6B6B6B;">Transferencias — badge violeta</span></div>
</div>
<div style="margin-top:0.75rem;padding-top:0.75rem;border-top:1px solid #E5E5E5;">
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.5;">📅 La fecha y hora del movimiento se muestra al lado del código. Pasa el cursor para ver el código completo.</p>
</div>
</div>
</div>
<div>
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778534567/codigov1_iwo1be.png" alt="Badges código de movimiento" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
</div>
</div>

---

### Monto

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>
<p style="font-size:13px;color:#6B6B6B;line-height:1.7;margin-bottom:1rem;">El monto se colorea según si es un ingreso o egreso, con formato numérico estándar.</p>
<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.75rem;">Formato visual</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:13px;font-weight:700;color:#249F65;font-family:'JetBrains Mono',monospace;flex-shrink:0;">+ 1,250.00</span><span style="font-size:12px;color:#6B6B6B;">Ingresos — verde con signo <strong>+</strong></span></div>
<div style="display:flex;align-items:center;gap:0.75rem;"><span style="font-size:13px;font-weight:700;color:#EF4444;font-family:'JetBrains Mono',monospace;flex-shrink:0;">− 430.50</span><span style="font-size:12px;color:#6B6B6B;">Egresos — rojo con signo <strong>−</strong></span></div>
<div style="margin-top:0.5rem;padding-top:0.5rem;border-top:1px solid #E5E5E5;"><p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.5;">Separador de miles y 2 decimales en todos los montos</p></div>
</div>
</div>
</div>
<div>
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778534854/VERSION2_sjcx3r.png" alt="Columna monto ingresos egresos" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
</div>
</div>

---

### Badges con colores

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>
<p style="font-size:13px;color:#6B6B6B;line-height:1.7;margin-bottom:1rem;">Las columnas de estado, moneda, método y categoría usan badges de color para identificación visual rápida.</p>
<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.75rem;">Moneda</p>
<div style="display:flex;gap:0.5rem;margin-bottom:0.875rem;">
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:600;">PEN</span>
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#DBEAFE;border:1px solid #BFDBFE;color:#1E40AF;font-weight:600;">USD</span>
</div>
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.75rem;">Estado</p>
<div style="display:flex;gap:0.5rem;flex-wrap:wrap;margin-bottom:0.875rem;">
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#D1FAE5;border:1px solid #A7F3D0;color:#065F46;font-weight:500;">Procesado</span>
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#FEF3C7;border:1px solid #FDE68A;color:#92400E;font-weight:500;">Pendiente</span>
<span style="font-size:11px;padding:0.2rem 0.6rem;border-radius:9999px;background:#FEE2E2;border:1px solid #FECACA;color:#991B1B;font-weight:500;">Rechazado</span>
</div>
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.5rem;">Método · Categoría · Canal</p>
<p style="font-size:11px;color:#6B6B6B;margin:0;line-height:1.5;">Cada valor tiene un color asignado automáticamente para diferenciarlo visualmente en la tabla.</p>
</div>
</div>
<div>
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778535351/image_mdmibt.png" alt="Badges colores tabla" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
</div>
</div>

---

### Contacto

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>
<p style="font-size:13px;color:#6B6B6B;line-height:1.7;margin-bottom:1rem;">La columna de contacto muestra el cliente o proveedor asociado al movimiento con su avatar e información de contacto.</p>
<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.75rem;">Información mostrada</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;align-items:center;gap:0.75rem;">
<div style="width:28px;height:28px;border-radius:50%;background:#249F65;display:flex;align-items:center;justify-content:center;flex-shrink:0;"><span style="font-size:12px;font-weight:700;color:#fff;">A</span></div>
<div><p style="font-size:12px;font-weight:500;color:#121212;margin:0;line-height:1.3;">Avatar con inicial del nombre</p><p style="font-size:11px;color:#9CA3AF;margin:0;">Color generado automáticamente</p></div>
</div>
<div style="display:flex;align-items:center;gap:0.75rem;">
<div style="width:28px;height:28px;border-radius:50%;background:#E5E5E5;display:flex;align-items:center;justify-content:center;flex-shrink:0;"><span style="font-size:12px;">👤</span></div>
<div><p style="font-size:12px;font-weight:500;color:#121212;margin:0;line-height:1.3;">Nombre completo del contacto</p></div>
</div>
<div style="display:flex;align-items:center;gap:0.75rem;">
<div style="width:28px;height:28px;border-radius:50%;background:#E5E5E5;display:flex;align-items:center;justify-content:center;flex-shrink:0;"><span style="font-size:12px;">📞</span></div>
<div><p style="font-size:12px;font-weight:500;color:#121212;margin:0;line-height:1.3;">Teléfono si está disponible</p></div>
</div>
</div>
</div>
</div>
<div>
<img src="https://res.cloudinary.com/ddedghgb6/image/upload/v1778535537/image_yszqen.png" alt="Columna contacto" style="width:100%;border-radius:0.75rem;border:1px solid #E5E5E5;object-fit:contain;" />
</div>
</div>
````