# CONTEXT.md

Memoria del proyecto entre clases. El agente lee la sección **Estado actual** al iniciar (desde la clase 5, con un hook). Mantenla corta.

## Estado actual

| Campo | Valor |
|---|---|
| Producto | _(nombre de tu producto)_ |
| Clase en curso | 2 · Tu entorno y tu producto |
| Última clase completada | — |
| Fecha | _(AAAA-MM-DD)_ |
| Siguiente paso | Completar la ficha de la idea |
| Progreso | 1 / 7 |

---

## Mi perfil

- Rol actual y experiencia: _(p. ej., backend 3 años, frontend 1 año)_
- Lo que quiero lograr en la cohorte: _(una frase)_
- Horas por semana fuera de clase: _(número)_

## Stack

Por defecto: Next.js + TypeScript, Vitest, Playwright, GitHub Actions, Docker, Terraform, k6. Si cambias algo, enlaza el ADR.

## Bitácora

Entradas nuevas **arriba**. No se reescriben las anteriores.

```
### Clase N · Título · AAAA-MM-DD
- Entregable: …
- Decisiones: … (enlace al ADR si aplica)
- Aprendí: …
- Pendiente: …
```

### Clase 2 · Tu entorno y tu producto · 2026-11-24
- Hicimos: ficha de la idea completa (`docs/ficha-idea.md`) y producto definido en `CLAUDE.md` (pinceladas-de-belleza).
- Decisiones: usuario principal = la clienta (dueño y soporte como secundarios); demora actual estimada 1–2 días; línea base <20 % de consultas resueltas sin asesor, meta 70 %; negocio mediano (20–100 pedidos/día, 3–5 en soporte).
- Siguiente paso: hacer commit de los ajustes pendientes y arrancar la clase 3 (PRD en `docs/prd.md`), validando las estimaciones con el negocio.
