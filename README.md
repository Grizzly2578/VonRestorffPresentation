# The Von Restorff Experience 🧠
https://grizzly2578.github.io/VonRestorffPresentation/

**An Interactive Psychology Presentation**

This project is a standalone, interactive web presentation designed to demonstrate the **Von Restorff Effect** (also known as the Isolation Effect). It uses visual experiments to prove to an audience that *items that stand out are more likely to be remembered.*

## 🚀 How to Run (No Internet Required*)

Since you aren't hosting this online, you can run it directly from your computer.

1. **Save the File:** Ensure you have the `index.html` file saved in a folder.

2. **Open it:** Right-click `index.html` and select **Open with Google Chrome** (or Edge/Safari).

3. **Presentation Mode:** Press `F11` (Windows) or `Cmd + Ctrl + F` (Mac) to go full screen for the best effect.

*> Note: The project uses Tailwind CSS and FontAwesome via CDN. You will need an active internet connection when you open the file for the styling and icons to load. Once loaded, it will stay working as long as you don't refresh without internet.*

## 🎤  Controls

Use this guide.

### 1. Introduction (The Hook)

* **Action:** Scroll to the top "Hero" section.

* **Say:** "We are constantly bombarded by information. Why do we remember some things and forget others? Today, I'm going to demonstrate the **Von Restorff Effect**—the psychological principle that humans are biologically wired to focus on the anomaly."

### 2. Experiment 01: Color Isolation

* **Action:** Click "Start Experiment" or scroll to Section 01.

* **Interact:** Click the **"Randomize"** button a few times.

* **Say:** "Scan this grid. Where do your eyes go? The red checkmark. This is the most basic form of isolation: **Contrast**. You didn't have to search for it; your brain found it for you before you even consciously decided to look."

### 3. Experiment 02: Motion Isolation

* **Action:** Scroll to Section 02. Point at the boring server log list.

* **Say:** "Now look at this data. It's boring. It's hard to spot the critical error."

* **Interact:** Click **"Start Motion"**.

* **Say:** "Even if you look away, your peripheral vision catches the movement. Our survival instincts prioritize motion over static text because motion usually implies a threat or a change."

### 4. Experiment 03: Visual Clarity (Focus)

* **Action:** Scroll to Section 03. Move your mouse around the black screen.

* **Say:** "We can also artificially create isolation. By blurring the 'noise,' we force the user to focus only on the 'signal.' This reduces Cognitive Load."

* **Interact:** Hover over the text to show the "flashlight" effect.

### 5. Experiment 04: The Memory Test

* **Action:** Scroll to Section 04.

* **Say:** "Does isolation actually help us *learn*? Let's test the class."

* **Interact:**

  1. Click **"Initialize Test"**.

  2. Let the timer run down (4 seconds).

  3. When the screen says "Time's Up," ask the class: **"Which file do you remember?"**

  4. They will shout out the odd item (e.g., "Nuclear Codes" or "Alien Signal").

  5. Click **"Reveal Answer"**.

* **Conclusion:** "You forgot the 10 boring files, but you remembered the unique one. That is the Von Restorff Effect."

### 6. Experiment 05: The Blink Test (Speed Run)

* **Action:** Scroll to Section 05.

* **Say:** "Does isolation work instantly? I'm going to flash an image for 200 milliseconds—literally the blink of an eye."

* **Level 1 (Color):** Keep it on Level 1. Click **"BLINK"**. Ask the class where the RED dot was. (They will know).

* **Level 2 (Shape):** Switch to Level 2. Click **"BLINK"**. Ask where the Triangle was. (Harder).

* **Level 3 (Emotion):** Switch to Level 3. Warn them this is "Impossible Mode." Click **"BLINK"**. Ask where the Sad Face was.

* **The Point:** "We spot color instantly. We spot shapes slowly. We spot meaning (emotion) slowest of all. Isolation works best when it is visual."

## 🛠️ Customization

If you want to change the "Odd items" in the memory test to something funnier for your specific class:

1. Open `index.html` in a text editor (like Notepad or VS Code).

2. Scroll to the bottom script section (around line 350).

3. Look for the `oddities` list:

   ```javascript
   const oddities = [
       { text: "☢️ NUCLEAR_CODES", icon: "fa-radiation" },
       { text: "YOUR_TEACHERS_NAME", icon: "fa-user" }, // <--- You can add this!
       ...
   ];
