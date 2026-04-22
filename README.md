# Roku BrightScript Crash Course

Source code and project files for the **Roku BrightScript Crash Course**. Each section folder contains the channel projects built throughout the course, organized by lecture so you can follow along step by step.

## Repository Structure

```
RokuCourse/
└── Section-1/                    # Introduction & Setup
    ├── 1-3-HelloWorld/           # Lecture 1.3 — Dev Environment Setup
    └── 1-5-HelloWorld/           # Lecture 1.5 — Understanding Roku Resolutions
```

Project folders are named `<lecture>-<project>` so you can check out the exact state of the code at each point in the course.

## Prerequisites

- **Roku device** with [Developer Mode enabled](https://developer.roku.com/en-gb/docs/developer-program/getting-started/developer-setup.md)
- **VS Code** with the [BrightScript Language](https://marketplace.visualstudio.com/items?itemName=RokuCommunity.brightscript) extension
- A computer on the **same local network** as your Roku device

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/jack1590/RokuCourse.git
   ```

2. Open any project folder in VS Code (e.g. `Section-1/1-3-HelloWorld/`).

3. Press **F5** to launch the BrightScript debugger — it will prompt you for your Roku device IP and developer password.

## Course Content

### Section 1 — Introduction & Setup

| Lecture | Project | What You Build |
|---------|---------|----------------|
| 1.3 — Dev Environment Setup | `1-3-HelloWorld` | Minimal Roku channel — project structure, manifest, SceneGraph basics, sideloading |
| 1.5 — Understanding Roku Resolutions | `1-5-HelloWorld` | Adds FHD/HD/SD resolution support with `ui_resolutions`, `uri_resolution_autosub`, and `$$RES$$` image paths |

> More sections will be added as the course progresses.

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
