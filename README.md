# yapmaxxing-registry

The central data hub for the **yapmaxxing** ecosystem. This repository serves as a curated registry of guides, userscripts, and community tools for web-based games (currently only *Milky Way Idle* for now)

This data is automatically pulled and displayed in:
- **[yapmaxxing codex]()** (Astro-powered community wiki) **WIP**
- **[modmaxxing]()** (web-based mod manager) **WIP**
---

## Repository Structure

To support multiple games, this registry is organized by **Game ID** first:

```text
/games
  /milkywayidle
    /guides   <- Markdown files (.md) for long-form tutorials
    /scripts  <- JSON metadata for userscripts
    /tools    <- JSON metadata for external websites/apps
    /assets   <- images and icons
registry.json <- The master index for machine-reading
