graph LR

subgraph Epidemiología Mundial
    A((2013: 17.3M)) -- Aumento --> B((Siglo XXI))
    B -- Disminución tasa de mortalidad --> C((22%))
end

subgraph Estados Unidos
    D((Hombres: 50% | Mujeres: 33%)) -- Disminución --> E((Tasa de mortalidad))
    E -- Factores de riesgo --> F(Tabaquismo, Obesidad)
end

subgraph Europa
    G((Reducción significativa)) --> H((Francia, Dinamarca, Portugal, Países Bajos, España))
end

subgraph Australia
    I((22% de la población)) --> J((Enfermedad coronaria))
    J -- Incidencia aumenta con la edad --> K((Envejecimiento poblacional))
end

subgraph Asia
    L((Accidentes cerebrovasculares)) --> M((Japón, Singapur))
    M -- Aumento en casos --> N((Infartos de miocardio))
end

subgraph América Latina
    O((Principal causa de mortalidad)) -- Inequidad acceso a servicios de salud --> P((Más complicaciones y tasas de mortalidad))
    P -- Factores de riesgo prevalentes --> Q((Obesidad, Hipertensión, Diabetes))
end

A -- Mortalidad --> D
G -- Mortalidad --> D
I -- Mortalidad --> D
L -- Mortalidad --> D
O -- Mortalidad --> D
