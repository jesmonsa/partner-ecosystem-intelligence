# 🔒 /corpus — Datos reales de partners (Oracle Restricted)

**ESTE DIRECTORIO ESTÁ VACÍO A PROPÓSITO. NO subir aquí datos confidenciales mientras el repositorio sea PÚBLICO.**

Este es el lugar reservado para el corpus que el **Partner Intelligence Engine** lee para recomendar partners. Mientras el repo sea público, el corpus real (Excel de ISVs, estudios estratégicos detallados) debe vivir **fuera** de este repositorio: en OneDrive/SharePoint interno o en un repo privado separado.

## Qué contiene el corpus (en su ubicación privada)

- Mapeo de ISVs gerenciados: PAM, niveles OPN (L1/L2/L3), Comp IDs, razón social.
- Estudios estratégicos detallados por partner, siguiendo `docs/estudio-estrategico/PLANTILLA.md`.

## Reglas de manejo

1. **Confidencial — Oracle Restricted \ Including External Recipients.** No publicar en repos públicos.
2. **Sin datos personales sensibles.** Solo datos corporativos necesarios para el matchmaking.
3. **Acceso por rol.** El corpus real vive en ubicación privada; acceso por necesidad.
4. **Validación previa.** El uso por agentes de IA pasa revisión de compliance y legal antes del piloto.

## Formato que consume la IA *(ejemplo ficticio)*

Registro mínimo por partner (datos de ejemplo, no reales):

| Campo | Ejemplo (ficticio) |
|-------|--------------------|
| Partner | Partner Ejemplo S.A. |
| Comp ID | X-000000000000 |
| Nivel OPN | L2 |
| PAM | (responsable asignado) |
| Expertise / track | Tech (DB, OCI) |
| Certificaciones | OCI Foundations, Associate |

> El requerimiento confirma que el archivo **puede ser una lista simple**, ya que será interpretado por la IA.
