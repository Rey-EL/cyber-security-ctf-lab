# Cyber Security CTF Lab

This project is a web-based, interactive terminal simulator for learning basic cybersecurity concepts. It's a single HTML file that creates a "Capture The Flag" (CTF) style learning environment in your browser.

## Features

- **Zero Installation:** Runs entirely in your web browser. No need to install VMs or other software.
- **Interactive Terminal:** A simulated Linux terminal to practice commands, complete with command history and autocomplete.
- **CTF Challenges:** Multiple levels of challenges that mirror real-world security analyst tasks, featuring an enhanced narrative and progression system with Analyst Ranks.
- **Dedicated Answer Area:** Submit flags in a separate input field for a clearer CTF experience.
- **Collapsible Hints:** Hints are hidden by default and can be revealed with a click.
- **Safe Environment:** All commands are simulated, so it's completely safe to use and practice.

## How to Use

1.  Open the `cyber_lab.html` file in your web browser.
2.  Follow the "Mission Briefing" and narrative on the left side of the screen.
3.  Use the terminal on the right to enter commands and find information relevant to the challenge.
4.  When you find an answer (flag), type it into the "Your Answer:" box and click "Submit" to complete the level.

## Deployment

This project can be easily deployed to GitHub Pages to make it accessible via a public URL.

1.  Ensure the `cyber_lab.html` file is in the root of your repository.
2.  In your repository's settings, navigate to the "Pages" section.
3.  Under "Build and deployment", select `Deploy from a branch`.
4.  For "Branch", select `main` (or your primary branch) and choose the `/(root)` folder.
5.  Click "Save".
6.  Your lab will be live at `https://<your-username>.github.io/<your-repository-name>/cyber_lab.html`.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contributing

Contributions are welcome! If you have suggestions for new features, bug fixes, or additional CTF levels, please feel free to:

1.  Fork the repository.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'feat: Add amazing feature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

