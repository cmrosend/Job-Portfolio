---
layout: single
title: "Rapid Prototyping"
author: Christopher Rosend
author_profile: true
related: true
classes: wide
header: 
    image: /assets/images/rapid-prototyping/rapidbanner.jpg
    teaser: /assets/images/rapid-prototyping/rapid-prototyping.jpg
show_date: true 

gallery:
  - url: /assets/images/rapid-prototyping/moai-head.jpg
    image_path: /assets/images/rapid-prototyping/moai-head.jpg
    alt: "Moai head"
    title: "An example of AFDS from the MELD printworks trip"

  - url: /assets/images/rapid-prototyping/accuracy-test.jpg
    image_path: /assets/images/rapid-prototyping/accuracy-test.jpg
    alt: "Accuracy test"
    title: "Small assignment to design something that could test accuracy of a printer in only one orientation"

  - url: /assets/images/rapid-prototyping/rock.jpg
    image_path: /assets/images/rapid-prototyping/rock.jpg
    title: "The print of the final project"

  - url: /assets/images/rapid-prototyping/rock-testing.jpg
    image_path: /assets/images/rapid-prototyping/rock-testing.jpg
    title: "How we tested our rock in practice"
---


## What is it?

This is a class taught by Dr. Christopher Williams and it is about everything related to Additive Manufacturing the generation of suitable CAD models, current rapid prototyping fabrication technologies, their underlying material science, the use of secondary processing, and the impact of these technologies on society.

## What have I done?

The class is split up into two parts: Learning about Additive Manufacturing, and applying that knowledge.
For the first part of the class, we went in-depth about the following AM processes:

<style>
table, th, td {
  border:1px solid black;
}
</style>

<table style="width:125%">
  <tr>
    <th>Process:</th>
    <th>Material Extrusion</th>
    <th>Powder Bed Fusion</th>
    <th>Vat Photo-polymerization</th>
    <th>Binder Jetting</th>
    <th>Material Jetting</th>
    <th>Directed Energy Deposition</th>
    <th>Sheet Lamination</th>
  </tr>
  <tr>
    <td>What is it?</td>
    <td>Putting a filament through a nozzle to achieve extrusion of material</td>
    <td>Using an IR laser to selectively fuse powder together</td>
    <td>Using a UV laser to cure a layer of resin, which then has to be post-processed</td>
    <td>Depositing Binder using a print-head into a layer of powder. The green part must be cured, then sintered later</td>
    <td>Depositing Material using a print-head onto a bed, then curing each layer</td>
    <td>Feeding a material into either a laser or a wire, similar to welding</td>
    <td>Material sheets are layer ontop of each other, cut using a laser or bond using binder and heat</td>
  </tr>
  <tr>
    <td>Specifics Talked About?</td>
    <td>Cooling, bed adhesion, warpage, layer strengths, direct ink write</td>
    <td>Metal and polymer PBF, Amorphous vs Semi-crystalline polymers, shrinkage, energy density, coalescence and cooling</td>
    <td>Thermoplastics vs Thermosets, top down vs bottom up, cure depth, critical exposure, depth of penetration, working curve</td>
    <td>Porosity, process variables, primitives, drying and curing, sintering, binder saturation</td>
    <td>Process overview</td>
    <td>Wire vs Powder DED, inert gasses, uses, machining, thermal accumulation, warping, toolpathing solutions, Hybrid DED processes</td>
    <td>Process overview, ultrasonic consolidation, multi-material laminates</td>
  </tr>
</table>

The second half of the class is described as being “choose your own adventure”, where you choose 3 labs to do out of a selection of 15, as well as a final project. For my labs, I chose to learn about Directed Energy Deposistion, Powder Bed Fusion, and a new type of printing called Additive Friction Stir Deposition. The labs were eye opening on how new this technology really is and all of the struggles that come along with utlizing it. DED especially was hard to work with, but AFSD seemed really promising despite some questions about the structural integrity of the parts.

For my final project I was paired with 3 other students and we chose to design realistic rock climbing holds. This was because they are extremely expensive; they are currently made 20-25 units at a time with injection molding. It was identified that removing the cost of the mold and using AM could speed up the creation process and drive the price way down. To achieve this, we scanned a rock face and imported it into nTop so that we could perform strucutural analysis and improve it through the use of specific infill settings. Then, we printed it and tested it in field to much success. Our end decision was that it would be cost effective in the long run for a gym to buy a printer and make their own holds, but some things would still have to be tested like lifetime of the hold and if it retains moisture.

<video width="900" height="600" controls muted>
  <source src="/assets/images/rapid-prototyping/eyobel-pullup.mp4" type="video/mp4">
</video>

{% include gallery layout="half" caption="Different parts of the class, read more in captions." %}

## What have I learned from this?

<ins>Experience</ins>

* Knowledge of the advantages and weaknesses of the 7 main AM processes
* Knowledge of traditional manufacturing processes like injection molding, milling, etc.
* Specifics about Material Extrusion, PBF, and VPP processes
* Basic knowledge of nTop
* Learned to Design for AM

<ins>Concepts</ins>

* While it seems like AM is the future of manufacturing, in most scenarios it is cheaper and faster to create a part traditionally
* The price of AM includes buying the machine, similar to injection molding
* AM is typically used for things that either cannot be physically manufactured, or needs to be customized
