Music
📻 Radio Tekileros - Base de Datos Musical
Este repositorio gestiona los recursos de audio y arte para las secciones principales de la plataforma. Todo el contenido está optimizado para su despliegue mediante Vercel y GitHub Pages.

📊 Inventario de Tracks (2026)
Sección	Género	Total de Tracks
Asfalto Urbano	Rock Urbano	88
Skañol	Ska en Español	35
Zona Ska	Ska Internacional/Local	22
TOTAL GENERAL		145 tracks
📁 Estructura de Almacenamiento Actual
Para garantizar la estabilidad del servicio, los assets están distribuidos de la siguiente manera:

Carátulas: https://iraked.github.io/SantiGraphics/assets/cover1/
Audios: https://radio-tekileros.vercel.app/assets/audio2/
🚀 Reglas de Escalabilidad y Migración
Para prevenir errores de lectura en el servidor y saturación de directorios, se ha definido la siguiente política de mantenimiento:

Caution

Límite de 1,000 Tracks
Al momento en que el conteo global de la base de datos alcance los 1,000 tracks, se deberá realizar la migración inmediata a las nuevas carpetas de destino:

Nueva ruta de Audio: assets/audio3/
Nueva ruta de Covers: assets/cover2/
🛠️ Estándar de Formato "Asfalto Urbano"
Todas las nuevas entradas deben respetar estrictamente el siguiente esquema JSON:

{
  "caratula": "https://iraked.github.io/SantiGraphics/assets/cover1/ID.jpg",
  "id": "nombre-del-track-en-minusculas",
  "emotion": "PalabraUnica",
  "artista": "Nombre Real",
  "nombre": "Nombre de la Canción",
  "album": "Disco Original",
  "enlace": "https://radio-tekileros.vercel.app/assets/audio2/ (.mp3 / .MP3)",
  "duracion": "0:00",
  "genero": "rock urbano",
  "country": ["México"]
}

