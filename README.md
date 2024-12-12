# Data Management and Statistical Core Sharing Hub
A public website showcasing resources from the Data Management and Statistical Core at the Michigan Alzheimer's Disease Center.

---

## Setting Up and Contributing to a Quarto Website Project

### Prerequisites
Ensure you have completed the following steps:
- Download [Git](https://git-scm.com/downloads)
- Create a GitHub account ([sign up here](https://github.com/)) if you do not already have one

### Setting Up a Quarto Website Project

#### 1. Install VS Code
Download and install Visual Studio Code: [VS Code Download Page](https://code.visualstudio.com/)

#### 2. Install Quarto Locally
Follow the instructions to install Quarto on your system: [Quarto Installation Guide](https://quarto.org/docs/get-started/)

#### 3. Install Quarto Extension for VS Code
Add the Quarto extension to VS Code from the Marketplace: [Quarto Extension](https://marketplace.visualstudio.com/items?itemName=quarto.quarto)

#### 4. Restart VS Code
If VS Code is open during installation, quit and relaunch it to ensure the extension loads properly.

#### 5. Create the Quarto Project
1. Open VS Code.
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac) to open the Command Palette.
3. Type and select `Quarto: Create Project`.
4. Choose `Website` as the project type.
5. Specify a folder location and project name, then click `Create`.
6. Edit the configuration file (`_quarto.yml`) and content files to customize the website.
7. Preview the website locally:
   - Right-click on the `index.qmd` file and select `Quarto: Preview`.

#### 6. Deploy to GitHub Pages
Follow the publishing instructions to deploy the website: [GitHub Pages Deployment Guide](https://quarto.org/docs/publishing/github-pages.html)

1. Use the Quarto extension to publish:
   - Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac).
   - Type and select `Quarto: Publish`. Choose `GitHub Pages`.
2. Enable GitHub Pages for the repository:
   - Go to your repository’s `Settings`.
   - Under `Pages`, select the `gh-pages` branch as the source.

### How to Contribute to This Project

#### 1. Fork the Repository
1. Go to the main repository on GitHub: [dmsc-madc](https://github.com/MichiganADC/dmsc-madc).
2. Click the `Fork` button in the upper-right corner to create a copy of the repository in your own GitHub account.

#### 2. Clone Your Forked Repository
##### Option 1: Using the VS Code UI
1. Open the Source Control view (Ctrl+Shift+G).
2. Click `Clone Repository` and paste the URL of your forked repository (e.g., `https://github.com/your-username/repo-name.git`).
3. Choose a folder location for the repository.

##### Option 2: Using the Terminal
1. Open a terminal window in VS Code (Ctrl+` or `Cmd+` on Mac).
2. Run the following command:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   ```
3. Navigate into the cloned repository:
   ```bash
   cd repo-name
   ```

#### 3. Create a New Branch
##### Option 1: Using the VS Code UI
1. Open the Source Control view.
2. Click the `...` menu in the top right and select `Branch > Create Branch`.
3. Enter a name for your branch (e.g., `your-feature-branch`).

##### Option 2: Using the Terminal
1. Run the following command to create a new branch:
   ```bash
   git checkout -b your-feature-branch
   ```

#### 4. Make Edits Locally
1. Open the project folder in VS Code.
2. Edit existing content or add new pages as appropriate.
3. Preview your Quarto documents locally:
   - Right-click a `.qmd` file and select `Quarto: Preview`.

#### 5. Commit Your Changes
##### Option 1: Using the VS Code UI
1. Open the Source Control view.
2. Stage your changes by clicking the `+` next to the files you modified.
3. Enter a commit message and click the checkmark to commit.

##### Option 2: Using the Terminal
1. Stage your changes:
   ```bash
   git add .
   ```
2. Commit your changes:
   ```bash
   git commit -m "Your commit message"
   ```

#### 6. Push Your Branch
##### Option 1: Using the VS Code UI
1. Open the Source Control view.
2. Click the `...` menu and select `Push`.

##### Option 2: Using the Terminal
1. Push your branch to GitHub:
   ```bash
   git push origin your-feature-branch
   ```

#### 7. Submit a Pull Request
1. Go to the original repository on GitHub.
2. Click `Compare & pull request`.
3. Add a descriptive title and details about your changes.
4. Submit the pull request for review.

#### 8. Follow Up
- Monitor your pull request for any comments or requested changes from maintainers.
- Address feedback by committing new changes to the same branch and pushing them.

---

### Additional Resources
- Learn how to [sync your fork](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) to keep it up to date with the original repository.
- Review the [GitHub Pages Deployment Guide](https://quarto.org/docs/publishing/github-pages.html) for additional details.
- Brush up on [Markdown Basics](https://quarto.org/docs/authoring/markdown-basics.html) to format your contributions effectively.