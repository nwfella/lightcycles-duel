# 🏍️ Lightcycles Duel

**Mobile-first 1v1 lightcycle combat** — Practice vs AI or challenge friends online. Built with vanilla HTML5 Canvas, Web Audio API, and PeerJS for P2P networking.

Inspired by the classic Tron Lightcycles arcade game with a **diagonal movement twist** — 8-directional steering for tighter traps and slicker escapes.

## Features

- 🎮 **Practice Mode** — Play against an AI opponent with adaptive difficulty
- 🌐 **Online Duel** (Coming Soon) — P2P matches via PeerJS
- 📱 **Mobile-first** — One joystick, full-screen canvas, touch-optimized
- 🎵 **Web Audio Engine** — Sawtooth hums, direction-change filter sweeps, explosion noise
- 💎 **TON Blockchain** (Coming Soon) — Wallet connect + stake-to-play duels
- 💬 **Telegram Mini App** (Coming Soon) — Launch directly from Telegram

## Play

👉 **[Play Now](https://nwfella.github.io/lightcycles-duel/)** (mobile recommended)

## How to Play

1. **Select Practice** to duel the AI
2. **Drag the joystick** to steer your lightcycle
3. **Avoid walls and trails** — yours and theirs
4. **Last cycle standing wins!**

## Controls

| Input | Action |
|-------|--------|
| 🕹️ Joystick | Drag to steer (8-directional) |
| 👆 Tap canvas | Skip countdown |

## Tech Stack

- Vanilla HTML5 Canvas 2D
- Web Audio API (procedural sound synthesis)
- PeerJS (P2P WebRTC, coming)
- TON Connect (blockchain wallet, coming)
- Telegram Mini App API (coming)

## Development

```bash
git clone https://github.com/nwfella/lightcycles-duel.git
cd lightcycles-duel
# Serve locally
python -m http.server 8000
# Or use any static file server
```

## Roadmap

- [x] Practice mode with AI
- [ ] Online P2P duels (PeerJS)
- [ ] Telegram Mini App wrapper
- [ ] TON Connect wallet auth
- [ ] Stake-to-play matches
- [ ] Leaderboard
- [ ] Custom arenas

## License

MIT
