# Actividades 1 y 2 de Semana Pre-Hackatón
Repositorio de interacciones tróficas (presa-depredador) en el Océano Atlántico Sudoccidental.
El conjunto de datos unificado corresponde a registros de interacciones bióticas, consolidando información extraída de la API de GloBI y 
registros suplementarios provenientes del archivo local ListaInteracciones_BurdwoodBank.csv. Al aplicar nuestros filtros espaciales y combinar los datos, el data frame resultante posee las siguientes características:

Naturaleza de los datos: Se trata de una red ampliada de interacciones depredador-presa (tróficas). 
Los registros de GloBI están limitados estrictamente al polígono del Océano Atlántico Sudoccidental, y ahora se encuentran enriquecidos por los datos empíricos específicos del Banco Burdwood.

Estructura: Cada fila representa una observación única de una interacción entre dos organismos. 
La función bind_rows garantizó que las columnas coincidentes entre ambas fuentes se alinearan correctamente, rellenando con valores nulos (NA) aquellas variables que solo existían en una de las dos tablas.