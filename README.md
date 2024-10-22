# One Last Mission

A short film project inspired by Star Wars Battlefront, created in Unreal Engine 5.5. This project serves as both a fan tribute and a technical demonstration of emerging technologies in real-time cinematography.

## 🎬 About The Project

One Last Mission leverages the power of Unreal Engine 5.5 to create cinematic experiences with game engine technology. By utilizing features like Lumen, Nanite, and the latest in lighting and rendering techniques, we aim to showcase the convergence of game engine capabilities with traditional filmmaking techniques to produce quality cinematics deserving of the Star Wars, and Battlefront, franchises.

## 🛠️ Built With

* Unreal Engine 5.5
* Fab QuixelMegascan Assets
* [Add other major tools/technologies used]

## 🧑‍💻 Meet The Team

### Leadership
* **Tyler Grow** - *Creative Director*
* **Alec Brandt / *(Azterisk)*** - *Technical Director*

### Development
* [Name] - *Technical Artist*
* [Name] - *Environment Artist*
* [Name] - *Character Artist*

### Creative
* [Name] - *Storyboard Artist*
* [Name] - *Concept Artist*
* [Name] - *Sound Designer*

### Technical
* [Name] - *Visual Effects Artist*
* [Name] - *Technical Animator*
* [Name] - *Lighting Artist*

## 📝 Contributing

We're always looking for talented individuals to join our project. If you're interested in contributing, please reach out to [contact information].

## 🔧 Development Setup

### Prerequisites
1. **Git**
   - Download and install from [Git-SCM](https://git-scm.com/downloads)
   - During installation, choose "Use Git from Git Bash and Command Prompt"

2. **Git LFS**
   - Download and install from [Git LFS](https://git-lfs.github.com/)
   - After installing both Git and Git LFS, open a terminal and run:
     ```bash
     git lfs install
     ```

3. **Epic Games Launcher & Unreal Engine 5.5**
   - Install Epic Games Launcher from [Epic Games](https://www.epicgames.com/store/en-US/download)
   - In the launcher, go to the Unreal Engine tab
   - Install Unreal Engine version 5.5

4. **Visual Studio 2022** (if working with C++ components / not most of you)
   - Download Community Edition from [Visual Studio](https://visualstudio.microsoft.com/vs/community/)
   - During installation, select:
     - "Game development with C++"
     - "Windows 10/11 SDK"

5. **System Requirements**
   - At least 200GB free disk space *(project is much less especially when all other components/applications are installed already)*
   - 32GB RAM recommended
   - Graphics card compatible with DirectX 12 or Vulkan

### Installation Steps

1. Install Git LFS if you haven't already:
```bash
git lfs install
```

2. Clone the repository:
```bash
git clone https://github.com/Azteriisk/OneLastMission.git
```

3. Navigate to the project directory:
```bash
cd OneLastMission
```

4. Pull LFS content:
```bash
git lfs pull
```

### Setting Up the Project

0. *(If using C++ components)* Right-click \OneLastMission.uproject\ and select "Generate Visual Studio project files" (Required for rebuilding the project)

1. Launch the project
  - Double-click \OneLastMission.uproject\
  - If prompted about missing modules, click "Yes" to rebuild them

### Common Issues and Solutions

- **Missing .dll errors**: Rebuild the project in Visual Studio
- **Black textures/Missing content**: Verify Git LFS pulled all content correctly
- **Shader compilation issues**: Delete the Saved/ShaderDebugInfo folder and restart

### Project Structure
```bash
OneLastMission/
├── Content/               # Main content folder
│   ├── Main.umap         # Main level
│   ├── Megascans/        # Environmental assets
│   └── ... 
├── Config/               # Project configuration
└── Source/               # C++ source files (if any)
```

### Updating Your Local Copy
```bash
git pull
git lfs pull
```

Remember to always pull both regular files and LFS content when updating.

### Working with Large Files

This project uses Git LFS for large files. Any new large assets should be tracked in Git LFS. The following file types are automatically tracked:
- *.uasset
- *.umap
- Other large binary files

To add new file types to LFS:
```bash
git lfs track "*.your_extension"
git add .gitattributes
```

## 📜 License

This project is a non-commercial fan film and is not affiliated with or endorsed by Lucasfilm Ltd. or Electronic Arts Inc. All Star Wars related content belongs to their respective owners.

## 🙏 Acknowledgments

* Epic Games - Unreal Engine
* Quixel - Megascans Assets
* [Other acknowledgments]

---
*A long time ago in a galaxy far, far away...*