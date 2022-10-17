---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: .                                                      
layout: single
classes: wide
author_profile: true
# excerpt: Welcome!!
header:
  overlay_image: /assets/images/banner.jpg
actions:
  - label: "Resume"
    url: "https://github.com"
tags:
  pdf
---
<div id="adobe-dc-view" style="width: 800px;"></div>

> A sample code using Java double produces surprising results.
<br />

```UNEXPECTED Result: 0.1d + 0.2d - 0.3d = 5.551115123125783E-17 ```

<script src="https://gist.github.com/viraj-vs/041d25ef3fd2913e8e99f3731d06aca9.js"></script>

> Same code using Java float does not.
<br />

```EXPECTED Result: 0.1d + 0.2d - 0.3d = 0 ```
<script src="https://gist.github.com/viraj-vs/b7816ec8892a12c82aba4535aa90cb5b.js"></script>

<br />



<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/u8WjMyR6Xh4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> **Ariane 5 rocket:** <br />
> Ariane 5 rocket exploded 40 seconds after being launched by European Space Agency. Maiden voyage after a decade and 7 billion dollars of research and development. The sensor reported acceleration that so was large that it caused an overflow in the part of the program responsible for recalibrating inertial guidance. 64-bit floating point number was converted to a 16-bit signed integer, but the number was larger than 32,767 and the conversion failed. The unanticipated overflow was caught by a general systems diagnostic and dumped debugging data into an area of memory used for guiding the rocket's motors. Control was switched to a backup computer, but this had the same data. This resulted in a drastic attempt to correct the nonexistent problem, which separated the motors from their mountings, leading to the end of Ariane 5.

> **Patriot missile accident:** <br />
> On February 25, 1991 an American Patriot missile failed to track and destroy an Iraqi Scud missile. Instead it hit an Army barracks, killing 26 people. The cause was later determined to be an inaccurate calculation caused by measuring time in tenth of a second. Couldn't represent 1/10 exactly since used a 24-bit floating point. The software to fix the problem arrived in Dhahran on February 26. Here is more information.
Intel FDIV Bug Error in Pentium hardwire floating point divide circuit. Discovered by Intel in July 1994, and rediscovered and publicized by math professor in September 1994. Intel recall in December 1994 cost $300 million. Another floating point bug discovered in 1997.

> **Sinking of Sleipner oil rig:** <br />
> Sleipner A $700 million platform for producing oil and gas sprang a leak and sank in the North Sea in August, 1991. Error in inaccurate finite element approximation underestimate shear stress by 47% Reference.

> **Vancouver stock exchange:** <br />
> Vancouver stock exchange index was undervalued by over 50% after 22 months of accumulated roundoff error. The obvious algorithm is to add up all the stock prices Instead a "clever" analyst decided it would be more efficient to recompute the index by adding the net change of stock after each trade. This computation was done using four decimal places and truncating (not rounding) the result to three. Reference
