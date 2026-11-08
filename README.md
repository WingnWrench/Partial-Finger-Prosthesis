# PROTITIC HAND

A low-cost, durable, open-source prosthetic hand for people missing two phalanges on each finger.

<p align="center">
  <img src="claudia-using-hand.jpg" width="420" alt="Claudia holding a water bottle with the prosthetic hand">
</p>

🔗 **CAD (Onshape):** <ADD CAD LINK HERE>
📐 **Kinematics model (Desmos):** https://www.desmos.com/calculator/bnfynyphme

> ⚠️ Read the [safety notice](SAFETY.md) before building or using this device. See also the [patent notice](PATENTS.md).

## About

The goal of this project is to create a low-cost, durable, open-source prosthetic hand for people missing two phalanges on each finger. We have already incorporated all six main grasp types (tip, hook, palmar, spherical, lateral, and cylindrical), which served as the primary stepping stones for the project. But there is still much progress to be made to make it more practical, reliable, and easier to repair/construct.

At the time of writing, there is no open-source prosthetic hand for people missing two phalanges. Buying one is for the few: commercial prosthetic fingers can cost around R$100,000 each, and they need to be replaced every 3 years. The primary purpose of the project is to make something open source, so that anyone can download, adapt, and improve it, greatly expanding who can benefit from it.

Building a device that Claudia can use to help grab objects was already incredibly rewarding. But we haven't stopped. Our goal is to make a device that actually benefits people in their daily lives, and hopefully the project continues with another student, online, continually improving the design.

## Design

Fully mechanical, fully rigid, reliable, durable, and simple in appearance. The main priority is functionality. The CAD is parametric, so the finger can be rescaled to each person's measurements.

<p>
  <img src="finger-side.png" width="32%" alt="Finger, side view">
  <img src="finger-tip-joint.png" width="32%" alt="Fingertip and joint">
  <img src="linkage-2d.png" width="32%" alt="Linkage sketch">
</p>
<p>
  <img src="fingertip-v2.png" width="32%" alt="Redesigned fingertip">
  <img src="fingertip-assembly.png" width="32%" alt="Fingertip assembly">
  <img src="mid-grip.png" width="32%" alt="Mid grip">
</p>

**Attachment.** The device is attached to the residual finger and the back of the hand.

<p>
  <img src="attachment-ring.png" width="32%" alt="Attachment ring">
  <img src="back-hand-attachment.png" width="32%" alt="Back of hand attachment">
</p>

**Grip.** Textured pads for better grip, with molds for an optional silicone version.

<p>
  <img src="grip-pad.png" width="24%" alt="Grip pad">
  <img src="grip-texture.png" width="24%" alt="Grip texture">
  <img src="mold-1.png" width="24%" alt="Mold">
  <img src="mold-2.png" width="24%" alt="Mold">
</p>

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

## Testing

Dozens of prototypes, tested on a real hand. Acrylic handled stress much better than MDF.

<p>
  <img src="testing-on-hand.jpg" width="24%" alt="Testing on a hand">
  <img src="printing.png" width="45%" alt="3D printing a part">
</p>

## Why it matters

Being able to grab objects safely and reliably changes what someone can do at home, at work, and in public. And unlike one-off inventions that help only a single person, an affordable open-source prosthesis can be replicated and improved anywhere in the world.

For our learning, we're applying trigonometry and mechanics to a real human hand, iterating through dozens of prototypes, and working directly with a patient (Claudia), translating her needs about comfort, durability, and repairability into engineering decisions.

## License

[CC0 1.0](LICENSE): free to use, copy, modify, and sell for any purpose. No credit needed.
