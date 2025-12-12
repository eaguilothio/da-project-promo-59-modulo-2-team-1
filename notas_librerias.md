# ────────────────────────────────────────────────
# 1. Cargar librerías necesarias
# ────────────────────────────────────────────────

# 🔹 Librerías de la biblioteca estándar de Python
# → Ya vienen instaladas con Python. No necesitan 'pip install'.
# → Se usan para tareas comunes sin depender de paquetes externos.

import os
# 'os' = "operating system" (sistema operativo)
# Permite interactuar con el sistema de archivos: crear carpetas, leer rutas,
# y, muy importante, acceder a variables de entorno (ej. claves de API en .env).

import time
# Permite pausas controladas con time.sleep(segundos).
# Muchas APIs (como Spotify) tienen "rate limits": límites de peticiones por segundo/minuto.
# Si los excedes, puedes recibir error 429 o ser bloqueado temporalmente.
# Añadir pausas evita este problema y hace tu código más respetuoso con el servicio.

# 🔹 Librerías externas
# → NO vienen con Python. Debes instalarlas con: pip install nombre_paquete
# → Se gestionan como dependencias del proyecto (ej. en requirements.txt).

import pandas as pd
# Librería para trabajar con datos tabulares (como hojas de Excel, pero en código).
# El alias 'pd' es una convención universal: más corto y legible.

import spotipy
# Librería oficial de Python para acceder a la API de Spotify.

from spotipy.oauth2 import SpotifyClientCredentials
# Permite autenticarte en Spotify usando el flujo "Client Credentials" (OAuth 2.0).
# Solo necesitas tu Client ID y Client Secret (¡nunca los escribas directamente en el código!).
# Lo seguro es cargarlos desde variables de entorno (ej. con python-dotenv).