# Roller Thrower Die Soon

Throw guests to their death for fun. Roller Thrower Die Soon is our submission to Tojam in Allegro 5.

## Getting started

### Windows (MSYS2)

#### Install Libraries

```bash
pacman --noconfirm -S mingw-w64-i686-gcc-libs mingw-w64-i686-dumb mingw-w64-i686-flac mingw-w64-i686-opusfile mingw-w64-i686-freetype mingw-w64-i686-libjpeg-turbo mingw-w64-i686-libpng mingw-w64-i686-libvorbis mingw-w64-i686-libwebp mingw-w64-i686-openal mingw-w64-i686-physfs mingw-w64-i686-allegro
```

#### Build

```bash
cmake -G "MSYS Makefiles" .
```

```bash
make
```

### Mac OS

#### Install Libraries

```bash
brew install allegro
```

#### Build

```bash
cmake -G "Unix Makefiles" .
```

```bash
make
```

### Linux

#### Install Libraries

```bash
sudo apt install liballegro5-dev liballegro-acodec5-dev liballegro-audio5-dev liballegro-image5-dev liballegro-dialog5-dev liballegro-ttf5-dev
```

#### Build

```bash
cmake -G "Unix Makefiles" .
```

```bash
make
```
