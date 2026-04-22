# Documentacion de rama: dev

**Proyecto:** gamma-web-client
**Creado:** 2026-04-22 10:34

> Este documento se actualiza automaticamente con cada push.



---

## Fecha: 2026-04-22 - 2026-04-22 10:34

### Rama: dev
**Proyecto:** gamma-web-client

### Resumen de cambios


### Commits
- d46c00f Merge branch 'qa' into dev (por Alejandro, 2026-04-22)
- 9ef3c0a fix para abm minimos (por Alejandro, 2026-04-21)
- fed742c fix(comisiones): validar unicidad de detalle por importe, fecha y zona en FE (por Ricardo Tejerina Perezlindo, 2026-04-21)
- 572b7f3 fix: eliminar comisi├│n usa DELETE real y corrige timezone en validaci├│n fecha desde de descuentos (por Ricardo Tejerina Perezlindo, 2026-04-20)
- 2b0275e enviar null en vez de 0 en categoria, abm minimos. (por Alejandro, 2026-04-17)
- 12c062c fix(comisiones): eliminar regla la remueve de la lista inmediatamente (por Ricardo Tejerina Perezlindo, 2026-04-17)
- e6b2e50 fix(comisiones): reactiva Guardar en modal vista y normaliza porcentajes (por Ricardo Tejerina Perezlindo, 2026-04-17)
- dd7136e Revert "fix(comisiones): preserva 2 decimales en campos PDV% y CON% al reabrir modal edici├│n" (por Ricardo Tejerina Perezlindo, 2026-04-16)
- d9b2913 fix(comisiones): preserva 2 decimales en campos PDV% y CON% al reabrir modal edici├│n (por Ricardo Tejerina Perezlindo, 2026-04-16)
- 1c1c91d fix(comisiones): corrige bot├│n Guardar silencioso y errores invisibles en modal detalle (por Ricardo Tejerina Perezlindo, 2026-04-16)
- df70207 fix(comisiones): decimales y validaci├│n de importe en modal editar detalle (por Ricardo Tejerina Perezlindo, 2026-04-16)
- 78ece46 fix(comisiones): corregir bot├│n Actualizar que no ejecutaba el guardado (por Ricardo Tejerina Perezlindo, 2026-04-16)
- c7aa8c4 fix(comisiones): evitar ruido IEEE 754 al mostrar alicuotas en modal de edici├│n (por Ricardo Tejerina Perezlindo, 2026-04-16)
- f4bf689 fix(discounts): minDate en DatePicker dateFrom seg├║n pr├│xima liquidaci├│n (por Ricardo Tejerina Perezlindo, 2026-04-16)
- 283832a fix(comisiones+descuentos): corrige validaci├│n de submit, hasExecutions y confirmaci├│n de cambios cr├¡ticos (por Ricardo Tejerina Perezlindo, 2026-04-15)
- 9e4dc36 Fix(deleteRaffleConfiguration): se actualiza lista de sorteos disponibles al eliminar una configuraci├│n (por Paolo Alarc├│n, 2026-04-15)
- d93af1e feat(raffles-special): mejorar manejo de llamadas API paralelas y actualizaci├│n de lista (por Paolo Alarc├│n, 2026-04-15)
- c593c98 fix(commissions): corrige doble divisi├│n de porcentaje y fechaDesde vac├¡a (por Ricardo Tejerina Perezlindo, 2026-04-14)
- 21280aa Merge branch 'qa' of https://ta-gitlab.tecnoaccion.com.ar/gamma/gamma-web-client into qa (por Ricardo Tejerina Perezlindo, 2026-04-13)
- dc58553 Merge fix/discount-manual-payment-method into qa (por Ricardo Tejerina Perezlindo, 2026-04-13)
- ed5236a feat: wire editHeader service and fix paymentMethod field in edit mode (por Ricardo Tejerina Perezlindo, 2026-04-13)
- 3bd1582 fix: add paymentMethodId to LoteItem type and map it from header in audit dashboard (por Ricardo Tejerina Perezlindo, 2026-04-13)
- 1e5dfcb se agrega validaciones para los dias, opcion de seleccionar todos los dias y mejoras en categoria. (por Alejandro, 2026-04-09)
- 54189a1 Merge branch 'qa' of https://ta-gitlab.tecnoaccion.com.ar/gamma/gamma-web-client into qa (por Alejandro, 2026-04-08)
- 831100d agrego validaciones (por Alejandro, 2026-04-08)
- 2f82a90 fix de errores qa (por Alejandro, 2026-04-08)
- 6ba39ff Fix: Se corrige nombre propiedad (por Paolo Alarc├│n, 2026-04-08)
- 095b3ab Merge branch 'fix-qa/tk-880-liqEspecial' into qa (por Paolo Alarc├│n, 2026-04-08)
- d7311c2 feat(raffles-special): filtrar configuraciones sin liquidar (por Paolo Alarc├│n, 2026-04-08)
- c7b425a style(raffles-special): reducir espacio horizontal entre cards (por Paolo Alarc├│n, 2026-04-08)
- 4b13e7b refactor(raffles-special): mejorar manejo de estado y correcci├│n de bugs (por Paolo Alarc├│n, 2026-04-08)
- 17acfac prueba de alerta error exportar minimos (por Alejandro, 2026-04-08)
- 9154baf fix(discount): modal ojito muestra nroLote primero, fileName como fallback (por Ricardo Tejerina Perezlindo, 2026-03-26)
- 344a32c fix(discounts): mostrar nroLote en columna nombre cuando el lote no tiene fileName (por Ricardo Tejerina Perezlindo, 2026-03-26)
- 173f8e9 fix(discounts): mostrar nombre o nroLote en t├¡tulo del modal de detalle de lote (por Ricardo Tejerina Perezlindo, 2026-03-26)
- f45102a fix(commissions): corrige bugs en ABM comisiones FE (por Ricardo Tejerina Perezlindo, 2026-03-26)
- eab0400 kk (por Ricardo Tejerina Perezlindo, 2026-03-16)
- 38e1cdd fix(discounts-bonuses): edici├│n de lotes y deleteLotes (por Ricardo Tejerina Perezlindo, 2026-03-16)
- 57f811b fix(discounts-bonuses): corregir edici├│n de lotes y eliminaci├│n en panel de auditor├¡a (por Ricardo Tejerina Perezlindo, 2026-03-16)
- be3de57 fix(commissions): validaci├│n nombre, conversi├│n porcentajes y visualizaci├│n decimales (por Ricardo Tejerina Perezlindo, 2026-03-16)
- 658c776 Merge branch 'MAN-8131-intervalos-de-liquidacion' into qa (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 49e59cb fix(discounts): mejorar parseo de fecha para formato H+DDMMYYYY (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 9df984b Merge branch 'MAN-8131-intervalos-de-liquidacion' into qa (por Ricardo Tejerina Perezlindo, 2026-03-11)
- c8d8903 fix(discounts): corregir c├â┬ílculo de isUniqueMode en useMemo para habilitar bot├â┬│n (por Ricardo Tejerina Perezlindo, 2026-03-11)
- ce4ff82 Merge branch 'MAN-8131-intervalos-de-liquidacion' into qa (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 264d0a4 fix(discounts): validaci├â┬│n y env├â┬¡o obligatorio de dateTo para todas las modalidades (por Ricardo Tejerina Perezlindo, 2026-03-11)
- ab8fa03 Merge branch 'qa' of https://ta-gitlab.tecnoaccion.com.ar/gamma/gamma-web-client into qa (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 459923d Merge branch 'MAN-8131-intervalos-de-liquidacion' into qa (por Ricardo Tejerina Perezlindo, 2026-03-11)
- ca900f7 fix(discounts): corregir tipo de isImportButtonDisabled para evitar error de TypeScript (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 30ac2e3 Merge branch 'qa' of https://ta-gitlab.tecnoaccion.com.ar/gamma/gamma-web-client into qa (por Alejandro, 2026-03-11)
- 905d65b Merge branch '957-tk-fix-qa' into qa (por Alejandro, 2026-03-11)
- 9459863 cambios para mostrar correctamente datos en sorteos especiales (por Alejandro, 2026-03-11)
- b5f580d Merge branch 'MAN-8131-intervalos-de-liquidacion' into qa (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 2b52495 fix(discounts): usar fecha del archivo como fecha desde y hasta en modalidad ├â┬║nica vez (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 741873e Merge branch 'MAN-8131-intervalos-de-liquidacion' into qa (por Ricardo Tejerina Perezlindo, 2026-03-11)
- ed8ef7c fix(discounts): validaci├â┬│n dateTo obligatorio y parseo mejorado de fecha del archivo (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 052a235 Merge MAN-8131-intervalos-de-liquidacion into qa - fix parsing error (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 6ed9091 fix(settlement): corregir c├â┬│digo activo fuera de funci├â┬│n que causaba error de parsing (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 47b1a39 Merge MAN-8131-intervalos-de-liquidacion into qa (por Ricardo Tejerina Perezlindo, 2026-03-11)
- afde90e fix(settlement): corregir comentario JSX anidado que causaba error de parsing (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 8473b7b Merge branch 'MAN-8131-intervalos-de-liquidacion' into qa (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 9d8cc22 fix(discounts): parsear fecha del archivo y validaci├â┬│n defensiva en file.loader (por Ricardo Tejerina Perezlindo, 2026-03-11)
- 4738ef9 fix(settlement): corregir cierre prematuro de comentario JSX en settlement.data.component (por Ricardo Tejerina Perezlindo, 2026-03-10)
- d7fc935 correccion de merge (por Marcos, 2026-03-10)
- c22a46d Merge branch 'MAN-8131-intervalos-de-liquidacion' into qa (por Marcos, 2026-03-10)
- e6c5435 Correcciones al importar archivo (por Marcos, 2026-03-10)

### Archivos modificados
- M	components/discounts-and-bonuses/audit-dashboard/audit.dashboard.tsx
- M	components/discounts-and-bonuses/file.loader.tsx
- M	components/discounts-and-bonuses/manual.loading.tsx
- M	components/modules/minimum/container/minimum.list/minimum.list.container.tsx
- M	components/modules/sale-points/container/abm.commission.container/abm.commission.cards/modal.update.commission.detail.tsx
- M	components/modules/sale-points/container/abm.commission.container/abm.commission.container.tsx
- M	components/modules/sale-points/container/abm.commission.container/abm.commission.modals/abm.commission.modal.edit.tsx
- M	components/modules/sale-points/container/abm.commission.container/abm.commission.modals/abm.commission.modal.view.tsx
- M	components/modules/settlement/components/settlement.data/settlement.data.component.tsx
- M	components/modules/settlement/components/show.raffles.includes.liquidaton/show.raffles.includes.component.tsx
- M	components/modules/shared/components/card.game.special/card.game.special.component.tsx
- M	components/modules/shared/components/card.minimum/card.minimum.component.tsx
- M	components/modules/shared/components/raffle.special/iRaffleNext.ts
- M	components/modules/shared/components/raffle.special/raffles.special.component.tsx
- M	components/modules/shared/components/table/table.component.II.tsx
- M	core/models/domain/discounts.bonuses.dto.ts
- M	core/models/domain/minimumSales.dto.ts
- M	core/models/domain/raffles.configuration.dto.ts
- M	core/services/agencies.service.ts
- M	core/services/discounts.bonuses.service.ts

