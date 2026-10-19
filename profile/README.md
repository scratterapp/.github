<p align="center">
  <a href="https://github.com/scratterapp/scratter">
    <img src="https://raw.githubusercontent.com/scratterapp/scratter/main/docs/assets/scratter-banner.png" alt="Scratter: a native Apple Music client for Linux and Windows. Unofficial and open source. Not affiliated with Apple." width="100%">
  </a>
</p>

## What we're building

**[Scratter](https://github.com/scratterapp/scratter)** is a small, fast Apple Music player
written in C++23. It comes in two pieces: a background daemon that does the actual playing,
and a lightweight window you can open and close whenever you like.

- **Music keeps playing when the window is closed.** The daemon, `scratterd`, runs on its own,
  like `mpd`.
- **Built to feel native.** It shows up in your desktop's media controls, so your keyboard's
  media keys work.
- **Stays out of the way.** No Electron. Close the window while you game and the music carries on.
- **Linux and Windows.** PipeWire on Linux, WASAPI on Windows.

## Where it's at

Early days. On Linux the daemon already plays audio, takes remote commands through `amctl`
and shows up in the system media controls. Apple Music itself, the Windows side and the
window are next. Follow along in the [roadmap](https://github.com/scratterapp/scratter/issues/6).

## Want to help?

Read [CLAUDE.md](https://github.com/scratterapp/scratter/blob/main/CLAUDE.md) for the rules
and what to work on, then pick an open
[issue](https://github.com/scratterapp/scratter/issues).

<br>

<sub>Apple Music is a trademark of Apple Inc. Scratter is an independent project and isn't
endorsed by Apple. You need your own Apple Music subscription.</sub>
