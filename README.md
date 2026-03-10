# Reflex Symphony 🎮 — Build APK via GitHub

## You only need to do ONE thing with folder structure:
Put `build.yml` inside `.github/workflows/` — GitHub requires this.
Everything else (index.html, config.xml, package.json) goes in the **root** of the repo.

---

## Steps

### 1. Create a free GitHub account
https://github.com — click Sign Up

### 2. Create a new repository
- Click **+** → **New repository**
- Name: `reflex-symphony`
- Set to **Public**
- Click **Create repository**

### 3. Upload the files
Drag ALL files into the repo root EXCEPT `build.yml`:
- `index.html`
- `config.xml`
- `package.json`
- `.gitignore`
- `README.md`

Then for `build.yml`:
- Click **Create new file**
- In the filename box type: `.github/workflows/build.yml`
- Paste the contents of `build.yml` into the editor
- Click **Commit new file**

### 4. Watch the build (Actions tab)
Takes about 5 minutes. Wait for ✅

### 5. Download your APK
Actions tab → click the finished run → scroll to **Artifacts** → download **ReflexSymphony-debug**

### 6. Install on Android
- Copy `app-debug.apk` to your phone
- Settings → Security → **Allow unknown sources**
- Tap the APK → Install
- Plays 100% offline, no WiFi ever needed ✅
