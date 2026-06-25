# Elvis Escape 🐺

An action-adventure **escape-room platformer** starring **Elvis**, a pure-white Siberian husky and an absolute menace. Every time the humans leave for work, it is Elvis's job to break out of the room: shove things into place, climb, tip furniture, and paw the levers to crack open the sliding door. Grow from a 3-month-old puppy into a 4-year-old escape artist across eight rooms.

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
- **Knock-over furniture**: press `E` next to a tall pillar to tip it into a bridge across a gap.
- **One-way platforms**: jump up through them from below, land and stand on top. Use them as a ladder to high places.
- **The sliding door** opens only when every paw-plate is pressed and every lever is on.
- Steal the **socks** 🧦 scattered through each room for bonus mischief.

On escape, Elvis does a backflip, wags his tail, and howls.

### The eight rooms

Living Room (3 months) → Kitchen (5 months) → Bedroom (8 months) → Garage (1 year) → Hallway & Laundry (1.5 years) → Basement (2 years) → Attic Sunroom (3 years) → the Great Sliding Door (4 years).

Progress saves automatically (localStorage). A **House Map** screen lets you replay any unlocked room, and each room tracks a medal (🥉/🥈/🥇), best socks, and best time. The view follows Elvis with a camera so later rooms can be bigger than the screen. Gentle ambient music plays per room (toggle with `M`).

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
