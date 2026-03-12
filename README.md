📻 Radio Tekileros - Base de Datos MusicalEste repositorio centraliza y gestiona los activos de audio y arte para las secciones principales de la plataforma. La arquitectura está diseñada para un consumo eficiente mediante Vercel y GitHub Pages.📊 Inventario de Tracks (2026)SecciónGénero PrincipalTotal TracksAsfalto UrbanoRock Urbano88SkañolSka en Español35Zona SkaSka Internacional/Local22La CantinaRegional / Ranchera105TOTAL GENERAL—250 tracks[!NOTE]Almacenamiento Acumulado: > * CARIBE 360: 650MBCANTINA: 460MB📁 Estructura de AssetsPara garantizar la estabilidad del servicio y evitar latencias, los recursos se distribuyen de la siguiente manera:Carátulas: https://iraked.github.io/SantiGraphics/assets/cover3/Audios: https://radio-tekileros.vercel.app/assets/audio3/🚀 Reglas de Escalabilidad y MigraciónPara prevenir errores de lectura (404) y saturación de directorios, se aplica la siguiente política de mantenimiento:[!CAUTION]Límite de 1,000 TracksAl alcanzar los 1,000 tracks globales, es obligatorio iniciar la migración a las nuevas rutas de destino para mantener la integridad del despliegue:Nueva ruta Audio: assets/audio4/Nueva ruta Covers: assets/cover4/🛠️ Estándar de Formato JSONTodas las entradas deben seguir estrictamente este esquema para asegurar la compatibilidad con el reproductor:JSON{
  "id": "nombre-del-track-en-minusculas",
  "caratula": "https://iraked.github.io/SantiGraphics/assets/cover3/ID.jpg",
  "artista": "Nombre Real",
  "nombre": "Nombre de la Canción",
  "album": "Disco Original",
  "enlace": "https://radio-tekileros.vercel.app/assets/audio3/ID.mp3",
  "genero": "GéneroÚnico",
  "emotion": "PalabraÚnica",
  "seccion": "nombre-seccion",
  "duracion": "0:00",
  "country": ["País"]
}
📋 Checklist de Actualización[ ] Validar que el id sea único y en minúsculas.[ ] Verificar que el archivo .mp3 no contenga espacios en el nombre.[ ] Comprobar que la carátula esté en formato .jpg.[ ] Actualizar el conteo en la tabla de inventario.
