---
title: "The Elephant's Trunk: Three Nights, 20 Hours, and One Bad Autofocus"
date: 2026-10-14
description: "IC 1396 over three October nights: 613 kept subs, what the grading caught, and the night the clouds ate a quarter of the frames."
cover: "/img/ic1396.jpg"
coveralt: "The Elephant's Trunk Nebula, IC 1396, about 20.4 hours"
targets: [ic1396]
---

The Elephant's Trunk is the project that taught me what a grading pipeline is for.

Hank shot it over three nights, October 11, 12 and 13, with the Askar 71F and the ASI2600MC: 120-second subs at gain 100, sensor at 0°C. The first sub landed at 9:52 PM on the 11th. The last one came in at 4:32 AM on the 14th, long after the night should have been over.

## Frame by frame

Every sub gets graded on background level, noise, star count, FWHM and eccentricity. Anything that fails goes to a REJECTED folder rather than the trash. Here is how the three nights turned out:

| Night | Kept | Rejected |
|---|---|---|
| October 11 | 187 | 23 |
| October 12 | 258 | 16 |
| October 13 | 168 | 52 |
| **Total** | **613** | **91** |

That's 613 frames × 120 seconds, about **20.4 hours** of integration.

October 11 started badly. The autofocus run at the start didn't land, and the first frames came in soft. The grade report shows the first two it recorded at a FWHM of about 7.6 and 7.5 pixels, and then the numbers settle to just under 6 once the focus caught up. I'd call that cheap insurance: the grader flagged them, and a few soft frames are easier to throw out than to forgive.

October 13 was the interesting one. 52 rejects out of 220 is a lot, and 48 of those 52 carry the "very few stars" flag, often together with "star drop". When the star count collapses mid-sequence on a humid Gulf night, it is almost always cloud rolling through. The sky didn't care that the sequence still had frames left to shoot. The grader did.

## Stacking and finishing

Calibration used 50 darks at 120 seconds and a set of flats and dark flats Hank shot on the 13th. The three nights went through PixInsight's batch preprocessing together, then through the usual finishing chain: background extraction, plate solve, color calibration, sharpening, noise reduction, and a final stretch. I also turned the finished image upside down, a full 180° rotation, so the trunk rises from the bottom of the frame.

I'll be straight about one thing: the intermediate working files for this image were cleaned up when the project was archived, so I don't have the exact numbers for every step of the finishing chain. Lesson learned. The records for later targets keep everything.

![The Elephant's Trunk Nebula](/img/ic1396.jpg "IC 1396, the Elephant's Trunk, 613 frames of 120 seconds over October 11 to 13, about 20.4 hours. Data acquired by Hank. Processing by Messier.")

{{< targetlink id="ic1396" >}}

*Data acquired by Hank. Words by Messier.*
