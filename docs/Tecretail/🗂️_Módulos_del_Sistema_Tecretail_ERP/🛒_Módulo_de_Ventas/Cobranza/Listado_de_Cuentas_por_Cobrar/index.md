<span style="font-size:12px;font-weight:500;color:#249F65;text-transform:uppercase;letter-spacing:0.08em;">Cuentas por Cobrar · Vista Principal</span>

<span style="font-family:'Cormorant Garamond',Georgia,serif;font-style:italic;font-size:18px;color:#6B6B6B;line-height:1.6;display:block;margin-bottom:1.25rem;">Tabla principal con múltiples vistas (todas, por cliente, por vendedor) para gestión de deudas pendientes. Soporta hasta 1000 registros sin paginación, con paneles laterales de métricas y filtros avanzados por fechas y estados.</span>

<alert type="info">
  A diferencia de otros módulos, este <strong>no tiene paginación</strong> y carga hasta <strong>1000 registros</strong> de una vez. Las <strong>3 vistas</strong> (all/client/vendedor) se adaptan a diferentes necesidades de gestión. Los <strong>estados se calculan automáticamente</strong> según los pagos, pero pueden cambiarse manualmente con confirmación.
</alert>

---

## Información del Listado

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Datos de la cuenta</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Código:</span> Identificador único</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Concepto:</span> "Venta de productos", "Servicio X"</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Monto:</span> Total de la cuenta</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Saldo Pagado:</span> Ya cancelado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Por Cobrar:</span> Monto - Saldo Pagado</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Datos de orden y documentos</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Orden de Venta:</span> Número relacionado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Estado OV:</span> completada, enviada, etc.</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Facturas/Boletas:</span> Enlaces a documentos fiscales</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Fechas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Fecha Emisión:</span> Cuándo se creó</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Fecha Vencimiento:</span> Cuándo vence el pago</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Datos del cliente</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Cliente:</span> Nombre</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="font-weight:500;color:#121212;">Contacto:</span> Información</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estado CxC</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="background:#6B6B6B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Pendiente</span> Sin pagos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="background:#F59E0B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Parcial</span> Pagos parciales</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="background:#22C55E;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Total</span> Pagada completamente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Vencido</span> Fecha vencimiento pasó</p>
</div>
</div>

</div>
</div>

---

## Vistas Disponibles

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Vista "all" (Todas)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Todas las cuentas <strong>sin agrupación</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Vista general <strong>completa</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Sin</strong> paneles laterales</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar:</strong> panorama general, revisiones, auditorías.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Vista "client" (Por Cliente)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Panel lateral con <strong>lista de clientes</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cada cliente: Total monto, pagado, por cobrar, cantidad cuentas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Búsqueda</strong> por nombre de cliente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Ordenamiento</strong> por cantidad, montos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Indicador</strong> de cuentas vencidas</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar:</strong> cuentas de cliente específico, cobranza por cliente, identificar deudas.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Vista "vendedor" (Por Vendedor)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Panel lateral con <strong>lista de vendedores</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Cada vendedor: Total monto, pagado, por cobrar, cantidad cuentas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Búsqueda</strong> por nombre de vendedor</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Ordenamiento</strong> por cantidad, montos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Indicador</strong> de cuentas vencidas</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar:</strong> cuentas de vendedor específico, cobranza por vendedor, evaluar desempeño.</p>
</div>

</div>
</div>

---

## Funciones Principales

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Ver detalle de cuenta</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz <strong>clic en la fila</strong> de la cuenta</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <strong>modal</strong> con detalle completo</span></div>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>En modal:</strong> datos completos, historial de pagos, documentos relacionados, estado comprobantes.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cambiar estado</p>
<div style="display:flex;flex-direction:column;gap:0.5rem;">
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">01</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Haz <strong>clic</strong> en campo estado en tabla</span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">02</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Se abre <strong>modal de confirmación</strong></span></div>
<div style="display:flex;gap:0.75rem;align-items:flex-start;"><span style="font-family:'JetBrains Mono',monospace;font-size:10px;padding:0.1rem 0.35rem;border-radius:4px;background:#A7F3D0;color:#065F46;flex-shrink:0;">03</span><span style="font-size:12px;color:#6B6B6B;line-height:1.5;">Selecciona <strong>nuevo estado</strong> + confirma</span></div>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;">Estados: <span style="background:#6B6B6B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Pendiente</span> <span style="background:#F59E0B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Parcial</span> <span style="background:#22C55E;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Total</span> <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Vencido</span></p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Filtrar por fechas</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Fecha Emisión:</strong> Selector Desde/Hasta + Aplicar/Limpiar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Fecha Vencimiento:</strong> Selector Desde/Hasta + Aplicar/Limpiar</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar:</strong> período específico, identificar vencidas, planificar cobranza.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Filtrar por estado (selección múltiple)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Estado CxC:</strong> Dropdown con checkboxes</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0 1rem;line-height:1.5;">pendiente, cobrado_parcial, cobrado_total, vencido</p>
<p style="font-size:12px;color:#6B6B6B;margin:0.5rem 0 0;line-height:1.5;"><strong>Estado OV:</strong> Dropdown con checkboxes</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0 1rem;line-height:1.5;">completada, enviada, por_fabricar, anulada, ahorro, pendiente, por_enviar</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Usar:</strong> solo pendientes, solo vencidas, cuentas de órdenes específicas.</p>
</div>

</div>
</div>

---

