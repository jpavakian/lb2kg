<img src="apple-touch-icon.png" alt="" width="72" align="right">

# lb → kg

A small, phone-friendly converter for the gym. Many machines show their weight stacks in pounds; this page turns that number into kilograms as you slide or type.

**Live:** https://jpavakian.github.io/lb-to-kg/

## Features

- **Slider** to pick the weight on the machine, with − / + buttons for single steps
- **Step sizes** of 0.5, 1, 2.5, 5 or 10 lb, so the slider matches the machine's increments
- **Manual entry**: tap the pound field to type an exact weight (opens the number pad on phones)
- **One-tap copy** of the result, e.g. `45.36 kg`
- **Adjustable range**: 0–200, 300, 500 or 1000 lb, for plate-loaded machines too
- **Remembers** your step size, range and last weight on your device
- Light and dark mode, follows your phone's setting

## How it converts

1 lb = 0.45359237 kg (the exact international definition). Results are rounded to two decimals.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app: one self-contained page, no build step |
| `favicon.svg` | Browser tab icon |
| `favicon.ico` | Fallback icon for older browsers |
| `apple-touch-icon.png` | Home-screen icon on phones |

## Use it like an app

Open the live link on your phone, then:

- **iPhone:** Share → Add to Home Screen
- **Android:** ⋮ menu → Add to Home screen

## Hosting

Served with GitHub Pages from the `main` branch, root folder (Settings → Pages). To update, replace `index.html` and commit; the live page refreshes within a minute or two.
