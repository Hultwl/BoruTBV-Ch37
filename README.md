# Boruto: Two Blue Vortex — Chapter 37

A [Cubari.moe](https://cubari.moe/) repository hosting **Boruto: Two Blue Vortex, Chapter 37**.

## Read it

Paste this into <https://cubari.moe/>:

```
https://raw.githubusercontent.com/Hultwl/BoruTBV-Ch37/main/cubari.json
```

Cubari turns that into a permanent, shareable chapter link.

## How it works

Cubari hosts no files. It reads `cubari.json`, which points at the images on this
repo, and serves them through its reader UI. So the chapter stays available as
long as this repo does.

```
cubari.json              chapter list + metadata for Cubari
cover/cover.png          cover art (also reader page 1)
chapters/Ch37/01.png     page 2
          ...
          40.png         page 41
```

`cover/` is deliberately separate from `chapters/Ch37/`. Cubari orders pages
alphabetically, and a file named `0.png` would sort between `09.png` and
`10.png` — landing the cover in the middle of the chapter as page 10.

## Adding a chapter

1. Drop the pages in `chapters/Ch<NN>/`, named `01.png`…`NN.png`.
2. Add a new entry under `chapters` in `cubari.json`, pointing at those paths.
3. Commit and push — the Cubari link updates automatically.

## Credits

- **Story:** Masashi Kishimoto
- **Art:** Mikio Ikemoto
- **Publisher:** Shueisha / VIZ Media

## Disclaimer

An unofficial, non-commercial fan archive, uploaded for personal reading and
reference only. All rights to *Boruto* and its characters belong to Shueisha and
VIZ Media. No affiliation or endorsement is claimed. If you are a rights holder
and want this removed, open an issue or DMCA notice and it will be taken down.
