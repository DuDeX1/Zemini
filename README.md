<h1 align="center">Zemini</h1>
<div align="center">
    <a href="https://zen-browser.app/">
        <img width="120" alt="zen-badge-dark" src="https://github.com/user-attachments/assets/d6ab3ddf-6630-4062-92d0-22497d2a3f9a" />
    </a>
</div>

<h2 align="center">It was based on Gemini</h2>

![image](https://github.com/user-attachments/assets/ef394c98-7319-4ea4-878c-6c3004728371)


## ✨**What is Zemini?**
Zemini is a comprehensive theme pack for Zen Browser that fuses two signature styles into one cohesive UI overhaul:

* **Nebula:** a minimal theme made for Zen Browser which adds a lot of new animations, glass-like blur, UI changes, and more. It is inspired by glassmorphism and minimal gradients.
* **Personal Tweaks:** made by me, cool animations, general ui tweaks, Better font, text contrast, essetial tweaks, urlbar tweaks and more.


This theme customizes virtually every corner of Zen—tabs, toolbar, sidebar, context menus, pinned extensions, group tabs, the mini-player, URL bar, workspace buttons, and more—while still letting you tweak or disable any part if you prefer a lighter touch. ❤️

---

## 🚀 **Installation Guide** (Windows, macOS, and Manual Linux)

1. 📁 **Create the Chrome Folder**
   If you haven’t already, follow the \[Zen Live Editing Guide] to locate or create your `chrome/` directory inside your Zen profile.

2. 📦 **Download & Extract**

   * Download the `Zemini.zip` from the latest release.
   * Extract it so you have a top-level `Zemini/` folder plus two CSS files:

     ```
     userChrome.css
     userContent.css
     ```
   * Move **both** the `Zemini/` folder and those two CSS files into your `chrome/` directory.

3. 🧩 **Apply the Theme**
   You have two options:

   **Option A – Manual Imports**

   * Open your existing `userChrome.css` and add:

     ```css
     /*  Zemini v2.0.0  */

     /* Nebula */
     @import "Zemini/Nebula/Nebula.css";

     /* Zemini */
     @import "Zemini/Personal-Tweaks/Zemini.css";
     ```
   * Open (or create) your `userContent.css` and add:

     ```css
     /*  Zemini v2.0.0  */

     /* Nebula */
     @import "Zemini/Nebula/Nebula-content.css";
     ```

   **Option B – Use the Provided Files**

   * Simply replace your existing `userChrome.css` and `userContent.css` in the `chrome/` folder with the ones from the ZIP, which already include all necessary imports.

4. 🔄 **Restart Zen**
   Close and reopen Zen Browser to see all the new UI changes in action.

---

## ⚙️ **Enable Transparent Tabs**
To let the background bleed through your tabs (for that true glass effect):

1. In the address bar, go to `about:config`.
2. Search for `browser.tabs.allow_transparent_browser`.
3. If it appears, double-click to set it to **true**.

---

## Add the extension [Zen Internet by Sameerasw](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) (Optional)

---

## **Customization Tips**

* Prefer fewer animations? In `Nebula-config.css`, reduce the animation or even remove it if you really want.

Enjoy your freshly “zen-ified” browser! If you’d like further tweaks—whether lighter, darker, or more playful—just dive into the CSS or ask ChatGPT for custom snippets. 😊



