# 2_esquemas_drawio.md

## Contenidos esenciales

### Conceptos fundamentales

- Mapa conceptual: herramienta gráfica para organizar y representar conocimiento.
- Concepto: regularidad percibida en acontecimientos u objetos, designada mediante una etiqueta.
- Etiqueta: palabra o símbolo que nombra un concepto.
- Palabras de enlace: expresiones que especifican la relación entre dos conceptos.
- Proposición: unidad de significado formada por dos o más conceptos conectados mediante palabras de enlace.
- Conocimiento organizado: estructura compuesta por conceptos y proposiciones relacionados.
- Pregunta de enfoque: pregunta que delimita el problema, contexto y propósito del mapa.
- Jerarquía conceptual: organización desde conceptos generales e inclusivos hacia conceptos específicos.
- Enlaces cruzados: relaciones entre conceptos ubicados en diferentes secciones del mapa.
- Aprendizaje significativo: integración de nuevos conceptos y proposiciones en la estructura cognitiva previa.
- Aprendizaje memorístico: incorporación débil o aislada de información, con baja transferencia.
- CmapTools: software para construir, revisar, compartir, publicar y enriquecer mapas conceptuales.
- Modelo de conocimiento: conjunto de mapas conceptuales y recursos digitales conectados sobre un dominio.
- Evaluación conceptual: uso del mapa para diagnosticar comprensión, errores conceptuales y progreso.

### Relaciones teóricas clave

- Los mapas conceptuales representan conocimiento organizado.
- El conocimiento organizado está compuesto por conceptos y proposiciones.
- Los conceptos se conectan mediante palabras de enlace.
- Los conceptos y palabras de enlace forman proposiciones.
- Las proposiciones funcionan como unidades de significado.
- La pregunta de enfoque define el contexto y orienta la selección de conceptos.
- La jerarquía conceptual ordena el mapa desde lo general hacia lo específico.
- Los enlaces cruzados muestran relaciones entre segmentos distintos del mapa.
- Los enlaces cruzados favorecen creatividad y comprensión profunda.
- El aprendizaje significativo integra conocimiento nuevo con conocimiento previo.
- Los mapas conceptuales facilitan aprendizaje significativo, evaluación y planificación curricular.
- CmapTools amplía el mapa con colaboración, recursos digitales, búsqueda web y comparación de mapas.

## Guía de estilo para draw.io

### Figuras

- Concepto principal: rectángulo redondeado grande.
- Concepto general: rectángulo redondeado.
- Concepto específico: rectángulo redondeado pequeño.
- Pregunta de enfoque: paralelogramo o llamada.
- Proposición: rectángulo con borde destacado.
- Palabra de enlace: etiqueta sobre el conector, no como nodo principal.
- Enlace cruzado: conector curvo o diagonal.
- Recurso digital: icono de documento, enlace o cilindro.
- Proceso o paso: rectángulo numerado.
- Advertencia o criterio de calidad: rombo.
- Ejemplo concreto: nota o documento con borde discontinuo.

### Colores recomendados

- Concepto raíz: fondo #0B6E4F, borde #064E3B, texto #FFFFFF.
- Conceptos generales: fondo #E8F5E9, borde #2E7D32, texto #064E3B.
- Conceptos específicos: fondo #F1F8E9, borde #66BB6A, texto #1B5E20.
- Pregunta de enfoque: fondo #FFF3CD, borde #F59E0B, texto #78350F.
- Proposiciones: fondo #F3E8FF, borde #7E22CE, texto #4C1D95.
- Enlaces cruzados: línea #BE185D, estilo discontinuo.
- Procesos de construcción: fondo #E3F2FD, borde #1565C0, texto #0D47A1.
- Recursos CmapTools: fondo #E0F2FE, borde #0284C7, texto #075985.
- Evaluación y revisión: fondo #FEF3C7, borde #D97706, texto #78350F.
- Ejemplos: fondo #F9FAFB, borde #6B7280, texto #374151.

### Conectores

- Relación conceptual normal: línea continua con flecha simple.
- Relación jerárquica: línea vertical descendente, de general a específico.
- Palabra de enlace: texto breve sobre la línea, preferentemente verbo o frase verbal.
- Enlace cruzado: línea discontinua o curva entre ramas distintas.
- Revisión iterativa: línea punteada de retorno.
- Secuencia de construcción: flechas numeradas de izquierda a derecha o de arriba abajo.

## Estructura para importación en draw.io

### Diagrama 1: estructura teórica del mapa conceptual

