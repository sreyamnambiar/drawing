# Living Kolam

A floor made of light that draws a pattern as you walk on it.

Concept and prototype by **Sreya M Nambiar** for DJXHack 2026, "Everyday Magic".

Every dawn, in homes across India, someone draws a pattern at the doorstep. It is walked over and gone by evening, and drawn again the next morning. Living Kolam keeps that ritual and lets everyone take part, including children who cannot draw the lines yet, grandparents who cannot bend down, and families in apartments with no doorstep.

## Try it

Open `index.html` in any modern browser. No install or build step.

To host it on GitHub Pages, go to **Settings, Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save. The page will be served at `https://sreyamnambiar.github.io/drawing/`.

You can open a tradition directly with a link such as `.../drawing/#aipan`.

## What it does

1. A grid of glowing dots lies on a stone floor.
2. When someone steps on it, the dots near their feet scatter like flour.
3. As they walk, their path draws loops of light around the dots. Sreya's loops are gold.
4. A second person, Paati, joins and her loops (teal) mirror the first person's.
5. When the pattern is nearly full, it completes together with a soft chime and a glow.
6. As the sun rises it fades, and the floor is clear for tomorrow.

Press **Play the story** for a 47-second guided run with captions, then take over yourself.

## Controls

| Control | What it does |
| --- | --- |
| Mouse, touch, arrow keys | Walk across the floor. A second finger acts as Paati. |
| Play the story | Guided run through all six steps with captions. |
| Tradition | Switch between Kolam, Rangoli, Alpona and Aipan. |
| Paati mirrors me | Adds a mirrored second walker when only one person is moving. |
| Sound | A soft note for each loop and a chime on completion. |
| Camera | Uses motion in front of your camera as footsteps. A second moving person draws as Paati. Needs the page to be served over HTTPS or opened locally, and camera permission. |
| Sunrise slider | Fades the pattern out by hand. |

Camera video stays in the browser. Nothing is recorded or sent anywhere.

## Traditions

The same engine draws four floor traditions. Each is a simplified generative drawing inspired by the real practice, not a traditional design.

| Tradition | Region | Look in this prototype |
| --- | --- | --- |
| Kolam | Tamil Nadu | Rice-flour diamond loops around a dot grid |
| Rangoli | Maharashtra, Gujarat | Colored circles on a square grid |
| Alpona | West Bengal | Rice-paste lotus petals |
| Aipan | Uttarakhand | White loops on a red-ochre floor |

## Real, simulated and proposed

| Part | Status |
| --- | --- |
| Web prototype in `index.html` | Working. Cursor, touch or camera motion stands in for footsteps. |
| Concept video | Simulated scenes of the floor. |
| Floor projection with a depth camera | Proposed, not built. |

## Proposed installation

1. **Sense:** a ceiling-mounted depth camera or LiDAR sensor sees feet on the floor.
2. **Track:** OpenCV or MediaPipe finds each person's position and path.
3. **Generate:** the same dot-grid engine used in this prototype draws loops along each path.
4. **Project:** a short-throw projector paints the light on the floor and a small speaker plays the chime.

Likely places: apartment lobbies, school entrances, temple streets, cultural centres, and festivals such as Pongal and Margazhi.

## Files

- `index.html`: the whole prototype in one file (HTML, CSS and JavaScript).
- `Living_Kolam_Concept.pdf`: the three-page concept document.

## Credits

Concept, interaction design and prototype by Sreya M Nambiar. Fonts: Yatra One and Hanken Grotesk from Google Fonts.
