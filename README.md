# Bikepacking Journal

[https://bikepacking.haslehurst.net](https://bikepacking.haslehurst.net)

This repo contains the source for my bikepacking journal.

### Resizing images

First install `imagemagick` and `jpegoptim` from Homebrew, then:

```
$ mogrify -resize 2500x2500 *.jpg
$ jpegoptim -m85 *.jpg
```
