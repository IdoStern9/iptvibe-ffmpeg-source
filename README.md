# FFmpeg source for IPTVibe

The IPTVibe Android app includes FFmpeg 6.0.1 audio decoders (ac3, eac3, dca, truehd) as shared libraries, licensed under the GNU LGPL v2.1.

The exact source and the build script are attached to the release:
https://github.com/IdoStern9/iptvibe-ffmpeg-source/releases/tag/ffmpeg-6.0.1

Configure flags include --disable-gpl --disable-nonfree --enable-shared --disable-static. See build-ffmpeg.sh for the full build.
