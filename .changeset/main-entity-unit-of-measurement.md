---
"power-flow-card-plus": patch
---

Fix: `unit_of_measurement`, `unit_white_space` and `decimals` on grid, battery and solar are now applied (the UI editor already offered them, but they had no effect). This allows using the card for non-electrical flows such as water in L/min (#193).
