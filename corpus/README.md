# 🔒 /corpus — Datos reales de partners (Oracle Restricted)

**ESTE DIRECTORIO NO SE PUBLICA EN GITHUB PAGES.**

Aquí vive el corpus que el **Partner Intelligence Engine** lee para recomendar partners. Contiene información confidencial de Oracle y de terceros:

- `Proposta_MPL_FY26.xlsx` — mapeo de ISVs gerenciados: PAM, niveles OPN (L1/L2/L3), Comp IDs, razón social.
- `estudos/` — estudios estratégicos detallados por partner (Veritran, Engineering, Pipefy, ArquitecSOFT, WideLabs, …), siguiendo `docs/estudio-estrategico/PLANTILLA.md`.

## Reglas de manejo

1. **Confidencial — Oracle Restricted \\ Including External Recipients.** No compartir fuera de canales autorizados.
2. **Sin datos personales sensibles.** Solo datos corporativos necesarios para el matchmaking.
3. **Acceso por rol.** Repositorio privado; acceso por necesidad.
4. **Validación previa.** El uso por agentes de IA pasa revisión de compliance y legal antes del piloto.
5. **No publicar.** Si el plan no permite Pages privado, este directorio se excluye del deploy.

## Formato que consume la IA

Registro mínimo por partner:

| Campo | Ejemplo |
|-------|---------|
| Partner | Brasoftware |
| Comp ID | 4-853715250632 |
| Nivel OPN | Potential L2 |
| PAM | Grazielle Forne |
| Expertise / track | Tech (DB, OCI) |
| Certificaciones | OCI Foundations, Associate |

> El correo de Diogo Shibata confirma que el archivo **puede ser una lista simple**, ya que será interpretado por la IA.
