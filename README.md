# champions-art

Art for a private Roll20 character sheet: locations and figures. The sheet's CSS loads these files by address.

Addresses always name a tag, never a branch, so a released sheet's art can't change under it:

    https://raw.githubusercontent.com/robopuffin/champions-art/<tag>/locations/city.jpg

- `art-6`: fourteen locations and thirty-three figures. `BRIEF.md` says how the locations were made.
- `art-7`: adds Howler's three colour masks and thirteen objects for the sheet's widgets, each with three.

## Names

A file's name says who or what it is:

- `figures/howler.webp`: a character, by the id the sheet uses.
- `figures/susan-sonderheim.webp`: a person, by that person's name.
- `figures/police-female.webp`, `figures/jim-robbins-ranger.webp`: another kind or look takes another word.
- `locations/city.jpg`: a location, by the id the sheet uses.
- `widgets/strike.webp`: an object a widget wears, neutral grey.
- `figures/masks/howler-suit.png`, `widgets/masks/strike-primary.png`: which part of that picture takes a colour, by its alpha, cut to the same size and crop.

All lowercase, as the addresses are case-sensitive.
