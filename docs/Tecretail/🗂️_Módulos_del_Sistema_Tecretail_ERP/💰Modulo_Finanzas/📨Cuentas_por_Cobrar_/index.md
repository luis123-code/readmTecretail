<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Módulo de Finanzas · Submódulo</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Control de todos los cobros pendientes con clientes.</span>

<p style="font-size:14px;color:#6B6B6B;line-height:1.7;max-width:680px;">Registra, edita y da seguimiento a facturas por cobrar con semáforo de días vencidos, gestor de cobro asignado y estado de pago. Muestra el saldo pendiente vs. cobrado y alerta sobre vencimientos próximos o ya vencidos.</p>

<div style="display:flex;gap:0.5rem;flex-wrap:wrap;margin:1.25rem 0;">
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">Días vencidos</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">Gestor asignado</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">PEN · USD</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">Saldo pendiente</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #249F65;background:#E8F5EE;font-size:11px;color:#115233;">● Activo</span>
</div>

---

## Funcionalidades

<Cards>
  <Card title="Registro de cuenta" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M22 6V8.42C22 10 21 11 19.42 11H16V4.01C16 2.9 16.91 2 18.02 2C19.11 2.01 20.11 2.45 20.83 3.17C21.55 3.9 22 4.9 22 6Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M2 7V21C2 21.83 2.94001 22.3 3.60001 21.8L5.31 20.52C5.71 20.22 6.27 20.26 6.63 20.62L8.28999 22.29C8.67999 22.68 9.32001 22.68 9.71001 22.29L11.39 20.61C11.74 20.26 12.3 20.22 12.69 20.52L14.4 21.8C15.06 22.29 16 21.82 16 21V4C16 2.9 16.9 2 18 2H7H6C3 2 2 3.79 2 6V7Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M6.25 10H11.75' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M9 12.75V7.25' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Cliente, Monto, Vencimiento">
    Registra una nueva cuenta por cobrar con cliente, concepto, monto, moneda, fechas de emisión y vencimiento, gestor de cobro asignado, categoría y método de cobro.
  </Card>
  <Card title="Seguimiento de saldo" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M8.57007 15.2704L15.11 8.73047' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M8.98001 10.3701C9.65932 10.3701 10.21 9.81948 10.21 9.14017C10.21 8.46086 9.65932 7.91016 8.98001 7.91016C8.3007 7.91016 7.75 8.46086 7.75 9.14017C7.75 9.81948 8.3007 10.3701 8.98001 10.3701Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M15.52 16.0899C16.1993 16.0899 16.75 15.5392 16.75 14.8599C16.75 14.1806 16.1993 13.6299 15.52 13.6299C14.8407 13.6299 14.29 14.1806 14.29 14.8599C14.29 15.5392 14.8407 16.0899 15.52 16.0899Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Pendiente, Cobrado, Porcentaje">
    Visualiza el monto total, saldo pendiente en rojo y porcentaje cobrado en verde por cada cuenta. Balance actualizado en tiempo real.
  </Card>
  <Card title="Semáforo de días vencidos" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M12 14C13.1046 14 14 13.1046 14 12C14 10.8954 13.1046 10 12 10C10.8954 10 10 10.8954 10 12C10 13.1046 10.8954 14 12 14Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M20 18C21.26 16.33 22 14.25 22 12C22 9.75 21.26 7.67 20 6' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M4 6C2.74 7.67 2 9.75 2 12C2 14.25 2.74 16.33 4 18' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M16.8 15.6004C17.55 14.6004 18.0001 13.3504 18.0001 12.0004C18.0001 10.6504 17.55 9.40039 16.8 8.40039' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M7.20001 8.40039C6.45001 9.40039 6 10.6504 6 12.0004C6 13.3504 6.45001 14.6004 7.20001 15.6004' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Al día, 30d, 60d, +60d">
    Indicador automático por días transcurridos desde el vencimiento. Escala de verde a rojo según la antigüedad de la deuda.
  </Card>
  <Card title="Gestor de cobro" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M10.49 2.23055L5.50003 4.10054C4.35003 4.53054 3.41003 5.89053 3.41003 7.12053V14.5505C3.41003 15.7305 4.19005 17.2805 5.14005 17.9905L9.44003 21.2005C10.85 22.2605 13.17 22.2605 14.58 21.2005L18.88 17.9905C19.83 17.2805 20.61 15.7305 20.61 14.5505V7.12053C20.61 5.89053 19.67 4.53054 18.52 4.10054L13.53 2.23055C12.68 1.92055 11.32 1.92055 10.49 2.23055Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M12.0001 10.9204C11.9601 10.9204 11.9101 10.9204 11.8701 10.9204C10.9301 10.8904 10.1801 10.1104 10.1801 9.1604C10.1801 8.1904 10.9701 7.40039 11.9401 7.40039C12.9101 7.40039 13.7001 8.1904 13.7001 9.1604C13.6901 10.1204 12.9401 10.8904 12.0001 10.9204Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M10.01 13.7213C9.05004 14.3613 9.05004 15.4113 10.01 16.0513C11.1 16.7813 12.89 16.7813 13.98 16.0513C14.94 15.4113 14.94 14.3613 13.98 13.7213C12.9 12.9913 11.11 12.9913 10.01 13.7213Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Asignación, Responsable, Seguimiento">
    Asigna un gestor responsable por cada cuenta. Permite filtrar y hacer seguimiento por gestor para una cobranza más organizada.
  </Card>
