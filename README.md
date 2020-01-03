# Illusion

This is a variant of Gianni Sarcone's (@gsarcone) illusion, which is itself a variant of the original Müller-Lyer illusion

See [tweet](https://twitter.com/Chris_Said/status/1213217943414136833) for more details 

The notebook is somewhat cleaned up. The `make_animation` function will create some .png files that you can stitch together into an animated gif with ImageMagick

```
convert -delay 7 -loop 0 frame*.png  animation.gif
```
