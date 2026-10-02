# Catan Map Generator (New World, 5-6 Players)

**About the Project**
This project is a custom web-based map generator for the board game Catan, specifically tailored for the "New World" scenario (5-6 players). I created this tool to save time on manually randomizing and balancing the map according to the game's complex rules. Instead of spending 10–15 minutes shuffling tiles, tokens, and checking for rule conflicts, you can just press a single button and set up your physical board exactly as the program shows.

**Key Features:**

*   **One-Click Generation:** Instantly creates a fully playable and visually clear map.
*   **Smart Number Distribution:** Places number tokens using either a Spiral/Alphabetical method or Full Random. It includes a built-in rule checker to guarantee that red numbers (6 and 8) are **never** placed adjacent to each other.
*   **Two Generation Modes:** 
    *   *Full Random:* A chaotic, completely random distribution of all resources and islands.
    *   *Controlled Islands:* Generates a large main island and a specific number of smaller foreign islands.
*   **Advanced Island Customization:** Specify the exact number of foreign islands (1-6) and define their sizes (either randomly within a range or by an exact count).
*   **Desert Placement Rules:** Choose how deserts behave:
    *   Use 3 deserts to separate the islands.
    *   Use 5 deserts to separate the islands (removes 1 sea and 1 gold tile).
    *   Place 3 deserts completely randomly on the main island without separating anything.
*   **Gold Hex Logic:** An optional toggle that forces Gold tiles to spawn *only* on foreign islands to incentivize players to build ships and explore.
*   **Intelligent Port Placement:** A dedicated "Place Ports" button that automatically distributes the 11 ports along the coastlines. The algorithm ensures ports are spaced at least one hex edge apart, gracefully falling back to closer placements only if the generated island is too small.
*   **Interactive & Mobile-Friendly UI:** Features a responsive sidebar, pinch-to-zoom, pan controls, and a history system (Undo button) to easily revert to a previously generated map.
