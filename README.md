# pablo-sefaria-torah

> **Parte del set `Hermes2-` de [PabloRuizD](https://github.com/PabloRuizD).** Esta skill fue generada con asistencia de Hermes2 para uso del agente personal de Pablo Ruiz Danegger (Instituto Técnico UNT Tucumán).

📂 **Categoría:** 🕊 Religiones y Filosofía
🏷️ **Tipo:** Wrapper (fork simbólico)

## Descripción

Sefaria Jewish texts structured export (Torah/Tanakh/Talmud/Mishnah in JSON/XML/text). Use for Jewish text analysis, comparison across translations, and structural queries of Tanakh. Triggers: 'Torah', 'Tanakh', 'Talmud', 'Mishnah', 'Sefaria', 'Jewish text', 'Hebrew text structure', 'Jewish Bible', 'Tannaim', 'Amoraim'.

## Origen

- **Upstream:** https://github.com/Sefaria/Sefaria-Export
- **Autor del port:** Pablo Agustín Ruiz Danegger con Hermes2 (agosto 2026)
- **Propósito:** marcar y disponibilizar esta skill para el agente personal Hermes2, en una cuenta separada para evitar confusión con otros repos de Pablo.

## Instalación

### Opción A — Descarga directa

```bash
git clone https://github.com/PabloRuizD/Hermes2-pablo-sefaria-torah.git
mkdir -p ~/.hermes/skills/pablo-sefaria-torah
cp -r Hermes2-pablo-sefaria-torah/* ~/.hermes/skills/pablo-sefaria-torah/
```

### Opción B — Como submódulo

```bash
mkdir -p ~/.hermes/skills/pablo-sefaria-torah
git submodule add https://github.com/PabloRuizD/Hermes2-pablo-sefaria-torah.git ~/.hermes/skills/pablo-sefaria-torah/source
```

## Estructura

```
pablo-sefaria-torah/
├── SKILL.md           # Definición técnica (frontmatter YAML + cuerpo Markdown)
├── README.md          # Este archivo
├── LICENSE            # Licencia MIT
└── .gitignore
```

Si la skill incluye datos locales (textos, corpus, datasets), los encontrarás en subcarpetas dentro del repo según se defina en `SKILL.md`.

## Uso

Una vez instalada en `~/.hermes/skills/pablo-sefaria-torah/`, el agente Hermes2 carga automáticamente la skill y la activa cuando tu pedido contenga los triggers listados en `SKILL.md`.

Ejemplo:
```
Usuario: "<algún trigger de la skill>"
Hermes2: invoca la skill, carga references/, ejecuta scripts/ si aplica.
```

## Licencia

- **Código (SKILL.md, README.md, scripts propios):** MIT — ver `LICENSE`.
- **Datos del upstream (si aplica):** ver la sección "Origen" arriba; cada upstream mantiene su propia licencia (CC-BY, CC-BY-SA, ODbL, MIT, o Public Domain según el caso).

## Aviso

Esta skill fue generada con asistencia de IA. Verificar los outputs antes de uso en producción. Para correcciones o ampliaciones, abrir un issue en el repositorio.

---

*Generado: 2026-08-29 · Hermes2 para Pablo Ruiz Danegger*
