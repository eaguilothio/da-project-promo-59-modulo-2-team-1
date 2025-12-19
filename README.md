# grupo_1_proyecto_2_music_stream

# 🎶 MusicStream
*Análisis musical de 2010 a 2018 con datos reales de Spotify y Last.fm*

> Proyecto del Módulo 2 realizado por **5 mujeres apasionadas por la música y los datos**.  
> Objetivo: hacer un **análisis de datos** de cómo evolucionaron géneros, artistas y canciones entre 2010 y 2018.

---

## 🎯 Objetivo
Analizar la **evolución de la música** entre 2010 y 2018 a partir de datos de **Spotify** y **Last.fm**, centrándonos en **"country","latin","jazz","rock"**.  

Buscamos mostrar de manera clara cómo evolucionaron los géneros, cuáles artistas se mantuvieron activos a lo largo de los años y qué canciones o álbumes alcanzaron mayor popularidad.

---

## 🛠️ Cómo lo hicimos

### 1. Extracción de datos 

## Datos obtenidos
- **Rango temporal:** 2010–2018 (cada 2 años: 2010, 2012, 2014, 2016, 2018)  
- **Géneros musicales:** country, latin, jazz, rock  

## Plataformas y campos
- **Spotify API:** artista, género, tipo (canción o álbum), nombre, año, cantidad de canciones  
- **Last.fm API:** biografía, número de oyentes (*listeners*), reproducciones (*playcount*), artistas similares  


---

### 2. Almacenamiento de la información

- **Base de datos**: se utiliza para almacenar y gestionar la información de forma estructurada y eficiente.
- **Tabla base**: todos los datos se concentran en una sola tabla, evitando la complejidad de relaciones y tablas intermedias.
- **Carga de datos**: se genera un archivo CSV consolidado con la información de todos los años, integrando datos de Spotify y Last.fm, que luego se utiliza para la inserción en la base de datos.

---

### 3. Análisis y conclusiones
- **Consultas analíticas**: se exploran los datos para identificar tendencias musicales, evaluar la popularidad de artistas y detectar patrones de consumo, a partir de preguntas de interés analítico.

---

## 🧠 Metodología
Trabajamos con **Agile + Scrum**, con roles:  
- **Scrum Master:** facilita el flujo  
- **Equipo de desarrollo:** construye y valida el análisis  
