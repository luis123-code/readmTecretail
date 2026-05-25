<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Módulo de Finanzas · Submódulo</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Control de todas las obligaciones financieras pendientes con proveedores.</span>

<p style="font-size:14px;color:#6B6B6B;line-height:1.7;max-width:680px;">Registra, edita y da seguimiento a facturas por pagar con indicadores de vencimiento, prioridad y estado de pago. Muestra el saldo pendiente vs. pagado por cada cuenta y alerta sobre vencimientos próximos o ya vencidos.</p>

<div style="display:flex;gap:0.5rem;flex-wrap:wrap;margin:1.25rem 0;">
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">Prioridad</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">Vencimientos</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">PEN · USD</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">Saldo pendiente</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #249F65;background:#E8F5EE;font-size:11px;color:#115233;">● Activo</span>
</div>

---

## Funcionalidades

<Cards>
  <Card title="Registro de cuenta" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M22 6V8.42C22 10 21 11 19.42 11H16V4.01C16 2.9 16.91 2 18.02 2C19.11 2.01 20.11 2.45 20.83 3.17C21.55 3.9 22 4.9 22 6Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M2 7V21C2 21.83 2.94001 22.3 3.60001 21.8L5.31 20.52C5.71 20.22 6.27 20.26 6.63 20.62L8.28999 22.29C8.67999 22.68 9.32001 22.68 9.71001 22.29L11.39 20.61C11.74 20.26 12.3 20.22 12.69 20.52L14.4 21.8C15.06 22.29 16 21.82 16 21V4C16 2.9 16.9 2 18 2H7H6C3 2 2 3.79 2 6V7Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M6.25 10H11.75' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M9 12.75V7.25' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Proveedor, Monto, Vencimiento">
    Abre el formulario con "Nueva Cuenta por Pagar". Completa proveedor, concepto, monto, moneda, fecha de emisión, fecha de vencimiento, categoría, prioridad y método de pago.
  </Card>
  <Card title="Seguimiento de saldo" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M8.57007 15.2704L15.11 8.73047' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M8.98001 10.3701C9.65932 10.3701 10.21 9.81948 10.21 9.14017C10.21 8.46086 9.65932 7.91016 8.98001 7.91016C8.3007 7.91016 7.75 8.46086 7.75 9.14017C7.75 9.81948 8.3007 10.3701 8.98001 10.3701Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M15.52 16.0899C16.1993 16.0899 16.75 15.5392 16.75 14.8599C16.75 14.1806 16.1993 13.6299 15.52 13.6299C14.8407 13.6299 14.29 14.1806 14.29 14.8599C14.29 15.5392 14.8407 16.0899 15.52 16.0899Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Pendiente, Pagado, Porcentaje">
    Visualiza el monto total, saldo pendiente en rojo y porcentaje pagado en verde por cada cuenta. Balance actualizado en tiempo real.
  </Card>
  <Card title="Alertas de vencimiento" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M2 22H22' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M12 6C7.03 6 3 10.03 3 15V22H21V15C21 10.03 16.97 6 12 6Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M12 2V3' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M4 4L5 5' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M20 4L19 5' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Próximos, Vencidos, Semáforo">
    Semáforo automático por días restantes. Alerta visual desde 7 días antes del vencimiento hasta marcar la cuenta como vencida.
  </Card>
  <Card title="Filtros y búsqueda" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><circle cx='11.5' cy='11.5' r='9.5' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M18.5 18.5L22 22' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Fechas, Código, Proveedor">
    Filtra por rango de fechas con campos Desde / Hasta. Busca por código o nombre de proveedor. Botones Aplicar y Limpiar para gestionar el filtro.
  </Card>
</Cards>

---

## Indicadores visuales

### Prioridad

