<p align="center">
  <img src="logo.png" alt="politraumat logo" width="50%">
</p>

# politraumat
UPV-themed, Anki-style flashcards — single HTML file, runs in your browser.

## What it is
- One self-contained HTML file.
- Mobile-first dark UI with **poli[traumaT]** rainbow logo.
- Cards live in the page; progress is saved in your browser (localStorage).

## Why it’s useful
- No install, no server — open and study anywhere.
- Fast swipe grading with clear stats (**Remaining / Done / Mastered**).
- Full backup/restore of your deck **and** progress via JSON export/import.

## How to use
- **Open the HTML** in your browser (phone or desktop).
- **Import a deck**: tap **📥 Importar** and choose:
  - CSV with headers `Front,Back` (supports quoted newlines), or
  - JSON (list of `{front, back}` or a saved session).
- **Study**:
  - Tap card to flip (**Front / Back**).
  - Swipe: **← Again**, **↓ Hard**, **↑ Good**, **→ Easy**.
- **Export progress**: tap **📤 Exportar** to save a JSON snapshot.
- **Reset**: tap **🗑️** to rebuild the queue and stats from the current deck.

## Settings (⚙️ bottom sheet)
- Positions for **Again / Hard / Good / Easy** in the queue.
- Passes required to mark a card **Mastered**.
- Initial order: **Shuffle** or **Original**.
- Start on **Front** or **Back**.

---
Single file. Smooth gestures. Your state persists automatically.
