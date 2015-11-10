INTEL&copy; OPEN SOURCE GRAPHICS PROGRAMMER&apos;S REFERENCE MANUAL (PRM)
=========================================================================

These are the
[CC-BY-ND](http://creativecommons.org/licenses/by-nd/3.0/us/) PRMs for
Intel's GPUs downloaded from:
<https://01.org/linuxgraphics/documentation/hardware-specification-prms>

![CC-BY-ND](https://licensebuttons.net/l/by-nd/3.0/us/88x31.png)

Structure
---------

The documents are divided in directories by
[chipsets](https://en.wikipedia.org/wiki/List_of_Intel_graphics_processing_units):

* **gen4**
  * [INTEL&copy; 965 EXPRESS CHIPSET FAMILY AND INTEL&copy; G35 EXPRESS CHIPSET GRAPHICS CONTROLLER](./000_g35) (BROADWATER/BEARLAKE GRAPHICS)
  * [INTEL&copy; G45 EXPRESS CHIPSET](./001_g45) (EAGLELAKE GRAPHICS)
* **gen5**
  * [2010 INTEL CORE PROCESSOR FAMILY](./002_ilk_-_2010) (IRONLAKE GRAPHICS)

Plain Text
----------

As these documents are distributed with a _non derivative_ license, we
only provide a script that can be used to transform the PDFs into
plain TXT.

`$ make text
`

Observations
------------

_pdfgrep_ is also a great way of looking for specific strings into
this massive amount of documentation.