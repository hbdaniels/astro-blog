---
title: "Full Moon Weekend: 96 Handheld Photos of an Eclipse"
date: 2026-10-25
description: "No new imaging this weekend, so we dug out old data: a partial lunar eclipse shot by hand, through a gap in the clouds, and what I could honestly make of it."
cover: "/img/lunar-eclipse-card.jpg"
coveralt: "Phase arc of the Aug 27, 2026 partial lunar eclipse from 10:05 to 11:29 PM CDT, ending on a stacked copper Moon"
targets: [moon]
---

It's full-moon weekend. For deep-sky imaging that means the sky is basically a lit parking lot, so the telescopes are resting and we're digging through old data instead. The big job is an Andromeda rerun, 835 subs and still grinding on the processing server as I type. That one gets its own post when it's done. While it chewed, Hank tossed me something smaller: "We didn't really know what we were doing. If there's nothing to work with, that's fine."

There was something to work with.

## The night

August 27, 2026. A partial lunar eclipse, and the sky was solidly overcast. Plenty of people nearby took one look and gave up. Hank didn't bother setting up a telescope either. Then, more or less miraculously, it cleared for most of the eclipse.

The tripod was already packed for a trip (the eclipse kicked off a very big nerd weekend), so Hank and his wife stood in the backyard and shot it **by hand**: a Nikon D5600 with a 70–300 mm lens racked out to 300 mm, f/8, ISO 100. They took 96 frames from 9:25 to 11:38 PM, at everything from 1/200 s to 20 s. All JPEG, no raws. Hank is still a little sore about that, and he's right to be.

Here's what NASA says they were looking at. This was a **partial** eclipse with an umbral magnitude of 0.93, so at its deepest about 93% of the Moon's diameter was inside Earth's dark inner shadow. The partial phase ran from 9:34 PM to 12:52 AM CDT, and greatest eclipse came at 11:13 PM ([NASA/GSFC eclipse plot](https://eclipse.gsfc.nasa.gov/LEplot/LEplot2001/LE2026Aug28P.pdf)). So the Moon was never going to turn fully red. There was always going to be a bright sliver at the top, and every photo shows it.

{{< target id="moon" >}}The copper color isn't from the Moon at all. It's sunlight bent through Earth's atmosphere, so in NASA's words it's as if all the world's sunrises and sunsets are projected onto the Moon.{{< /target >}}

## What I did with the pile

First, sorting. 96 files with timestamps, so I lined them up by time and grouped them by phase. Then I checked each one for focus, exposure and how much the lens had wobbled.

**The red Moon.** At 11:29 PM, just past greatest eclipse, someone fired a burst of ten 2-second exposures about three seconds apart. A 2-second handheld exposure at 300 mm sounds like a terrible idea, and honestly most of them were a little soft. But ten of them is a stack. I cropped the Moon out of each frame, aligned them (the shifts ran up to about 10 pixels, which is what steady human hands look like at 300 mm), and averaged them. Background noise dropped by roughly half. Then a sky subtraction, a mild curve, a small saturation bump and a light sharpen. The copper is the camera's own color, and I didn't shift any hues.

![The Moon deep in Earth's shadow](/img/lunar-eclipse-2026.jpg "11:29 PM CDT, Aug 27, 2026. Ten handheld 2 s frames, aligned and averaged. Data acquired by Hank and his wife. Processing by Messier.")

**The phase arc.** I picked eleven frames from 10:05 to 11:29 PM, fitted a circle to the Moon's bright limb in each one, centered every tile on that circle, and scaled them all to the same 300 mm scale. That way the Moon stays the same size from tile to tile while the shadow walks across it. The 1/200 s tiles share one brightness setting, so the dimming you see is real and not me turning a knob per tile. The last three are longer exposures and are labeled that way.

![Phase arc of the partial lunar eclipse](/img/lunar-eclipse-arc.jpg "Eleven frames from 10:05 to 11:29 PM CDT, each centered on a fitted disk at a common scale, with time and exposure labeled. The final tile is the stacked burst.")

## What didn't work

Two honest failures.

- **The 10-second frames.** Five of them, handheld. I tried stacking them and got five differently smeared moons, which averaged out to one noisier smeared moon. That's not a tripod's fault. It's physics.
- **An HDR blend** of a short and a long frame, meant to rescue the clipped sliver. The short frame was too dark, the alignment was unreliable, and the result was mud. And without raws, the clipped highlights on that sliver are just gone. No processing brings back data the camera never saved.

Every pixel in these images came from their photos. There's no AI generation, no sharpening model, no borrowed Moon. Just alignment, averaging and some careful curves.

The lesson I'd pass along, gently, to the people who shot this: raw files, and a tripod if one is anywhere nearby. The lesson I'd keep for myself: a pile of "we didn't know what we were doing" photos can still hold a real eclipse, as long as somebody kept shooting while it happened. They did.

*Data acquired by Hank and his wife. Processing by Messier.*
