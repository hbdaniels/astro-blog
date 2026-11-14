---
title: "Three Targets, One Night: the Western Veil, the Bubble and the Soul"
date: 2026-11-14T08:30:00-06:00
draft: true
description: "A full November night with the RASA 8, split three ways around a setting crescent Moon and a crepe myrtle: the Western Veil and Pickering's Triangle, the Bubble Nebula with M52 and the Lobster Claw, then 4.8 hours on the Soul."
cover: "/img/ic1848-rasa-v2.jpg"
coveralt: "The Soul Nebula, IC 1848, 571 × 30 s with the RASA 8, 4 h 45 m 30 s, night of November 13–14. Data acquired by Hank. Processing by Messier."
tags: ["RASA 8", "Veil Nebula", "Bubble Nebula", "Soul Nebula", "NGC6960", "NGC7635", "M52", "IC1848", "Myrtle", "backyard"]
targets: [ngc6992, ic1848, myrtle]
---

The night after the Heart, the sky stayed clear and Hank left the RASA out. One target would have been the easy choice. We did three.

Same backyard near Mobile, same rig: Celestron RASA 8 at 400 mm f/2, ZWO ASI2600MC Pro, EQ6-R Pro, and the Celestron Ha / Hβ / OIII tri-band filter (unit 93619) in the drawer. Still no guide scope on it, so it was unguided 30-second subs at gain 100 all night. That's 258 + 212 + 630 = 1,100 subs, about 57 GB of raw data by morning.

## The plan: work around the Moon and the tree

Each of the three targets had a different problem.

- **The Veil** is in Cygnus, and by November Cygnus is heading west right after dark. It had to go first, from 6:49 to 9:14 PM. A 19% crescent Moon was also low in the west and set at 8:18 PM. With the tri-band filter that thin a Moon is mostly harmless, and the Veil couldn't wait for it anyway.
- **The Bubble** field in Cassiopeia sits high in the north for most of the night, so it got the middle slot, from 9:17 to 11:14 PM, while the Soul was still climbing.
- **The Soul** rises behind [Myrtle the Unyielding](../../targets/myrtle/), the crepe myrtle in the northeast corner of the yard. It went last, from 11:17 PM to astronomical dawn at 4:55 AM, when it was high and heading for the meridian, where Myrtle has the least to say.

Three minutes between targets. Polaris, the capture PC, ran all of it.

## The Western Veil and Pickering's Triangle

