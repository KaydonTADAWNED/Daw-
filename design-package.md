# Freedom Contracting: Design Package (Tier 1)

## 1. Brand premise
One idea: **follow-through.** Midlands homeowners and property owners fear crews that "don't show up or follow through," jobs that run "over budget and over time," and getting overcharged. Freedom Contracting shows up, gives a clear price, keeps the site clean, and finishes what it starts. Every section proves follow-through, and the one call to action is **Request an estimate**.

## 2. Palette (direction from the footage world: pine shade, red brick, porch light; finalize from approved footage)
```css
:root{
  --canvas:#1b1e1a;        /* pine-shade charcoal, tinted green, never pure black */
  --panel:#252923;         /* raised surfaces */
  --brick:#8a3e2c;         /* secondary tone from the brick, used sparingly */
  --accent:#f2763c;        /* construction orange (user's choice): CTA and rare emphasis */
  --accent-hover:#ff8850;
  --accent-muted:rgba(242,118,60,.22);
  --text-secondary:#bdb7aa;
  --text-primary:#f3efe6;  /* warm cream from the user's pasted hero */
}
```
Deviation said out loud: dark canvas + warm accent sits near a banned cliché. It is earned here because the orange is the client's own color and the charcoal is sampled from pine shade, not a default. No high-contrast serif display face, to stay clear of the template look.

## 3. Type trio
- Display: **Big Shoulders Display** 800 (signage and jobsite stencil feel, echoes the logo's lettering weight)
- Body: **Public Sans** 400, 600
- Mono labels: **IBM Plex Mono** 500 (site notes, step numbers)

## 4. Band map (starting points, validated by the flick test)
| Band | Range | Footage moment | Copy (verbatim) | Entrance |
|---|---|---|---|---|
| 1 | 0.00 to 0.22 | High in the pines, morning haze | "Built with care." / kicker "Freedom Contracting · South Carolina Midlands" | Blur-to-sharp (haze clearing), load ramp |
| 2 | 0.26 to 0.48 | Sinking through the canopy toward the roof | "We show up when we say we will." | Drift-down (the camera is descending) |
| 3 | 0.52 to 0.74 | Passing the new roofline and red brick | "Clear price. Clear plan. Clean site, every day." | Grid snap-align (laid like brick courses) |
| 4 | 0.80 to 1.00 | At rest on the front walk, porch light on | "Made to last." / "Homes, remodels, and rental units across the Midlands." / CTA "Request an estimate" + "See the work" | Word rise into staged settle |

Captions live in the left third; the descent lane runs center-right.

## 5. Static-hero copy
Headline "Built with care. Made to last." Subline "Homes, remodels, and rental units across the South Carolina Midlands. We show up, we give you a clear price, and we finish the job." CTA "Request an estimate".

## 6. Below-fold outline (all funnel to #estimate)
1. **Before and after** (interactive moment): drag handle over the real 540 building photos. Heading "From boarded up to move-in ready." Line "Same building. Same brick. New siding, new railings, new life."
2. **The work**: four real photos, equal cards. Kitchen "Galley kitchen, rebuilt." Bedroom "New floors, new doors, fresh paint." Tub "Tile surround, floor to ceiling." Bath "Vanity, fixtures, and finish."
3. **What we build**: Homes ("New residential builds and additions."), Remodels ("Kitchens, baths, floors, and whole-unit refreshes."), Rental and commercial ("Unit turns that get you back to rent-ready, fast.").
4. **How it works**, three steps with drawn SVG marks: 1 "We walk the job with you." 2 "You get a written price. No guessing." 3 "We build, clean up daily, and walk it again with you at the end."
5. **Straight answers (FAQ)**: "Will you actually show up?" / "What if the price changes?" / "Do you work on rentals and apartments?" / "Who do I talk to during the job?" / "Where do you work?"
6. **Estimate form**: name, phone, email, project type, short note. Button "Request my estimate". Success "Got it. We'll call you within one business day." Handling: TBD with the client (mailto or form service; contact details needed).
7. **Footer**: logo, "Freedom Contracting, LLC · South Carolina Midlands", contact.

## 7. Vector layer
A self-drawing roofline (from the logo's roof) above section heads; a plumb-line hairline that draws down the How-it-works steps; whisper-level dust motes in warm light; one fixed background layer of slow pine-shadow drift. All honor reduced motion.

## 8. Engineering list
Blob fetch with loading ring, dt-normalized lerp, gated seeks, delta-gated DOM writes, band pacing plus flick test, four-layer legibility system, five static-hero gates live in CSS and JS, complete without video, full quality floor, whole-site-animated standard.

## 9. Copy gate
Every line above ships verbatim. The built page must pass the grep gate (zero em dashes, zero stock words) and the AI-tell sweep. The staccato "Clear price. Clear plan. Clean site, every day." is a deliberate device.
