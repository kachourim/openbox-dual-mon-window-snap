## openbox-window-snap

Patch to enable window snapping by dragging the window (aero snap) for openbox. This patch supports dual monitors providing that they are placed next to each other in a horizontal configuration.

![Demonstration](https://i.imgur.com/tGs1Y6i.gif)

Usage:

```bash
git clone https://github.com/danakj/openbox
git clone https://github.com/kachourim/openbox-dual-mon-window-snap.git
cp openbox-dual-mon-window-snap/openbox-dual-mon-window-snap.diff openbox
cd openbox
git apply openbox-dual-mon-window-snap.diff
```

Then build openbox according to the instructions [here.](http://openbox.org/wiki/Help:Installing)
