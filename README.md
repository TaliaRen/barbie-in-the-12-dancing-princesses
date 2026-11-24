# Barbie in the 12 Dancing Princesses · The Dancing Floor

A small interactive web toy inspired by the singing floor in *Barbie in the 12 Dancing Princesses*.

- **`dancing-floor.html`**: the main experience, a single self-contained page built with Three.js.
  - Step on the twelve flower tiles in the princesses' bedroom, in the order of the melody.
  - After the twelfth step the floor melts away into gold dust, and a spiral stair of flower stones appears, going down into a shaft hung with vines and wisteria.
  - **Replay** (top left) closes the floor so you can dance again.
  - The cursor is a ballet slipper; choose any of the twelve princesses' slippers at the top right.
- **`index.html`**: the earlier, simpler 2D version of the flower-tile keyboard.

## Running it

The page loads Three.js from a CDN and needs to be served over HTTP (not opened as a file). From this folder:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/dancing-floor.html>.

Controls: click or tap the tiles, or use the keys `1`–`0`, `-` and `=`.

A personal, non-commercial fan project.
