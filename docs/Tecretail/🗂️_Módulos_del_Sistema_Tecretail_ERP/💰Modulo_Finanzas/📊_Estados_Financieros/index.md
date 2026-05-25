<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Módulo de Finanzas · Submódulo</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Estado de resultados mensual con datos automáticos y campos manuales combinados.</span>

<p style="font-size:14px;color:#6B6B6B;line-height:1.7;max-width:680px;">Visualiza ingresos, gastos operativos, financieros y extraordinarios para calcular la utilidad neta del período. Soporta monedas PEN y USD, y permite guardar y cargar el estado financiero por mes y año.</p>

<div style="display:flex;gap:0.5rem;flex-wrap:wrap;margin:1.25rem 0;">
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">PEN · USD</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">Datos automáticos</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">Campos manuales</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #E5E5E5;background:#fff;font-size:11px;color:#6B6B6B;">Por mes · año</span>
  <span style="display:inline-flex;align-items:center;padding:0.125rem 0.5rem;border-radius:9999px;border:1px solid #249F65;background:#E8F5EE;font-size:11px;color:#115233;">● Activo</span>
</div>

---

## Funcionalidades

<Cards>
  <Card title="Selección de período" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M8 2V5' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M16 2V5' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M3.5 9.08984H20.5' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M21 8.5V17C21 20 19.5 22 16 22H8C4.5 22 3 20 3 17V8.5C3 5.5 4.5 3.5 8 3.5H16C19.5 3.5 21 5.5 21 8.5Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M11.9955 13.6992H12.0045' stroke='#121212' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'/><path d='M8.29431 13.6992H8.30329' stroke='#121212' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'/><path d='M8.29431 16.6992H8.30329' stroke='#121212' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Mes, Año, PEN, USD">
    Selecciona el mes, año y moneda del estado a consultar o crear. El sistema carga automáticamente los datos del período desde los movimientos financieros registrados.
  </Card>
  <Card title="Datos automáticos" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M12.0001 7.89062L10.9301 9.75063C10.6901 10.1606 10.8901 10.5006 11.3601 10.5006H12.6301C13.1101 10.5006 13.3001 10.8406 13.0601 11.2506L12.0001 13.1106' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M8.29999 18.0402V16.8802C5.99999 15.4902 4.10999 12.7802 4.10999 9.90018C4.10999 4.95018 8.65999 1.07018 13.8 2.19018C16.06 2.69018 18.04 4.19018 19.07 6.26018C21.16 10.4602 18.96 14.9202 15.73 16.8702V18.0302C15.73 18.3202 15.84 18.9902 14.77 18.9902H9.25999C8.15999 19.0002 8.29999 18.5702 8.29999 18.0402Z' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/><path d='M8.5 21.9992C10.79 21.3492 13.21 21.3492 15.5 21.9992' stroke='#121212' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Movimientos, Sin doble ingreso">
    Los ingresos y gastos se jalan automáticamente desde los movimientos financieros — sin necesidad de ingreso manual duplicado.
  </Card>
  <Card title="Listado de estados" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M5 10H7C9 10 10 9 10 7V5C10 3 9 2 7 2H5C3 2 2 3 2 5V7C2 9 3 10 5 10Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M17 10H19C21 10 22 9 22 7V5C22 3 21 2 19 2H17C15 2 14 3 14 5V7C14 9 15 10 17 10Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M17 22H19C21 22 22 21 22 19V17C22 15 21 14 19 14H17C15 14 14 15 14 17V19C14 21 15 22 17 22Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M5 22H7C9 22 10 21 10 19V17C10 15 9 14 7 14H5C3 14 2 15 2 17V19C2 21 3 22 5 22Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Tarjetas, Ventas, Utilidad">
    Visualiza todos los estados registrados en formato de tarjetas con nombre, tipo, moneda, ventas netas, utilidad bruta, utilidad neta, fecha y usuario responsable.
  </Card>
  <Card title="Acciones por estado" icon="<svg width='28' height='28' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'><path d='M12 15C13.6569 15 15 13.6569 15 12C15 10.3431 13.6569 9 12 9C10.3431 9 9 10.3431 9 12C9 13.6569 10.3431 15 12 15Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/><path d='M2 12.8801V11.1201C2 10.0801 2.85 9.22006 3.9 9.22006C5.71 9.22006 6.45 7.94006 5.59 6.37006C5.11 5.47006 5.42 4.34006 6.29 3.86006L7.06 3.44006C7.85 3.00006 8.85 3.28006 9.31 4.07006L9.4 4.23006C10.25 5.80006 11.75 5.80006 12.61 4.23006L12.7 4.07006C13.16 3.28006 14.16 3.00006 14.95 3.44006L15.72 3.86006C16.59 4.34006 16.9 5.47006 16.42 6.37006C15.56 7.94006 16.3 9.22006 18.11 9.22006C19.15 9.22006 20.01 10.0701 20.01 11.1201V12.8801C20.01 13.9201 19.16 14.7801 18.11 14.7801C16.3 14.7801 15.56 16.0601 16.42 17.6301C16.9 18.5401 16.59 19.6601 15.72 20.1401L14.95 20.5601C14.16 21.0001 13.16 20.7201 12.7 19.9301L12.61 19.7701C11.76 18.2001 10.26 18.2001 9.4 19.7701L9.31 19.9301C8.85 20.7201 7.85 21.0001 7.06 20.5601L6.29 20.1401C5.42 19.6601 5.11 18.5301 5.59 17.6301C6.45 16.0601 5.71 14.7801 3.9 14.7801C2.85 14.7801 2 13.9201 2 12.8801Z' stroke='#121212' stroke-width='1.5' stroke-miterlimit='10' stroke-linecap='round' stroke-linejoin='round'/></svg>" href="#" tags="Editar, Duplicar, Nuevo">
    Edita un estado existente o duplícalo como base para uno nuevo. Botón "Nuevo Estado" para crear desde cero el estado del período.
  </Card>