</Cards>

---

## Indicadores visuales

### Semáforo de días vencidos

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(175px,1fr));gap:0.75rem;margin:0.75rem 0 1.5rem;">
  <div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#065F46;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#249F65;display:inline-block;"></span> Al día</p>
    <p style="font-size:11px;color:#065F46;margin:0;opacity:0.85;">Sin días vencidos</p>
  </div>
  <div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#92400E;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#F59E0B;display:inline-block;"></span> Leve</p>
    <p style="font-size:11px;color:#92400E;margin:0;opacity:0.85;">1 – 30 días vencido</p>
  </div>
  <div style="background:#FEF3C7;border:1px solid #FED7AA;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#C2410C;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#F97316;display:inline-block;"></span> Moderado</p>
    <p style="font-size:11px;color:#C2410C;margin:0;opacity:0.85;">31 – 60 días vencido</p>
  </div>
  <div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#991B1B;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#DC2626;display:inline-block;"></span> Crítico</p>
    <p style="font-size:11px;color:#991B1B;margin:0;opacity:0.85;">Más de 60 días vencido</p>
  </div>
  <div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
    <p style="font-size:12px;font-weight:600;color:#6B6B6B;margin:0 0 0.25rem;display:flex;align-items:center;gap:0.4rem;"><span style="width:8px;height:8px;border-radius:50%;background:#6B6B6B;display:inline-block;"></span> Cobrado</p>
    <p style="font-size:11px;color:#6B6B6B;margin:0;opacity:0.85;">Cuenta saldada en su totalidad</p>
  </div>
</div>

### Estado de la cuenta

<div style="display:flex;flex-wrap:wrap;gap:0.5rem;margin:0.75rem 0 1.5rem;">
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #FDE68A;background:#FEF3C7;font-size:11px;color:#92400E;font-weight:500;">Pendiente</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #FED7AA;background:#FFEDD5;font-size:11px;color:#C2410C;font-weight:500;">Cobrado Parcial</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:11px;color:#065F46;font-weight:500;">Cobrado Total</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #FECACA;background:#FEE2E2;font-size:11px;color:#991B1B;font-weight:500;">Vencido</span>
</div>

### Método de cobro

<div style="display:flex;flex-wrap:wrap;gap:0.5rem;margin:0.75rem 0 1.5rem;">
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #BFDBFE;background:#DBEAFE;font-size:11px;color:#1E40AF;">Transferencia</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:11px;color:#065F46;">Efectivo</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #DDD6FE;background:#EDE9FE;font-size:11px;color:#5B21B6;">Cheque</span>
  <span style="display:inline-flex;align-items:center;padding:0.2rem 0.6rem;border-radius:9999px;border:1px solid #FED7AA;background:#FEF3C7;font-size:11px;color:#92400E;">Tarjeta</span>
  <span style="font-family:'JetBrains Mono',monospace;font-size:11px;padding:0.2rem 0.5rem;border-radius:4px;background:#F5F5F5;color:#6B6B6B;border:1px solid #E5E5E5;">N/A</span>
</div>

