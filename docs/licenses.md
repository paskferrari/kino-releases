---
title: Licenze open source
permalink: /licenses/
---

# Licenze open source / Open-source licences

Kino è software proprietario che include componenti open source. L'elenco completo, con i testi delle licenze, è nell'app: **Impostazioni → Licenze open source**. Kino is proprietary software that includes open-source components; the full list with licence texts is in the app under Settings → Open-source licences.

## Motore video / Video engine

| Componente | Licenza | Sorgente |
|---|---|---|
| libmpv (mpv-player/mpv), compilato senza componenti GPL | LGPL-2.1-or-later | <https://github.com/mpv-player/mpv> |
| FFmpeg (`--disable-gpl --disable-nonfree --enable-version3`) | LGPL-3.0 | <https://ffmpeg.org/download.html> |
| Build Android (media_kit_libs_android_video, flavor "default") | LGPL | <https://github.com/media-kit/libmpv-android-video-build> |
| dav1d | BSD-2-Clause | <https://code.videolan.org/videolan/dav1d> |
| mbedTLS | Apache-2.0 | <https://github.com/Mbed-TLS/mbedtls> |
| libass | ISC | <https://github.com/libass/libass> |
| FreeType | FTL | <https://freetype.org> |
| HarfBuzz | MIT | <https://github.com/harfbuzz/harfbuzz> |
| FriBidi | LGPL-2.1 | <https://github.com/fribidi/fribidi> |
| libxml2 | MIT | <https://gitlab.gnome.org/GNOME/libxml2> |
| shaderc | Apache-2.0 | <https://github.com/google/shaderc> |
| libvpx | BSD-3-Clause | <https://chromium.googlesource.com/webm/libvpx> |
| media_kit (Flutter) | MIT | <https://github.com/media-kit/media-kit> |

Le librerie LGPL sono incluse nell'app come librerie dinamiche separate (`.so`) e non vengono modificate: l'utente può sostituirle con una versione compatibile. The LGPL libraries ship as separate, unmodified dynamic libraries (`.so`) and can be replaced by the user with a compatible version.

Testi: [LGPL-2.1](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.txt) · [LGPL-3.0](https://www.gnu.org/licenses/lgpl-3.0.txt)

## Font

- Plus Jakarta Sans — [SIL Open Font License 1.1](https://github.com/tokotype/PlusJakartaSans/blob/master/OFL.txt)

## Framework

- Flutter (BSD-3-Clause) e pacchetti Dart: dio, provider, shared_preferences, path_provider, cached_network_image, package_info_plus, open_filex, sqflite, xml, url_launcher e altri, ciascuno con la propria licenza MIT/BSD/Apache, elencati nell'app.
