# How to convert Imacon Photo / 343 to 646 848 949 Hasselblad X1 X5

The 1st question is why? </br>
¿Why a Film Scanner in the Digital Era? </br>
similar dilema: </br>
LP´s Vinyl 12" vs. 320kbps .mp3 / .flac / .wav </br>
.tiff vs. .jpg </br>

Digital camera is "the same" sensor direct to lens / source, </br>
skipping film, develpment, chemicals, Faster, etc... </br>

some people condense the answer to a simple: </br>
Silver particles capture light different. </br>
but is it? </br>

[C-41 Color](https://en.wikipedia.org/wiki/C-41_process) Negative Film or [E-6 Color](https://en.wikipedia.org/wiki/E-6_process) Positive Film, have RGB in micron layers each over the other, like 3 Lens [RGB Projectors](https://www.youtube.com/watch?v=CURsJDfdbfc&t=498s) and 3 CRT [Projector TV´s](https://www.youtube.com/watch?v=DdgzgeGw78E&t=259s), in parallel to display RGB. </br>
Digital sensor RGB pixels are microns to the side, slightly out-of-phase, like [YUV 4:2:0 Chroma Subsampling](https://en.wikipedia.org/wiki/Chroma_subsampling) </br>
RGB pixels are Not alighned in X-Y axis like Analog, Analog Film has a small phase shift / skew in the Z-Axis, </br>
Some lenses have bigger Out of Phase shift, and the sollution is [Apochromatic lenses](https://en.wikipedia.org/wiki/Apochromat) to minimize Z-Axis aberrations. </br>
RGB Pixels depend on the brand, have [different patterns](https://en.wikipedia.org/wiki/Bayer_filter) </br>

Profesional CCD Scanners like Imacon / Hasselblad sensor have: 1 or 3 pixel x 8000 </br>
Horizontal is Bigger 8cm / 80mm vs. Medium Format 57mm Digital Backs & 35mm Full Frame sensors. </br>
Semi-Profesional Flatbed scanners like Epson v600-v850 have a 1" sensor, and concave / [parabolic reflector](https://en.wikipedia.org/wiki/Parabolic_reflector) mirrors to shrink the image. </br>
older Profesional Drum Scanners have PMT ["Photo-Multiplier Tubes"](https://en.wikipedia.org/wiki/Photomultiplier_tube) to convert the photons that enter the aperture into electrons, and amplify electrons to minimize signal to noise ratio, and match Analog to Digital converters </br>

Digital quality depends on the size of the sensor, Light Lumens & Digital ISO </br>
sensors like [Sony x1000v](https://www.sony.com/electronics/support/action-cam-fdr-x-series/fdr-x1000v/specifications) 1/2.3" sensor require over >1000 Lumens in video mode lumens at 24fps to minimize digital noise, more at 3fps, 60fps, 120fps, 240fps. </br>
Some Digital cameras use all kinds of tricks to improve low light sensitivity, </br>

old sensors like [PhaseOne P45+](http://www.phaseonekorea.com/datasheet/Phase-One-645DF-P45-p-datasheet-english.pdf) iso 80 "the minimum setting" gives much better quality vs. ISO 800 </br>
using High Speed Flash, the difference is Night & Day in Resolution: [LinePairs/mm](https://en.wikipedia.org/wiki/1951_USAF_resolution_test_chart) </br>
Basically its 50MegaPixels at ISO 80, and Resolution lowers as ISO increase, but file size is the same, similar to Epson scanners and [mega pixel phone cameras](https://www.youtube.com/watch?v=FoF_JeWnvu8&t=274s) that file size increase but [LinePairs/mm](https://en.wikipedia.org/wiki/1951_USAF_resolution_test_chart) does Not. </br>
Newer Sensors have improved low light sensitivity drastically, for example: old Samsung S860 vs. Newer Motorola G20 Phone camera </br>

Cameras like [Sony A7S](https://en.wikipedia.org/wiki/Sony_α7#Model_differences) use a 24MegaPixel sensor, Pixel Pairs in parallel, to double low light sensitivity. </br>
but that method lowers Resolution: [LinePairs/mm](https://en.wikipedia.org/wiki/1951_USAF_resolution_test_chart) becoming a [12MegaPixel camera.](https://en.wikipedia.org/wiki/Sony_α7#Model_differences), </br>
Physical Pixel Pairs or "Digital Pixel Pairs" or both methods</br>
Physical RGB Pixel pairs also increase pixel skew phase error. </br>

Film Camera: </br>
most require a mirror, mirror creates vibrations, affecting Resolution: [LinePairs/mm](https://en.wikipedia.org/wiki/1951_USAF_resolution_test_chart) </br>
Medium Format cameras require 1/125 speed or faster to avoid mirror vibrations in 6x6 film or digital back, </br>
35mm cameras have a smaller mirror, less agressive vibrations, body of the camera can absorb / contain vibrations more easy, vibrations spread different. </br>

#### Analog and Digital are affected by different things: </br>
C-41 was designed to be developed at 104°F / 40°C for 3:00 minutes exactly </br>
if you develop C-41 at room temp. 20°C to avoid toxic smell vapour, requires much more time, arround ~20 minutes, and colors will be completely "wrong",  </br>
developing at room temp. requires more time in post, in a software like GIMP or Imacon / Hasselblad FlexColor 4.0 to color correct the scan, but that gives more artistic / creative freedom </br>
developing at recommended settings, gives a "standard" look, like flipping burgers, less random, more controlled / generic result. </br>
older versions of GIMP could Not Edit in 16-Bit RGB mode, Imacon software could since 1997, but latest versions of GIMP work ok at 16-Bits, the only problem is Dither, is On by default, at the beggining of the chain. </br>

1 year Expired film has lower Blue saturation / sensitivity. </br>

