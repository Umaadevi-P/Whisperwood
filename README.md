# Whisperwood 🌲✨

> *A dark fantasy 2D adventure where you brave a living, cursed forest to fulfill a forgotten promise.*

🎮 **[Play the game right here!](https://insert-your-link-here.com)** 🎮

## 📖 The Story
Armed with only a lantern and a sword, you must venture deep into the creeping shadows of Whisperwood. Your goal? To locate four lost Memory Fragments and restore the Forest Heart. 

But beware: the forest is alive. Shadowy beasts roam the paths, and a thick, purple **Corruption** mist slowly drains your life the longer you linger. Can you uncover the hidden Restoration Key, survive the darkness, and find your way back out into the morning light?

## 🛠️ How I built it using the Maki Framework
This game was proudly built using the **[Maki Framework](https://www.npmjs.com/package/@tialops/maki)**, which wraps **Phaser 3** and **Vite** for a modern developer experience. 

Here is exactly how Maki powered my workflow:
- **Scaffolding:** I started the project instantly using the `maki new` command.
- **Fast Development:** Running `maki dev` gave me lightning-fast Hot Module Replacement (HMR) so I could see my game update in real-time as I coded.
- **Scene Management:** I utilized Maki's intuitive scene structure to easily transition between my 4 game areas (Fog Entrance, Root Marsh, Lantern Grove, and Heart Hollow).
- **Production Build:** When it was time to share the game, `maki build` automatically bundled all of my code, compressed my audio and pixel art assets, and generated a highly optimized web package ready for Itch.io!

If you love building 2D web games but want a snappy, command-line driven workflow, Maki is the way to go!

## 🎮 Controls
| Key | Action |
|-----|--------|
| **WASD / Arrows** | Move |
| **Space** | Attack |
| **E** | Interact / Talk |
| **H** | Use healing herb |
| **R** | Restore the Forest Heart |

## 💻 Running it Locally
Want to dive into the code?

1. Clone the repository.
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Start the Maki development server:
   ```bash
   npm run dev
   ```
4. Open `http://localhost:3000` in your browser and start exploring!
