# CANprep

CANprep is a practice-question app for your computer. Setting it up takes about 5 minutes:

1. **Download** the app from this page.
2. **Open** it. Your computer asks you to confirm the first time.
3. **Type your name.**
4. **Add the questions** from your question file.

The app does not come with questions. They come in a separate **question file** that you get from the person who
shared this page with you. The app calls it the "content file". There is one file for every computer:

- **Every computer** (Windows, and Macs with any macOS, CANprep 1 or CANprep 2): the same file, whose name ends in
  `.canprep`.

---

## Step 1: Download the app

**First, check which computer you have:**

- **Windows PC:** you need the Windows download.
- **Mac:** click the Apple menu (top-left corner of the screen), then **About This Mac**, and look at the line
  that starts with **macOS**.
  - **macOS 14 (Sonoma) or newer** (15 Sequoia, 26 Tahoe…): you need the **Mac app, CANprep 2**. It is one
    download for every Mac, Apple silicon and Intel alike.
  - **macOS 12 (Monterey) or 13 (Ventura):** you need CANprep 1. Look at the same window again:
    - if it says **Chip: Apple M1** (or M2, M3…), you need the **Apple silicon** download;
    - if it says **Processor** and mentions **Intel**, you need the **Intel** download.

**Then download it:**

1. Go to the **[latest release](https://github.com/jobeconners/canprep-releases/releases/latest)**. If you are on the
   main GitHub page, click the release under **Releases** on the right.

   ![On the main page, click the latest release under Releases](docs/gh-1-latest-release.png)

2. On the release page, scroll to the bottom to **Assets**. If you don't see a list of files there, click the word
   **Assets** to open it.
3. Click the **one** file for your computer. It downloads to your **Downloads** folder.

   | Your computer | Click this file |
   | --- | --- |
   | Mac with macOS 14 or newer (any Mac) | `CANprep-2.…-mac.zip` |
   | Mac with macOS 12 or 13, Apple M1, M2, M3… | `CANprep-1.…-mac-arm64.zip` |
   | Mac with macOS 12 or 13, Intel | `CANprep-1.…-mac-intel.zip` |
   | Windows | `CANprep-1.…-windows-x64.zip` |

   Ignore the other files. They are for automatic updates.

   ![Assets at the bottom of the release page: click the zip for your computer](docs/gh-2-assets.png)

## Step 2: Open the app for the first time

The first time you open CANprep, your computer shows a warning because the app is not from the App Store or the
Microsoft Store. This is normal. Follow the steps for your computer:

- [Windows](#windows)
- [Mac with macOS 14 or newer (CANprep 2)](#mac-with-macos-14-or-newer-canprep-2)
- [Mac with macOS 12 or 13, Apple silicon (M1 or newer)](#mac-with-macos-12-or-13-apple-silicon-m1-or-newer)
- [Mac with macOS 12 or 13, Intel processor](#mac-with-macos-12-or-13-intel-processor)

### Windows

1. Open your **Downloads** folder. Right-click the CANprep zip file, choose **Extract All…**, then click **Extract**.
2. A new folder opens. Keep this folder (the app lives in it). You can move it to **Documents** if you like.
3. Open the **CANprep-win32-x64** folder inside it. You will see many files. Double-click the one called **CANprep**
   with the CANprep icon (it may show as **CANprep.exe**).
4. If a blue box says **"Windows protected your PC"**, click **More info**, then **Run anyway**.

Tip: right-click **CANprep** and choose **Pin to Start** so it is easy to find next time.

### Mac with macOS 14 or newer (CANprep 2)

1. Open your **Downloads** folder and double-click the `CANprep-2.…-mac.zip` file. (If you already see a **CANprep**
   app there, your Mac unzipped it for you.)
2. Drag **CANprep** onto **Applications** in the left sidebar of the Finder window. If your Mac asks whether to
   replace an older CANprep, click **Replace**. Your progress is kept: it is stored separately from the app.
3. Open **Applications** and double-click **CANprep**. A message says Apple could not verify CANprep. Click
   **Done**. Do **not** click "Move to Trash".
4. Click the Apple menu → **System Settings** → **Privacy & Security**. Scroll all the way down and click
   **Open Anyway** next to the message about CANprep.
5. Confirm with your Mac password or Touch ID. If asked again, click **Open Anyway** or **Open**.

**If it says CANprep "is damaged and can't be opened":**

1. Press **Command + Space**, type **Terminal**, and press **Return**.
2. Copy the line below, paste it into the Terminal window (**Command + V**) and press **Return**. Nothing seems to
   happen. That is normal.

   ```bash
   xattr -cr /Applications/CANprep.app
   ```

3. Close Terminal and open CANprep again.

### Mac with macOS 12 or 13, Apple silicon (M1 or newer)

1. Open your **Downloads** folder and double-click the CANprep zip file. (If you already see a **CANprep** app there,
   your Mac unzipped it for you.)
2. Drag **CANprep** onto **Applications** in the left sidebar of the Finder window.
3. Open **Applications** and double-click **CANprep**. A message says Apple could not verify CANprep. Click
   **Done**. Do **not** click "Move to Trash".
4. Click the Apple menu → **System Settings** → **Privacy & Security**. Scroll all the way down and click
   **Open Anyway** next to the message about CANprep.
5. Confirm with your Mac password or Touch ID. If asked again, click **Open Anyway** or **Open**.

On older Macs, step 4 is called **System Preferences → Security & Privacy**. You can also right-click CANprep and
choose **Open**, then **Open** again.

**If it says CANprep "is damaged and can't be opened":**

1. Press **Command + Space**, type **Terminal**, and press **Return**.
2. Copy the line below, paste it into the Terminal window (**Command + V**) and press **Return**. Nothing seems to
   happen. That is normal.

   ```bash
   xattr -cr /Applications/CANprep.app
   ```

3. Close Terminal and open CANprep again.

### Mac with macOS 12 or 13, Intel processor

1. Open your **Downloads** folder and double-click the CANprep zip file. (If you already see a **CANprep** app there,
   your Mac unzipped it for you.)
2. Drag **CANprep** onto **Applications** in the left sidebar of the Finder window.
3. Open **Applications** and double-click **CANprep**. A message says Apple could not verify CANprep. Click
   **Done**. Do **not** click "Move to Trash".
4. Click the Apple menu → **System Settings** → **Privacy & Security**. Scroll all the way down and click
   **Open Anyway** next to the message about CANprep.
5. Confirm with your Mac password or Touch ID. If asked again, click **Open Anyway** or **Open**.

On older Macs, step 4 is called **System Preferences → Security & Privacy**. You can also right-click CANprep and
choose **Open**, then **Open** again.

**If it says CANprep "is damaged and can't be opened":**

1. Press **Command + Space**, type **Terminal**, and press **Return**.
2. Copy the line below, paste it into the Terminal window (**Command + V**) and press **Return**. Nothing seems to
   happen. That is normal.

   ```bash
   xattr -cr /Applications/CANprep.app
   ```

3. Close Terminal and open CANprep again.

You only need to do Step 2 once. After that, CANprep opens like any other app.

## Step 3: Type your name

CANprep asks what to call you. Type your name **(1)** and click **Continue (2)**. There is no account and no password.

![First start: type your name, then Continue](docs/2-name.png)

## Step 4: Add the questions

After you click Continue, CANprep shows **"No question bank is installed yet"** with a box that says **"Drop your
content file here to begin"**. This is where you add the questions.

1. Find your question file. It is usually in your **Downloads** folder. It ends in `.canprep`, on
   Windows and on every Mac, whichever version of CANprep you use.
2. Drag it into that box. Or click **Choose a file…** and pick it.

   ![Drag the question file into the box, or click Choose a file](docs/3-import.png)

3. Wait while it loads. When the list of question banks appears, click **Done**. You're ready to study.

   ![Import finished: click Done](docs/4-report.png)

**Can't find the box?** Click **Home** at the top of the left sidebar. You can also click **Settings** (bottom of the
left sidebar), then the **Content** tab. The pictures on this page show CANprep 1; CANprep 2 on a Mac looks a little
different but asks for the same steps.

Keep the question file somewhere safe. You need it again if you set up CANprep on another computer.

---

## Later

**New or fixed questions:** when you get a newer question file, click **Settings** (bottom left) → **Content (1)**
and drop the file into the box **(2)**. Your answers, notes, flags and highlights are kept.

![Settings, Content tab: drop the new file into the box](docs/5-update.png)

**App updates:** nothing to do. The app updates itself. When a new version has been downloaded, a small card in the
corner says **CANprep has been updated** (while you are taking a test it waits, and it appears once the test is
finished or left): click **Restart now** and the app reopens exactly where you were. **Later** is fine too: the new
version is then used the next time you open the app.

If CANprep says it is older than your progress data and cannot install a newer version by itself, download the
newest version from this page; your progress stays.

**Macs: CANprep 2 is the Mac app from now on.** On a Mac with macOS 14 or newer, CANprep 1 moves to CANprep 2 by
itself: after an update, the next time you quit CANprep it replaces itself, and the next time you open it (from the
Dock, Applications or Spotlight, as always) it is CANprep 2. Your answers, tests, notes, flags, highlights, notebook,
plan and question banks are all kept. There is nothing to import again.

- **If CANprep shows "CANprep 2 for this Mac is ready to download" instead,** it could not replace itself (for
  example, it was opened straight from the Downloads folder, or your Mac account cannot change the Applications
  folder). Click **Open Download Page**, download `CANprep-2.…-mac.zip`, and follow Step 2,
  "Mac with macOS 14 or newer": drag the new CANprep into **Applications** and click **Replace**. Your progress stays: it is stored separately from the app.
- **Macs with macOS 12 or 13 stay on CANprep 1.** It keeps updating itself as before.
- **A Mac that moves from CANprep 1 to 2** keeps its installed question banks and imports nothing. **A new Mac**
  with macOS 14 or newer needs the `.canprep` question file in Step 4, like any other computer.

**Updating to version 1.1.0 (the study plan): import the question file once more.** The new study plan uses a map of
the concepts each question tests, and that map comes in the newest question file
(`CANprep-content-2026112020.canprep` or later). After the app has updated, drop that file into Settings → Content
as above. Until you do, the app shows a short reminder on Home and the plan still works, with fewer "second
questions" on what you met before. Your answers, notes, flags, notebook and plan are kept.

**Moving to another computer:** in CANprep, click **Settings** → **Data** → **Export progress**. This saves one file. **Update CANprep on both computers first:** from versions 1.3 (Windows) and 2.1 (Mac) the progress file holds more, and an older CANprep cannot read all of it.
Set up CANprep on the new computer (Steps 1 to 4), then drop that file onto the CANprep window. Your progress is
added; nothing is lost.
