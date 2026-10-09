# Cyber Security CTF Lab

I built a Capture The Flag game that runs as a single HTML file in the browser. It simulates a Linux terminal where you work through security challenges, find flags, and rank up as an analyst.

## How to play

1. Open `cyber_lab.html` in any web browser. Nothing to install.
2. Read the mission briefing on the left side of the screen.
3. Use the terminal on the right to run commands and hunt for information.
4. When you find a flag, type it into the answer box and submit to clear the level.

## What is in it

- A simulated Linux terminal with command history and autocomplete.
- Multiple challenge levels based on tasks a real security analyst does.
- An analyst rank system that tracks your progress.
- Hints hidden behind a click, so you only see them when you want them.
- Everything runs locally. No VMs, no setup, no risk.

## Why I built it

I wanted a way to practice terminal skills and security thinking without spinning up a lab environment. One file, open it, play. It is also a good example of what I can do with plain HTML, CSS, and JavaScript.

## Hosting it

The lab works from a file, but you can put it on GitHub Pages if you want a public link:

1. Keep `cyber_lab.html` in the root of the repo.
2. Go to the repo Settings, then Pages.
3. Set source to Deploy from a branch, pick `main`, folder `/ (root)`, and save.
4. It will be live at `https://<your-username>.github.io/<repo-name>/cyber_lab.html`.

## License

MIT License. See [LICENSE.md](LICENSE.md) for details.
