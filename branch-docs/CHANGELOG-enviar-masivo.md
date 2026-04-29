# Documentacion de rama: enviar-masivo

**Proyecto:** gamma-web-client
**Creado:** 2026-04-29 15:39

> Este documento se actualiza automaticamente con cada push.



---

## Fecha: 2026-04-29 - 2026-04-29 15:39

### Rama: enviar-masivo
**Proyecto:** gamma-web-client

### Resumen de cambios
RESUMEN DE CAMBIOS - RAMA: enviar-masivo

1. Se agregaron nuevas funcionalidades para envio masivo de certificados en el modulo de contabilidad, incluyendo un nuevo contenedor dedicado (envio.masivo.container.tsx).

2. Se modificaron los componentes de filtro de certificados (filter.certificado.component) para soportar la nueva funcionalidad de envio masivo, tanto en la logica como en los tipos de datos.

3. Se actualizo el componente de tabla de retenciones de certificados (table.certificado.retention.component) para trabajar con el nuevo flujo de envio masivo.

4. Se realizaron cambios en el modulo de buzones (Mailbox.tsx y SentMessagesOutbox.tsx) para integrar la funcionalidad de envio masivo y visualizacion de mensajes enviados.

5. Se amplio el servicio de registros (records.service.ts) para soportar las operaciones necesarias del envio masivo de certificados.

### Commits
- c2180fe modificaciones para envio masivo de certificados (por Alejandro, 2026-04-29)

### Archivos modificados
- M	components/modules/accountancy/components/filter.certificado.component/filter.certificado.component.tsx
- M	components/modules/accountancy/components/filter.certificado.component/filter.certificado.component.types.ts
- M	components/modules/accountancy/components/table.certificado.retention.component/table.certificado.retention.component.tsx
- A	components/modules/accountancy/containers/envio.masivo.container/envio.masivo.container.tsx
- M	components/modules/mailbox/Mailbox.tsx
- M	components/modules/mailbox/components/sent.messages/SentMessagesOutbox.tsx
- M	core/services/records.service.ts

