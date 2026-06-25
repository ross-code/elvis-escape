# Elvis Escape 🐺

An action-adventure **escape-room platformer** starring **Elvis**, a pure-white Siberian husky and an absolute menace. Every time the humans leave for work, it is Elvis's job to break out of the room: push things into place, climb, and paw the levers to crack open the sliding door. Grow from a 3-month-old puppy into a fully grown escape artist across five rooms.

Built as a single self-contained HTML file. No build step, no dependencies, no installs.

## Play

Open `index.html` in any modern browser, or play the hosted version (link in the repo's About / Pages settings).

### Controls

| Action | Keys |
| --- | --- |
| Move | `←` `→` or `A` `D` |
| Jump | `Space`, `↑`, or `W` |
| Paw the lever | `E` |
| Restart room | `R` |
| Mute | `M` (or the 🔊 button) |

Touch controls appear automatically on phones and tablets.

## The puzzles

You cannot lift crates, but you can **shove** them along the floor and **stand on them** to reach high ledges and levers.

- **Paw-plates**: shove a crate on top to hold it down.
- **Levers**: get close and press `E`. Elvis pauses, reaches out a paw, and taps it down.
- **The sliding door** opens only when every paw-plate is pressed and every lever is on.
- Steal the **socks** 🧦 scattered through each room for bonus mischief.

Rooms: Living Room (3 months) → Kitchen (5 months) → Bedroom (8 months) → Garage (1 year) → the big Sliding Glass Door (1.5 years).

## Run a local server (optional)

Any static file server works, for example:

```bash
npx serve .
# then open the printed http://localhost:... URL
```

## Tech

Vanilla HTML5 Canvas + JavaScript. Per-pixel AABB physics for stable crate pushing, stacking, and climbing. Elvis is drawn entirely in code (vector art), modelled on a real white husky named Elvis.

---

Made with Claude Code.
