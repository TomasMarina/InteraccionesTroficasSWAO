# Interacciones tróficas en el Océano Atlántico Sudoccidental
Repositorio de interacciones tróficas (presa-depredador) en el Océano Atlántico Sudoccidental.
Bases de datos consultadas: Global Biotic Interactions (GloBI).

El conjunto de datos recuperado corresponde a registros georreferenciados de interacciones tróficas extraídos a través de la API de GloBI.
Se trata de una red de interacciones depredador-presa (tróficas) limitadas estrictamente al polígono del Océano Atlántico Sudoccidental,
abarcando desde el Ecuador hasta el límite Antártico y el Pasaje de Drake.

Estructura: Cada fila representa una observación única de una interacción entre dos organismos.

Variables clave:

source_taxon_name y target_taxon_name: Indican los nombres científicos de las especies involucradas
(el consumidor y el recurso, o viceversa, dependiendo del tipo de interacción).

interaction_type: Define el rol ecológico en el encuentro
(por ejemplo, eats o preysOn significa que el taxón de origen depreda al taxón objetivo).