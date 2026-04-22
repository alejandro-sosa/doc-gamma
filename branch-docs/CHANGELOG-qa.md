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


---

## Fecha: 2026-04-09 - 2026-04-09 14:40

### Rama: qa
**Proyecto:** gamma-web-client

### Resumen de cambios
CAMBIOS EN LA RAMA QA - PROYECTO GAMMA-WEB-CLIENT

1. Se agregaron validaciones para los dias en el componente de lista minima, asegurando que solo se acepten valores validos.

2. Se implemento la opcion de seleccionar todos los dias de una vez, mejorando la experiencia del usuario al no necesitar seleccionar cada dia individualmente.

3. Se realizaron mejoras en la gestion de categorias dentro del mismo componente contenedor.

4. Los cambios fueron realizados en el archivo minimum.list.container.tsx ubicado en la ruta components/modules/minimum/container/minimum.list/.

5. Estos ajustes buscan optimizar la funcionalidad y usabilidad del modulo de configuracion minima en el cliente web gamma.

### Commits
- 1e5dfcb se agrega validaciones para los dias, opcion de seleccionar todos los dias y mejoras en categoria. (por Alejandro, 2026-04-09)

### Archivos modificados
- M	components/modules/minimum/container/minimum.list/minimum.list.container.tsx


---

## Fecha: 2026-04-17 - 2026-04-17 15:14

### Rama: qa
**Proyecto:** gamma-web-client

### Resumen de cambios
RESUMEN DE CAMBIOS - RAMA QA - GAMMA-WEB-CLIENT

1. Se modifica el envio de datos de categoria para utilizar null en lugar de 0 como valor predeterminado.

2. Cambios aplicados en el componente container de lista minima: minimum.list.container.tsx

3. Actualizacion del modelo de datos minimumSales.dto.ts para reflejar la nueva logica de categoria.

4. Los cambios afectan la funcionalidad de altas, bajas y modificaciones minimas (ABM).

5. Commit realizado el 2026-04-17 por Alejandro.

### Commits
- 2b0275e enviar null en vez de 0 en categoria, abm minimos. (por Alejandro, 2026-04-17)

### Archivos modificados
- M	components/modules/minimum/container/minimum.list/minimum.list.container.tsx
- M	core/models/domain/minimumSales.dto.ts


---

## Fecha: 2026-04-21 - 2026-04-21 17:35

### Rama: qa
**Proyecto:** gamma-web-client

### Resumen de cambios
Cambios en rama qa - Proyecto gamma-web-client

1. Fecha: 2026-04-21
2. Autor: Alejandro
3. Tipo de cambio: Correccion de errores en funcionalidad ABM (Alta, Baja, Modificacion) de minimos
4. Archivo afectado: components/modules/shared/components/card.minimum/card.minimum.component.tsx
5. Alcance: Componente de tarjeta para gestion de minimos en la aplicacion web

### Commits
- 9ef3c0a fix para abm minimos (por Alejandro, 2026-04-21)

### Archivos modificados
- M	components/modules/shared/components/card.minimum/card.minimum.component.tsx


---

## Fecha: 2026-04-22 - 2026-04-22 15:10

### Rama: qa
**Proyecto:** gamma-web-client

### Resumen de cambios
Resumen de cambios en rama qa del proyecto gamma-web-client:

1. Se modifico el componente card.minimum.component.tsx en la carpeta components/modules/shared/components/card.minimum/

2. Los cambios apuntan a evitar la repeticion de sorteos en el modulo ABM minimos

3. La modificacion fue realizada por Alejandro el 22 de abril de 2026

4. Se trata de una unica modificacion en un archivo de componente TypeScript/React

5. Los cambios forman parte del trabajo de refinamiento de la funcionalidad de sorteos dentro del sistema de administracion de minimos

### Commits
- 08f2f24 cambios para no repetir sorteos en abm minimos. (por Alejandro, 2026-04-22)

### Archivos modificados
- M	components/modules/shared/components/card.minimum/card.minimum.component.tsx


---

## Fecha: 2026-04-22 - 2026-04-22 15:30

### Rama: qa
**Proyecto:** gamma-web-client

### Resumen de cambios
RESUMEN DE CAMBIOS - Rama QA (Proyecto gamma-web-client)

1. Actualizacion de funcionalidad de busqueda en categorias: Se implementaron modificaciones para permitir buscar dentro de las categorias del sistema.

2. Cambios en componente de listado: Se modifico el archivo minimum.list.container.tsx para integrar la nueva funcionalidad de busqueda.

3. Actualizacion de componente de tarjeta: Se ajusto el archivo card.minimum.component.tsx para reflejar los cambios en la presentacion de elementos minimos.

4. Mantenimiento ABM: Se realizaron operaciones basicas de Altas, Bajas y Modificaciones en los modulos minimos.

5. Merge de rama: Se integro correctamente la rama qa con los ultimos cambios del repositorio remoto.

### Commits
- 1ab4993 Merge branch 'qa' of https://ta-gitlab.tecnoaccion.com.ar/gamma/gamma-web-client into qa (por Alejandro, 2026-04-22)
- e580f55 modificaciones para poder buscar en categorias, abm minmos (por Alejandro, 2026-04-22)

### Archivos modificados
- M	components/modules/minimum/container/minimum.list/minimum.list.container.tsx
- M	components/modules/shared/components/card.minimum/card.minimum.component.tsx