</Cards>

---

## Estructura del estado de resultados

<span style="font-size:13px;color:#6B6B6B;line-height:1.7;display:block;margin-bottom:1rem;">Los datos se organizan en cuatro categorías — las marcadas con <span style="display:inline-flex;align-items:center;padding:0.1rem 0.4rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:10px;color:#065F46;">auto</span> se cargan desde movimientos.</span>

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:0.75rem;margin:1rem 0;">

  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:0.75rem;">
      <p style="font-size:13px;font-weight:600;color:#249F65;margin:0;"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="vertical-align:middle;margin-right:0.3rem;"><path d="M19.3 7.91949V13.0695C19.3 16.1495 17.54 17.4695 14.9 17.4695H6.10995C5.65995 17.4695 5.22996 17.4295 4.82996 17.3395C4.57996 17.2995 4.33996 17.2295 4.11996 17.1495C2.61996 16.5895 1.70996 15.2895 1.70996 13.0695V7.91949C1.70996 4.83949 3.46995 3.51953 6.10995 3.51953H14.9C17.14 3.51953 18.75 4.46953 19.18 6.63953C19.25 7.03953 19.3 7.44949 19.3 7.91949Z" stroke="#249F65" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M22.3011 10.9196V16.0696C22.3011 19.1496 20.5411 20.4696 17.9011 20.4696H9.11105C8.37105 20.4696 7.70106 20.3697 7.12106 20.1497C5.93106 19.7097 5.12105 18.7997 4.83105 17.3397C5.23105 17.4297 5.66105 17.4696 6.11105 17.4696H14.9011C17.5411 17.4696 19.3011 16.1496 19.3011 13.0696V7.91962C19.3011 7.44962 19.2611 7.02965 19.1811 6.63965C21.0811 7.03965 22.3011 8.37962 22.3011 10.9196Z" stroke="#249F65" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M10.4984 13.1394C11.9564 13.1394 13.1384 11.9574 13.1384 10.4994C13.1384 9.04136 11.9564 7.85938 10.4984 7.85938C9.04038 7.85938 7.8584 9.04136 7.8584 10.4994C7.8584 11.9574 9.04038 13.1394 10.4984 13.1394Z" stroke="#249F65" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M4.78003 8.2998V12.6998" stroke="#249F65" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M16.2217 8.2998V12.6998" stroke="#249F65" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/></svg> Ingresos</p>
      <span style="display:inline-flex;align-items:center;padding:0.1rem 0.4rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:10px;color:#065F46;">auto</span>
    </div>
    <div style="display:flex;flex-direction:column;gap:0.3rem;">
      <span style="font-size:12px;color:#6B6B6B;">· Suscripciones</span>
      <span style="font-size:12px;color:#6B6B6B;">· Implementación</span>
      <span style="font-size:12px;color:#6B6B6B;">· Capacitación</span>
      <span style="font-size:12px;color:#6B6B6B;">· Soporte</span>
      <span style="font-size:12px;color:#6B6B6B;">· Consultoría</span>
    </div>
  </div>

  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:0.75rem;">
      <p style="font-size:13px;font-weight:600;color:#F59E0B;margin:0;"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="vertical-align:middle;margin-right:0.3rem;"><path d="M12 6.43945V9.76945" stroke="#F59E0B" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round"/><path d="M12.02 2C8.34002 2 5.36002 4.98 5.36002 8.66V10.76C5.36002 11.44 5.08002 12.46 4.73002 13.04L3.46002 15.16C2.68002 16.47 3.22002 17.93 4.66002 18.41C9.44002 20 14.61 20 19.39 18.41C20.74 17.96 21.32 16.38 20.59 15.16L19.32 13.04C18.97 12.46 18.69 11.43 18.69 10.76V8.66C18.68 5 15.68 2 12.02 2Z" stroke="#F59E0B" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round"/><path d="M15.33 18.8203C15.33 20.6503 13.83 22.1503 12 22.1503C11.09 22.1503 10.25 21.7703 9.65004 21.1703C9.05004 20.5703 8.67004 19.7303 8.67004 18.8203" stroke="#F59E0B" stroke-width="1.5" stroke-miterlimit="10"/></svg> Gastos de Ventas</p>
      <span style="display:inline-flex;align-items:center;padding:0.1rem 0.4rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:10px;color:#065F46;">auto</span>
    </div>
    <div style="display:flex;flex-direction:column;gap:0.3rem;">
      <span style="font-size:12px;color:#6B6B6B;">· Marketing</span>
      <span style="font-size:12px;color:#6B6B6B;">· Publicidad</span>
    </div>
  </div>

  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:0.75rem;">
      <p style="font-size:13px;font-weight:600;color:#3B82F6;margin:0;"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="vertical-align:middle;margin-right:0.3rem;"><path d="M22 21.4502H2" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M19.4902 18.4502V21.4502" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M22 13.9502C22 12.5695 20.8807 11.4502 19.5 11.4502C18.1193 11.4502 17 12.5695 17 13.9502V15.9502C17 17.3309 18.1193 18.4502 19.5 18.4502C20.8807 18.4502 22 17.3309 22 15.9502V13.9502Z" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 4.4502H11C11.55 4.4502 12 4.9002 12 5.4502V7.4502H8V5.4502C8 4.9002 8.45 4.4502 9 4.4502Z" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M10 2.4502V4.4502" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M6 21.4502V8.4502C6 7.9002 6.45 7.4502 7 7.4502H13C13.55 7.4502 14 7.9002 14 8.4502V21.4502" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M8.5 16.4502H11.5" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M8.5 13.4502H11.5" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M8.5 10.4502H11.5" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M10 19.9502V21.4502" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M6 13.4502H4C3.45 13.4502 3 13.9002 3 14.4502V21.4502" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg> Gastos Administrativos</p>
      <span style="display:inline-flex;align-items:center;padding:0.1rem 0.4rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:10px;color:#065F46;">auto</span>
    </div>
    <div style="display:flex;flex-direction:column;gap:0.3rem;">
      <span style="font-size:12px;color:#6B6B6B;">· Alquiler</span>
      <span style="font-size:12px;color:#6B6B6B;">· Servicios básicos</span>
      <span style="font-size:12px;color:#6B6B6B;">· Sueldos administrativos</span>
    </div>
  </div>

  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1.25rem;">
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:0.75rem;">
      <p style="font-size:13px;font-weight:600;color:#5B21B6;margin:0;"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="vertical-align:middle;margin-right:0.3rem;"><path d="M12 15C13.6569 15 15 13.6569 15 12C15 10.3431 13.6569 9 12 9C10.3431 9 9 10.3431 9 12C9 13.6569 10.3431 15 12 15Z" stroke="#5B21B6" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M2.90997 17.2502C2.74997 16.3502 2.66997 15.3502 2.66997 14.2802C2.66997 11.5902 3.68997 9.17024 5.39997 7.39024C7.10997 5.61024 9.32997 4.66024 11.8399 4.64024" stroke="#5B21B6" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M21.0901 6.75C21.2501 7.65 21.3301 8.65 21.3301 9.72C21.3301 12.41 20.3101 14.83 18.6001 16.61C16.8901 18.39 14.6701 19.34 12.1601 19.36" stroke="#5B21B6" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M9.00006 22H15.0001C20.0201 22 21.9801 20.24 22.0501 15.43L22.2001 9.53C22.2801 5.28 20.7201 3.27 17.5301 2.71" stroke="#5B21B6" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M7.96998 2.69995C4.75998 3.26995 3.15998 5.31995 3.28998 9.54995L3.49998 15.4199C3.61998 20.1799 5.54998 21.9399 10.38 21.9399H14.42" stroke="#5B21B6" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M16 11V13" stroke="#5B21B6" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/><path d="M8 11V13" stroke="#5B21B6" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/></svg> Gastos Operacionales</p>
      <span style="display:inline-flex;align-items:center;padding:0.1rem 0.4rem;border-radius:9999px;border:1px solid #A7F3D0;background:#D1FAE5;font-size:10px;color:#065F46;">auto</span>
    </div>
    <div style="display:flex;flex-direction:column;gap:0.3rem;">
      <span style="font-size:12px;color:#6B6B6B;">· Software · Nómina</span>
      <span style="font-size:12px;color:#6B6B6B;">· Internet · Luz</span>
      <span style="font-size:12px;color:#6B6B6B;">· Figma · Google Workspace</span>
      <span style="font-size:12px;color:#6B6B6B;">· Digital Ocean · Google Cloud</span>
    </div>
  </div>

