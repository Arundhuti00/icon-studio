# Celestial Glass Icons: Rules v2.2

Style taken from two references: a cocktail illustration (translucent glass overlaps, grain, thin sticks) and a ceramics catalogue (simple solid silhouettes, soft blended gradients, grain). v2 adds stronger gradients, softer blended edges, only brown and blue, and grain.

## Rules
1. 64 × 64 grid, 4 px padding (live area 56 × 56), geometry on a 0.5 grid.
2. Palette is brown and blue shades only; the browns lean golden (v2.1). Brown: espresso #3B2610, cocoa #5C3A14, brown #8C5A1E, caramel #BC8432, tan #DDB15E, latte #F3E0B0. Blue: navy #1A2F6E, cobalt #2F5FD0, azure #5B8EEA, sky #9DC1F2, ice #E1ECFA.
3. Strong gradients: every main surface is a 2–4 stop gradient running clearly from light to deep. Spheres are radial, lit from the upper left. Trails and flames fade out to transparent.
4. Blended interiors: inner layers (bands, land, craters, shading, cores) are blurred (1.2 or 3) and clipped to the silhouette. No hard seams inside an icon.
5. Soft edges: the whole icon gets a 0.35 blur. Luminous objects (sun, stars, comet head, galaxy, supernova, nebula stars) get a soft glow of their own colour (2.5 blur).
6. Grain: fine fractal-noise grain (light and dark specks), clipped to the shape, on every icon.
7. Strokes are only for lines that are the object (rays, trails, spiral arms, constellation links): 3 px or 5 px, round caps and joins.
8. At most 10 shapes per icon and 3 interior marks. Must read at 24 px and in silhouette at 16 px.
9. Front view, upright. No rotation or text. No faces, except simple eyes on the character icons: alien, robot and space dog (v2.2).

## Known limits
- Grain and blur are SVG filters. Browsers and resvg render them; Figma imports the blur but drops the grain.
