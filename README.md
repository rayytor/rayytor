<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.png">
    <img alt="A libadwaita window describing Rayyan's Linux desktop work: GTK4 + libadwaita, system integration, touch and smartboards, and the apps Interaktiv, Insha, Rayyanpen, Marker, ybell and Kitlenk." src="assets/hero-dark.png" width="100%">
  </picture>
</p>

<p align="center">
  Rayyan &nbsp;·&nbsp; Kahramanmaraş, Türkiye &nbsp;·&nbsp; <a href="https://rayytor.github.io">rayytor.github.io</a>
</p>

<br>

## Linux desktop

Native apps for the touch whiteboards in Turkish classrooms (Pardus ETAP) and for everyday Debian and Ubuntu machines. Instant startup, bounded memory, no bundled browser runtime.

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/interaktiv-reader.png" alt="Interaktiv showing a chemistry textbook as a two-page spread" width="100%"><br>
      <b><a href="https://github.com/rayytor/interaktiv">Interaktiv</a></b> · School Edition<br>
      <sub>Textbook reader for classroom smartboards. Two-page book spread, activity hotspots with click-to-zoom, full-text search, four reading themes applied as GPU colour matrices. A spread draws in a millisecond or two, on a fixed memory budget.</sub><br>
      <sub><code>Python</code> <code>GTK4</code> <code>libadwaita</code> <code>PyMuPDF</code> <code>WebKitGTK</code></sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/insha.png" alt="Insha editor with Scratch-style blocks building a catch-the-apple game" width="100%"><br>
      <b>Insha</b><br>
      <sub>A block-based (no text) editor that builds real GTK4 + Python desktop apps. Humans drag Blockly blocks inside a native libadwaita window; AI agents edit the same project through a CLI and an MCP server. Both produce plain, readable PyGObject code.</sub><br>
      <sub><code>Python</code> <code>GTK4</code> <code>Blockly</code> <code>MCP</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/marker.png" alt="Marker editing a scidown document with live preview" width="100%"><br>
      <b><a href="https://github.com/rayytor/kecheli">Marker</a></b> · GTK4 port<br>
      <sub>The Marker markdown editor brought to GTK4 and libadwaita: split editor and live preview, scidown scientific extensions, KaTeX math, beamer slides, sketch insertion.</sub><br>
      <sub><code>C</code> <code>GTK4</code> <code>GtkSourceView</code> <code>WebKitGTK</code> <code>Meson</code></sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/rayyanpen.png" alt="Rayyanpen floating toolbar with the settings panel open" width="100%"><br>
      <b>Rayyanpen</b><br>
      <sub>Draw on top of anything on a Linux screen: slides, web pages, video or a blank board. Built for ETAP touch whiteboards as a pardus-pen replacement, with the soft, smooth ink of the Draw on Screen browser extension. Fingers, styluses and mice all work.</sub><br>
      <sub><code>C++</code> <code>Qt 6</code> <code>Meson</code> <code>multi-touch</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/interaktiv-library.png" alt="Interaktiv library with textbook covers filtered by grade" width="100%"><br>
      <b><a href="https://github.com/rayytor/interaktiv">Interaktiv</a></b> · library<br>
      <sub>The catalogue side of the same app: the MEB textbook list with grade filters, installs and previews, and finger-sized targets throughout.</sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/ybell.png" alt="ybell live ISO booted in QEMU showing the Xfce desktop" width="100%"><br>
      <b>ybell</b> · in progress<br>
      <sub>A lightweight Debian 13 based distribution whose whole point is compatibility: apt, Flatpak, Snap, AppImage, Fedora and Arch containers, Wine, Bottles and Proton, all behind one GTK4 store. Idle budget under 650 MB. Phase 1 boots; the store comes next.</sub><br>
      <sub><code>Debian 13</code> <code>live-build</code> <code>Xfce</code> <code>Distrobox</code> <code>GTK4</code></sub>
    </td>
  </tr>
</table>

Also on the desktop side:

