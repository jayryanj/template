---
layout: project
type: project
image: images/telescope.jpg
title: Micromouse
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2019-08-14
labels:
  - Robotics
  - Arduino
  - C++
summary: My team developed a robotic mouse that won first place in the 2015 UH Micromouse competition.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/telescope.jpg">
  <img class="ui image" src="../images/hsc.jpg">
  <img class="ui image" src="../images/left.png">
  <img class="ui image" src="../images/right.png">
</div>

The Hyper-Suprime Cam (HSC) is a large mosaic CCD imager instrument for the Subaru Telescope. It's one of the main instruments for the organization because it's so actively used—it takes up roughly 40% of Subaru’s observation time—and it yields very significant scientific results. However, operating and monitoring the instrument during observation are difficult tasks for astronomers because of its command-line interface (CLI) and the need for manual inspection.

As a software engineering intern for the organization, I worked under the Instruments division to develop an integrated status monitor for the Hyper-Suprime Cam. Using Python, I created a graphical user-interface with Tkinter to replace the system's CLI. I chose Tkinter to minimalize third-party imports. The software also provides centralized status monitoring functionality by integrating all the necessary information and pre-existing tools in one program. This feature automates the process of monitoring the shutter position, filter exchange unit, and read-out status for the astronomers.

Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).