<div style="display:flex;flex-wrap:wrap;gap:0.5rem;margin:0.75rem 0 1.5rem;">
  <span style="display:inline-flex;align-items:center;gap:0.35rem;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #FECACA;background:#FEE2E2;font-size:11px;color:#991B1B;font-weight:500;"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M19 8C20.6569 8 22 6.65685 22 5C22 3.34315 20.6569 2 19 2C17.3431 2 16 3.34315 16 5C16 6.65685 17.3431 8 19 8Z" stroke="#991B1B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14.02 2.2C13.36 2.07 12.69 2 12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 11.32 21.93 10.65 21.8 10.01" stroke="#991B1B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg> Alta</span>
  <span style="display:inline-flex;align-items:center;gap:0.35rem;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #FDE68A;background:#FEF3C7;font-size:11px;color:#92400E;font-weight:500;"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M19 8C20.6569 8 22 6.65685 22 5C22 3.34315 20.6569 2 19 2C17.3431 2 16 3.34315 16 5C16 6.65685 17.3431 8 19 8Z" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14.02 2.2C13.36 2.07 12.69 2 12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 11.32 21.93 10.65 21.8 10.01" stroke="#92400E" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg> Media</span>
  <span style="display:inline-flex;align-items:center;gap:0.35rem;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:11px;color:#065F46;font-weight:500;"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M19 8C20.6569 8 22 6.65685 22 5C22 3.34315 20.6569 2 19 2C17.3431 2 16 3.34315 16 5C16 6.65685 17.3431 8 19 8Z" stroke="#065F46" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14.02 2.2C13.36 2.07 12.69 2 12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 11.32 21.93 10.65 21.8 10.01" stroke="#065F46" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg> Baja</span>
</div>

### Categoría

<div style="display:flex;flex-wrap:wrap;gap:0.5rem;margin:0.75rem 0 1.5rem;">
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #BFDBFE;background:#DBEAFE;font-size:11px;color:#1E40AF;font-weight:500;">Materia Prima</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:11px;color:#065F46;font-weight:500;">Servicios</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #DDD6FE;background:#EDE9FE;font-size:11px;color:#5B21B6;font-weight:500;">Equipos</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #FED7AA;background:#FEF3C7;font-size:11px;color:#92400E;font-weight:500;">Mantenimiento</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #E5E5E5;background:#F5F5F5;font-size:11px;color:#6B6B6B;font-weight:500;">Otros</span>
</div>

### Método de pago

<div style="display:flex;flex-wrap:wrap;gap:0.5rem;margin:0.75rem 0 1.5rem;">
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #BFDBFE;background:#DBEAFE;font-size:11px;color:#1E40AF;">Transferencia</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:11px;color:#065F46;">Efectivo</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #DDD6FE;background:#EDE9FE;font-size:11px;color:#5B21B6;">Cheque</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #FED7AA;background:#FEF3C7;font-size:11px;color:#92400E;">Tarjeta</span>
  <span style="font-family:'JetBrains Mono',monospace;font-size:11px;padding:0.2rem 0.5rem;border-radius:4px;background:#F5F5F5;color:#6B6B6B;border:1px solid #E5E5E5;">N/A</span>
</div>

### Semáforo de vencimiento

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:0.75rem;margin:0.75rem 0 1.5rem;">
  <div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#065F46;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#249F65;display:inline-block;"></span> Al día</p>
    <p style="font-size:11px;color:#065F46;margin:0;opacity:0.85;">Más de 7 días para vencer</p>
  </div>
  <div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#92400E;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#F59E0B;display:inline-block;"></span> Próximo</p>
    <p style="font-size:11px;color:#92400E;margin:0;opacity:0.85;">Entre 4 y 7 días para vencer</p>
  </div>
  <div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#DC2626;display:inline-block;"></span> Urgente</p>
    <p style="font-size:11px;color:#991B1B;margin:0;opacity:0.85;">Vence hoy o en menos de 3 días</p>
  </div>
  <div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#7F1D1D;display:inline-block;"></span> Vencido</p>
    <p style="font-size:11px;color:#991B1B;margin:0;opacity:0.85;">Ya superó la fecha de vencimiento</p>
  </div>
  <div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#6B6B6B;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#6B6B6B;display:inline-block;"></span> Pagado</p>
    <p style="font-size:11px;color:#6B6B6B;margin:0;opacity:0.85;">Obligación completamente saldada</p>
  </div>
