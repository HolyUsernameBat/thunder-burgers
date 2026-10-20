# Thunder Burgers

A scroll-driven landing page for Thunder Burgers, a spicy food truck with a four-step heat ladder: Echo, Sparkler, Firecracker and Lightning.

Thunder Burgers is a concept brand, built as a portfolio piece. The truck, the location, the prices and the phone number (from Ofcom's range reserved for drama) are made up, and the order buttons open a note saying so.

## What to look at

- **The heat lever.** Drag it to pick your max heat. Lightning sits past a spring, so you have to hold the lever there: a bolt leaves the lever, the section shakes once and flashes once, and Lightning is yours only if you hold to the end. Let go early and it springs back to Firecracker. It works with mouse, touch and keyboard (arrow keys, and hold Up at Firecracker). With reduced motion on, the strike is a colour change only.
- **Scrubbed clips.** The hero and the truck hatch are short camera moves that play under your scroll, with a separate portrait clip for phones.
- **The loud bar.** It carries your max heat down the page, and its marquee speeds up as the heat climbs.

## Run it locally

It's a static site with no build step. Serve the folder over HTTP rather than opening the file directly, because the clips are fetched as blobs:

```
npx serve .
```

## Credits

- Built with the [scroll-craft](https://github.com/nateherkai/scroll-craft) engine (`scrollcraft.js`, `scrollcraft.css`), MIT licensed; see `LICENSE-scrollcraft.txt`.
- Type: Antonio and Barlow Condensed, from Google Fonts.
- Illustrations and clips were generated for this build and recoloured to the brand palette.
