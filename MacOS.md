# BetterAnimations (macOS)

BetterAnimations can completely change the look and feel of Discord with smoother animations and effects.

## Requirements

### 1. Install Git

* **macOS:** https://git-scm.com/install/mac

### 2. Install Node.js

Download and install the **LTS** version:
https://nodejs.org/

### 3. Install pnpm

Open **Terminal** and run:

```bash
npm install -g pnpm
```

### 4. Download the UserPlugins Folder

Download it here:

https://drive.google.com/drive/folders/1YqK1TjD8bo89cTzpCyGJH5RF-pYZYObG?usp=drive_link

---

# Installation

## Step 1

Open **Terminal**.

## Step 2

Go to your Downloads folder:

```bash
cd ~/Downloads
```

## Step 3

Clone Vencord:

```bash
git clone https://github.com/Vendicated/Vencord.git
```

## Step 4

Move the downloaded **userplugins** folder into:

```
Vencord/src/
```

It should look like:

```
Vencord
└── src
    └── userplugins
```

## Step 5

Go into the Vencord folder:

```bash
cd ~/Downloads/Vencord
```

## Step 6

Install dependencies:

```bash
pnpm install
```

## Step 7

Build Vencord:

```bash
pnpm build
```

## Step 8

Inject into Discord:

```bash
pnpm inject
```

If prompted for your Discord installation, press **Enter** to use the default location.

## Step 9

Restart Discord.

---

# Enable BetterAnimations

1. Open **Discord**.
2. Go to **Settings**.
3. Click **Plugins**.
4. Search for **BetterAnimations**.
5. Turn it **ON**.

🎉 You're done! BetterAnimations is now installed on macOS.

---

## Requirements

* macOS
* Discord Desktop
* Git
* Node.js (LTS)
* pnpm
* Internet connection

If you don't understand the written guide, watch the video tutorial:

**Video Guide:** *(Add your video link here)*
