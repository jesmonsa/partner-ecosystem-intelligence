# 📑 Estudio estratégico corporativo — Plantilla

Estructura común que **debe tener** cada estudio de partner para alimentar el corpus que la IA lee en el matchmaking. Derivada de estudos já produzidos (Veritran, Engineering, Pipefy, ArquitecSOFT, WideLabs) y alineada con el modelo **ELG (Ecosystem-Led Growth)** de CAMCAR.

> Objetivo: que la IA responda *"¿qué partner activo para esta oportunidad?"* con evidencia, no con intuición. Secciones factuales, con fuentes; marcar hipótesis como tales.

---

## 1. Resumen ejecutivo
Qué hace el partner, para quién, y por qué importa para Oracle. Tesis central.

## 2. Visión general corporativa
Fundación, sede, presencia, tamaño, liderazgo, hitos. Datos verificables.

## 3. Modelo de negocio, go-to-market y posicionamiento
Cómo gana dinero, segmentos, canales, alianzas, posicionamiento.

## 4. Portafolio de plataforma y soluciones
- **4.1 Núcleo tecnológico** público (stack, cloud, arquitectura).
- **4.2 Comparativo de productos y funcionalidades.**
- **4.3 APIs, SDKs, integraciones y deployment.**
- **4.4 Encaje con OCI** (Autonomous, Exadata, OKE, IA, seguridad, migración).

## 5. Mercados, clientes, casos de éxito y parcerías
Industrias, casos referenciables, partnerships (incluida relación con Oracle).

## 6. Financiero, competencia, compliance y riesgos
Señales financieras públicas, competidores, postura regulatoria, riesgos.

## 7. Oportunidades, recomendaciones estratégicas y próximos pasos
Dónde Oracle y el partner co-crean; recomendaciones; siguiente paso.

## 8. Segmentación ELG y metadatos para el matchmaking *(estructurado, lo lee la IA)*

Segmento por **rol en el ecosistema** (modelo ELG): **Build** (construyen sobre OCI — ISVs/startups), **Sell** (venden Oracle — VARs/integradores), **Service** (implementan y migran — consultoras/MSPs), **Influence** (abren puertas — VCs/comunidades/hubs). Un partner puede tener más de un rol.

```yaml
partner: "{{nombre}}"
comp_id: "{{Comp ID}}"
opn_level: "{{L1|L2|L3|Potential L2}}"
elg_segment: ["{{Build|Sell|Service|Influence}}"]
pam: "{{owner}}"
track: "{{Tech|Apps}}"
# Capability mapping (modelo CAMCAR — alimenta el score de fit)
capability_map:
  vertical_expertise: ["{{banca}}","{{retail}}","{{sector público}}"]
  account_relationships: ["{{cuentas donde tiene relación}}"]
  technical_capability: ["DB","IA","Kubernetes","Seguridad","Migración"]
  geographic_coverage: ["BR","CO","MX"]
certifications: ["OCI Foundations","Associate"]
oci_fit_score: "{{0-100, a calcular}}"
sources: ["{{url 1}}"]
last_updated: "{{YYYY-MM-DD}}"
```

## 9. Fuentes consultadas
URLs y documentos. Sin esta sección, el estudio no entra al corpus.

---
*Estudios completos con datos reales en `/corpus/estudos/` (privado). La plantilla es pública; el contenido sensible no.*
