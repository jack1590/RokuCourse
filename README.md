# Roku BrightScript Crash Course

Source code and project files for the **Roku BrightScript Crash Course**. Each section folder contains the complete channel projects built throughout the course, so you can follow along or use them as reference.

## Repository Structure

```
RokuCourse/
├── Section-1/          # Introduction & Setup
│   └── HelloWorld/     # Your first Roku channel
├── Section-2/          # (coming soon)
└── ...
```

Each section folder maps to a course section and contains one or more Roku channel projects ready to sideload onto your device.

## Prerequisites

- **Roku device** with [Developer Mode enabled](https://developer.roku.com/en-gb/docs/developer-program/getting-started/developer-setup.md)
- **VS Code** with the [BrightScript Language](https://marketplace.visualstudio.com/items?itemName=RokuCommunity.brightscript) extension
- A computer on the **same local network** as your Roku device

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/jack1590/RokuCourse.git
   ```

2. Open any project folder in VS Code (e.g. `Section-1/HelloWorld/`).

3. Press **F5** to launch the BrightScript debugger — it will prompt you for your Roku device IP and developer password.

## Project Overview

| Section | Project | Description |
|---------|---------|-------------|
| 1 | **HelloWorld** | Minimal Roku channel — covers project structure, manifest, SceneGraph basics, and sideloading |

> More sections and projects will be added as the course progresses.

## Roku Channel Project Structure

Every Roku channel in this repo follows the standard layout:

```
ProjectName/
├── manifest                # Channel metadata (title, version, artwork paths)
├── source/
│   └── main.brs            # Entry point — creates the screen and event loop
├── components/
│   └── MainScene.xml       # Root SceneGraph scene
└── images/                 # Channel posters and splash screens
```

## License

This project is licensed under the [MIT License](LICENSE).

## Author

**Juan Carlos Joya Carvajal**
