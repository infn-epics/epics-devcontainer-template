# EPICS Dev Container Template

This repository provides a ready-to-use **Dev Container** setup for EPICS-based development using [Visual Studio Code](https://code.visualstudio.com/) and the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).

It includes:

- A prebuilt Docker image or a Dockerfile to build a suitable EPICS runtime environment
- Multi-platform support (x86_64, with optional ARM64 instructions)
- Streamlined configuration using `.devcontainer` folder

---

## 🚀 How to Use This Template

You can use this repo as a **GitHub template**:

1. Click the green **“Use this template”** button on this page.
2. Create your own repository from it.
3. Clone your new repo locally:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

## 💻 Open in VS Code with Dev Containers

1. **Install Requirements**  
   Make sure you have the following installed:

   - [Visual Studio Code](https://code.visualstudio.com/)
   - [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
   - [Docker](https://www.docker.com/)

2. **Open the Folder in VS Code**

   - Launch VS Code.
   - Choose `File > Open Folder...` and select your cloned repository.

3. **Reopen in Container**

   - When prompted by VS Code, click **“Reopen in Container”**.
   - Or manually use the Command Palette:

     ```
     Dev Containers: Reopen in Container
     ```

4. VS Code will:

   - Pull or build the Docker image
   - Start the container
   - Attach the editor to it

You’ll now be working inside a fully configured development environment with EPICS preinstalled.

