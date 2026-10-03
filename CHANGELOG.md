# Changelog

## 1.0.2

- Use `createSpan` for the time label instead of `createEl("span", ...)`.

## 1.0.1

- Use Obsidian's `createEl` and `createDiv` helpers instead of `document.createElement`.

## 1.0.0

- Initial release.
- Audio keeps playing when its embed is scrolled out of view.
- Remembers the playback position per note.
- Now-playing bar with play/pause, 5-second skip, draggable seek, and speed cycling.