```mermaid
flowchart TB
    MC["Mapas conceptuales"]:::root
    CO["Conocimiento organizado"]:::concept
    FQ["Pregunta de enfoque"]:::focus
    CTX["Contexto de uso"]:::focus
    C["Conceptos"]:::concept
    PE["Palabras de enlace"]:::concept
    P["Proposiciones"]:::proposition
    US["Unidades de significado"]:::proposition
    J["Estructura jerárquica"]:::concept
    EC["Enlaces cruzados"]:::cross
    AS["Aprendizaje significativo"]:::learning
    AM["Aprendizaje memorístico"]:::warning
    CC["Estructura cognitiva previa"]:::learning
    EX["Ejemplos concretos"]:::example
    CRE["Creatividad"]:::cross

    MC -- "representan" --> CO
    MC -- "responden a" --> FQ
    FQ -- "define" --> CTX
    CO -- "se compone de" --> C
    CO -- "se expresa mediante" --> P
    C -- "se conectan con" --> PE
    C -- "junto con palabras de enlace forman" --> P
    P -- "constituyen" --> US
    MC -- "se organizan en" --> J
    J -- "ordena de general a específico" --> C
    MC -- "incluyen" --> EC
    EC -- "relacionan segmentos distintos" --> CO
    EC -- "favorecen" --> CRE
    EX -- "clarifican" --> C
    AS -- "integra conocimiento nuevo en" --> CC
    MC -- "facilitan" --> AS
    AM -- "dificulta integración en" --> CC

    classDef root fill:#0B6E4F,stroke:#064E3B,color:#FFFFFF,stroke-width:2px;
    classDef concept fill:#E8F5E9,stroke:#2E7D32,color:#064E3B;
    classDef focus fill:#FFF3CD,stroke:#F59E0B,color:#78350F;
    classDef proposition fill:#F3E8FF,stroke:#7E22CE,color:#4C1D95;
    classDef cross fill:#FCE7F3,stroke:#BE185D,color:#831843;
    classDef learning fill:#F1F5F9,stroke:#475569,color:#1E293B;
    classDef warning fill:#FEE2E2,stroke:#DC2626,color:#7F1D1D;
    classDef example fill:#F9FAFB,stroke:#6B7280,color:#374151;
```

### Diagrama 2: procedimiento para construir un buen mapa conceptual

```mermaid
flowchart TD
    A["1. Seleccionar dominio familiar"]:::process
    B["2. Formular pregunta de enfoque"]:::focus
    C["3. Identificar 15-25 conceptos"]:::process
    D["4. Crear estacionamiento de conceptos"]:::process
    E["5. Ordenar de general a específico"]:::process
    F["6. Iniciar con 1-4 conceptos generales"]:::process
    G["7. Añadir conceptos específicos"]:::process
    H["8. Elegir palabras de enlace explícitas"]:::process
    I["9. Formar proposiciones claras"]:::proposition
    J["10. Continuar la jerarquía"]:::process
    K["11. Buscar enlaces cruzados"]:::cross
    L["12. Añadir ejemplos o recursos"]:::resource
    M["13. Revisar relevancia y organización"]:::review
    N["14. Reposicionar y refinar"]:::review
    O["Mapa conceptual que responde la pregunta"]:::root

    Q1["Evitar frases completas dentro de cajas"]:::warning
    Q2["Evitar mapas en cadena sin jerarquía"]:::warning

    A --> B --> C --> D --> E --> F --> G --> H --> I --> J --> K --> L --> M --> N --> O
    H -. "criterio de calidad" .-> Q1
    J -. "criterio de calidad" .-> Q2
    N -. "revisión iterativa" .-> B
    N -. "ajuste conceptual" .-> C
    K -. "relaciona ramas distintas" .-> J

    classDef root fill:#0B6E4F,stroke:#064E3B,color:#FFFFFF,stroke-width:2px;
    classDef process fill:#E3F2FD,stroke:#1565C0,color:#0D47A1;
    classDef focus fill:#FFF3CD,stroke:#F59E0B,color:#78350F;
    classDef proposition fill:#F3E8FF,stroke:#7E22CE,color:#4C1D95;
    classDef cross fill:#FCE7F3,stroke:#BE185D,color:#831843;
    classDef resource fill:#E0F2FE,stroke:#0284C7,color:#075985;
    classDef review fill:#FEF3C7,stroke:#D97706,color:#78350F;
    classDef warning fill:#FEE2E2,stroke:#DC2626,color:#7F1D1D;
```

### Diagrama 3: usos de CmapTools y mapas conceptuales

```mermaid
flowchart LR
    MC["Mapa conceptual"]:::root
    CM["CmapTools"]:::tool
    COL["Colaboración síncrona o asíncrona"]:::tool
    PUB["Publicación en servidores"]:::tool
    REC["Recursos digitales vinculados"]:::resource
    WEB["Búsqueda web contextual"]:::resource
    KM["Modelos de conocimiento"]:::concept
    EVA["Evaluación conceptual"]:::assessment
    CUR["Planificación curricular"]:::assessment
    EXP["Captura de conocimiento experto"]:::assessment
    PRE["Presentaciones y portafolios"]:::assessment

    CM -- "permite construir y modificar" --> MC
    CM -- "facilita" --> COL
    CM -- "permite" --> PUB
    MC -- "puede enlazar" --> REC
    CM -- "ejecuta" --> WEB
    MC -- "se integra en" --> KM
    MC -- "sirve para" --> EVA
    MC -- "apoya" --> CUR
    MC -- "ayuda a representar" --> EXP
    MC -- "organiza" --> PRE

    classDef root fill:#0B6E4F,stroke:#064E3B,color:#FFFFFF,stroke-width:2px;
    classDef tool fill:#E0F2FE,stroke:#0284C7,color:#075985;
    classDef resource fill:#F0FDFA,stroke:#0F766E,color:#134E4A;
    classDef concept fill:#E8F5E9,stroke:#2E7D32,color:#064E3B;
    classDef assessment fill:#FEF3C7,stroke:#D97706,color:#78350F;
```