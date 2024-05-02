# ![[tktk Module Name] - tktk Microlesson Name](./assets/the-installfest-journey.png)

**Learning objective:** By the end of this lesson, students will be able to setup the workspace.

## Installing IntelliJ Community Edition with JDK 17

This guide will help you install and set up IntelliJ Community Edition alongside JDK 17 on your computer. This setup is essential for Java development, providing a robust environment for writing, testing, and debugging Java applications.

## Prerequisites

Before you begin, ensure your system meets these requirements:
- Operating System: Windows 10/8/7, macOS, or Linux
- RAM: Minimum of 4GB (8GB recommended)
- Disk Space: Minimum of 2GB free space

## Downloading the Software

### JDK 17

1. Visit the Oracle JDK download page: [Oracle JDK 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
2. Select the appropriate JDK version for your operating system.
3. Click on the download link and accept the license agreement.
4. Download the executable file.

### IntelliJ Community Edition

1. Go to the JetBrains download page: [IntelliJ Community Edition](https://www.jetbrains.com/idea/download/)
2. Choose your operating system.
3. Click the "Download" button for the Community Edition.

## Installation

### Installing JDK 17

1. Run the downloaded JDK installer.
2. Follow the on-screen instructions to complete the installation.
3. Set the `JAVA_HOME` environment variable to the path where JDK is installed.
   - Windows: Set through System Properties -> Environment Variables.
   - macOS/Linux: Add `export JAVA_HOME="/path/to/jdk"` to your `.bashrc` or `.zshrc`.

### Installing IntelliJ Community Edition

1. Run the downloaded IntelliJ installer.
2. Follow the instructions provided by the setup wizard.
3. Choose a directory for installation and complete the setup.

## Configuring IntelliJ

1. Open IntelliJ IDEA.
2. Go to `File` -> `Project Structure` -> `Project`.
3. Under "Project SDK," click on "New" and then "JDK."
4. Navigate to the directory where you installed JDK 17 and select it.
5. Click "OK" to save the settings.

## Verifying the Installation

1. Restart IntelliJ IDEA.
2. Create a new project: `File` -> `New` -> `Project`.
3. Select "Java" from the options and make sure JDK 17 is selected as the project SDK.

## Creating Your First Project

1. In IntelliJ, go to `File` -> `New` -> `Project`.
2. Select "Java" from the left-hand panel and make sure JDK 17 is selected as the SDK.
3. Follow the prompts to name and create your project.

## Installing Git on Your Computer

Git is a distributed version control system that is essential for managing and tracking changes in your projects, especially in collaborative environments. This guide will help you install Git on your system, whether you're using Windows, macOS, or Linux.

## Downloading Git

1. Visit the official Git website to download the latest version: [Git Downloads](https://git-scm.com/downloads)
2. Click on the download link for your specific operating system.

## Installation Instructions

### Windows

1. Run the downloaded executable file to start the installer.
2. Follow the on-screen instructions. Select "Next" for most options, but pay attention to the following:
   - **Adjusting your PATH environment**: Select "Git from the command line and also from 3rd-party software."
   - **Choosing the default editor used by Git**: Select your preferred text editor.
   - **Configuring line ending conversions**: Choose "Checkout Windows-style, commit Unix-style line endings" for compatibility.
3. Complete the installation and click "Finish."

### macOS

1. For macOS, you can install Git through the binary installer or use Homebrew:
   - **Binary Installer**:
     - Open the downloaded `.dmg` file and follow the prompts to install Git.
   - **Homebrew**:
     - If Homebrew is not installed, open Terminal and run: 
       ```bash
       /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
       ```
     - Install Git by running:
       ```bash
       brew install git
       ```

### Linux

1. Open Terminal.
2. Depending on your distribution, use one of the following commands to install Git:
   - **Debian/Ubuntu**:
     ```bash
     sudo apt-get update
     sudo apt-get install git
     ```
   - **Fedora**:
     ```bash
     sudo dnf install git
     ```
   - **Arch Linux**:
     ```bash
     sudo pacman -Sy git
     ```

## Verifying the Installation

1. To verify that Git is installed correctly, open your command line or Terminal and type:

```bash
git --version
```

2. You should see the installed version of Git displayed. If you encounter any issues, make sure your PATH environment variable includes the directory where Git is installed.

## Configuring Git

After installing Git, configure your identity, which is important for commit messages:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

Congratulations! You have successfully installed IntelliJ Community Edition, JDK 17, and Git on your computer. You are now ready to start coding in Java and managing your projects with Git.
