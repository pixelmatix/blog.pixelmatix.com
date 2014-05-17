---
layout: post

title: Fadecandy and the Aurora Display
#subtitle: "What's in the box"
#cover_image: blog-cover.jpg

excerpt: "Fadecandy and the Aurora Display - Coming Soon"

author:
  name: Louis Beaudoin
  twitter: PixelmatixRGB
  bio: Owner - Pixelmatix
  image: lbavatar2.png
---

After seeing the awesome open source project [Fadecandy](https://github.com/scanlime/fadecandy), and how beautiful and smooth it is able to control LEDs, I had to try to port the Fadecandy firmware to run on the SmartMatrix.  I'm happy to say the project was a success, and I have a heavily modified fork of the Fadecandy firmware running on a Teensy 3.1.  The firmware in combination with a slightly modified Fadecandy server is able to drive a 32x32 RGB matrix panel with 36-bit color at >120 Hz refresh.

In parallel with the Fadecandy firmware port, I have been working on an enclosure design that protects the panel, while adding nice looking diffusion and color contrast.  After testing many different materials, I found a white plastic that provides good diffusion, and in combination with a light gray transparent acrylic, good color contrast.

The Aurora Display is a combination of SmartMatrix Shield, and an enclosure with an adjustable diffusion screen that can be separated from the RGB matrix panel.  By putting the diffusion screen close to the panel, the screen shows a pixelated effect.  By separating the diffusion screen from the panel, the individual pixels lose focus and blur together.  The images that can be made with the out of focus panel don't look like they could be made by such a low resolution display.

Unmodified photo of the display (other than cropping out the background):  
![Aurora Display](/images/AuroraIsolated.png)

I am showing the initial prototypes at the Bay Area Maker Faire, and will have a limited number available for sale.  More information and videos of the display will come in the next few weeks, as well as information on preordering from the first production run.

