# Kinfield

**A cozy interactive game / virtual world** built with Grok Build.

Walk around the town of Kinfield, talk to people, take jobs, manage money, customize your character, and explore.

## How to Play (Local)

1. Clone this repo:
   ```bash
   git clone https://github.com/afnan-ab/Kinfield.git
   cd Kinfield
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open the URL shown in the terminal (usually http://localhost:8080)

You will see the title screen → create a character → start playing!

Controls are on-screen + keyboard (WASD / arrows to move, E or click to interact, etc.).

## Project Structure

- `src/components/Kinfield.tsx` – Main game UI & title screen
- `src/game/engine.ts` – Game engine (canvas / rendering)
- `src/game/state.ts` – Game state, save/load, inventory, jobs
- `src/game/data.ts` – Buildings, jobs, items, map data
- `src/game/input.ts` – Controls
- `src/game/audio.ts` – Sound

## Notes

This is the full source extracted from the Grok workspace export you provided.
The original Grok preview “Open” button sometimes fails — running it locally is the reliable way to play.

Enjoy Kinfield!
