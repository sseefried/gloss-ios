Touch devices are fundamentally different to desktops:

a) You can't open a window like you can on a desktop, of a given size and with top-left corner
   at a given a position. (And even you can, it's not a normal practise for tablets.)

b) Gustures such a multi-touches, pinch-and-zoom cannot be done on a desktop.

Sticking points for me:

- Graphics.Gloss.Internals.Interface.Backend.Types.hs defines
  initBackendState, openWindow, runMainLoop

  openWindow and runMainLoop really occur together on an iOS app, is there a way of merging
  these two calls together for all the backends?