</div>

---

## Indicadores de utilidad

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:0.75rem;margin:1rem 0;">
  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:1rem;padding:1.25rem;">
    <p style="font-size:11px;font-weight:500;color:#6B6B6B;text-transform:uppercase;letter-spacing:0.06em;margin:0 0 0.5rem;">Ventas Netas</p>
    <p style="font-size:22px;font-weight:600;color:#121212;letter-spacing:-0.03em;margin:0;font-family:'Inter',sans-serif;">S/ —</p>
    <p style="font-size:11px;color:#6B6B6B;margin:0.25rem 0 0;">Total ingresos del período</p>
  </div>
  <div style="background:#fff;border:1px solid #E5E5E5;border-radius:1rem;padding:1.25rem;">
    <p style="font-size:11px;font-weight:500;color:#6B6B6B;text-transform:uppercase;letter-spacing:0.06em;margin:0 0 0.5rem;">Utilidad Bruta</p>
    <p style="font-size:22px;font-weight:600;color:#121212;letter-spacing:-0.03em;margin:0;font-family:'Inter',sans-serif;">S/ —</p>
    <p style="font-size:11px;color:#6B6B6B;margin:0.25rem 0 0;">Ventas − Costo de ventas</p>
  </div>
  <div style="background:#D1FAE5;border:1px solid #A7F3D0;border-radius:1rem;padding:1.25rem;">
    <p style="font-size:11px;font-weight:500;color:#065F46;text-transform:uppercase;letter-spacing:0.06em;margin:0 0 0.5rem;">Utilidad Neta ↑</p>
    <p style="font-size:22px;font-weight:600;color:#249F65;letter-spacing:-0.03em;margin:0;font-family:'Inter',sans-serif;">S/ —</p>
    <p style="font-size:11px;color:#065F46;margin:0.25rem 0 0;">Período cerró con ganancia</p>
  </div>
  <div style="background:#FEE2E2;border:1px solid #FECACA;border-radius:1rem;padding:1.25rem;">
    <p style="font-size:11px;font-weight:500;color:#991B1B;text-transform:uppercase;letter-spacing:0.06em;margin:0 0 0.5rem;">Utilidad Neta ↓</p>
    <p style="font-size:22px;font-weight:600;color:#DC2626;letter-spacing:-0.03em;margin:0;font-family:'Inter',sans-serif;">−S/ —</p>
    <p style="font-size:11px;color:#991B1B;margin:0.25rem 0 0;">Período cerró con pérdida</p>
  </div>
</div>

<alert type="success">
  Los datos de movimientos financieros alimentan automáticamente cada categoría del estado de resultados — sin doble ingreso y siempre actualizados al período seleccionado.
</alert>