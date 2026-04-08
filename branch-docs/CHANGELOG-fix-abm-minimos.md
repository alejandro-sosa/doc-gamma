# Documentacion de rama: fix-abm-minimos

**Proyecto:** gamma-web-client
**Creado:** 2026-04-08 10:27

> Este documento se actualiza automaticamente con cada push.



---

## Fecha: 2026-04-08 - 2026-04-08 10:27

### Rama: fix-abm-minimos
**Proyecto:** gamma-web-client

### Resumen de cambios
Resumen de cambios - Rama fix-abm-minimos

1. Se corrigio el componente modal de auditoria de descuentos y bonificaciones para mejorar la visualizacion de datos de lote.

2. Se modifico el orden de presentacion en el ojito modal: ahora muestra nroLote como dato primario.

3. Se implemento fileName como valor alternativo o fallback cuando nroLote no esta disponible.

4. El cambio afecta unicamente al archivo audit.dashboard.tsx en la seccion de descuentos y bonificaciones.

5. Esta correccion mejora la consistencia y claridad en la informacion mostrada al usuario en la interfaz de auditoria.

### Commits
- 9154baf fix(discount): modal ojito muestra nroLote primero, fileName como fallback (por Ricardo Tejerina Perezlindo, 2026-03-26)

### Archivos modificados
- M	components/discounts-and-bonuses/audit-dashboard/audit.dashboard.tsx


---

## Fecha: 2026-04-08 - 2026-04-08 11:11

### Rama: fix-abm-minimos
**Proyecto:** gamma-web-client

### Resumen de cambios
Resumen de cambios:

1. Se agrego una prueba para validar el comportamiento de alertas de error al exportar minimos en el modulo de liquidacion.

2. El archivo modificado es el componente TypeScript que muestra los rifas incluidas en la liquidacion (show.raffles.includes.component.tsx).

3. Los cambios se encuentran en la rama fix-abm-minimos del proyecto gamma-web-client.

4. La modificacion fue realizada por Alejandro el 08 de abril de 2026.

5. El objetivo es mejorar el manejo de errores durante el proceso de exportacion de valores minimos en el flujo de liquidacion.

### Commits
- 17acfac prueba de alerta error exportar minimos (por Alejandro, 2026-04-08)

### Archivos modificados
- M	components/modules/settlement/components/show.raffles.includes.liquidaton/show.raffles.includes.component.tsx

