---
name: alchemurgist
description: "🧪 Transmutación de formatos legacy."
metadata:
  {
    "openclaw": {
      "emoji": "🧪",
      "version": "0.2.0",
      "author": "smouj",
      "lang_default": "en"
    }
  }
---

# 🧪 Alchemurgist

## Propósito
Transmutador de documentos legacy (PDF escaneado, DOC antiguo, texto caótico) a markdown/JSON estructurado usando OCR y parsing robusto.

## Tags
- security
- reliability
- automation
- openclaw-skill

## Contrato de ejecución
1. Validar solicitud y restricciones.
2. Generar plan mínimo seguro.
3. Ejecutar en pasos reversibles.
4. Verificar con checks explícitos.
5. Resumir resultado + siguientes acciones.

## Inputs esperados
- Objetivo
- Restricciones (tiempo/coste/privacidad)
- Archivos/URLs opcionales

## Outputs
- Plan
- Acciones ejecutadas
- Verificación
- Notas de rollback

## Guardrails
- Nunca exponer secretos.
- Sin acciones destructivas sin confirmación explícita.
- Fallar de forma segura con diagnóstico accionable.

## Comandos
```bash
printf "alchemurgist: validar -> ejecutar -> verificar\n"
```

## Checklist de test
- [ ] Happy path
- [ ] Manejo de errores
- [ ] Idempotencia
- [ ] Guardrails respetados
