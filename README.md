# Pagani Huayra BC Simulator

A browser-based Pagani Huayra BC simulator with a detailed cockpit UI, real circuit layouts, active aero, audio effects, test-driver mode, rival cars, and manual driving controls.

Live site:

https://richardjiangs.github.io/pagani-huayra-bc-simulator/

## Features

- Single-file HTML simulator that runs directly in a modern browser.
- Pagani Huayra BC inspired drivetrain, boost, gear, aero, and telemetry systems.
- Real-world circuit selections including Monaco, Suzuka, Silverstone, Nurburgring, Nardo, and Pagani Arte in Pista.
- Widened 2.5x track rendering with roadside barriers and scenery placed at the correct track edge.
- Manual steering assist toggle with fully manual behavior when assist is off.
- Desktop trackpad steering mode with fullscreen capture and two-finger horizontal steering.
- Mobile touch steering wheel and touch throttle/brake controls.
- Test driver, rival grid, lap timing, cruise, launch control, ESC, active aero, lights, horn, and cabin controls.

## Controls

| Action | Keyboard |
| --- | --- |
| Throttle | `W` or `ArrowUp` |
| Brake | `S`, `ArrowDown`, or `Space` |
| Steer | `A` / `D` or `ArrowLeft` / `ArrowRight` |
| Shift up | `E` |
| Shift down | `Q` |
| Reverse | `R` |
| Neutral | `N` |
| Launch control | `L` |
| Horn | `H` |

## Trackpad Steering

Hold `Space` + `T` for 3 seconds to enable desktop trackpad steering mode. You can also long-press and release on the driving canvas to toggle it.

When enabled:

- The simulator requests fullscreen.
- Two-finger horizontal swipes steer the car.
- Keyboard controls still work.
- `Esc` or leaving fullscreen turns trackpad steering off.
- Steering recenters after you stop swiping.

## Running Locally

Open `index.html` in a browser.

For a local web server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Repository Layout

```text
index.html   Simulator app
README.md    Project documentation
LICENSE      License
```

## Notes

This is a fan-made simulator project for browser experimentation. It is not affiliated with Pagani Automobili.
