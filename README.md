# Webkit13
* For 13.02 to 13.52
* Goldhen added 
---
## Issues
~~As you see.. video has a bad time getting to be played! tryina fix it~~ - **FIXED?**
| Aspect | Md Test G (works) | JB.html (black) |
|---|---|---|
| Video positioning | `position: absolute` inside a full-viewport fixed parent (`#fs-stage`) | `position: fixed` on the video itself |
| Visibility toggle | `display: none` → `display: block` on the container | `opacity: 0` + `z-index: -1` on the video |
| Video `src` | Assigned at the moment of playback (`fsV.src = url`) | Baked in via `<source>` children, preloaded from load |
| Sibling elements | Parent `#fs-stage` gets `display: block`; debug chrome hidden via `visibility: hidden` | Card siblings stay in flow; video styled independently |

---
## Source code & Credits
original by [Raw-Game](https://raw13g.github.io)
[source code](https://github.com/raw13g/raw13g.github.io)
[GoldHen](https://ko-fi.com/s/ccbe9f7bf0)  Added

---
