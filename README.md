# Video Showcase Website

A cinematic, modern video website designed to host and stream `Video-15594.mp4` with high-performance edge delivery on Vercel.

## Features
- **Cinematic HTML5 Player**: Ambient backdrop glow reflecting video frames dynamically in real-time.
- **Full Custom Controls**: Play/pause, scrubbing timeline, volume slider, mute, PiP, loop, playback rate (0.5x to 2x), and fullscreen.
- **Keyboard Shortcuts**:
  - `Space` / `K`: Play / Pause
  - `F`: Fullscreen
  - `M`: Mute / Unmute
  - `←` / `→`: Seek ±5 seconds
  - `↑` / `↓`: Volume Up / Down
- **Direct Download & Share**: Download button and 1-click URL sharing with toast notification.
- **Edge CDN Optimization**: HTTP headers configured for chunked range streaming and edge caching on Vercel.

## Deployment
This project is configured for instant zero-config deployment on Vercel:
```bash
npx vercel --prod
```
