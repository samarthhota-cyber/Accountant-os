# Accountant OS // Fiscal Computing System

Accountant OS is an interactive, vintage-themed web operating system simulator built for the Hack Club Stardance WebOS Challenge. It mimics a retro accounting and bookkeeping workstation from the mid-to-late 1990s, integrating classic aesthetics with practical, interconnected utilities.

The system is constructed as a self-contained, single-file application (`index.html`) using pure HTML, CSS, and vanilla JavaScript without external library dependencies, ensuring fast load times and offline accessibility.

## Core Features

*   **Draggable & Resizable Window Manager**: Drag windows across the screen with strict viewport boundary clamping to prevent elements from going off-screen. Standard minimize (-), maximize (□), and close (X) controls are supported.
*   **Central File Database (`DATABASE.EXE`)**: A relational file manager representing the primary directory. It displays stored documents and spreadsheets, keeping track of names, formats, file sizes, and dates. Double-clicking any listed document launches it directly in its respective application.
*   **Dynamic Spreadsheet (`SHEETS.EXE`)**: An Excel-style 4x6 interactive ledger grid (A1 to D6) featuring an active Formula Bar. The application parses mathematical cell-reference equations (e.g., `=A1+B1` or `=C3*1.21`) in real-time.
*   **Multi-Document Text Editor (`DOCS.EXE`)**: A clean ledger pad designed for writing and editing files with options to export directly to the local disk as `.txt` files or commit changes back to the virtual system database.
*   **Tactile Audio Engine**: A Web Audio API-driven sound engine generates mechanical typewriter keyclick feedback as you type inside text fields, textareas, or grid cells.
*   **Financial Monitor (`ASSETS.EXE`)**: A real-time market tracker detailing machinery and T-bill valuations, accompanied by a vector sparkline trend graph drawn on an HTML `<canvas>`.
*   **System Shell (`CMD.EXE`)**: A classic terminal and interpreter responsive to commands such as `help`, `about`, `clear`, `market`, and `cheat`.
*   **Synthesis Jukebox (`SYNTH.EXE`)**: Generates custom square-wave chiptune melody loops, complete with an animated equalizer visualizer driven by procedural step timing.
*   **Persistent Memory State**: Window coordinates, active dimension states, local databases, game statistics, themes, and customized taskbar branding strings are saved in the browser's `localStorage` to persist across system restarts.

## Themes Supported

*   **Vintage Ledger**: A parchment-styled, cream-tinted bookkeeping design with dark charcoal text and muted accents.
*   **Windows Classic**: The recognizable teal desktop layout with clean grey panels and blue title highlights.
*   **Midnight Nebula**: A cosmic violet and deep space theme displaying vivid cyan indicators.
*   **Green Phosphor (Toxic)**: A dark glass aesthetic overlaid with high-contrast glowing neon green lines and a subtle CRT scanline effect.

## How to Run

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Interact with the BIOS boot screen and click `[ LOAD ACCOUNTANT_OS.EXE ]` to enter the desktop environment.
