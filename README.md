# Perceptually uniform color spaces

Short presentation to be given by Will Henney at DAWGI, Morelia meeting 2023-04-24

## Summary

Suppose we want to write some red, green, and blue text. We want the red, green and blue to be equally bright, so that the text is easy to read. I will show why this is difficult to do in the RGB color space, and how perceptually uniform color spaces, such as CIE L\*a\*b\* and HSLuv can help. 

## Resumen

Supongamos que queremos escribir un texto rojo, verde, y azul. Queremos que el rojo, el verde y el azul tengan el mismo brillo, para que el texto sea fácil de leer. Mostraré por qué esto es difícil de hacer en el espacio de color RGB, y cómo los espacios de color perceptualmente uniformes, como CIE L\*a\*b\* y HSLuv, pueden ayudar.

## Links

* [RGB wikipedia page](https://en.wikipedia.org/wiki/RGB_color_space)
* [Color model wikipedia page](https://en.wikipedia.org/wiki/Color_model)
* [Spectral sensitivity wikipedia page](https://en.wikipedia.org/wiki/Spectral_sensitivity)
* [Wavelength sensitivity of cones (U. Toronto)](https://www.physics.utoronto.ca/~jharlow/cones.html)
* [CIELab wikipedia page](https://en.wikipedia.org/wiki/CIELAB_color_space)
* [HSLuv online visual conversion tool](https://www.hsluv.org/)
* [CIELuv wikipedia page](https://en.wikipedia.org/wiki/CIELUV)

## Slides

![Slide 01](./cspace-01-RGB.jpg)

We want to write some red, green, and blue text, and we want the red, green and blue to be equally bright, so that the text is easy to read. But this is difficult to do in the RGB color space.

Naively, we might try to max out the red, green and blue values, but this gives us a green that is very bright (hard to see on a bright background) and a blue that is very dark (hard to see on a dark background).

The reason for this is that the RGB color space is not perceptually uniform. This means that equal changes in the RGB values do not correspond to equal changes in the perceived brightness of the color. This is mainly due to the [spectral response of the three types of cone cells in the human eye](https://www.physics.utoronto.ca/~jharlow/cones.html). 

![Relative sensitivity curves for the three types of cones log vertical scale, cone spectral curves from "On the derivation of the foveal receptor primaries" by J.J. Vos and P.L. Walraven (1971) Vision Research 11, 799-818.](https://www.physics.utoronto.ca/~jharlow/conesens1.gif "Relative sensitivity curves for the three types of cones log vertical scale, cone spectral curves from "On the derivation of the foveal receptor primaries" by J.J. Vos and P.L. Walraven (1971) Vision Research 11, 799-818.
")


![Slide 02](./cspace-02-Lab.jpg)
![Slide 03](./cspace-03-Lab.jpg)
![Slide 04](./cspace-04-HSLuv.jpg)
![Slide 05](./cspace-05-HSLuv.jpg)
![Slide 06](./cspace-06-HSLuv.jpg)
![Slide 07](./cspace-07-HSLuv.jpg)