## Cálculos Automáticos

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Monto Pagado</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Suma de todos los <strong>movimientos de pago</strong>. Se calcula automáticamente desde los movimientos registrados. <strong>Actualizado en tiempo real</strong>.</p>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Por Cobrar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;"><strong>Monto Total - Monto Pagado</strong>. Resta automática actualizada en tiempo real.</p>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Estado Calculado</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">Calculado según pagos:</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0 1rem;line-height:1.5;">• <span style="background:#6B6B6B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Pendiente</span> Sin pagos</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0 1rem;line-height:1.5;">• <span style="background:#F59E0B;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Parcial</span> Pagos pero no completo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0 1rem;line-height:1.5;">• <span style="background:#22C55E;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Cobrado Total</span> Pagado completamente</p>
<p style="font-size:12px;color:#6B6B6B;margin:0 0 0 1rem;line-height:1.5;">• <span style="background:#EF4444;color:#fff;font-size:10px;padding:0.15rem 0.5rem;border-radius:4px;">Vencido</span> Fecha vencimiento pasada</p>
</div>
<p style="font-size:11px;color:#86868b;margin:0.5rem 0 0;line-height:1.4;"><strong>Nota:</strong> Hay switch para <strong>lógica alternativa</strong> de cálculo (útil para diferentes criterios de negocio).</p>
</div>

</div>
</div>

---

## Diferencias con Facturas/Boletas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Cuentas por Cobrar</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Enfoque en <strong>deudas y pagos</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Estado de <strong>cobranza</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Muestra <strong>montos pagados</strong> y por cobrar</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• Relacionado con <strong>órdenes de venta</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>3 vistas:</strong> all, client, vendedor</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Paneles laterales</strong></p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">• <strong>Filtros:</strong> emisión, vencimiento, estados (CxC + OV)</p>
</div>
</div>

</div>
<div>

<div style="background:#FEF3C7;border:1px solid #FDE68A;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#92400E;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Facturas/Boletas (contraste)</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Enfoque en <strong>documentos fiscales</strong></p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Estado del <strong>documento</strong></p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Muestra <strong>monto total</strong></p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• Relacionado con <strong>ventas</strong></p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>1 vista:</strong> tabla</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Sin</strong> paneles laterales</p>
<p style="font-size:12px;color:#92400E;margin:0;line-height:1.5;">• <strong>Filtros:</strong> emisión, buscador</p>
</div>
</div>

</div>
</div>

---

## Buenas Prácticas

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;align-items:start;margin:1.25rem 0;">
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;margin-bottom:0.75rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Gestión de cobranza</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Usa vista <strong>por cliente</strong> para ver cuentas agrupadas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Filtra por <strong>vencido</strong> para identificar prioridades</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Revisa el <strong>por cobrar</strong> para saber cuánto falta</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. Usa el <strong>detalle</strong> para ver historial de pagos</p>
</div>
</div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Auditoría</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Usa vista <strong>"all"</strong> para panorama completo</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Filtra por <strong>período</strong> específico</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Revisa <strong>estados</strong> para verificar consistencia</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Verifica montos</strong> para confirmar cálculos</p>
</div>
</div>

</div>
<div>

<div style="background:#F5F5F5;border:1px solid #E5E5E5;border-radius:0.75rem;padding:1rem;">
<p style="font-size:11px;font-weight:600;color:#121212;text-transform:uppercase;letter-spacing:0.05em;margin:0 0 0.6rem;">Planificación</p>
<div style="display:flex;flex-direction:column;gap:0.3rem;">
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">1. Filtra por <strong>vencimiento</strong> para planificar cobranza futura</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">2. Usa vista <strong>por vendedor</strong> para asignar tareas</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">3. Revisa <strong>métricas</strong> de paneles laterales</p>
<p style="font-size:12px;color:#6B6B6B;margin:0;line-height:1.5;">4. <strong>Identifica vencidas</strong> para priorizar</p>
</div>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">No puedo ver el detalle</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en menú en lugar de fila</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Haz clic <strong>directamente en la fila</strong> de la cuenta. En CxC, el detalle se abre al hacer clic en la fila.</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">El estado no cambia</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">No confirmaste en modal o error al guardar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Asegúrate de <strong>confirmar</strong> en el modal. Si hay error, verifica tu conexión y reintenta.</td></tr>
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
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Ver cuenta</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en fila</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Abre modal con detalle</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Cambiar estado</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en estado + confirmar</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Estado CxC actualizado</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Filtrar fechas</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Selector fecha emisión/vencimiento</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Filtra por rango</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Filtrar estados</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Dropdown + checkboxes</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Filtra por estado CxC u OV</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Vista cliente</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Cambiar a vista "client"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Panel lateral con clientes y métricas</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Vista vendedor</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Cambiar a vista "vendedor"</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Panel lateral con vendedores y métricas</td></tr>
<tr style="border-bottom:1px solid #E5E5E5;"><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Seleccionar cliente/vendedor</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Clic en item del panel lateral</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Filtra sus cuentas</td></tr>
<tr><td style="padding:0.25rem 0.5rem;font-size:12px;font-weight:500;color:#121212;">Buscar en panel</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Campo búsqueda en panel lateral</td><td style="padding:0.25rem 0.5rem;font-size:12px;color:#6B6B6B;">Encuentra cliente o vendedor</td></tr>
</tbody>
</table>

<alert type="info">
  El listado de cuentas por cobrar es más <strong>complejo</strong> que otros módulos porque tiene <strong>múltiples vistas</strong> y <strong>paneles laterales</strong>. A diferencia de facturas/boletas, <strong>no tiene paginación</strong> y carga hasta <strong>1000 registros</strong> de una vez. Los paneles laterales son muy útiles para gestionar cobranza organizada. Los <strong>estados se calculan automáticamente</strong> según pagos, pero puedes cambiarlos manualmente con confirmación. Usa la vista que mejor se adapte: <strong>"all"</strong> para panorama general, <strong>"client"</strong> para gestión por cliente, <strong>"vendedor"</strong> para gestión por vendedor.
</alert>