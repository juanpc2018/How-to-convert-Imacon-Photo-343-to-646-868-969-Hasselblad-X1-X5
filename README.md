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
RGB pixels are Not aligned in X-Y axis like Analog, Analog Film has a small phase shift / skew in the Z-Axis, </br>
Some lenses have bigger Out of Phase shift, and the sollution is [Apochromatic lenses](https://en.wikipedia.org/wiki/Apochromat) to minimize Z-Axis aberrations. </br>
RGB Pixels depend on the brand, have [different patterns](https://en.wikipedia.org/wiki/Bayer_filter) </br>

Profesional CCD Scanners like Imacon / Hasselblad sensor have: 1 or 3 pixel x 8000 </br>
Horizontal is Bigger 8cm / 80mm vs. Medium Format 57mm Digital Backs & 35mm Full Frame sensors. </br>
The lack of pixels in the Vertical axis, is compensated by moving the film in micro steps with a stepper motor. </br>

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

------------------

 Imacon Photo / 343 has some important differences vs. 646 848 949 Hasselblad X1 X5

Photo vs. 343 are basically the same, Not a big difference, </br>
the main upgrade is that 343 has modern Firewire port, and allows Newer Flexcolor 4.8 software, but 4.8 is almost the same as FlexColor 4.0, the Zoom tool is a bit different </br>
Photo is SCSI Only, limited to FlexColor 4.0 </br>

both have the same problems: </br>
the Virtual Drum "the Air Barrel Drum" moves flexholder Upward, against gravity, making a posibility of sliding -0.1mm easy, </br>
an error of 0.1mm is very visible when scanning at 3200ppi / 126ppmm </br>

both scanners are slow, takes 15 minutes to scan a 6x18 "3x 6x6" </br>
Not because SCSI in Async Mode is 5MB/s, 6x18 RAW File is 1600MB = 320seconds = 5.3 minutes. </br>

its because the 386sx CPU and the 4MB PC100 72-pin memory. </br>
The X5 is a rocket, super fast, like scanning at 150ppi. </br>

sliding -0.1mm scan is ruined, requires to re-scan, </br>
cleaning the edges of the flexholder with alchohol to remove any finger sweat oil grease, works ok but Not always </br>
some people open the scanner and replace springs with stronger springs, </br>
in my opinion on the long run thats a mistake, </br>
because virtual drum is rubber, with time rubber will become compact, drum radius / diameter -0.1mm smaller, increasing the problem in the end. </br>
cleaning the Virtual drum rubber from grease, finger sweat / grease works better. </br> 

the bigger / newer brothers: </br>
646 848 949 & Hasselblad X1 X5 are the opposite, </br>
virtual drum rotates downward with gravity, not against, much more stable, less prone to slide errors. </br>

343 / Photo problem can be solved very easy by placing rubber feet on the top of the scanner, and place the scanner up side down, very easy mod, works flawless. </br>
but thats Not the only problem... </br>

Imacon scanners have an Instant Start Ballast technology, </br>
KinoFlo 165x has Rapid Start ballast technology. </br>

instant Start ballast, generates a very high volgate to [kick start](https://www.youtube.com/watch?v=ybcxIpb-R_0&t=30s) the mercury spheres / vapour inside the 6" CFL Tube </br>
after a few seconds, voltage retun to standard operating voltage around 100v-150v AC </br>

Rapid Start Ballast, there is No Kick start, IF Ballast is set to 100% output, will generate standard voltage only, </br>
in this technology CFL tube needs several minutes to warm up and stabilize, the usual 15-minutes / 30-minutes. </br>
The advantage of Instant Start is obvious </br>
the advantege of Rapid start is Not as obvious: Extended bulb life. </br>

Other problem of Imacon Scanners is that were designed around a CFL bulb No longer manufactured by Osram </br>
Newer bulbs are "better" have more lumens output for the same watts, brighter, </br>
Most Newer bulbs have a lower quality [CRI](https://en.wikipedia.org/wiki/Color_rendering_index), but KinoFlo KF55 bulbs have similar or higher [Color Rendering Index](https://en.wikipedia.org/wiki/Color_rendering_index) "Higher Quality" </br>
 
Imacon CCD sensor requires a 2-stop down .6 lower light / exposure, and brighter bulbs give wrong exposure "too dark" if negative was exposed properly, and developed properly, </br>
internal Ballast is factory calibrated to older lower output bulb </br>
has 2x 10-turn trimp pots, and output can be re-calibrated, but... </br>
there is another problem: </br>
Ballast designed for Profesional photography has an oscillating frequency of 25KHz to 50KHz, </br>
when Ballast output is lowered too much, bulb becomes unstable, generating horizontal lines on the scan, some lines are brighter some are darker. <br>

The proper sollution to that dilema: </br>
is placing a 4x5 flass ND .6 filter between the bulb and the negative. </br>
or between the negative and the 1:1 Lens </br>
i did tests, placing the ND.6 filter between the bulb and the negative gives better results. in my opinion. </br>
one of the reasons is that a bright light inside a black chanmber, creates reflections, </br>
imacon chamber is Not painted with [Kiwami Black](https://www.youtube.com/watch?v=43OGgDaR2aE&t=29s) </br>
using a cheaper / smaller ND.6 filter in-front of the 1:1 lens Require Kiwami Black. </br>








