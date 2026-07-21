#                                                           𝗕𝗲𝘁𝘁𝗲𝗿𝗔𝗻𝗶𝗺𝗮𝘁𝗶𝗼𝗻𝘀

<p align="center">
  <img src="cover.png" alt="BetterAnimations Banner" width="100%">
</p>

Make Discord feel smoother with **BetterAnimations!** Transform the look and feel of Discord with improved animations and transitions.

---

# 📋 Requirements

Before installing **BetterAnimations**, make sure you have the following installed:

### 1. Node.js

Download the **Current** version of Node.js:

https://nodejs.org/en/download/current

#### How to install Node.js

1. Open the link above.
2. Download the **Windows Installer (.msi)**.
3. Run the installer.
4. Click **Next** until you reach the **Install** button.
5. Leave all settings as their default values.
6. Click **Install**.
7. Wait for the installation to finish.
8. Click **Finish**.

---

### Verify Node.js Installation

Press **Windows + R**

```text
Windows + R
```

Type:

```text
cmd
```

Press **Enter**.

Run:

```bash
node -v
```

You should see something similar to:

```text
v24.8.0
```

Then run:

```bash
npm -v
```

You should see a version number, for example:

```text
11.6.0
```

If both commands return version numbers, Node.js was installed successfully.

---

### Install pnpm

In the same Command Prompt window, run:

```bash
npm install -g pnpm
```

After it finishes, verify the installation:

```bash
pnpm -v
```

You should see a version number.

---

### 2. Git

Download Git for Windows:

https://git-scm.com/install/windows

Install Git using the default settings.

After installing, verify it by running:

```bash
git --version
```

You should see something like:

```text
git version 2.xx.x.windows.x
```

---

### 3. Discord Desktop

Make sure the **Discord Desktop Application** is installed.

Download Discord:

https://discord.com/download

---

### 4. UserPlugins Folder

Download the `userplugins` folder:

https://drive.google.com/drive/folders/1YqK1TjD8bo89cTzpCyGJH5RF-pYZYObG?usp=drive_link

Extract it if it downloads as a ZIP.

---

# 🚀 Installation

## Step 1

Open Command Prompt.

Press:

```text
Windows + R
```

Type:

```text
cmd
```

Press **Enter**.

---

## Step 2

Go to your Downloads folder:

```bash
cd Downloads
```

---

## Step 3

Clone the Vencord repository:

```bash
git clone https://github.com/Vendicated/Vencord.git
```

Wait for Git to finish downloading the repository.

---

## Step 4

Move the downloaded **userplugins** folder into:

```text
Vencord/src/
```

Your folder structure should look like:

```text
Vencord
└── src
    └── userplugins
        └── BetterAnimations
```

---

## Step 5

Open the Vencord folder:

```bash
cd Vencord
```

---

## Step 6

Install all required packages:

```bash
pnpm install
```

This may take several minutes.

---

## Step 7

Build Vencord:

```bash
pnpm build
```

Wait until the build completes successfully.

---

## Step 8

Inject Vencord into Discord:

```bash
pnpm inject
```

If you're asked to choose your Discord installation, simply press **Enter** to use the default installation.

---

## Step 9

Restart Discord completely.

If Discord was already open, close it and open it again.

---

# ✅ Enable BetterAnimations

1. Open **Discord**.
2. Click the **Settings** ⚙️ icon.
3. Scroll down to **Vencord**.
4. Open **Plugins**.
5. Search for **BetterAnimations**.
6. Turn the plugin **ON**.

🎉 **BetterAnimations is now installed!**

---

# ✅ Requirements Checklist

- ✅ Windows
- ✅ Node.js
- ✅ npm
- ✅ pnpm
- ✅ Git
- ✅ Discord Desktop
- ✅ Internet Connection

---

# ❓ Troubleshooting

### `'node' is not recognized`

Node.js is either not installed or your PC needs to be restarted.

Restart your computer and try again.

---

### `'pnpm' is not recognized`

Run:

```bash
npm install -g pnpm
```

Then restart Command Prompt.

---

### `'git' is not recognized`

Reinstall Git using the installer from:

https://git-scm.com/install/windows

---

### `pnpm build` failed

Make sure you're inside the **Vencord** folder.

You can check by running:

```bash
dir
```

You should see folders like:

```text
src
scripts
package.json
```

---

### Discord doesn't show BetterAnimations

Make sure the plugin is located here:

```text
Vencord
└── src
    └── userplugins
        └── BetterAnimations
```

Then run:

```bash
pnpm build
```

again and restart Discord.

---

# ❤️ Need Help?

<p align="center">
  <img src="end" alt="BetterAnimations Banner2" width="100%">
</p>

If you're having trouble installing BetterAnimations, watch the installation video.

**📺 Video Guide:** *(Add your YouTube link here)*

If you encounter any bugs or installation issues, feel free to open an issue on the GitHub repository.
