# Feynman Lectures Vol. III, with interactive demos

[![Live site](https://img.shields.io/badge/live-utsav1033.github.io%2Ffeynman--vol3-1f6feb)](https://utsav1033.github.io/feynman-vol3/) [![License: MIT](https://img.shields.io/badge/license-MIT-green)](LICENSE)

Read *The Feynman Lectures on Physics, Volume III* (quantum mechanics) side by side with a live, interactive demo for every chapter. Scroll the book and the demo follows; pick a chapter and the book jumps there.

**Open it:** https://utsav1033.github.io/feynman-vol3/

**Code:** https://github.com/utsav1033/feynman-vol3

## How to use

1. Open the link above.
2. Click **Open PDF** and choose your own PDF of Volume III. The file stays in your browser and is never uploaded anywhere. It is remembered for next time.
3. Read. As you scroll into a new chapter, the demo on the left switches to match. Press **Hold demo** to keep the current demo while you look elsewhere.

No PDF? Each chapter links to the free official online edition at feynmanlectures.caltech.edu.

## Chapter detection

- The 329-page Volume III PDF is recognized automatically, with chapter start pages built in.
- Any other PDF is scanned once for chapter titles (or its bookmarks are used).
- If a chapter lands on the wrong page, go to the right page and press **Fix start of ch. N**.

## Keyboard

`←` / `→` previous / next page, `[` / `]` previous / next chapter.

## The demos

| Ch. | Demo |
|---|---|
| 1 | Electrons through two slits, one at a time |
| 2 | Wave packets and Δx·Δk |
| 3 | Adding amplitude arrows for a grating |
| 4 | Bosons vs. fermions in scattering |
| 5 | Spin one through tilted Stern–Gerlach filters |
| 6 | Spin one-half on a sphere, with measurements |
| 7 | Stationary states and sloshing superpositions |
| 8 | Two-state system oscillations |
| 9 | Ammonia energy levels and maser resonance |
| 10 | The H₂⁺ bond |
| 11 | Photons through polarizers |
| 12 | Hydrogen hyperfine levels in a field |
| 13 | An electron moving along a crystal lattice |
| 14 | Electrons, holes and doping |
| 15 | Spin waves |
| 16 | A free wave packet spreading |
| 17 | Parity in a double well |
| 18 | Angular momentum vector model and Yₗₘ |
| 19 | Hydrogen orbitals |
| 20 | Expectation values following the classical orbit |
| 21 | Josephson junctions and SQUIDs |

## Running locally

It is a single `index.html` file. Double-click it, or serve the folder with `python3 -m http.server` and open http://localhost:8000. An internet connection is needed the first time for the PDF viewer (pdf.js) and fonts.

## Notes

The book is not included in this repository; it is copyrighted. This project contains only the reader and the demos.