- **[Kitlenk](https://github.com/rayytor/Kitlenk)** turns any Bluetooth device or USB drive into a physical key for your session. A systemd user service locks the screen when the key goes away and unlocks when it returns, with hysteresis so a flaky connection never locks you out mid-sentence.
- **Gelgit** is a small Qt desktop app for GNOME that sets up Git and GitHub once (SSH keys, keyring, remote) and then gets out of the way.
- **[Pardus Builder](https://github.com/rayytor/pardus-builder)** is the public home for the block-based GTK4 and libadwaita builder. Empty for now, code lands soon.

<br>

## AI work

Retrieval, document understanding and small trained models, mostly aimed at Turkish schools.

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/konusbitr.png" alt="Konusbitr document library" width="100%"><br>
      <b><a href="https://github.com/rayytor/konusbitr">Konusbitr</a></b><br>
      <sub>Open-source, self-hostable alternative to PDF.ai. Upload documents, chat with them, and get answers with clickable citations that jump to the exact page and highlight the source. Exposes a PDF.ai-wire-compatible <code>/v2</code> REST API.</sub><br>
      <sub><code>Next.js</code> <code>FastAPI</code> <code>pgvector</code> <code>PyMuPDF</code> <code>Docker</code></sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/e4m.png" alt="E4M lesson note generator home screen" width="100%"><br>
      <b>E4M · Ders Notu Üretici</b><br>
      <sub>Takes the official MEB question-distribution tables and the 100 to 400 MB MEB textbooks, slices the exact chapters an exam covers, and has Gemini write an exam-focused study note that prints pixel-for-pixel like the hand-made original.</sub><br>
      <sub><code>FastAPI</code> <code>Gemini</code> <code>PyMuPDF</code> <code>headless Chrome PDF</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/denemedir.png" alt="Denemedir home screen with study calendar and daily goal" width="100%"><br>
      <b><a href="https://github.com/rayytor/denemedir">Denemedir</a></b><br>
      <sub>TYT practice-exam app. Ingests official exam PDFs, builds custom tests per subject, tracks mistakes, and grades filled answer sheets with an OpenCV pipeline plus a small neural bubble classifier (MarkerAI) trained on synthetic data.</sub><br>
      <sub><code>Python</code> <code>OpenCV</code> <code>NumPy</code> <code>vanilla JS</code></sub>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/rayytor/trainai">trainai</a></b><br>
      <sub>The training and annotation pipeline behind Denemedir's answer detector: synthetic dataset generation, a NumPy-only network, and an annotation server for real sheets.</sub><br><br>
      <b>Insha for agents</b><br>
      <sub>Insha's core is headless. Every project operation is a JSON op applied through a CLI or the built-in MCP server, so Claude Code and other agents can build, validate, screenshot and ship a GTK4 app without touching the GUI.</sub><br><br>
      <b>Agent-driven development</b><br>
      <sub>Larger projects here (ybell, Rayyanpen, Insha) are built phase by phase by fresh AI agents working from written briefs, with hard gates like idle-RAM budgets and golden-image tests keeping them honest.</sub>
    </td>
  </tr>
</table>

<br>

## Web and other work

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/tyrmyk.png" alt="Tyrmyk vector editor with a smiling purple face on the canvas" width="100%"><br>
      <b><a href="https://github.com/rayytor/tyrmyk">Tyrmyk</a></b><br>
      <sub>Standalone, offline-first image editor: a rebranded and upgraded scratch-paint with vector and bitmap modes, multiple costumes, and IndexedDB storage. Installs as a PWA or runs as a desktop app.</sub><br>
      <sub><code>JavaScript</code> <code>Canvas</code> <code>PWA</code> <code>zero runtime deps</code></sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/trigonometri.png" alt="Trigonometri Rehberi home page listing guides, formulas and labs" width="100%"><br>
      <b>Trigonometri Rehberi</b><br>
      <sub>A study portal for the MEB trigonometry unit: step-by-step guides, a formula library with proofs, interactive labs (unit circle, triangle solver), solved problems and progress tracking.</sub><br>
      <sub><code>React</code> <code>TypeScript</code> <code>Vite</code></sub>
    </td>
  </tr>
</table>

- **[Desloppify EBA](https://github.com/rayytor/desloppify-eba)** is a lightweight client for eba.gov.tr that strips the AI widgets, tracking scripts and UI clutter.
- **[Microphone extension for TurboWarp](https://github.com/rayytor/Microphone-Turbowarp-Extension)** gives Scratch projects real microphone input.

<br>

<p align="center">
  <sub>Screenshots are of real builds on this machine. The libadwaita window at the top is rendered with <code>GskRenderer.render_texture</code> from a running GTK4 app.</sub>
</p>
