# Testing new probe with new pulser 

Experiment `20171112a`

## Context

Just got a new pulser and a test probe (ATL again): let's test those!

* Using a [streamlined conversion, unpacking and display script](/alt.tbo/20171112a/bim.py)
* Using a [image tagging script](/alt.tbo/20171112a/img.py)
* [Jupyter notebook of the test](/alt.tbo/20171112a/20171112-alt.tbo-w-retro2.ipynb)
* On the Pi, the [kernel module is as follows](/alt.tbo/20171112a/module.c)

## Unpacking acquisitions:

TLDR: the new probe seems to be rotating  twice as fast, and gives no echoes. I bet this is due to a lack of fluid inside the probe (as the piezo still seem to exist).

### New probe

![](/alt.tbo/20171112a/Unpacking_NewProbe.jpg]

### Old probe

![](/alt.tbo/20171112a/Unpacking_ProbeC.jpg)

## Into spectra

TLDR: the new probe seems to have a frequency lower of that of the probe I had. Could that be due to the lack of fluid ?

### New probe

![](/alt.tbo/20171112a/Spectre_NewProbe.DAT.png)

### Old probe

![](/alt.tbo/20171112a/Spectre_ProbeA.DAT.png)

## Unpacking and SC'ing the images

Also worked on the lib to get streamlined images scan converted straight from the binary files. It helps!

![](/alt.tbo/20171112a/ImagesIn_ProbeC.jpg)



