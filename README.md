# Space Marines vs Chaos — Browser RTS

A complete, single-file browser-based real-time strategy game. Open `index.html` in any modern browser — no server, no build tools, no dependencies required.

![Space Marines vs Chaos Warriors RTS](https://github.com/user-attachments/assets/431a8761-98a1-454b-8d8c-1256eb4cf43c)

## How to Play

Open `index.html` directly in a web browser.

### Controls

| Action | Input |
|--------|-------|
| Scroll camera | **WASD** or **Arrow Keys** |
| Edge scroll | Move mouse within 50px of screen edge |
| Select unit | **Left-click** unit |
| Box select | **Left-click drag** (selects all player units in box) |
| Add to selection | **Shift + Left-click** |
| Move selected units | **Right-click** on empty ground |
| Attack enemy | **Right-click** on enemy unit or Chaos Base |
| Deselect all | **Escape** |
| Produce units | **Left-click** your base → click produce buttons in panel |
| Jump camera | **Click** on the minimap (bottom-right) |

### Winning & Losing

- **Victory**: Destroy the Chaos Base (top-right of the map)
- **Defeat**: Your Space Marine Base (bottom-left) is destroyed

---

## Unit Roster

### Space Marines (Player — Blue)

| Unit | HP | Damage | Range | Speed | Cost | Notes |
|------|----|--------|-------|-------|------|-------|
| **Space Marine** | 100 | 15 | 200 | 80 | ⚡ 50 | Ranged — fires laser bolts |
| **Terminator** | 200 | 40 | 50 | 45 | ⚡ 150 | Heavy melee tank, slow but durable |
| **Scout** | 60 | 10 | 50 | 120 | ⚡ 30 | Fast melee skirmisher |

Produce units by selecting your **SM Base** and clicking the buttons in the bottom panel.

### Chaos Warriors (AI — Red)

| Unit | HP | Damage | Range | Speed | Notes |
|------|----|--------|-------|-------|-------|
| **Chaos Warrior** | 120 | 18 | 55 | 70 | Melee berserker |
| **Chaos Sorcerer** | 80 | 20 | 220 | 50 | Ranged — throws fireballs |
| **Chaos Chosen** | 180 | 45 | 55 | 40 | Heavy melee elite |

The Chaos AI spawns waves every 30 seconds (scaling in size), and periodically launches coordinated attacks on your base.

---

## Resources

- Start with **200 Minerals** (⚡)
- Passively gain **+10 minerals/second**
- Kill an enemy unit to gain **+15 minerals**
- Spend minerals to produce units at your base

## Tips

- Terminators make great front-line tanks — push them forward while Space Marines shoot from behind.
- Scouts are cheap and fast; use them to harass the Chaos base early.
- Keep an eye on the minimap — red blips heading toward the bottom-left is a sign of an incoming attack wave.
- The AI ramps up over time; try to push and destroy the Chaos Base before wave counts get too high.
