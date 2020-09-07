## Adafruit Circuit Playgound Tri-Color E-Ink Gizmo PCB

<a href="http://www.adafruit.com/products/4428"><img src="assets/4428.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Circuit Playground Tri-Color E-Ink Gizmo. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4428

### Description

Extend and expand your Circuit Playground projects with a bolt on E-Ink Gizmo that lets you add a lovely tri-color e-Ink display in a sturdy and reliable fashion. This PCB looks just like a round E-Ink breakout but has permanently affixed M3 standoffs that act as mechanical and electrical connections.

Chances are you've seen one of those new-fangled 'e-readers' like the Kindle or Nook. They have gigantic electronic paper 'static' displays - that means the image stays on the display even when power is completely disconnected. The image is also high contrast and very daylight readable. It really does look just like printed paper!

Once attached you'll get a 1.54" 152x152 display (black and red ink pixels and a white-ish background), two 3-pin STEMMA connectors for attaching NeoPixel strips or servos, and a Class D audio amplifier with a Molex PicoBlade connector that can plug one of our lil speakers.

Using our CircuitPython or Arduino library, you can create a 'frame buffer' with what pixels you want to have activated and then write that out to the display. The library we wrote does all the work for you, you can just interface with it as if it were an Adafruit_GFX compatible display. This E-Ink breakout does not contain an extra SRAM chip (not enough pins are available) so you'll need ~7K of SRAM to spare for a display buffer, the CPX has 32KB and the CPB has 256KB, so there's plenty of RAM.

This is a great companion for our Circuit Playground Express or Bluefruit boards thanks to their fast SPI hardware speeds and plenty of RAM, and works in Arduino and CircuitPython. If you're using this with Circuit Playground Express and CircuitPython, you won't be able to do a lot because there isn't a ton of memory - mostly just displaying the REPL and maybe running an image slideshow. For CircuitPython use, the Bluefruit is recommended and works really great!

You cannot use it with the Circuit Playground Classic in Arduino, there's not enough RAM!

Comes with a PCB that has pre-soldered standoffs attached, and 12x M3 screws for attachment. Fits all Circuit Playgrounds, but like we mentioned earlier, the Express and Bluefruit are recommended.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
