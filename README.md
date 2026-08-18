# chrg

> [!IMPORTANT]
> Need to do 3D model, case, and images of those
> Need to export and BOM optimize. 

![](blend/render1.png)

chrg is a usbc charging hub. You can use it to charge your devices! It uses a CH224K PD sink as input, and then 4xIP6518 PD source controllers as output. 

Thanks to the IP6518, it should support:

 - USB-C Power Delivery
 - BC1.2 charging
 - Qualcomm QC2.0 and 3.0 charging
 - Apple, Huawei, Samsung, and Speadtrum fast charging protocols

 Of course, YMMV when plugging in multiple devices. It's mostly bottlenecked by the wattage of your upstream brick.

 I made this project because I like doing USB projects, and after making a [USB *data* hub](https://github.com/jblitzar/uhub), I thought it would be cool to make a *charging* hub. Plus, this way I can plug in one brick and charge my phone and headphones at the same time. I also think it's cool and was a way to learn a new chip (IP6518).

## Schematic

Root schematic:

![](docs/schematic1.png)

Schematic for the `out` block:

![](docs/schematic2.png)


## PCB

[View on Kicanvas](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FJBlitzar%2Fchrg%2Ftree%2Fmain%2FPCB%2Fchrg)

![](docs/pcb.png)


## Testimonials

Don't just take it from me! Hear what users are saying about chrg


> *What are you making...*

> *this shit is not passing tsa bro*

> *Scary*


## BOM


### Fabrication BOM

Other fabrication outputs at [PCB/chrg/production](PCB/chrg/production)
