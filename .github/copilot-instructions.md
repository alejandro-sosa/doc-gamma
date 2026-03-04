# Instrucciones para documentación automatizada en este repositorio

Este archivo define convenciones y formatos para la documentación de cambios, tickets y arquitectura. GitHub Copilot usará esto como contexto persistente en tu IDE.

---

## 📋 Estructura de documentación

Colocá la documentación relevante en las siguientes ubicaciones:

- `docs/tickets/`  
  Un archivo `.md` por ticket/jira/caso, siguiendo el formato provisto abajo.

- `docs/adr/`  
  Decisiones de arquitectura (Architecture Decision Records), en formato Markdown.

- `docs/changelog.md`  
  Cambios importantes, agrupados por versión o por sprint.

- `docs/deuda-tecnica.md`  
  Deuda técnica identificada, estado y responsables.

---

## 🏷️ Convenciones de tickets

- Cada ticket (ej: `TICK-42`) debe tener un archivo Markdown dedicado:  
  `docs/tickets/TICK-42.md`

- El contenido debe seguir la siguiente estructura:
  
  ```
  # Ticket: TICK-XX

  ## Resumen

  _Breve descripción del cambio, bugfix o mejora implementada_

  ## Implementación

  - Componentes/ficheros modificados
  - Justificación de las decisiones tomadas
  - Cambios relevantes al negocio

  ## Pruebas

  - Descripción de tests
  - Criterios de aceptación comprobados

  ## Notas

  _Observaciones adicionales, migraciones, instrucciones especiales, etc._
  ```

- Usar referencia al ticket en los mensajes de commit y PR para mantener trazabilidad.

---

## 🛠️ Cómo contribuye Copilot

- Copilot leerá este archivo para sugerir documentación en los tickets siguiendo el formato arriba.
- Podés pedir en el chat:  
  > "Documentá este cambio como TICK-42"  
  y va a generar `docs/tickets/TICK-42.md` siguiendo el formato.
- Si nombrás tickets en el chat (ej: "esto está en TICK-17"), Copilot entenderá el contexto y continuará agregando/modificando la documentación correspondiente.

---

## 💡 Recomendaciones

- Mantené este archivo actualizado con tus propias convenciones.
- Asegurate que la opción  
  `github.copilot.chat.codeGeneration.useInstructionFiles`  
  está activa en la configuración de tu IDE para aprovechar este sistema.

---

_Agregá ejemplos específicos o normas adicionales si tu equipo lo requiere._