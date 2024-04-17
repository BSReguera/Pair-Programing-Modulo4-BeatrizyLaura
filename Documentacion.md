## DOCUMENTACIÓN

Estudio de Canciones Populares desde los años 90 hasta la Actualidad.

Para nuestro análisis, utilizaremos un dataset que incluye las siguientes columnas:

- trackname: Nombre de la canción.
- artist(s)name: Nombre del artista o artistas.
- country: País asociado.
- artistcount: Número de artistas en la canción.
- releasedyear, releasedmonth, releasedday: Fecha de lanzamiento.
- inspotifyplaylists, inspotifycharts: Presencia en listas de reproducción y gráficos de Spotify.
- streams: Número de streams.
- inappleplaylists, inapplecharts: Presencia en listas de reproducción y gráficos de Apple Music.
- indeezerplaylists, indeezercharts: Presencia en listas de reproducción y gráficos de Deezer.
- inshazamcharts: Presencia en gráficos de Shazam.
- bpm, danceability, valence, energy, acousticness, instrumentalness, liveness, speechiness: Características musicales.

# Objetivos
Objetivo principal: Explorar y visualizar datos para comprender mejor la evolución de la música popular desde los años 90 hasta la actualidad, utilizando diferentes métricas y características musicales.

Objetivos Específicos:
- 1. Análisis de popularidad por año y país:
Determinar la popularidad de las canciones lanzadas desde los años 90 hasta la actualidad.
Analizar la popularidad de artistas por país de origen.
- 2. Comparar los atributos y caraterísticas de las canciones más visualizadas de los últimos años.
Observar la relación entre BPM (beats per minute/ pulsos por minutos) y Géneros Musicales (pop, electro, baladas etc...):
- 3. Observar la popularidad y características de los 10 artistas con una mayor popularidad (streams).

# Dashboards Propuestos:
Interpretaciones de los Dashbords y Gráficos:

Dashboard 1:
El primer dashboard ofrece una visión general de la diversidad geográfica de los artistas musicales con 41 paises, 645 artistas, 943 canciones, destacando una concentración significativa en Estados Unidos(38,4%), seguido por el Reino Unido(11,1%) y Canadá(7,7%). Esto revela la prominencia de estos países en la escena musical global. Además, identifica claramente los artistas más populares según las visualizaciones, mostrando el dominio de figuras como The Weekend, Taylor Swift y Ed Sheeran. Los filtros para buscar artistas o canciones permiten una exploración más detallada y personalizada de la base de datos.

Dashboard 2:
El segundo dashboard revela la influencia de las plataformas de transmisión musical en la popularidad de las canciones, con Spotify, Deezer y Apple Music emergiendo como las aplicaciones más utilizadas por los oyentes. Asimismo, las clasificaciones de las canciones por género basadas en el ritmo (bpm) proporcionan información valiosa sobre las preferencias musicales actuales. Esta tendencia ascendente en la industria musical, impulsada por la tecnología, muestra cómo las nuevas plataformas están dando forma al consumo de música.
- Rap: 90-110 BPM.
- Hip Hop: 80-100 BPM.
- Reggae: 90-120 BPM.
- Cumbia : 90-110 BPM.(México)
- Reggaetón: 100-120 BPM.
- Pop/rock/ Dance: 120-140 BPM.
- Rock metálico/ Punk 140-190 BPM.

Dashboard 3:
El tercer dashboard podemos observar la procedencia de cada artista con mayor visualización (top 10) junto con sus atributos musicales: Liveness, Speechiness, Valence, Danceability, Energy, Acoustiness. 
- Liveness: ¿Suena como si fuera en vivo o en estudio?
- Speechiness: ¿Cuánto habla la canción en lugar de cantar?
- Valence: ¿Qué tan positiva o negativa es la canción?
- Danceability: ¿Es adecuada la canción para bailar?
- Energy: ¿Cuán enérgica es la canción?
- Acousticness: ¿Qué tan acústica es la canción en comparación con electrónica?
Finalizando con un link de acceso a una playlist de los artistas. 

# Conclusiones:
- Observar el surgimiento de nuevos artistas populares en la era digital y tecnológica.
- Identificar tendencias de géneros musicales en función del ritmo y la energía de las canciones.
- Analizar la influencia de la disponibilidad en plataformas de streaming en la popularidad de canciones y artistas.
- Identificar de los diez artistas más populares que atributos les ha llevado a la fama. 


# Next Steps: 
- Transferencia del dataset a una base de datos SQL, para tener las últimas tendencias musicales. 
- Elaboración de diferenes gráficos con el fin de tener un análisis más completo de las variables. 