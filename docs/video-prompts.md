# Christmas Dashboard CCTV Prompts & Assets

> [!IMPORTANT]
> **Global suffix – append to EVERY anchor and video prompt:**
> `No text, no captions, no timestamp, no camera label, no watermark, no on-screen UI or HUD anywhere in the frame.`
> The card draws the REC dot, live date/time and camera name itself. Earlier test clips had a burned-in timestamp/label
> (the generator invents them for "CCTV" prompts), which then shows twice – regenerate those.

## Step 1: Empty Base Reference Images
- **Base 01 - Reindeer Paddock:** `base_01_reindeer_paddock.jpg`
- **Base 02 - Toy Workshop:** `base_02_toy_workshop.jpg`
- **Base 03 - Nice-List Mailroom:** `base_03_mailroom.jpg`

---

## Step 2: CAM 01 - Reindeer Paddock and Barn (Base 01)

### 1. Morning - Arctic Dawn
- **Anchor Frame:** `cam01_01_arctic_dawn_anchor.jpg`
- **Anchor Prompt:** Same fixed CCTV view of the snowy reindeer paddock and open-fronted timber barn at pink and blue Arctic dawn, warm lanterns glowing inside the barn, two reindeer standing at a full wooden hay trough in the center of the yard, one elf in a green winter coat standing beside a reindeer holding a wooden grooming brush, photorealistic.
- **Cyclical Video Prompt:** Static locked-off CCTV camera shot, zero camera movement. Pink and blue Arctic dawn light over the snowy paddock. Two reindeer stand in place at a full wooden trough calmly chewing hay with visible steam puffing rhythmically from their nostrils. Beside them, an elf in a green coat gently brushes one reindeer's flank in slow, repetitive strokes, returning to the starting pose at the end. Subtle cold wind and soft sleigh bells audio.

### 2. Day - Peak Activity
- **Anchor Frame:** `cam01_02_day_anchor.jpg`
- **Anchor Prompt:** Same fixed CCTV view of the snowy reindeer paddock in bright blue Arctic daylight, three reindeer standing in the snow near low wooden jumping hurdles, light snow falling, photorealistic.
- **Cyclical Video Prompt:** Static locked-off CCTV camera shot, zero camera movement. Bright blue Arctic daylight with light snow falling continuously. Three reindeer stand near the low wooden hurdles; two gently shake snow from their antlers and swish their tails while one reindeer in the center paws the snow and does a gentle, brief hover-hop in place before settling back into its exact starting pose. Subtle crunching snow and soft jingling bells audio.

### 3. Night - Aurora and Quiet
- **Anchor Frame:** `cam01_03_night_anchor.jpg`
- **Anchor Prompt:** Same fixed CCTV view of the reindeer paddock at dark starry night, vivid green Aurora Borealis in the sky above the barn, warm dim lantern glow inside the open-fronted barn stalls where three reindeer lie sleeping in the hay, one reindeer has a softly glowing red nose, photorealistic.
- **Cyclical Video Prompt:** Static locked-off CCTV camera shot, zero camera movement. Dark starry Arctic night with green Aurora Borealis rippling slowly across the sky. Inside the warmly lit open barn stalls, the sleeping reindeer breathe gently in the hay with occasional subtle ear twitches while one reindeer's red nose pulses with a soft warm glow, returning smoothly to the starting state at the end. Quiet night wind audio.

---

## Step 3: CAM 02 - Toy Workshop Floor (Base 02)

### 4. Morning - Warm-Up
- **Anchor Frame:** `cam02_04_morning_anchor.jpg`
- **Anchor Prompt:** Same fixed CCTV view inside Santa's wooden toy workshop lit by warm morning overhead lamps, two elves standing at the main oak workbench holding steaming mugs of cocoa next to a small circular model train track on the table, photorealistic.
- **Cyclical Video Prompt:** Static locked-off CCTV camera shot, zero camera movement. Warm morning lamps illuminate the toy workshop. Two elves stand in place at the main workbench holding steaming cocoa mugs, chatting and nodding naturally while returning to their starting poses at the end, as a miniature wooden train completes a continuous loop around the circular track on the table. Soft mechanical hum and quiet morning workshop ambience.

