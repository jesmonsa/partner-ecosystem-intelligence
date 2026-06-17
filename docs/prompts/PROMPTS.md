# 💬 Biblioteca de Prompts — Partner & Ecosystem Intelligence

Prompts versionados y curados por caso de uso. Estandarizan calidad y aceleran el día a día del equipo y de los partners.

> Convención: cada prompt declara **rol**, **contexto/insumos**, **tarea** y **formato de salida**. Reemplaza los `{{campos}}`.

---

## 1. Matchmaking de partners (núcleo del MVP)

```
Eres un analista de ecosistema de Oracle. Lee el corpus de partners en /corpus
(estudios estratégicos + Excel de ISVs con nivel OPN, expertise y certificaciones).

Proyecto del equipo: {{descripción del proyecto / necesidad del cliente}}
Industria: {{industria}}  ·  Workloads: {{workloads}}  ·  Región: {{país}}

Tarea: recomienda los 3 partners más calificados.
Para cada uno: nombre, por qué encaja (capacidades + certificaciones),
nivel OPN, riesgos/gaps y siguiente paso (Oracle Day, PoC, assessment).
No inventes datos: si falta info en el corpus, decláralo.
Formato: tabla + 2 líneas de recomendación final. El AE aprueba la decisión.
```

## 2. Radiografía empresarial 360° de una cuenta

```
Genera un perfil 360° de la cuenta {{cliente}} para una conversación comercial.
Incluye: industria, footprint tecnológico probable, señales de compra
(noticias, resultados, vacantes técnicas), relaciones con partners y whitespace.
Solo fuentes públicas y datos internos de relación; sin datos personales sensibles.
Marca cada afirmación como [dato] o [hipótesis a validar].
```

## 3. Comparativo OCI vs hyperscaler

```
Compara OCI con {{AWS|Azure|GCP}} para el caso {{caso de uso}}.
Criterios: red, compute, storage, base de datos, IA/ML, seguridad y TCO.
Tabla con ventajas, limitaciones y recomendación por criterio.
Sé honesto donde OCI no lidere. No inventes cifras: cita origen o marca "a validar".
```

## 4. BOM / arquitectura de referencia

```
A partir del requerimiento {{requerimiento}}, propón una arquitectura OCI usando
el catálogo oracle-cloud-latam cuando aplique. Entrega: diagrama lógico (texto),
servicios OCI con SKU/tamaño tentativo, supuestos, riesgos y dependencias.
Marca "a validar con producto" cualquier límite o disponibilidad por región.
```

## 5. Preparar un Oracle Day

```
Diseña la agenda de un Oracle Day para {{cliente}} desde su radiografía.
Combina sesión técnica y ejecutiva el mismo día, demos del repositorio GitHub
y cierra con un siguiente paso acordado (workshop, PoC o BOM).
```

## 6. Traducir/adaptar mensaje por audiencia

```
Adapta este mensaje a {{ejecutivo|técnico|comercial}} en {{ES|EN|PT}}, tono consultivo,
claro y sin clichés. Mantén la intención, ajusta el registro. Versión corta y formal.
```

---
*Contribuciones: PR con el prompt nuevo siguiendo la convención rol/contexto/tarea/formato.*
