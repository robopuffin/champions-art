# Location pictures: how they are made

Each picture is one location behind the sheet's figures. The sheet draws the people, doors and computers itself, so the pictures hold none.

## The rules

- **Horizon 60% down, eye level:** every figure's head sits on the horizon, so one size value places a figure at any distance, on any location.
- **Vanishing point 30% from the left:** distant foes stand at the left, the hero and those in melee at the right. The picture's depth has to run that way.
- **A flat wall on the right quarter, plain low down:** the sheet puts a door and a computer there.
- **Clear ground, nothing in the foreground:** figures stand there, and labels sit over it.
- **Darker colours:** the figures are pale.
- **The panel crops:** at its shortest it shows only 36% to 76% of the way down a picture, so what matters most goes in that band.

Finished files are 1600 by 940, JPG, about 300 to 500 KB. An address names a tag, never a branch. Name no artist, publisher or character in a prompt.

## The steps

1. Draw the location in code, at the rules' exact numbers.
2. In one ChatGPT chat, so the style holds, attach the drawing and ask for a repaint with the prompt below, one location per message.
3. Fit the result to 1600 by 940. A repaint either scales the drawing to its canvas (resize it back) or leaves it at size on a larger one (crop it): take whichever lines up with the drawing, then measure the vanishing point and the wall's corner and foot against it.

## The prompt

The first message says "in the style of a modern superhero comic", and the later ones "in the same style as before".

    Repaint the attached picture as a finished comic-book background panel, richly detailed, in the style of a modern superhero comic: confident inked linework, painted colour, dramatic light and shadow, a light halftone texture.

    The scene is <the location, in a sentence>.

    Keep the composition exactly as it is: the same horizon line, the same vanishing point, <what stands in it> in the same place and at the same size, in the same wide landscape shape. The flat wall on the right stays flat and facing the viewer, and its lower part stays plain, with no door.

    Keep the scene completely empty of people, animals and vehicles. No text, lettering, signs, logos, borders or speech balloons anywhere.

## Figures

A figure stands alone on a clear background, whole, head to foot. Finished files are 320 pixels tall, WebP, trimmed to the figure so the feet sit on the bottom edge, about 15 KB. The README says how they are named.
