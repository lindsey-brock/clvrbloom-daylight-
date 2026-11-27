# ClvrBloom — Gallery Daylight

A hero and onboarding prototype for ClvrBloom, a brand and web studio: the Nightbloom experience in the Playful Zephyr palette, by day. Gallery Cream page, Cocoa type and a Persimmon "going places."; the dandelion stands in front of her grainy Ultramarine sun so the white seed head still reads, with a Persimmon sun low on the left and Leaf-green grass.

A dandelion opens slowly and sways in the breeze, and single seeds drift away. Pressing **Make a wish** blows every seed outward, the screen slides over, and one glowing seed leads into a four-step wish journey: what you do, your business name, what you're wishing for, and a starting package (or a discovery call).

It's a sibling of [clvrbloom-night](https://github.com/lindsey-brock/clvrbloom-night): same copy and experience, different palette.

## Run it

It's a single self-contained page. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Where things live

Everything is in `index.html`:

- **Page colours and type** are CSS tokens at the top of the `<style>` block.
- **Canvas colours** (sky, stem, seeds, twinkles, fireflies, grass) are in the `TH` object near the top of the script.
- **Prices** for the package step are in the `PRICES` object.
- **Onboarding copy** is in the `step1`–`step4` functions.

The page respects `prefers-reduced-motion`.

## Notes

- The logo face is Forge Garage Blackletter; Grenze Gotisch from Google Fonts stands in until the licensed font is embedded.
- The "Your wish is planted" screen still contains a `[RESPONSE TIME]` placeholder.
