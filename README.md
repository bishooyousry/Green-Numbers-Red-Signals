# Green Numbers, Red Signals – online

A single-page web app for the staged case **Green Numbers, Red Signals** (Omar, Senior Sales Executive).
One `index.html` file, no build step, no libraries. It runs on **GitHub Pages**.

## Publish it on GitHub (5 minutes)
1. On github.com create a **new public repository**, for example `green-numbers`.
2. **Add file → Upload files**: drag in **`index.html`** (and `.nojekyll`), then **Commit changes**.
3. **Settings → Pages**: *Deploy from a branch*, branch **main**, folder **/(root)**, **Save**.
4. After 1–2 minutes the site is at `https://YOUR-USERNAME.github.io/green-numbers/`.
   (Pages on a private repository needs a paid plan, so keep the repository public.)

To change anything later, upload a new `index.html` to the same repository.

## Facilitator access
Open the site → **Facilitator** → enter the code **2026**. The same code opens **Debrief**.
(To use another code, open `index.html` in a text editor and change `const FAC_PIN = "2026";`.)
This keeps casual visitors out; it is not strong security, because the code is inside the page file.

## Run a session
1. **Setup and group link**: a random **session code** is created for you (press *New session code* for every session). Copy the **group link** and send it to the groups.
2. Groups open the link, pick their **group number** and press **Join**. A green dot appears next to their group in your console. While they wait they read the case: *Omar, Senior Sales Executive* and the ground rule **"Describe observable changes only. Do not diagnose the person or use medical labels."**
3. Press **Open Stage 1**. Every group screen unlocks by itself with a **STAGE 1** splash: the **green dashboard** (Target 112%, Pipeline Strong, Attendance 98%, Escalations Low, Forecast Good). Each group chooses its **concern level (1 = No concern … 5 = High concern)**, writes its evidence, and presses **Send our answer**. **Its answer appears in your console by itself.**
4. Open **Stage 2**, **Stage 3**, **Stage 4** and **Stage 5** in the same way. The dashboard strip **stays green at the top of every stage**, while the **red signals pile up** below it. Stage 4 asks for the pattern (Energy, Connection, Efficacy) and Stage 5 for the work conditions (Workload, Control, Reward, Community, Fairness, Values).
5. Open the **Final question**: *"The dashboard is still green. Has your leadership response changed?"* (Yes / No / Not sure, and what they would do differently).
6. Open **Debrief** and project the **Debrief** page: every group's concern curve, the room average, the answers group by group, the work-condition counts and the final tally, next to the line that never left green. The closing message is at the bottom: **GREEN NUMBERS. RED SIGNALS. Current output can stay high while the cost of producing it is rising.**

On the console, **Trainer notes** (facilitator only) show the prompt for the stage that is open, for example *"Is high effort automatically a problem?"* at Stage 2. You can **edit any concern level** in the table; the change is sent to that group's screen.

## Game feel and sound
Each stage opens with a full-screen splash, screens slide in, the dashboard numbers count up, red signals appear one by one with a pulse, and the group's concern line draws itself. Stages 4 and 5 and the final question have a warmer splash. Sound is made of short synthesized beeps and is **on by default on every screen**: press **Sound on / Sound off** in the top bar to turn it off (remembered on that device). Browsers only allow sound after the first tap on the page. Devices set to "reduce motion" get no animations or splash.

## How the live connection works
A website on GitHub has no server, so the app sends tiny messages (group number, stage, answer) through the **free public relay ntfy.sh**, on a private topic built from your session code. Because of that:
- Use a **new session code for every session**.
- The relay keeps messages for about 12 hours. Reloading a page rebuilds the session from them.
- If a group is offline, the screen shows **Live sync: offline**. Each stage also has a **backup 4-digit code** on your console that unlocks it on that group's screen (their answer then has to be passed to you verbally or typed into the table).
- Please **rehearse once with two phones** before a live session.
- Advanced: open the site with `?relay=https://your-server/` to use your own ntfy server.

## Good to know
- Everything is saved in the browser of the device in use. *Reset session* clears the facilitator side (and creates a new session code); *Leave* clears a group device.
- The trainer notes are part of the page code, so this is a classroom tool, not a secure exam. Group devices only show the group pages.
- You can test the app offline by double-clicking `index.html` (live sync needs internet).

Built for the Skills Bank "People First Leadership for Sales Leaders" programme.
