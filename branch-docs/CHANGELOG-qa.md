# Documentacion de rama: qa

**Proyecto:** gamma-web-client
**Creado:** 2026-03-11 16:44

> Este documento se actualiza automaticamente con cada push.



---

## Fecha: 2026-03-11 - 2026-03-11 16:44

### Rama: qa
**Proyecto:** gamma-web-client

### Resumen de cambios
Resumen de cambios - Rama QA - Proyecto gamma-web-client

1. Se integro la rama 957-tk-fix-qa a la rama qa mediante merge realizado por Alejandro el 11 de marzo de 2026

2. Se realizaron correcciones en el componente card.game.special para mejorar la presentacion visual de los datos en sorteos especiales

3. Se actualizaron las interfaces y tipos en iRaffleNext.ts para alinear la estructura de datos con los cambios en los componentes

4. Se modifico el componente raffles.special.component.tsx para procesar y mostrar correctamente la informacion de sorteos especiales

5. Se actualizo el modelo de dominio raffles.configuration.dto.ts para reflejar los cambios en la estructura de configuracion de sorteos especiales

### Commits
- 30ac2e3 Merge branch 'qa' of https://ta-gitlab.tecnoaccion.com.ar/gamma/gamma-web-client into qa (por Alejandro, 2026-03-11)
- 905d65b Merge branch '957-tk-fix-qa' into qa (por Alejandro, 2026-03-11)
- 9459863 cambios para mostrar correctamente datos en sorteos especiales (por Alejandro, 2026-03-11)

### Archivos modificados
- M	components/modules/shared/components/card.game.special/card.game.special.component.tsx
- M	components/modules/shared/components/raffle.special/iRaffleNext.ts
- M	components/modules/shared/components/raffle.special/raffles.special.component.tsx
- M	core/models/domain/raffles.configuration.dto.ts


---

## Fecha: 2026-04-08 - 2026-04-08 15:18

### Rama: qa
**Proyecto:** gamma-web-client

### Resumen de cambios
RESUMEN DE CAMBIOS - RAMA QA - PROYECTO GAMMA-WEB-CLIENT

1. Fecha de cambio: 08 de abril de 2026, realizado por Alejandro

2. Archivo modificado: componente TypeScript de visualizacion de rifas con liquidacion (show.raffles.includes.component.tsx)

3. Ubicacion: directorio de componentes del modulo settlement, seccion de incluidos en liquidacion

4. Proposito: prueba de alerta para capturar y validar errores durante el proceso de exportacion de valores minimos

5. Alcance: cambios internos en el componente de interfaz de usuario sin afectar estructura general del proyecto

### Commits
- 17acfac prueba de alerta error exportar minimos (por Alejandro, 2026-04-08)

### Archivos modificados
- M	components/modules/settlement/components/show.raffles.includes.liquidaton/show.raffles.includes.component.tsx


---

## Fecha: 2026-04-08 - 2026-04-08 17:33

### Rama: qa
**Proyecto:** gamma-web-client

### Resumen de cambios
RESUMEN DE CAMBIOS - RAMA QA - GAMMA-WEB-CLIENT

1. Se agregaron validaciones en los componentes de lista y tarjeta de minimos, mejorando la robustez del modulo de minimos.

2. Se corrigieron errores detectados en QA en el servicio de agencias que afectan la integracion con las APIs de datos.

3. Se realizaron cambios en tres archivos principales: el contenedor de lista de minimos, el componente de tarjeta de minimos y el servicio de agencias.

4. Los cambios fueron consolidados mediante merge de la rama QA, asegurando que todas las correcciones esten integradas en la rama principal de desarrollo.

5. Las modificaciones se enfocaron en aumentar la validacion de datos y corregir comportamientos indeseados identificados durante las pruebas de calidad.

### Commits
- 54189a1 Merge branch 'qa' of https://ta-gitlab.tecnoaccion.com.ar/gamma/gamma-web-client into qa (por Alejandro, 2026-04-08)
- 831100d agrego validaciones (por Alejandro, 2026-04-08)
- 2f82a90 fix de errores qa (por Alejandro, 2026-04-08)

### Archivos modificados
- M	components/modules/minimum/container/minimum.list/minimum.list.container.tsx
- M	components/modules/shared/components/card.minimum/card.minimum.component.tsx
- M	core/services/agencies.service.ts

