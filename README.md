# Partial Finger Prosthesis

A low-cost, durable, open-source prosthetic hand for people missing two phalanges on each finger.

<p align="center">
  <img src="claudia-using-hand.jpg" width="420" alt="Claudia holding a water bottle with the prosthetic hand">
</p>

🔗 **CAD (Onshape):** <https://cad.onshape.com/documents/2bf0948c0f6b5be1b848873e/w/4f982a2b256dcb1968b1714a/e/2326693e9b2c98c8c4b35fae?configuration=default&renderMode=0&uiState=6af1c1c144321995f021fa74>
📐 **Kinematics model (Desmos):** https://www.desmos.com/calculator/bnfynyphme

> ⚠️ Read the [safety notice](SAFETY.md) before building or using this device. See also the [patent notice](PATENTS.md).

## About

The goal of this project is to create a low-cost, durable, open-source prosthetic hand for people missing two phalanges on each finger. We have already incorporated all six main grasp types (tip, hook, palmar, spherical, lateral, and cylindrical), which served as the primary stepping stones for the project. But there is still much progress to be made to make it more practical, reliable, and easier to repair/construct.

At the time of writing, there is no open-source prosthetic hand for people missing two phalanges. Buying one is for the few: commercial prosthetic fingers can cost around $100,000 BRL each. The primary purpose of the project is to make something open source, so that anyone can download, adapt, and improve it, greatly expanding who can benefit from it.

## Design

Fully mechanical, fully rigid, reliable, durable, and simple in appearance. The main priority is functionality. The CAD is parametric, so the finger can be rescaled to each person's measurements.


## Movement

The joint angles were documented on a real hand and modelled with trigonometry, so the finger moves as close as possible to a natural one. Typical proportions used: proximal : middle : distal ≈ 2 : 1.2 : 1.

<p>
  <img src="angle-measurements.png" width="32%" alt="Measured joint angles">
  <img src="kinematics-equations.png" width="32%" alt="Kinematics equations">
  <img src="kinematics-desmos.png" width="32%" alt="Kinematics model in Desmos">
</p>
<p>
  <img src="angle-curves.png" width="32%" alt="Angle curves">
</p>


## Why it matters

Being able to grab objects safely and reliably changes what someone can do at home, at work, and in public. And unlike one-off inventions that help only a single person, an affordable open-source prosthesis can be replicated and improved anywhere in the world.

For our learning, we're applying trigonometry and mechanics to a real human hand, iterating through dozens of prototypes, and working directly with a patient (Claudia), translating her needs about comfort, durability, and repairability into engineering decisions.

## License

[CC0 1.0](LICENSE): free to use, copy, modify, and sell for any purpose. No credit needed.


