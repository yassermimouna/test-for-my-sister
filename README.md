# 🎉 Welcome to Your First Git Project!

Hi! This is your first step into the world of development and version control. Let's get you started with Git and GitHub!

## 📋 What You'll Learn

- Setting up your GitHub account
- Cloning a repository
- Making changes to code
- Committing your changes
- Pushing to GitHub

## 🚀 Getting Started

### Step 0: Create Your GitHub Account (If You Haven't Already)

1. Go to [github.com](https://github.com)
2. Click "Sign up"
3. Follow the steps to create your free account
4. Verify your email address
5. You're now part of the developer community! 🎉

### Step 1: Install VS Code

VS Code is a free code editor that makes coding super easy!

1. Go to [code.visualstudio.com](https://code.visualstudio.com)
2. Download VS Code for your operating system
3. Install it by following the installation wizard
4. Open VS Code - you're ready to code! 🎨

### Step 2: Install Git

If you don't have Git installed:

- **Windows**: Download from [git-scm.com](https://git-scm.com)
- **Mac**: Open Terminal and type `git --version` (it will prompt you to install if needed)
- **Linux**: Run `sudo apt-get install git` (Ubuntu/Debian) or `sudo yum install git` (Fedora)

### Step 3: Configure Git

Open your terminal/command prompt and run:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

Use the same email you used for your GitHub account!

### Step 4: Clone This Repository

Open your terminal/command prompt and run:

```bash
git clone https://github.com/yassermimouna/test-for-my-sister.git
cd test-for-my-sister
```

### Step 5: Open the Project in VS Code

Open VS Code, then:
1. Click **"File"** → **"Open Folder"**
2. Navigate to the `test-for-my-sister` folder you just cloned
3. Click **"Open"**

Now you can see all the project files in VS Code! Double-click `index.html` to open it.

To view the page in your browser, right-click on `index.html` in VS Code and select "Open with Live Server" (if you have the Live Server extension) or just open the file directly in your browser. You'll notice something is broken! 🐛

### Step 6: Create Your Own Branch

Before making changes, let's create a new branch (this is how developers work in teams!):

```bash
git checkout -b fix-css-bugs
```

Now you're working on your own branch called `fix-css-bugs`! This keeps your changes separate from the main code.

## 🔧 Your Mission

There are TWO CSS bugs in the project:

1. **The buttons are stacked vertically** - They should be side by side!
2. **The "NEW DEV" badge is invisible** - It's hiding behind the card!

### What to Do:

1. Open `index.html` in VS Code (you should already have it open from Step 5!)
2. Open the file in your browser to see the bugs
3. Look at the CSS in the `<style>` section
4. Find and fix both bugs:
   - **Hint 1**: Buttons need flexbox to sit side by side
   - **Hint 2**: The badge has a z-index problem
5. Refresh the browser to see your fixes!
6. Save your changes

## 📤 Submitting Your Fix

Once you've fixed the issue:

### Step 1: Check what changed

```bash
git status
```

You should see `index.html` as modified.

### Step 2: Stage your changes

```bash
git add index.html
```

### Step 3: Commit your changes

```bash
git commit -m "Fix: Corrected button layout and badge z-index"
```

### Step 4: Push your branch to GitHub

```bash
git push origin fix-css-bugs
```

### Step 5: Create a Pull Request (PR)

1. Go to the repository on GitHub: https://github.com/yassermimouna/test-for-my-sister
2. You'll see a yellow banner saying "fix-css-bugs had recent pushes" with a button **"Compare & pull request"** - click it!
3. Add a title like: "Fix CSS bugs in welcome card"
4. In the description, write what you fixed:
   ```
   ## What I Fixed
   - Changed button-group display to flex so buttons appear side by side
   - Fixed success-badge z-index so it's visible
   ```
5. Click **"Create pull request"**

### Step 6: Wait for Review

Your sibling will review your code and merge it into the main branch! This is how real developers collaborate! 🎉

## 🎯 Success!

Once your Pull Request is merged, you'll have officially contributed to a project using the proper Git workflow!

**You just learned:**

- ✅ Creating branches
- ✅ Making commits
- ✅ Pushing code
- ✅ Creating Pull Requests
- ✅ Code collaboration

Welcome to the world of development! 🚀

---

## 💡 VS Code Tips

- **Opening Terminal in VS Code**: Press `Ctrl + `` (backtick) or go to **Terminal** → **New Terminal**. You can run all Git commands directly in VS Code!
- **Useful Extension**: Install "Live Server" extension to preview HTML changes in real-time
- **Keyboard Shortcuts**: `Ctrl+S` (or `Cmd+S` on Mac) to save your files

---

**Need Help?** Ask your sibling or check out [GitHub's Git Guide](https://github.com/git-guides)
