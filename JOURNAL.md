---
title: "2-in-1 Cinema+FPV drone"
author: "@Chaos"
description: "A drone that can be switched from FPV to Cinema mode from the flick of a switch"
created_at: "2025-05-06"
---
# May 5th: Researched Parts and started BOM

I am researching the parts required to build the drone. [This](https://oscarliang.com/) website has been a great help and has helped me finalise my parts list. The BOM will soon be added as a seperate file.
![image](https://github.com/user-attachments/assets/10f82e0c-7727-454a-adbd-947d351c9734)

**Total time spent: 3h**

# May 6th: Made a Wiring Diagram

Now that I have the parts list, I started researching the datasheets of the individual parts. Luckily, most of the parts had a wiring diagram attached to the listing. Using these diagrams, I recreated them in KiCad and made up a schematic, with custom symbols for each part, for the drone. This should make it easier to wire the drone up later on.

![schematic](img/schem.png)

You might notice that there are some unused pins. This is because I fully copied over the wiring diagrams from the parts, and some of them had more pins than I needed. I will leave them there in case someone wants to use the same parts but with different wiring and needs the symbols.

I was also looking at alternative parts, and one caught my eye: the [SPEEDYBEE F405 V3 Stack](https://www.fpvfaster.com.au/products/speedybee-f405-v3-flight-controller-bls-50a-esc-stack-30-5x30-5mm?variant=40142631862354). 
![speedybee](https://www.fpvfaster.com.au/cdn/shop/products/5_9680e6c5-f137-4a33-902a-253bbeedae95_large.jpg?v=1662962813)

It has a lot of similar features to the XILO Stax V2 I was planning to use, so I will be looking into it more. It is also cheaper, so I might end up using it instead. Tomorrow, I will try to finish the 3D model of the drone case and submit the project as the other 3D prints require precise measurements.

**Total time spent: 4h**