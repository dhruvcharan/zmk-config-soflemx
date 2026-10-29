# Sofle MX Keymap Visual Guide

This guide represents the layout of your **Sofle MX** keyboard (split 5x6 with 5 thumb keys per side and two rotary encoders).

---

## Rotary Encoders (Knobs)

| Layer | Left Encoder (Turn) | Right Encoder (Turn) |
| :--- | :--- | :--- |
| **Base, LOWER** | 🔊 **Volume Control**<br>↳ Clockwise: Vol Up<br>↳ Counterclockwise: Vol Dn | 📜 **Page Navigation**<br>↳ Clockwise: Page Up<br>↳ Counterclockwise: Page Down |
| **RAISE (utility)** | 🔊 **Volume Control**<br>↳ Clockwise: Vol Up<br>↳ Counterclockwise: Vol Dn | 🖥️ **Windows Virtual Desktops**<br>↳ Clockwise: Ctrl+Win+Right<br>↳ Counterclockwise: Ctrl+Win+Left |
| **ADJUST (MASTERY)** | 💻 **Ghostty Split Navigation**<br>↳ Clockwise: Cmd+Alt+Right<br>↳ Counterclockwise: Cmd+Alt+Left | ✍️ **Neovim Jumps**<br>↳ Clockwise: Ctrl+I<br>↳ Counterclockwise: Ctrl+O |

---

## Layer 1: LOWER (`lower`)
*Trigger: Hold the **Left Thumb Hold/Tap Key** (held `TAB` key).*

### Left Half
```text
  ┌───────────┬───────────┬───────────┬───────────┬───────────┬───────────┐
  │ Alt+Left  │     !     │     @     │     #     │     $     │     %     │
  ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
  │     `     │  (trans)  │     ↑     │  (trans)  │  Ctrl + R │  (trans)  │
  ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
  │    DEL    │     ←     │     ↓     │     →     │  Ctrl + F │     {     │
  ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┼───────────┐
  │     [     │  Ctrl + Z │  Ctrl + X │  Ctrl + C │  Ctrl + V │   HOME    │  Encoder  │
  └───────────┴───────────┴───────────┼───────────┼───────────┼───────────┤   Click   │
                                      │  (trans)  │  (trans)  │  (trans)  │  (trans)  │  (trans)  │
                                      └───────────┴───────────┴───────────┴───────────┴───────────┘
```

### Right Half
```text
              ┌───────────┬───────────┬───────────┬───────────┬───────────┬───────────┐
              │     ^     │     &     │     *     │     (     │     )     │   PG_UP   │
              ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
              │  Ctrl + Z │     7     │     8     │     9     │     0     │   PG_DN   │
              ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
              │     }     │     4     │     5     │     6     │     =     │     \     │
  ┌───────────┼───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
  │  Encoder  │    END    │     1     │     2     │     3     │     -     │     ]     │
  │   Click   │───────────┴───────────┴───────────┴───────────┴───────────┴───────────┘
  │  (trans)  │  (trans)  │  (trans)  │  (trans)  │  (trans)  │
  └───────────┴───────────┴───────────┴───────────┴───────────┘
```

---

## Layer 2: RAISE (`utility`)
*Trigger: Hold the **Right Thumb Key** (momentary activation).*

### Left Half
```text
  ┌───────────┬───────────┬───────────┬───────────┬───────────┬───────────┐
  │    F12    │    F1     │    F2     │    F3     │    F4     │    F5     │
  ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
  │ Alt+Space │  Alt+F4   │     ↑     │ Task Mgr  │Ctrl+Sft+T │     %     │
  ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
  │ Win+Sft+S │     ←     │     ↓     │     →     │   PG_UP   │     _     │
  ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┼───────────┐
  │  (trans)  │   STOP    │Play/Pause │  VOL_DN   │   PG_DN   │     -     │  Encoder  │
  └───────────┴───────────┴───────────┼───────────┼───────────┼───────────┤   Click   │
                                      │  (trans)  │  (trans)  │  (trans)  │  (trans)  │  (trans)  │
                                      └───────────┴───────────┴───────────┴───────────┴───────────┘
```

### Right Half
```text
              ┌───────────┬───────────┬───────────┬───────────┬───────────┬───────────┐
              │    F6     │    F7     │    F8     │    F9     │    F10    │    F11    │
              ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
              │Win+Sft+←  │     7     │     8     │     9     │     *     │   BSPC    │
              ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
              │Win+Sft+→  │     4     │     5     │     6     │     +     │  (none)   │
  ┌───────────┼───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
  │  Encoder  │ Ctrl+BSPC │     1     │     2     │     3     │     =     │  (none)   │
  │   Click   │───────────┴───────────┴───────────┴───────────┴───────────┴───────────┘
  │  (none)   │  (trans)  │  (none)   │     0     │     .     │  (trans)  │
  └───────────┴───────────┴───────────┴───────────┴───────────┘
```

---

## Layer 3: ADJUST (`MASTERY`)
*Trigger: Hold **both LOWER and RAISE** keys down together.*

### Left Half
```text
  ┌───────────┬───────────┬───────────┬───────────┬───────────┬───────────┐
  │  BT_CLR   │ BT_SEL 0  │ BT_SEL 1  │ BT_SEL 2  │ BT_SEL 3  │ BT_SEL 4  │
  ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
  │STD_UNLOCK │  OUT_TOG  │  OUT_USB  │  OUT_BLE  │  (none)   │  (none)   │
  ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
  │  (none)   │  RGB_HUD  │  RGB_HUI  │  RGB_SAD  │  RGB_SAI  │  RGB_EFF  │
  ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┼───────────┐
  │  (none)   │  RGB_BRD  │  RGB_BRI  │  (none)   │  (none)   │  (none)   │  Encoder  │
  └───────────┴───────────┴───────────┼───────────┼───────────┼───────────┤   Click   │
                                      │  (none)   │  (none)   │  (none)   │  (trans)  │  (none)   │
                                      └───────────┴───────────┴───────────┴───────────┴───────────┘
```

### Right Half
```text
              ┌───────────┬───────────┬───────────┬───────────┬───────────┬───────────┐
              │  (none)   │  (none)   │  (none)   │  m_lock   │   SLEEP   │  (none)   │
              ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
              │  (none)   │  (none)   │  (none)   │  (none)   │  (none)   │  (none)   │
              ├───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
              │  (none)   │  (none)   │  (none)   │  (none)   │  (none)   │  (none)   │
  ┌───────────┼───────────┼───────────┼───────────┼───────────┼───────────┼───────────┤
  │  Encoder  │  (none)   │  (none)   │  (none)   │  (none)   │  (none)   │  (none)   │
  │   Click   │───────────┴───────────┴───────────┴───────────┴───────────┴───────────┘
  │  (none)   │  (none)   │  (trans)  │  (none)   │  (none)   │  (none)   │
  └───────────┴───────────┴───────────┴───────────┴───────────┘
```

*(Note: `(trans)` keys transparently fall back to the base layer's bindings. `(none)` keys have no assigned actions.)*
