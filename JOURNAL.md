# Journal

## 2026-03-22A - part selection and gantry plate

*1 hour*

Just had to grab the parts I had already researched prior - found motor dimensions [here](https://makers-hut.com/product/nema-8-hollow-shaft-stepper-motor-1-8deg-0-6a-18mnm-20x20x30mm-4-wire-nema8/).

![motor dimensions](https://makers-hut.com/wp-content/uploads/2019/01/nema8hsdraw.jpg)

The image doesn't say everything, but given it's a standard NEMA 8 motor, it's easy to find dimensions

![NEMA 8 dimensions](https://s3.moonsindustries.com/staticpic/8HY/image/zt0919_12.jpg)

As for the gantry plate, found dimensions for that, from which I made a quick sketch of the relevant holes in Inventor.

![gantry plate dimensions](https://www.makerstore.com.au/wp-content/uploads/2015/01/20mm-v-slot-gantry-plate.webp)

![holes in inventor](https://cdn.hackclub.com/019d173e-2b3d-7671-a4f7-03543445eaaa/image.png)

## 2026-03-22B - nozzle selection

*0.5 hours*

I found [this](https://groups.google.com/g/openpnp/c/s_PBSA7VQWM) usenet post, seems you can use all kinds of stuff as nozzles actually, including needles (for extruding glue and stuff). Since actual nozzles are expensive, I'll use those

## 2026-03-23A - camera selection and looked into motors more

*1 hour*

Spent some time trying to find which camera to use. Seems the best option is a pi camera-like module (65mm, autofocus, OV5647), so added that to the parts list. And given it's basically the same dimensions of a pi camera 2, I can design around that.

I also looked into motor selection more, turns out that motor I had previously selected is way too low voltage, I wouldn't be able to add a spring, and it's also more difficult to attach stuff to it given it's a smooth shaft. Instead, I'm going for a design similar to xpdiy's with a standard NEMA 17 motor, albeit with silicone to hold the nozzle for better fit, easier printing, and ease of design.

## 2026-03-23B - Designed the head, just need to design nozzle bits

*3 hours*

I designed the head, still need to design the nozzle bits but got a good start.

## 2026-03-24/25 - CAD yay

*7 hours*

So uh I actually got decent at CAD, even figured out how to do assembly somewhat competently. Not much to say here besides me just trying to figure out workarounds for Inventor being weird - I ended up creating a structure that would've made more sense as a loft by extruding and using the hole tool, and I even had to make a part that's literally just a sketch in order to align stuff in assembly.

Really not much to journal here unfortunately, besides just that I learned how to CAD half decently. Oh also fun fact apparently there isn't a single tutorial on how to use springs in Inventor, *everybody* just makes springs out of coils.

![image](/assets/pnp-head.webp)