</div>

### Monto por cuenta

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;margin:0.75rem 0 1.5rem;">
  <div style="display:flex;flex-wrap:wrap;gap:1.5rem;align-items:center;">
    <div>
      <p style="font-size:11px;color:#6B6B6B;margin:0 0 0.2rem;text-transform:uppercase;letter-spacing:0.05em;">Total</p>
      <p style="font-size:16px;font-weight:600;color:#121212;margin:0;font-family:'Inter',sans-serif;">S/ 5,200.00</p>
    </div>
    <div>
      <p style="font-size:11px;color:#6B6B6B;margin:0 0 0.2rem;text-transform:uppercase;letter-spacing:0.05em;">Pendiente</p>
      <p style="font-size:16px;font-weight:600;color:#DC2626;margin:0;font-family:'Inter',sans-serif;">S/ 3,100.00</p>
    </div>
    <div>
      <p style="font-size:11px;color:#6B6B6B;margin:0 0 0.2rem;text-transform:uppercase;letter-spacing:0.05em;">Pagado</p>
      <p style="font-size:16px;font-weight:600;color:#249F65;margin:0;font-family:'Inter',sans-serif;">40% ↑</p>
    </div>
  </div>
</div>

---

## Acciones por registro

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:0.75rem;margin:1rem 0;">
  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;display:flex;align-items:flex-start;gap:0.75rem;">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="flex-shrink:0;margin-top:0.15rem;"><path d="M15.58 11.9999C15.58 13.9799 13.98 15.5799 12 15.5799C10.02 15.5799 8.42004 13.9799 8.42004 11.9999C8.42004 10.0199 10.02 8.41992 12 8.41992C13.98 8.41992 15.58 10.0199 15.58 11.9999Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M12 20.2707C15.53 20.2707 18.82 18.1907 21.11 14.5907C22.01 13.1807 22.01 10.8107 21.11 9.4007C18.82 5.8007 15.53 3.7207 12 3.7207C8.46997 3.7207 5.17997 5.8007 2.88997 9.4007C1.98997 10.8107 1.98997 13.1807 2.88997 14.5907C5.17997 18.1907 8.46997 20.2707 12 20.2707Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>
    <div>
      <p style="font-size:13px;font-weight:500;color:#121212;margin:0 0 0.2rem;">Ver detalle</p>
      <p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Modal con información completa de la cuenta por pagar.</p>
    </div>
  </div>
  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;display:flex;align-items:flex-start;gap:0.75rem;">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="flex-shrink:0;margin-top:0.15rem;"><path d='M20.5 11.3V7.04001C20.5 3.01001 19.56 2 15.78 2H8.22C4.44 2 3.5 3.01 3.5 7.04V18.3C3.5 20.96 4.96001 21.59 6.73001 19.69L6.73999 19.68C7.55999 18.81 8.80999 18.88 9.51999 19.83L10.53 21.18' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M8 7H16' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M9 11H15' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M18.211 14.7703L14.671 18.3103C14.531 18.4503 14.401 18.7103 14.371 18.9003L14.181 20.2503C14.111 20.7403 14.451 21.0803 14.941 21.0103L16.291 20.8203C16.481 20.7903 16.751 20.6603 16.881 20.5203L20.421 16.9803C21.031 16.3703 21.321 15.6603 20.421 14.7603C19.531 13.8703 18.821 14.1603 18.211 14.7703Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M17.6992 15.2803C17.9992 16.3603 18.8392 17.2003 19.9192 17.5003' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/></svg>
    <div>
      <p style="font-size:13px;font-weight:500;color:#121212;margin:0 0 0.2rem;">Editar</p>
      <p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Modal con todos los campos modificables. Cambios se guardan al confirmar.</p>
    </div>
  </div>
</div>

<alert type="warning">
  Las cuentas con vencimiento en menos de 3 días o ya vencidas aparecen marcadas en rojo — revísalas con prioridad para evitar penalidades con proveedores.
</alert>