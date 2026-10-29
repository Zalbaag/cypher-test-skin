# cypher-test-skin

A fixture skin for live-testing Cypher's **Install from GitHub** (`owner/repo`) path.

- `skin.json` — manifest (`id: test-dusk`)
- `tokens.css` — `--color-*` tokens under `:root`; one `url()` line is a deliberate sanitizer
  control and should be dropped on install
- `layout.json` — a layout, so the "Apply layout / Keep mine" prompt appears

Install in Cypher: Settings → Skin → enter `Zalbaag/cypher-test-skin` → Install.
