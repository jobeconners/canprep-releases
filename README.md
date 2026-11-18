# CANprep

Download page for the CANprep exam simulator. The app comes **without questions**: you add them by importing your
CANprep content file (`.canprep`), once per computer.

---

## 1. Download

Open the **[latest release](../../releases/latest)** and click the zip for your computer under **Assets**:

- **Mac with Apple silicon** (M1, M2, M3, M4 …): `CANprep-<version>-mac-arm64.zip`
- **Mac with an Intel processor**: `CANprep-<version>-mac-intel.zip`
  (Not sure which you have? Apple menu → **About This Mac**: it shows **Chip: Apple M…** or **Processor: Intel**.)
- **Windows**: `CANprep-<version>-windows-x64.zip`

The other files on that page are for automatic updates; you don't need them.

## 2. Install and open

CANprep is not from the Mac App Store or the Microsoft Store, so your computer shows a security warning the first
time. That is expected. Go to the section for your computer below.

- [Windows](#windows)
- [Mac with Apple silicon (M1 or newer)](#mac-with-apple-silicon-m1-or-newer)
- [Mac with an Intel processor](#mac-with-an-intel-processor)

### Windows

1. Right-click the zip → **Extract All…**, and keep the folder somewhere permanent (e.g. Documents).
2. Open the folder and double-click **CANprep.exe**.
3. The first time, Windows shows **"Windows protected your PC"**. Click **More info**, then **Run anyway**.

### Mac with Apple silicon (M1 or newer)

1. Double-click the zip, then drag **CANprep** into your **Applications** folder.
2. Open **Applications** and double-click **CANprep**. macOS says it "could not verify CANprep is free of malware".
   Click **Done**. Do not click "Move to Trash".
3. Open **System Settings → Privacy & Security**, scroll down to the Security section, and click **Open Anyway**
   next to the message about CANprep.
4. Enter your Mac password if asked, then click **Open**.

If there is no **Open Anyway** button, double-click CANprep once more so macOS remembers it, then go back to
Privacy & Security and try again. On macOS 14 or older you can also right-click CANprep → **Open** → **Open**.

If it says CANprep **"is damaged and can't be opened"**, open the **Terminal** app (search for it with Spotlight),
paste the line below, press Return, then open CANprep again:

```bash
xattr -cr /Applications/CANprep.app
```

### Mac with an Intel processor

1. Double-click the zip, then drag **CANprep** into your **Applications** folder.
2. Open **Applications** and double-click **CANprep**. macOS says it "could not verify CANprep is free of malware".
   Click **Done**. Do not click "Move to Trash".
3. Open **System Settings → Privacy & Security**, scroll down to the Security section, and click **Open Anyway**
   next to the message about CANprep.
4. Enter your Mac password if asked, then click **Open**.

If there is no **Open Anyway** button, double-click CANprep once more so macOS remembers it, then go back to
Privacy & Security and try again. On macOS 14 or older you can also right-click CANprep → **Open** → **Open**.

If it says CANprep **"is damaged and can't be opened"**, open the **Terminal** app (search for it with Spotlight),
paste the line below, press Return, then open CANprep again:

```bash
xattr -cr /Applications/CANprep.app
```

You only need these steps the first time. After that, CANprep opens normally.

## 3. Enter your name

Type the name the app should use **(1)** and click **Continue (2)**. It stays on this computer: there is no
account and no password. You can change it later in Settings.

## 4. Import the content file

Drag your `.canprep` file onto the window, or click **Choose a file…** and pick it. You can drop it anywhere on the
window.

It takes a few seconds. A report lists every question bank that was added; click **Done** and start studying.

Keep the content file somewhere safe: you need it again to set up another computer.

---

## Getting new or fixed questions later

When you get a newer content file, import it the same way: drop it on the window, or go to **Settings** (bottom
left) → **Content (1)** → drop it on **Import (2)**. Only the banks that changed are replaced and nothing is
duplicated. The report shows what is new, changed or removed. Your answers, notes, flags and highlights are kept,
and your progress is backed up before every import.

![Settings, Content tab, Import area](docs/5-update.png)

## App updates

Nothing to do. The app checks this page by itself, downloads new versions in the background and uses them from the
next start. Every update is signed, and the app refuses anything that isn't. Updates never touch your progress or
your questions.

## Moving your progress to another computer

**Settings → Data → Export progress** saves one file with everything you've done. On the other computer, drop that
file on the window: it is merged in, nothing is overwritten.
