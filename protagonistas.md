```mermaid

graph TD
    %% Nodos de Síntesis y Doctrina
    JUST((Justicialismo: Síntesis No De Laboratorio))
    PER((Juan D. Perón: El Integrador Pragmático))
    CAT_MOR(Base Moral Católica)
    POL_EXT(Tercera Posición/Soberanía)

    %% Nodos de Fuentes Ideológicas (Nivel 1)
    subgraph I. Fuentes Intelectuales y Regionales
        VAR[Vargas (BR): Corporativismo]
        CAR[Cárdenas (MX): Nacionalismo de Recursos]
        CAT_DOC[Doctrina Social Católica]
        GBON[Gustave Le Bon: Psicología de Masas]
        MIL_MOS[Gral. Mosconi: Soberanía Energética]
        MIL_SAR[Gral. Sarobe: Reformismo Militar]
        BUNGE[Alejandro Bunge: Economista]
        APRA[APRA (PE): Antimperialismo]
    end

    %% Nodos de Mecanismos y Arquitectos (Nivel 2)
    subgraph II. Arquitectos y Mecanismos de Estado
        FIG[José Figuerola: Ordenador Económico]
        SAM[Arturo Sampay: Ordenador Legal]
        STP[Sec. Trabajo y Previsión (1943)]
        CGT[Sindicatos Paraestatales]
        GOU[G.O.U. / Alianza Militar]
        CONST[Constitución 1949]
    end

    %% 1. Flujo de Doctrina y Precursores hacia Perón (Integración)
    CAT_DOC -- Rerum Novarum / Justicia como Fundamento Social --> PER
    MIL_MOS -- Autarquía Económica y Rol del Estado --> PER
    MIL_SAR -- Vía Reformista desde el Ejército --> PER
    BUNGE -- Crítica a "Economía Colonial" / Necesidad ISI --> PER
    GBON -- Visceral Comprensión de Liderar Masas --> PER
    VAR -- Modelo de Sindicatos Controlados y Corporativismo --> PER
    CAR -- Ejemplar de Nacionalización y Retórica Social --> PER
    
    %% 2. Flujo de Mecanismos hacia la Doctrina
    PER -- Pragmatismo: Dejar Jugar Corrientes Sociales --> JUST
    PER -- Reluctancia a Citar Fuentes --> JUST
    
    FIG -- Provisión de Andamiaje para Política Laboral Inicial --> JUST
    SAM -- Provisión del Marco Legal-Institucional (Const. 1949) --> CONST
    CONST -- Ley de Derechos del Trabajador / Sustitución de 1853 --> JUST
    STP -- Reorganización de Trabajadores / Superación Anarquista --> CGT
    CGT -- Alineación con el Proyecto de Desarrollo Estatal --> JUST
    
    %% 3. Flujo de Resultados y Puntos Clave
    JUST -- Redistribución que Puso >50% del Ingreso en Obreros --> SOCI
    JUST -- Modernización y Sustitución de Burguesía --> ECON
    JUST -- Compromiso con Establecer Justicia como Base Social --> SOCI
    JUST -- Evitó Diseñar Ideas en un "Laboratorio" --> PER

    %% 4. Conexiones Cruzadas y Contexto
    GOU -- Vía para la Transformación Social --> PER
    APRA -- Fuente de Retórica Antimperialista --> POL_EXT
    POL_EXT -- Carácter No-Fascista (Refutación Estructural) --> TERCERISMO(Tercera Posición)
    PER -- Sustituyó al Capitalismo Liberal y al Marxismo --> POL_EXT
    JUST -- Fue Percibido por Oponentes como Autoritarismo Totalizador --> (Críticas)
```
    %% 5. El Lazo Directo entre Redistribución y Desarrollo
    SOCI((Justicia Social)) -- Combustible para el Consumo Masivo --> ECON((Ind. Económica))
