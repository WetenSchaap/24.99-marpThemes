---
marp: true
theme: reference
paginate: true

---

<!-- _class: lead -->
# Microfluidic computation

## Piet J.M. Swinkels

2023-02-22

---

# Computation with microfluidics

* Physical computing: Cool, but
  * hard to build
  * hard to program
  * hard to scale
  * and hard to use
* Make things easier with microfluidics:
  * Commercially available
  * Small
  * Used a lot: no exotic reactions, DNA, etc.
  * Automatable

---

# The concept

![bg right:50% w:500](figures/concept.svg "Photogel")

* Convert data into an obstacle pattern in the microfluidic cell
* Detect flow disturbances due to objects
* Use ML algorithm to tell you what object was projected based on disturbances

---

# Data to obstacle

![bg vertical right:50% w:450](figures/imagetopattern.svg "imagepattern")
![bg right:50% w:450](figures/dmd2.jpg "DMD")

* Convert data to illumination pattern
  * ~100x100 px, px in the order of 50μm
* Project pattern using DMD

---

# Data to obstacle

![center width:2000px](figures/photogelator.svg "Photogel")

* Using photo-gellator turns to gel when exposed to specific wavelengths
* Hydrogel can also be destroyed for next experiment
* So pattern is converted to obstacle

---

# Doing the experiment

* Convert input data to pattern (~100x100 pixels, px size in the order of 50μm)
* Project pattern using DMD, forms hydrogel obstacles in channel
* Flow in 3 channels with tracer particles
* Detect flow sculpting, output tracer particle distribution.

![center width:800](figures/setup.svg)