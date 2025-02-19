# How to convert Imacon Photo / 343 -to-> 646 848 949 X1 X5

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

[C-41 Color](https://en.wikipedia.org/wiki/C-41_process) Negative Film or [E-6 Color](https://en.wikipedia.org/wiki/E-6_process) Positive Film, have RGB in micron layers each over the other, like 3 Lens [RGB Projectors](https://www.youtube.com/watch?v=CURsJDfdbfc&t=498s) and 3 CRT [Projector TV´s](https://www.youtube.com/watch?v=DdgzgeGw78E&t=259s), to display RGB. </br>
Digital sensor RGB pixels are microns to the side, slightly out-of-phase, like [YUV 4:2:0 Chroma Subsampling](https://en.wikipedia.org/wiki/Chroma_subsampling) </br>
RGB pixels are Not aligned in X-Y axis like Analog, Analog Film has a small phase shift / skew in the Z-Axis, </br>
Some lenses have bigger Out of Phase shift, and the sollution is [Apochromatic lenses](https://en.wikipedia.org/wiki/Apochromat) to minimize Z-Axis aberrations. </br>
RGB Pixels depend on the brand, have [different patterns](https://en.wikipedia.org/wiki/Bayer_filter) </br>

Profesional CCD Scanners like Imacon / Hasselblad sensor have: 1 or 3 pixel x 8000 </br>
Horizontal is Bigger 8cm / 80mm vs. Medium Format 57mm Digital Backs & 35mm Full Frame sensors. </br>
The lack of pixels in the Vertical axis, is compensated by moving the film in micro steps with a stepper motor. </br>
a 80mm x 80mm sensor would be very expensive. </br>

Semi-Profesional Flatbed scanners like Epson v600-v850 have a 1" sensor + concave / [parabolic reflector](https://en.wikipedia.org/wiki/Parabolic_reflector) mirrors to shrink the image. </br>
older Profesional Drum Scanners have PMT ["Photo-Multiplier Tubes"](https://en.wikipedia.org/wiki/Photomultiplier_tube) to convert the photons that enter the aperture into electrons, and amplify electrons to minimize signal to noise ratio, and match Analog to Digital converters </br>

Digital quality depends on the size of the sensor, Light Lumens & Digital ISO </br>
sensors like [Sony x1000v](https://www.sony.com/electronics/support/action-cam-fdr-x-series/fdr-x1000v/specifications) 1/2.3" sensor require over >1000 Lumens in video mode at 24fps to minimize digital noise, more lumens at 30fps, 60fps, 120fps, 240fps. </br>
Some Digital cameras use all kinds of tricks to improve low light sensitivity, </br>

old sensors like [PhaseOne P45+](http://www.phaseonekorea.com/datasheet/Phase-One-645DF-P45-p-datasheet-english.pdf) iso 80 "the minimum setting" gives much better quality vs. [ISO 800](https://en.wikipedia.org/wiki/Film_speed) </br>
using High Speed Flash, the difference is Night & Day in Resolution: [LinePairs/mm](https://en.wikipedia.org/wiki/1951_USAF_resolution_test_chart) </br>
Basically its 40MegaPixels at ISO 80, and lowers > as ISO increase <, but file size is the same, similar to Epson scanners and [mega pixel phone cameras](https://www.youtube.com/watch?v=FoF_JeWnvu8&t=274s) file size increase but [LinePairs/mm](https://en.wikipedia.org/wiki/1951_USAF_resolution_test_chart) does Not. </br>
Newer Sensors have improved low light sensitivity drastically, for example: old Samsung S860 vs. Newer Motorola G20 Phone camera </br>

Cameras like [Sony A7S](https://en.wikipedia.org/wiki/Sony_α7#Model_differences) use a 24MegaPixel sensor, Pixel Pairs in parallel, to double low light sensitivity. </br>
but that method lowers Resolution: [LinePairs/mm](https://en.wikipedia.org/wiki/1951_USAF_resolution_test_chart) becoming a [12MegaPixel camera.](https://en.wikipedia.org/wiki/Sony_α7#Model_differences), </br>
Physical Pixel Pairs or "Digital Pixel Pairs" or both methods</br>
Physical RGB Pixel pairs also increase pixel skew phase error. </br>

Film Camera: </br>
most require a mirror, mirror creates vibrations, affecting Resolution: [LinePairs/mm](https://en.wikipedia.org/wiki/1951_USAF_resolution_test_chart) </br>
Medium Format cameras like 500c / 503 require 1/125 speed or faster to avoid mirror vibrations in 6x6 film or digital back, </br>
35mm cameras have a smaller mirror, less agressive vibrations, body of the camera can absorb / contain vibrations more easy, vibrations spread different. </br>

#### Analog and Digital are affected by different things: </br>
C-41 was designed to be developed at 104°F / 40°C for 3:00 minutes exactly </br>
if develop C-41 at room temp. 20°C to avoid toxic smell vapour, requires much more time, arround 15~20 minutes, and colors will be completely "wrong",  </br>
requires more time in post, in a software like GIMP or Imacon / Hasselblad FlexColor 4.0 to color correct the scan, but that gives more artistic / creative freedom </br>
developing at recommended settings, gives a "standard" look, like flipping burgers, less random, more controlled / generic result. </br>
older versions of GIMP could Not Edit in 16-Bit RGB mode, Imacon software could since 1997, but latest versions of GIMP work ok at 16-Bit Color, the only problem is Dither, is On by default, at the beggining of the chain. </br>
¿why 16-Bit Color if modern Monitors only reproduce 10-Bit Color? </br>
Imacon CCD board in many models have 14-Bit [ADC](https://en.wikipedia.org/wiki/Analog-to-digital_converter) even Raw file is 16-Bit RGB. </br>
to take use of all the Bits, requires proper light / exposure, too bright or too dim will be out of range. </br>

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

its because the 386sx CPU and the 4MB [72-pin memory](https://en.wikipedia.org/wiki/SIMM#72-pin_SIMMs) </br>
The X5 is a rocket, super fast, like scanning at 150ppi. </br>
as far as i know, 386sx does [Not run](https://www.youtube.com/watch?v=sfbqZPLYNpI&t=1100s) with more than 16MB. </br>

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
[KinoFlo Mini-Flo 139x page.31](https://kinoflo-lighting.com/downloads/Kino-Flo-Lighting-Catalog.pdf) has Rapid Start ballast technology.[1](https://kinoflo.com/mini-flo/).[2](https://kinoflo.com/ballast-boards/) </br>

instant Start ballast, generates a very high voltage to [kick start](https://www.youtube.com/watch?v=ybcxIpb-R_0&t=30s) the mercury spheres / vapour inside the 6" CFL Tube </br>
after a few seconds, voltage retun to standard operating voltage around 100v-150v AC </br>

Rapid Start Ballast, there is No Kick start, IF Ballast is set to 100% output, will generate standard voltage only, </br>
in this technology CFL tube needs several minutes to warm-up and stabilize, the usual 15-minutes ~ 30-minutes. </br>
Advantage of Instant Start is Obvious. </br>
Advantege of Rapid start is Longer bulb life. </br>

Other problem of Imacon Scanners is that were designed around a CFL bulb No longer manufactured by Osram </br>
Newer bulbs are "better" have more lumens for the same watts, brighter </br>
Most Newer bulbs have a lower quality [CRI](https://en.wikipedia.org/wiki/Color_rendering_index), but [KinoFlo KF55 pag.8](https://kinoflo-lighting.com/downloads/Kino-Flo-Lighting-Catalog.pdf) have CRI 95 [Color Rendering Index](https://en.wikipedia.org/wiki/Color_rendering_index) "Higher Quality" </br>
 
Imacon CCD sensor requires a 2-stop down .6 lower light / exposure using a Newer 280lux output bulb, </br>
brighter bulb without attenuation would give wrong exposure "too dark" if negative was exposed & developed properly </br>
internal Ballast is factory calibrated to attenuate older lower output bulb 230lux </br>
Imacon ballast has 2x 10-turn trimp pots, output can be calibrated, but... </br>
there is another problem: </br>
Ballast designed for Profesional film/photography have an oscillating frequency of 25KHz to 50KHz </br>
because scanner at 3200ppi takes too much time scanning each line </br>
when Ballast output is lowered /attenuated too much the bulb becomes unstable, generating horizontal lines on the scan, </br>
some lines are brighter some lines are darker. <br>

The proper sollution to that, is placing a 4x5" glass ND .6 filter between the bulb and the negative. </br>
imagon has a square metallic bar inside that can be used with strong double side foam tape 3M to glue the glass to the bar, and works ok. </br>

ND filter can also be placed between the negative and the 1:1 Lens, a smaller / less expensive ND .6 filter in front of the lens. </br>
i did tests, placing the Large expensive ND .6 glass filter between the bulb & the negative gives better results. </br>
one of the reasons is that a bright light inside a black chamber, creates reflections, </br>
imacon chamber is Not painted with [Kiwami Black](https://www.youtube.com/watch?v=43OGgDaR2aE&t=29s) </br>
using a smaller ND .6 filter in-front of the 1:1 lens Require Kiwami Black or Similar High absorption Black inside the chamber. </br>

another problem is that the CCD sensor board in the bigger models 848 949 & Hasselblad X1 X5 has a [TEC cooler](https://en.wikipedia.org/wiki/Thermoelectric_cooling) </br>
in theory to lower the noise floor "removing nautral dither" without creating air humidity condensation </br>
in my tests i think is better to use a lower voltage instead of the +/-15vdc, instead of using a higher voltage with Cooling. </br> 
but the original SMPS is fixed. </br>
usign linear PSU´s is more risk because when Linear PSU fail, voltage increase, killing all components, unless it has a [TVS](https://en.wikipedia.org/wiki/Transient-voltage-suppression_diode) </br>
and yes, Imacon main board has TVS. </br>

The Final Problem is the Lens distance & CCD sensor board are Fixed in 343 & Photo, cannot be moved, </br>
CCD board has a small adjustment. </br>

646 848 949 & Hasselblad X1 / X5 Lens & CCD sensor can be moved controlled by internal calibration CNC </br>
typing dbug or debg inside FlexColor software, makes visible a hidden calibration menu. </br>
moving lens & CCD board in micro steps allows to focus </br>
but in large steps allows to have different Resolutions for different film formats. </br>

343 / Photo are 3200ppi all formats 35mm & 6x6 ~ 6x18, does Not allow to scan 4x5", Nor positives. </br>
basically 343 & Photo are designed for Medium Format Film Only, but also scan 35mm at 3200 ppi if needed. </br>
with quality far beyond flatbed scanners. </br>

The other Virtual / Hollow Drum Scanners like the X5, allows to adjust lens & CCD to achieve 8000ppi at 35mm, and scan 4x5" at 1067 ppi. </br>
has double bulb / ballast to allow scanning reflective photos / paper like a flatbed scanner. </br>
646 848 949 & Hasselblad X1 X5 Drum is Bigger, Flexholders are Not compatible. </br>

The 949 also has a Light difuser lens infront of the bulb to scatter light, and minimize film grain, a [half-cylinder plano-convex lens](https://www.firebirdoptics.com/blog/intro-to-the-plano-convex-lens) 6" long </br>
instead of using a white softbox, like Profesional Enlargers, that method is controversial. </br>
making a small wood box painted inside with [Spectralon or White 2.0](https://www.youtube.com/watch?v=14EZliTWDAA) would be insteresting to test. </br>

The X1 & X5 have a smaller CFL bulb, like old Flatbed scanners & CFL Dell monitors, another controversial decision. </br>
instead old Real Drum scanners use a Tungsten 3200°K light source with 99 CRI. </br>
light source is the life of the scanner, image quality change drastically with a different bulb. </br>

To solve All those probrems is more advanced / complicated, </br>
requires creating a large custom wood/MDF box or aluminum, much bigger, </br>
requires creating 2x CNC sliding mechanism for the lens & the CCD board. </br>
and create a New Hollow Drum compatible with Bigger Flexholders, and abandon 343 / Photo flexholders completely. </br>

Thats the goal of this project, most mods have been done, so far works better than factory </br>
but i want to do more, go beyond. </br>

been thinking about using 2x Old abandoned Flatbed scanners like Epsoon Precision 610 or Acer/BenQ 3300U </br>
those scaners are big, and have a robust CNC mechanism that could work inside the New Box, would require 3D printed adapters / holders or better bent metallic plates. </br>
IF vintage flatbed scanners are Not available, there is also many Scanners from Newer MultiFunctional Printers like Epson L, Kodak, Canon, etc... </br>

If using 2x flat bed scanners does Not work as desired, there are China manufacturers that sell bigger, stronger, longer, more precise Z-Axis CNC sliders. </br>
1mm pitch is the maximum ive seen = 1x 360° turn in the stepper motor moves slider 1mm forward, </br>
there are direct Stepper motor to ballscrew with a metallic coupler, and Belt driven, for this a low vibration belt drive would be better. </br>

The 1st goal is to scan 8000ppi on a Modified 343 / Photo at 35mm, </br>
The 2nd goal could be to scan reflective papers </br>
The 3rd goal scan 4x5" film or 16mm / 8mm </br>
4th goal is to optimize the box for each resolution, for example: X5 has a single lens for all film formats </br>
but using different lenses could be optimized even more for each film format, not everybody wants to scan all formats, but instead 1x format as good as possible. </br>
and box can be modified later to other formats if needed. </br>
5th goal would be recreating the 4-layer Mainboard PCB in KiCad </br>
6th goal upgrade the 386sx 16MHz CPU & old memory with MISTer FPGA io486 core running at 90MHz or similar,  </br>
this would also require recreating the NEC SCSI in FPGA </br>
7th goal recreate CCD sensor board in KiCad </br>
8th goal upgrade CCD sensor pcb with Newer 16-Bit / 24-Bit ADC converters, highest precision / lowest jitter clock possible. </br>
using different parts would increase price according, maybe an economic version could also be developed. </br>
9th goal would be to create other film adapters different than a single drum, to allow scanning a complete roll of 35mm, 16mm, 8mm film. </br>

All modifications before creating a New Box are complete. </br>
