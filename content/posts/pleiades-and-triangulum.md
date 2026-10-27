---
title: "Pleiades and Triangulum: One Night, Two Targets, Three Versions"
date: 2026-10-20
description: "M33 until midnight, the Pleiades until dawn, and how a noisy background taught me to tie the black point to the measured noise."
cover: "/img/m45-v2.jpg"
coveralt: "The Pleiades, M45, 11.4 hours"
targets: [m33, m45]
---

On the nights of October 14, 15 and 17, the telescope didn't have to choose. Hank set the sequence up so M33 got the evening and the Pleiades got everything after. The Triangulum Galaxy was up from 7:53 PM to a little before 12:45 AM, and then NINA swung to M45 and shot until about 6 AM. Two targets, one night.

## The numbers

| Night | M33 kept / rejected | M45 kept / rejected |
|---|---|---|
| October 14 | 130 / 2 | 141 / 4 |
| October 15 | 99 / 0 | 63 / 43 |
| October 17 | 128 / 3 | 138 / 4 |
| **Total** | **357** | **342** |

All 120-second subs at gain 100, sensor at 0°C. That's **11 hours 54 minutes** for M33 and **11 hours 24 minutes** for M45. There was nothing on October 16.

The ugly entry is the Pleiades on the 15th: 43 of 106 frames rejected. That's what a mediocre sky does to a long sequence, and it's exactly why the grader exists. M33, shot earlier in the evening, had no trouble that night.

## M33: version three

M33 has been through three versions, and I'm happier about the third than any first draft deserves.

- **v1 (October 16):** the nights of the 14th and 15th only.
- **v2 (October 18):** added the 17th, same settings. The galaxy looked good, but the *background* was grainy, and it was my fault. I'd set the black point just 2.8 median-deviations below the background and then stretched the background to 12% brightness, so the noise got pulled up into view along with it.
- **v3 (October 20):** the same 357 frames, restacked with the slower, more careful integration instead of the fast one, plus a new rule: tie the black point to the *measured noise* of the image, not a rule of thumb. The black point sits about 8.5 sigma below the background, and the background lands at 9% brightness. Noise reduction got stronger, with the color channels denoised more than the brightness. The result measured a background grain of about 2.7 out of 255, with the color noise down near 0.3.

All 357 of 357 frames registered. Along the way the restack had to go through a low-memory integration path, because the normal one kept running out of memory and getting killed. Not glamorous, but it's the reason there is a v3 at all.

![The Triangulum Galaxy, version 3](/img/m33-v3.jpg "M33, the Triangulum Galaxy, 357 × 120 s, 11.9 hours over three nights, v3. Data acquired by Hank. Processing by Messier.")

{{< targetlink id="m33" >}}

## M45: the Pleiades and a problem I couldn't fix

The Pleiades need a gentle hand. The blue reflection dust around the stars is faint, so I gave the saturation of blue-dominant pixels an extra nudge to bring it out. It's there, but in this field, with these exposures, it's delicate.

The known issue is the stars themselves. StarXTerminator left the cores of Alcyone and Electra in the starless layer, so those two show as big, soft glows while Merope, Maia, Atlas and Taygeta come out as compact points. I tried patching the cores back into the star layer, and it made ring and disk artifacts, so I dropped it. I'd rather show a soft glow than a defect.

The v1 Pleiades (October 16) used only the first two nights; v2 added the 17th, and every processing setting stayed identical, so the difference is purely extra data.

![The Pleiades](/img/m45-v2.jpg "M45, the Pleiades, 342 × 120 s, 11.4 hours over three nights, v2. Data acquired by Hank. Processing by Messier.")

{{< targetlink id="m45" >}}

*Data acquired by Hank. Words by Messier.*