### Monto por cuenta

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;margin:0.75rem 0 1.5rem;">
  <div style="display:flex;flex-wrap:wrap;gap:1.5rem;align-items:center;">
    <div>
      <p style="font-size:11px;color:#6B6B6B;margin:0 0 0.2rem;text-transform:uppercase;letter-spacing:0.05em;">Total</p>
      <p style="font-size:16px;font-weight:600;color:#121212;margin:0;font-family:'Inter',sans-serif;">S/ 8,400.00</p>
    </div>
    <div>
      <p style="font-size:11px;color:#6B6B6B;margin:0 0 0.2rem;text-transform:uppercase;letter-spacing:0.05em;">Pendiente</p>
      <p style="font-size:16px;font-weight:600;color:#DC2626;margin:0;font-family:'Inter',sans-serif;">S/ 5,040.00</p>
    </div>
    <div>
      <p style="font-size:11px;color:#6B6B6B;margin:0 0 0.2rem;text-transform:uppercase;letter-spacing:0.05em;">Cobrado</p>
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
      <p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Modal con información completa de la cuenta por cobrar.</p>
    </div>
  </div>
  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;display:flex;align-items:flex-start;gap:0.75rem;">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="flex-shrink:0;margin-top:0.15rem;"><path d='M20.5 11.3V7.04001C20.5 3.01001 19.56 2 15.78 2H8.22C4.44 2 3.5 3.01 3.5 7.04V18.3C3.5 20.96 4.96001 21.59 6.73001 19.69L6.73999 19.68C7.55999 18.81 8.80999 18.88 9.51999 19.83L10.53 21.18' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M8 7H16' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M9 11H15' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M18.211 14.7703L14.671 18.3103C14.531 18.4503 14.401 18.7103 14.371 18.9003L14.181 20.2503C14.111 20.7403 14.451 21.0803 14.941 21.0103L16.291 20.8203C16.481 20.7903 16.751 20.6603 16.881 20.5203L20.421 16.9803C21.031 16.3703 21.321 15.6603 20.421 14.7603C19.531 13.8703 18.821 14.1603 18.211 14.7703Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M17.6992 15.2803C17.9992 16.3603 18.8392 17.2003 19.9192 17.5003' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/></svg>
    <div>
      <p style="font-size:13px;font-weight:500;color:#121212;margin:0 0 0.2rem;">Editar</p>
      <p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Modal con todos los campos modificables. Cambios se guardan al confirmar.</p>
    </div>
  </div>
  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;display:flex;align-items:flex-start;gap:0.75rem;">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="flex-shrink:0;margin-top:0.15rem;"><path d='M10.49 2.23055L5.50003 4.10054C4.35003 4.53054 3.41003 5.89053 3.41003 7.12053V14.5505C3.41003 15.7305 4.19005 17.2805 5.14005 17.9905L9.44003 21.2005C10.85 22.2605 13.17 22.2605 14.58 21.2005L18.88 17.9905C19.83 17.2805 20.61 15.7305 20.61 14.5505V7.12053C20.61 5.89053 19.67 4.53054 18.52 4.10054L13.53 2.23055C12.68 1.92055 11.32 1.92055 10.49 2.23055Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M12.0001 10.9204C11.9601 10.9204 11.9101 10.9204 11.8701 10.9204C10.9301 10.8904 10.1801 10.1104 10.1801 9.1604C10.1801 8.1904 10.9701 7.40039 11.9401 7.40039C12.9101 7.40039 13.7001 8.1904 13.7001 9.1604C13.6901 10.1204 12.9401 10.8904 12.0001 10.9204Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M10.01 13.7213C9.05004 14.3613 9.05004 15.4113 10.01 16.0513C11.1 16.7813 12.89 16.7813 13.98 16.0513C14.94 15.4113 14.94 14.3613 13.98 13.7213C12.9 12.9913 11.11 12.9913 10.01 13.7213Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>
    <div>
      <p style="font-size:13px;font-weight:500;color:#121212;margin:0 0 0.2rem;">Gestor asignado</p>
      <p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Reasigna el responsable de cobro directamente desde la tabla.</p>
    </div>
  </div>
</div>

<alert type="warning">
  Las cuentas con más de 60 días vencidos se marcan en <span style="color:#DC2626;font-weight:500;">rojo crítico</span> — asigna un gestor y prioriza su cobro para reducir la cartera morosa.
</alert>