# Print Doctor

A browser-based tool for diagnosing why an old family photo has faded or shifted color, and generating exact step-by-step repair instructions for Photoshop or GIMP.
https://mollypw.github.io/Print-Doctor/

## What it does

Upload a scan of an old print and Print Doctor will:

- **Measure the damage.** It reads the red, green, and blue channels of the photo and works out exactly how much each one has faded.
- **Explain what's wrong, in plain language.** Rather than showing raw numbers, it names the color cast (for example, "this photo has drifted pink-purple"), explains which dye layer is responsible, and tells you why — matched to when the photo was taken and how it was stored.
- **Tell the difference between a faded color print and a stained black-and-white print.** These need completely different fixes, and the tool detects which one it's looking at.
- **Write an ordered repair plan.** A sequence of steps — duplicate the layer, fix color, restore contrast, retouch damage, reduce grain, sharpen — with the exact menu paths and numbers to type into either Photoshop or GIMP.

## How to use it

1. Open the tool in a browser (the link above).
2. Choose a photo.
3. Set the approximate decade it was taken, where it's been stored, and whether it's color or black-and-white, if known.
4. Read the diagnosis, then pick Photoshop or GIMP and get the repair plan.

## Privacy

Everything runs locally in your browser. No photo is ever uploaded anywhere — the page works even with your internet turned off once it's loaded.

## Notes

This is a personal tool, not a finished product. The diagnosis is based on general knowledge of how print film dyes and black-and-white prints age, and it's a starting point for editing, not a substitute for judgment — always work on a copy of your scan, never the original.