### 5. Day - Peak Hustle
- **Anchor Frame:** `cam02_05_day_anchor.jpg`
- **Anchor Prompt:** Same fixed CCTV view inside the busy toy workshop, evenly spaced identical red-and-gold wrapped Christmas presents sitting along the central conveyor belt, three elves standing at the oak workbenches holding small wooden mallets and polishing cloths next to wooden toys, photorealistic.
- **Cyclical Video Prompt:** Static locked-off CCTV camera shot, zero camera movement. Busy daytime hustle in the toy workshop. Evenly spaced identical red-and-gold wrapped presents move at a steady, uniform pace down the central conveyor belt (advancing by an exact spacing interval so the belt aligns seamlessly at the end) while three elves stand at their workbenches gently tapping and polishing wooden toys in continuous rhythm, with tiny golden sparks flickering occasionally at a tinkering station, returning to their starting poses at the end. Subtle hammering and conveyor whirring audio.

### 6. Night - After-Hours Check
- **Anchor Frame:** `cam02_06_night_anchor.jpg`
- **Anchor Prompt:** Same fixed CCTV view inside the toy workshop at night, overhead lights off with only two warm desk lamps glowing, idle conveyor belt, a single night-shift elf standing near a stack of wrapped gifts holding an open clipboard and a pencil, photorealistic.
- **Cyclical Video Prompt:** Static locked-off CCTV camera shot, zero camera movement. Quiet after-hours night shift in the dimly lit workshop. A single elf stands in place beside stacks of wrapped gifts, glancing calmly between an open clipboard and the boxes while lightly tapping a pencil against the board in a slow cyclical rhythm, returning to the exact starting pose at the end. Soft clock ticking and quiet room tone.

---

## Step 4: CAM 03 - Nice-List Mailroom (Base 03)

### 7. Morning - Early Sorting
- **Anchor Frame:** *(Pending quota reset or `GEMINI_API_KEY`)*
- **Anchor Prompt:** Same fixed CCTV view inside the North Pole mailroom with pale blue morning light shining through the frosted windows, brass pneumatic tubes with pressure gauges mounted on the wall above woven baskets full of letters, one elf standing at the central wooden sorting table holding a neat stack of envelopes, photorealistic.
- **Cyclical Video Prompt:** Static locked-off CCTV camera shot, zero camera movement. Pale blue morning light filters through the frosted mailroom windows. Brass pneumatic tubes vent tiny puffs of steam from their pressure valves at steady intervals while an elf stands at the sorting desk gently tapping and squaring up a neat stack of envelopes in place, returning to the exact starting pose at the end. Soft steam hiss and gentle paper rustling audio.

### 8. Day - Peak Mail Rush
- **Anchor Frame:** `cam03_08_day_anchor.jpg`
- **Anchor Prompt:** Same fixed CCTV view inside the North Pole mailroom in bright daytime light, woven baskets filled with letters beneath brass pneumatic tubes, two elves standing across from each other at the central wooden table with ink pads, wooden stamps, and a brass magnifying glass next to neat trays of envelopes, photorealistic.
- **Cyclical Video Prompt:** Static locked-off CCTV camera shot, zero camera movement. Peak daytime mail rush in the mailroom. Two elves work in place at the central wooden table in a brisk, continuous rhythm—one elf rhythmically inks and stamps an envelope while the other inspects wax seals under a warm brass lamp, keeping all letter trays neat and unchanged and returning to their exact starting poses at the end. Crisp stamping sounds and quiet mailroom ambience.

### 9. Night - The Nice List
- **Anchor Frame:** *(Pending quota reset or `GEMINI_API_KEY`)*
- **Anchor Prompt:** Same fixed CCTV view inside the North Pole mailroom at night, soft blue moonlight and falling snow visible through frosted windows, a single warm desk lamp illuminating an elf seated at the central table reading an unrolled parchment scroll emitting a soft golden glow, photorealistic.
- **Cyclical Video Prompt:** Static locked-off CCTV camera shot, zero camera movement. Quiet nighttime in the mailroom with snow falling outside the frosted windows. Lit by a warm desk lamp, a single elf sits at the central table slowly tracing a finger down a softly glowing golden Nice List parchment, pausing to nod gently before reading again, returning to the exact starting pose at the end. Quiet ambient room tone and faint wind outside.

---

## Seamless Looping Tip (10s / 20s)
For every clip, pass the **same Anchor Frame as both the First Frame and Last Frame** (duration `10s`). If you want `20s` clips for your dashboard, repeat the seamless `10s` loop 2×.
