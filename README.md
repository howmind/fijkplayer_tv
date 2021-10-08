# Support android TV 
* add fullscreen panel builder, so custom the two panel layout between window and fullscreen.
* support FijkView to receive the focus event, so can handle the D-Pad select event on FijkView
``` dart
  FijkView({
    ...
    this.panelBuilder = defaultFijkPanelBuilder, // for normal window
    this.fullscreenPanelBuilder, //for fullscreen
    this.focusNode,
    this.onFocusChange,
    this.onKey,
  });
```
* add getTcpSpeed(), but not available on .m3u8 video stream.
---
### fork from fijkplayer, thank befovy/fijkplayer
