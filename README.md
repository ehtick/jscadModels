# Some OpenJSCAD models and libraries

This repository contains some of my personally developed OpenJSCAD models
and libraries.

## Installation

Note that the libraries are usually expected to be deployed on an server that
hosts an OpenJSCAD instance. On my setups I simply deploy the content of
the ```library``` folder to the ```/openjscad.jscad/```.

## Libraries

* Electronics
  * A template for the [Raspberry Pi B+](./library/electronics/embedded/raspberrypibplus.jscad) to
    be used during case builds or in cases on wants to embed an Raspberry Pi into a custom project
  * A template for the [HY86N forked light barrier](./library/electronics/forkedlightbarrier/hy86n.jscad)
* Mechanics
  * Generator for [4 digit NACA airfoils](./library/mechanics/airfoilNaca.jscad)
  * A [gear generator for involute gears](./library/mecahnics/gears.jscad)
  * A generator for metric [screw and nut templates](./library/mechanics/isothread.jscad) (without threads)
  * Simple [screwed clamps](./library/mechanics/screwclamp.jscad) for rods and wires
  * A template for the [SG90 servo](./library/mechanics/servoSG90.jscad)
  * A template for the [28BYJ_48 stepper](./library/mechanics/stepper28byj_48.jscad)
  * A template for [NEMA 17 steppers](./library/mechanics/stepperNema17.jscad)
  * Bearings templates
    * [LM8UU](./library/mechanics/bearingLM8UU.jscad)
	* [LM8LUU](./library/mechanics/bearingLM8LUU.jscad)
* Packaging
  * A [simple box](./library/packaging/basicbox1.jscad) generator with rounded edges
* Toys
  * A generator for [LEGO compatible](./library/toys/lego.jscad) parts to allow
    attachment of the common bricks to 3D printed parts (note that they can never
    replace real parts due to the hackisch way of attachment)

## Models

* Chemistry
  * A simple [gas bubbler](./models/chemistry/SimpleGasBubbler.jscad)
  * Parameterized [test tube holder](./models/chemistry/TestTubeHolder.jscad)
  * Simple [peristaltic pump](./models/chemistry/PeristalticPump.jscad) based on the 28BYJ_48 stepper motor
* Education
  * A dice to allow [rolling for decliations](./models/education/language/grammarPersonCube.jscad)
* 3D printer accessory
  * Holder for [3D printer spools](./models/printer3d/filament/)
* Toy components
* A small [MiniECM project](./models/miniecm/)