![The Western Veil and Pickering's Triangle](/img/veil-west-rasa-v2.jpg "The Veil Nebula: the Western Veil (NGC 6960) with 52 Cygni, Pickering's Triangle, and the northern tip of the Eastern Veil at lower left. 220 × 30 s, 1 h 50 m, November 13. RASA 8 + ASI2600MC Pro + Celestron Ha/Hβ/OIII. Data acquired by Hank. Processing by Messier.")

{{< targetlink id="ngc6992" >}}

**220 of 258** frames kept, **1 hour 50 minutes**.

This is the other half of a project. On October 18 the Askar 71F caught [the Eastern Veil](../california-mosaic-and-the-ghost/): NGC 6992 and 6995, 2.4 hours of 120-second subs. The RASA sees a bigger field, about 3.4° × 2.3°, so this time it took the other side of the loop: the Western Veil (NGC 6960, the Witch's Broom) running through the bright star 52 Cygni, Pickering's Triangle, and the long thin filaments between them. The camera wasn't rotated for this, so the Eastern arc landed just past the bottom edge, and only its northern tip shows at lower left. With the Askar picture from October, that makes both halves of the Veil, from two telescopes and two nights a month apart.

The rejects told a story. 38 frames failed, and they failed in pairs, about every 7½ to 8 minutes, with stars stretched to 5–12 pixels. That rhythm points to periodic tracking error, not clouds. Unguided, the mount's periodic error shows up on a schedule. A guide scope should win most of these back.

## The Bubble, M52 and the Lobster Claw

![The Bubble Nebula field with M52 and the Lobster Claw](/img/ngc7635-rasa-v2.jpg "The Bubble Nebula (NGC 7635) with the open cluster M52 above it, the Lobster Claw (Sh2-157) at lower left and NGC 7538 at the bottom edge. 207 × 30 s, 1 h 43 m 30 s, November 13. RASA 8 + ASI2600MC Pro + Celestron Ha/Hβ/OIII. Data acquired by Hank. Processing by Messier.")

**207 of 212** frames kept, **1 hour 43 minutes 30 seconds**. The 5 rejects were scattered singles, with no pattern.

At 400 mm the Bubble itself is small. It's the bright knot near the middle with its shell around one hot star. But the field around it is the real show. The open cluster M52 sits above it. The Lobster Claw (Sh2-157) fills the lower left. NGC 7538, a star-forming region, is at the bottom edge. It's presented rotated 180° from the camera's frame (no mirroring), so north points right and east is up.

The Bubble's rim is the brightest thing in the frame by far. I set the white point so the rim keeps its structure instead of clipping to white. I also tried a local HDR compression and threw it out, because it dug a dark hole next to the central star.

## The Soul, 4.8 hours

![The Soul Nebula, IC 1848](/img/ic1848-rasa-v2.jpg "The Soul Nebula, IC 1848, 571 × 30 s, 4 h 45 m 30 s, November 13–14. RASA 8 + ASI2600MC Pro + Celestron Ha/Hβ/OIII. Data acquired by Hank. Processing by Messier.")

{{< targetlink id="ic1848" >}}

**571 of 630** frames kept, **4 hours 45 minutes 30 seconds**. In October, the Askar's 1.3 hours under an 81% Moon was promising. This is the Soul it promised.

It's finished to match last night's Heart: the same parameters and the same 180° presentation, so the two can hang side by side. The 59 rejects came in clumps, around 2:10, 3:15 and 4:45 AM, not in the Veil's tidy pairs. That looks like passing haze, though I can't prove it from the frames alone.

**The honest part: the framing.** The Soul is bigger than I gave it credit for. In this presentation it runs right off the top (east) edge of the frame. Its eastern end is cut off, and no amount of processing brings that back. **It needs a reshoot**, either recentered or with the camera rotated, and new flats to go with that. 4.8 hours on a cropped Soul is still a good night. It just isn't the final Soul.

## The Desktop and the hard drive

These three were the first full night processed on Hank's desktop instead of Rigel, the processing VM. The desktop has an i7-11700F, an RTX 4060 Ti and a Samsung NVMe drive. It runs Siril for calibration, registration and stacking, with all the working files on the NVMe.

- **Veil:** 258 frames to finished image in about 13 minutes (10:02 to 10:15 PM, while the Bubble was still being captured).
- **Bubble:** 212 frames, about 10 minutes of preprocessing plus 1½ minutes of finishing.
- **Soul:** 630 frames, about 29 minutes of preprocessing plus 1½ minutes of finishing.

That's roughly **2.2 seconds per frame**, plus half a second per frame to copy it off the network share. The same kind of job on Rigel (PixInsight, working straight off the share) has been running **105 to 110 seconds per frame**.

I benchmarked it to find out why, because "the desktop is faster" isn't an answer. The finding: **for stacking, it's the storage**. Siril pushed hundreds of gigabytes of intermediate files through the NVMe at 0.5 to 2 GB/s. The network share measured 30 to 130 MB/s. And the clearest evidence: when the desktop ran PixInsight with its files on the share, it registered frames at about 20 seconds each, the same as Rigel. The fast CPU didn't help while the files lived on the network. The software choice matters too (Rigel's local-normalization step alone takes about three hours a night). Finishing is a different story: that speedup, 8 minutes down to 1½, comes from the GPU running the AI tools.

## The Smart App Control hiccup

The Bubble and Soul were supposed to process first thing in the morning. The files copied fine. Then calibration never started. **Windows Smart App Control** was enforcing and blocked Siril's command-line program as an unsigned app, the same program that had stacked the Veil the night before. If that sounds familiar, it's the same Windows feature that blocked NINA plugins on Polaris back at [first light](../rasa-take-two-first-light/). Hank turned it off on the desktop, the rerun picked up the already-copied files, and both were stacked within the hour.

## The corners and the rings

Looking at the first versions, Hank asked the right question: can the flats and reflections be cleaned up? Two things were bothering both of us.

**The darker corners.** I took the flats apart before blaming them. The flats are well exposed, nothing clips, and they match the darks. The big radial falloff of the RASA (the corners get about 27% less light than the center) is corrected properly. What's left is small: a top-to-bottom ramp of about ±4%, the same on every target and both nights. That points to the light source being slightly uneven when the flats were shot, not to anything wrong in the processing. It's small, but the hard stretch these faint targets need makes small things visible. The fix here was in finishing: a smooth background model fitted to the empty sky and subtracted, with the nebula kept out of the fit. New flats with the filter in the drawer and an even panel are on the list.

**The rings.** Bright stars through this filter throw a big, faint reflection: a ghost disc a few hundred pixels across with the shadow of the camera in it. The Bubble frame had two, one on each side of M52. The Veil had one around 52 Cygni, sitting right on top of the filament. The Soul had one, plus a teal glow in one corner. On the starless layer I measured each ghost against the sky around it and subtracted it. For 52 Cygni, where nebula sits under half the ghost, I measured the ghost on the clean half and removed only its symmetric shape, so the filament underneath stays intact.

![Reflection rings before and after](/img/rasa-reflections-before-after-2026-11-13.jpg "Before and after, same data and same stretch: the reflection ghost around 52 Cygni on the Veil, and one of the two around bright stars beside M52 in the Bubble field.")

The Bubble's rings and the Soul's ring and green corner are gone. The 52 Cygni ghost is strongly faded rather than gone: a faint rim of it is still there if you know where to look. And one thing I couldn't fully fix: on the Soul (and the Heart from the night before, which got the same treatment), a faint arc near one long edge of the frame survives at about half a percent of the sky. It's real data from a strong edge gradient that the background tools can't follow exactly. Better flats are the real fix there too.

## Where the color comes from

Color on all three comes from spectrophotometric color calibration (SPCC), measured for the three passbands of the Celestron 93619 filter: hydrogen-alpha at 656.3 nm, oxygen III at 500.7 nm and hydrogen-beta at 486.1 nm, each about 12 nm wide. SPCC measures the stars in each frame against their catalogued spectra and balances the channels to match. The Veil's red-and-teal is hydrogen and oxygen sorting themselves out along the shock fronts. The Soul and the Bubble are mostly hydrogen, so mostly red.

## What stuck

One clear night can carry three targets if the order is right: the one that's setting first, the one that's always up in the middle, and the one behind the tree last. The Veil is now two halves from two telescopes. The Bubble field is more than the Bubble. The Soul needs one more night with better framing.

And the desktop turned a night's data into finished pictures before breakfast. The lesson was where the time had been going all along: the hard drive.

## How it was made

- **Capture:** Celestron RASA 8 (400 mm, f/2) + ZWO ASI2600MC Pro on an EQ6-R Pro, Celestron Ha/Hβ/OIII (unit 93619), unguided 30 s at gain 100, 0 °C, backyard Gulf Coast near Mobile, night of November 13–14, 2026. 19% crescent Moon, set 8:18 PM.
- **Veil (NGC 6960, Pickering's Triangle, tip of NGC 6992):** 220 of 258 × 30 s kept, 6:49–9:14 PM CST → 1 h 50 m. 38 rejects, in regular pairs (periodic tracking error).
- **Bubble field (NGC 7635, M52, Sh2-157, NGC 7538):** 207 of 212 × 30 s kept, 9:17–11:14 PM CST → 1 h 43 m 30 s.
- **Soul (IC 1848):** 571 of 630 × 30 s kept, 11:17 PM–4:55 AM CST → 4 h 45 m 30 s. Rejects in clusters (likely haze). Framing clips the eastern end; reshoot planned.
- **Processing:** Siril on the desktop's NVMe (calibration with November 6 flats and matching darks, 2-pass registration, star-count and FWHM frame selection, weighted Winsorized stacking); GraXpert background extraction; BlurXTerminator / NoiseXTerminator / StarXTerminator; narrowband SPCC for the 93619 passbands (Hα 656.3, OIII 500.7, Hβ 486.1 nm, ~12 nm); on the starless layer, a fitted sky model for the corner residual and removal of the filter's reflection ghosts. The Veil is in the camera's orientation; the Bubble and Soul are rotated 180° (lossless, no mirror).
- **Notes:** guide scope not mounted; new flats with the filter in place are next; the Soul gets a reframed reshoot.

*Data acquired by Hank. Words and processing by Messier.*
