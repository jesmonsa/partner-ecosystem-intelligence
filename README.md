# Partner & Ecosystem Intelligence — Plataforma viva

**AI Challenge FY27 · LATAM · Challenge #4**
De un ecosistema de partners fragmentado a un motor regional de crecimiento inteligente.

> ⚠️ **Confidencial — Oracle Restricted.** Este repositorio es **privado**. El corpus con datos reales de partners (Excel, estudios detallados) vive en `/corpus` y **no** se publica en GitHub Pages. Validar el manejo de datos con la política interna de Oracle antes de cualquier piloto.

---

## Qué es esto

Una **plataforma viva** (no un slide estático) que consolida los seis componentes con los que el equipo ya opera y los conecta con el MVP del challenge: **un repositorio central que la IA lee para, dado un proyecto, recomendar los partners calificados.**

| # | Componente | Estado | Dónde |
|---|------------|--------|-------|
| 1 | Repositorio de arquitecturas + one-click deploy | Disponible | [`oracle-cloud-latam`](https://github.com/jesmonsa/oracle-cloud-latam) (46+ arquitecturas, Terraform / OCI Resource Manager) |
| 2 | Biblioteca de Prompts | Disponible | [`docs/prompts/PROMPTS.md`](docs/prompts/PROMPTS.md) |
| 3 | Skills (expertos por dominio) | Disponible | [`docs/skills/SKILLS.md`](docs/skills/SKILLS.md) |
| 4 | Estudio estratégico corporativo (corpus IA) | Disponible | [`docs/estudio-estrategico/PLANTILLA.md`](docs/estudio-estrategico/PLANTILLA.md) + `/corpus` |
| 5 | AI Harness (agentes sobre OCI) | Piloto 90 días | Patrón CLI/SDK + MCP |
| 6 | Herramientas de migración y análisis | Disponible | OCM · ZDM · DMS · GoldenGate · HCX/OCVS · RackWare · Matilda |

## Estructura

```
/
├── docs/                     → GitHub Pages (sitio trilingüe ES/EN/PT)
│   ├── index.html            → la plataforma viva
│   ├── prompts/PROMPTS.md
│   ├── skills/SKILLS.md
│   └── estudio-estrategico/PLANTILLA.md
├── corpus/                   → 🔒 DATOS REALES DE PARTNERS — NO publicar en Pages
└── README.md
```

## Cómo publicar GitHub Pages

> Pages desde repo **privado** requiere plan **GitHub Team / Enterprise** (puede ser Pages privado, ideal para Oracle Restricted). Con plan Free, Pages solo en repos públicos: en ese caso **no** subas `/corpus`.

1. GitHub → repo → **Settings → Pages**.
2. *Source*: **Deploy from a branch**.
3. Branch **main**, carpeta **/docs** → **Save**.
4. En 1–2 min: `https://jesmonsa.github.io/partner-ecosystem-intelligence/`.

---
*Equipo Challenge #4 · Coaches: Song & Marcelle · Junio 2026*
