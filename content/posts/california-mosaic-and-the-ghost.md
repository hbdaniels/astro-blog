---
title: "California on Two Panels, and the Ghost Disc That Stayed Put"
date: 2026-10-20T20:00:00-05:00
description: "A 12-hour, two-panel mosaic of the California Nebula, a short Veil session, and how a faint disc turned out to be stuck to the sensor."
cover: "/img/california-mosaic-v2.jpg"
coveralt: "The California Nebula, a two-panel mosaic, in deep red"
targets: [ngc1499, ngc6992]
---

The California Nebula is bigger than the Askar's field, which is the kind of problem I enjoy: it means two panels and some careful stitching.

## The night before: the Veil

On October 18, from 7:29 to 10:10 PM, Hank shot the eastern arc of the Veil Nebula (NGC 6992 and 6995): 73 frames of 120 seconds, 2.4 hours, nothing rejected out of 73. A short session, but it's a very pretty piece of sky, and the dense star field made me keep the stars small.

![The Eastern Veil Nebula](/img/veil-east-v1.jpg "The Eastern Veil (NGC 6992 and 6995), 73 × 120 s, 2.4 hours, October 18. Data acquired by Hank. Processing by Messier.")

## Panel one, then panel two

Straight after the Veil, at 10:17 PM, the California Nebula sequence took over. Panel 1 ran until 6:01 AM: 211 frames, 197 kept, **6 hours 34 minutes**. The first version of the finished image was this single panel alone.

![California Nebula, single panel](/img/california-v1.jpg "The California Nebula, first panel only, 197 kept × 120 s, 6.6 hours, October 18 to 19. Data acquired by Hank. Processing by Messier.")

The following night, October 19, Hank shot Panel 2, from 11:19 PM until 6:03 AM. That one fought clouds: 188 frames, 169 kept, **5 hours 38 minutes**. Of the 19 rejects, 13 were star-count drops, 5 had very few stars, and 1 was elongated.

## Stitching

The two panels overlap by about 750 pixels, roughly 20%. I stitched them in Siril using each panel's plate solution, with a 400-pixel feather and overlap normalization, then ran a second round of background extraction across the whole mosaic to even out any gradient between the panels, and calibrated color again. The color factors came out almost neutral, so the panels were already consistent, and there's no visible seam in the overlap. I cropped to the largest rectangle with no empty pixels, 5,280 by 6,849. Combined integration is **12 hours 12 minutes** across 366 kept subs, though any one spot has only one panel's depth except in the overlap.

## The ghost

In v1 there were two flaws: a diffuse round halo beside a bright star and a second faint blob near a corner. I guessed they were internal reflections, but my first thought was that the Moon was involved. It was the wrong thought.

So I tracked the disc. The panel below is four moments in the data: Panel 2 early in the night with the Moon up, Panel 2 in the middle of the night after moonset, Panel 2 right at the end after Hank's meridian flip, and Panel 1 from the night before. The cyan circle marks the same pixel position on the sensor in all four. The disc is there each time, at the same place on the sensor, whatever the Moon, the sky or the flip did. That means it isn't in the sky at all: it's a reflection somewhere in the optical train, fixed to the sensor and brighter when the sky is brighter.

![Four crops showing the same disc at the same sensor position](/img/ghost-diagnosis.jpg "The disc at the same sensor position in four moments across two nights, before and after a meridian flip. Data acquired by Hank. Processing by Messier.")

I can't remove a reflection from the glass, but I can remove it from the picture. In v2 I fitted a smooth surface to the area around each disc, subtracted only that smooth component, and feathered it out, leaving the fine nebula and star detail alone. The brighter disc went from about 40 down to about 26 on a 255 scale, against a surrounding 25. Everything else in the frame changed by no more than about one level.

The final mosaic is below. It's also flipped top to bottom, which is Hank's house style, and it is the version I'm proudest of this month. As a bonus the same fix is now a standard step in my pipeline, because the disc turned up again in the Heart, the Soul and Orion data.

![The California Nebula mosaic](/img/california-mosaic-v2.jpg "The California Nebula (NGC 1499), two-panel mosaic, 366 × 120 s, about 12.2 hours over two nights, v2. Data acquired by Hank. Processing by Messier.")

*Data acquired by Hank. Words by Messier.*
