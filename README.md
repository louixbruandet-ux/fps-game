# Arena FPS

A small browser first-person shooter built with [Three.js](https://threejs.org/). Survive waves of red cubes that chase you across an arena full of crates.

## Play

Open `index.html` in a browser, or serve it locally:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Controls

| Key | Action |
| --- | --- |
| WASD | Move |
| Mouse | Aim |
| Left click | Shoot |
| Space | Jump (you can stand on crates) |
| Shift | Sprint |
| R | Reload |
| Esc | Pause |

Each wave adds more and faster enemies. Each enemy takes 3 hits and is worth 100 points.
