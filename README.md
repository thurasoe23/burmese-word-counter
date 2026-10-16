# Burmese Word Counter · မြန်မာ စကားလုံး ရေတွက်စနစ်

A free, private word counter for Burmese (Myanmar) text.

Burmese doesn't put spaces between words, so normal word counters give numbers that are far too low. This tool splits the text with a dictionary instead and counts:

- **Words**, using the browser's built-in Burmese dictionary (ICU `Intl.Segmenter`)
- **Syllables**, using rules adapted from sylbreak
- **Sentences** and **characters**

It also detects Zawgyi text and converts it to Unicode in one click. The interface is available in English and Burmese.

Everything runs in the browser. Text is never uploaded.

## Use it

Open `index.html` in a browser, or visit the GitHub Pages site for this repository.

Word splitting works best in Chrome, Edge and Safari.

## Credits

- Syllable rules adapted from [sylbreak](https://github.com/ye-kyaw-thu/sylbreak) by Ye Kyaw Thu (Apache License 2.0). The breaking pattern was rewritten in JavaScript.
- Zawgyi conversion by [Rabbit](https://github.com/Rabbit-Converter/Rabbit) (rabbit-node 1.0.4, MIT License, © 2015 Rabbit-Converter), loaded unmodified from jsDelivr.
- Icon glyph traced from [Noto Sans Myanmar](https://fonts.google.com/noto/specimen/Noto+Sans+Myanmar) (SIL Open Font License 1.1).
- Fonts served by Google Fonts (SIL Open Font License 1.1).
