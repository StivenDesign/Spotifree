# Spotifree

Reproductor de música para Android con interfaz inspirada en Apple Music. Reproduce con YouTube Music, muestra letras sincronizadas palabra por palabra y tiene portadas animadas.

Creado por **Steven Pantoja**.

## Qué tiene

- **Pantallas:** Inicio, Novedades, Radio, Biblioteca y Buscar, con páginas de artista y de álbum.
- **Reproductor:** portada en 3D, colores que se adaptan a la canción, gestos para cerrar y modo horizontal.
- **Letras:** varios proveedores, brillo por palabra, puntos de espera en los instrumentales, dúos a ambos lados y modo karaoke.
- **Portadas animadas:** ilustración animada de Apple cuando existe, y animaciones propias de la app para el resto.
- **Música local y descargas:** escaneo de la música del teléfono y descargas desde fuentes legales.
- **Mezcla entre canciones:** crossfade con presets, curva, reverb y vista previa.
- **Audio:** ecualizador de 5 bandas, normalización de volumen, saltar intro y final, y reproducción estable en segundo plano.
- **Rendimiento:** calidades de Ultra a Patata, tasa de refresco (Hz) y ahorro de batería.
- **Respaldo y restauración** de tu biblioteca y ajustes.
- **Avisos de actualización** dentro de la app.

## Instalar

1. Entra a la pestaña **Releases** de este repositorio.
2. Descarga el archivo `app-debug.apk` de la versión más reciente.
3. Ábrelo en tu teléfono y permite instalar apps de origen desconocido si Android lo pide.

## Avisos de actualización

En la app: **Ajustes › Acerca de**. Escribe el repositorio como `usuario/repositorio` y activa "Avisar de actualizaciones". Cuando haya una versión nueva, la app lo avisa y te deja descargarla.

## Compilar

El APK se compila solo con GitHub Actions cada vez que se suben cambios (`.github/workflows/build.yml`) y se publica como Release. El proyecto es una app Android con Kotlin que muestra una interfaz web (HTML, CSS y JavaScript) dentro de un WebView.

## Aviso

Spotifree no extrae ni descarga audio de Spotify, YouTube o Apple Music, ni evita protecciones de copia. Las descargas son solo de fuentes que lo permiten. Usa la app respetando los derechos de autor y los términos de cada servicio.
