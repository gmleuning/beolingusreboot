# BEOLINGUS offline dictionary

An offline German–English dictionary page built from the BEOLINGUS / Ding word list
(© Frank Richter, TU Chemnitz, GPL v2 or later — https://dict.zero-g.net/).

## Files

- `beolingus.html` + `main.css` — the dictionary page
- `chemnitz_beolingus_de-en.txt` — the source word list
- `beolingus-data.js` — the word list wrapped as JavaScript so the page can load it from disk
- `build_beolingus.py` — regenerates `beolingus-data.js` from the txt

## Usage

Open `beolingus.html` in a browser. After replacing the txt with a newer version, rebuild:

    py build_beolingus.py
