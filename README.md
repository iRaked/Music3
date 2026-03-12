============================================================
       📻 RADIO TEKILEROS - MUSIC DATABASE (2026)
============================================================

[ DESCRIPCIÓN ]
Gestión centralizada de activos de audio y arte para la 
plataforma Spotune. Optimizado para Vercel y GitHub Pages.

------------------------------------------------------------
[ 📊 INVENTARIO DE RECURSOS ]
------------------------------------------------------------
SECCIÓN             GÉNERO              TOTAL TRACKS
------------------------------------------------------------
Asfalto Urbano      Rock Urbano         88
Skañol              Ska en Español      35
Zona Ska            Ska Internacional   22
La Cantina          Regional/Ranchera   105
------------------------------------------------------------
TOTAL GENERAL                           250 TRACKS
------------------------------------------------------------
ALMACENAMIENTO:
> CARIBE 360: 650MB
> CANTINA:    460MB

------------------------------------------------------------
[ 📁 ESTRUCTURA DE ALMACENAMIENTO ]
------------------------------------------------------------
COVERS: https://iraked.github.io/SantiGraphics/assets/cover3/
AUDIO:  https://radio-tekileros.vercel.app/assets/audio3/

------------------------------------------------------------
[ 🚀 POLÍTICA DE ESCALABILIDAD ]
------------------------------------------------------------
! CAUTION: Límite de 1,000 tracks por directorio.
Al alcanzar el límite, migrar a las siguientes rutas:
- AUDIO:  assets/audio4/
- COVERS: assets/cover4/

------------------------------------------------------------
[ 🛠️ ESTÁNDAR JSON (TEMPLATE) ]
------------------------------------------------------------
{
  "id": "nombre-del-track-en-minusculas",
  "caratula": "https://url.com/assets/cover3/ID.jpg",
  "artista": "Nombre Real",
  "nombre": "Nombre de la Canción",
  "album": "Disco Original",
  "enlace": "https://url.com/assets/audio3/ID.mp3",
  "genero": "PalabraUnica",
  "emotion": "PalabraUnica",
  "seccion": "nombre-seccion",
  "duracion": "0:00",
  "country": ["México"]
}

============================================================
      CONTROL DE VERSIONES: v3.0 | STABLE RELEASE
============================================================
