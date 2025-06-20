<h1 align="center">Zemini</h1>
<div align="center">
    <a href="https://zen-browser.app/">
        <img width="120" alt="zen-badge-dark" src="https://github.com/user-attachments/assets/d6ab3ddf-6630-4062-92d0-22497d2a3f9a" />
    </a>
</div>

<h2 align="center">It was based on Gemini</h2>

![image](https://github.com/user-attachments/assets/0e597435-e617-4b8e-ae56-e6fd45df9c6b)


## ✨**What is Zemini?**
Zemini is a comprehensive theme pack for Zen Browser that fuses two signature styles into one cohesive UI overhaul:

* **Nebula:** a minimal theme made for Zen Browser which adds a lot of new animations, glass-like blur, UI changes, and more. It is inspired by glassmorphism and minimal gradients.
* **Personal Tweaks:** made by me, cool animations, general ui tweaks, Better font, text contrast, essetial tweaks, urlbar tweaks and more.


This theme customizes virtually every corner of Zen—tabs, toolbar, sidebar, context menus, pinned extensions, group tabs, the mini-player, URL bar, workspace buttons, and more—while still letting you tweak or disable any part if you prefer a lighter touch. ❤️

---
<h2 align="left">☄️ Installation:</h2>

###

## 💫 Sine Installation Guide (Recommended)

Follow these steps to install and apply the **Zemini** theme to Zen Browser:

1. 📝 **Install Sine**
   - Go to [Sine's Github](https://github.com/CosmoCreeper/Sine/tree/main) and follow its installation process.
   - This includes downloading and setting up FX-Autoconfig using the auto installer or manual installation.
   - Then setting up Sine.
   
2. 💎 **Installing Zemini through Sine's Marketplace**
   - Go to settings and click **Sine**, from there a Marketplace will load where Zemini will be shown as a mod to install.
   - Click the install button and Nebula should be installed as a mod.
   
   ![image](https://github.com/user-attachments/assets/a6a88c52-011f-46aa-b4be-1f8fd147ac8c)

3. ⚙️ **Enable Transparent Tabs**
   - Go to `about:config` in Zen.
   - Search for `browser.tabs.allow_transparent_browser`.
   - If visible, set it to `true`.

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
     /*  Zemini v2.4.0  */

     /* Nebula */
     @import "Zemini/Nebula/Nebula.css";

     /* Zemini */
     @import "Zemini/Personal-Tweaks/Zemini.css";
     ```
   * Open (or create) your `userContent.css` and add:

     ```css
     /*  Zemini v2.4.0  */

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

<h3 align="left">Install Mica For Everyone (ONLY FOR WINDOWS 11 USERS)</h3>

###

<p align="left">
• To get real backdrop filter transparency (note: that this method provides a better blur effect than the transparent zen extension by sameerasw), go to "https://github.com/MicaForEveryone/MicaForEveryone" and install the app.<br><br>
• Click the "+ Add new Rule" at the bottom left and "Add process rule" for "zen".<br><br>
• NOTE: If you have "Show Accent color on title bars and window borders" enabled in Windows 11 settings, please disable it for transparency to work.
</p>
<img width="900" src="https://github.com/user-attachments/assets/e867a04e-a8ba-4795-bada-e22ca92fc657" />
<br><br>
<p align="left">
• Also, please make sure your Zen theme color contrast is set to 0 for it to look transparent.
</p>
<img width="250" src="https://github.com/user-attachments/assets/aff8398c-9457-4842-bb44-32932cb99e23" />

###

<div align="left">
  <img height="400" src="https://github.com/user-attachments/assets/34f6965c-1bdc-4ea1-8605-efde3b898d23"  />
</div>

###

<p align="left">• Change the Backdrop type to Acrylic and enable blur behind in advanced options.<br><br>• Restart Zen and see how it looks.</p>

###
<h3 align="left">Install kwin-effects-forceblur (ONLY FOR KDE LINUX)</h3>

###
<p align="left">• To get real backdrop filter transparency, go to "https://github.com/taj-ny/kwin-effects-forceblur" and install the app.<br><br>• It's required to install 'kwin-effects-forceblur' from AUR then go to System Settings -> Windows -> Desktop Effecs, disable Blur and enable Better Blur and in Better Blur settings go to 'Force blur' tab and add 'zen' to list of classes of windows.<br><br>• NOTE: If Zen was installed from AUR as "zen-browser-bin", then in KDE put the name "zen-browser" for blur Here is the blur configuration: </p>

###

<div align="center">
  <img height="300" src="https://github.com/user-attachments/assets/8a19fcdd-acf9-4540-9833-ae0be3cce363"  />
</div>


---
<h3 align="left">Add the Firefox extension Bonjourrr</h3>

###

<p align="left">• Go to "https://addons.mozilla.org/en-US/firefox/addon/bonjourr-startpage/" and install this extension.<br><br>• The new tab must be replaced by this now. On the bottom right, you will see a settings button for new tab. Change the settings to these:</p>

| ![image](https://github.com/user-attachments/assets/e7e27035-6e2b-4006-abf7-091a103536f9) | ![image](https://github.com/user-attachments/assets/d8fb107f-1247-4a3e-8026-619311e2dee5) | ![image](https://github.com/user-attachments/assets/724abcd8-a9f0-4d76-a054-3d76e3c7db60) |
|-|-|-|

###

<p align="left">• In the section where it says "Add custom CSS", add this code to change font of newtab and make it transparent:</p>

```css
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300&display=swap');

body, h1, h2, h3, h4, h5, h6, p, span, div {
    font-family: 'Comfortaa', sans-serif !important;
    font-weight: 300 !important;
    letter-spacing: 0.015em;
    font-smooth: always;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transition: color 0.3s ease, text-shadow 0.3s ease;
}

/* Light mode */
@media (prefers-color-scheme: light) {
    body, h1, h2, h3, h4, h5, h6, p, span, div {
        color: #222222;
        text-shadow: 0 0 1px rgba(0, 0, 0, 0.15);
    }
}

/* Dark mode */
@media (prefers-color-scheme: dark) {
    body, h1, h2, h3, h4, h5, h6, p, span, div {
        color: #e0e0e0;
        text-shadow: 0 0 1px rgba(255, 255, 255, 0.2);
    }
}

h1 {
    font-weight: 400 !important;
    letter-spacing: 0.025em;
}

p {
    font-weight: 300 !important;
    line-height: 1.6;
    letter-spacing: 0.015em;
}
#background {
    background-color: transparent !important;
}
#background {background-image: none !important; background-color: transparent !important;}
   .tabbing {background-color: transparent !important;} 
    body {background-color: transparent !important;}
#background-wrapper {
    opacity: 0 !important;
}
```
###

---


<h3 align="left">Using pinned extensions</h3>

###

<p align="left">• First pin an extension normally, it should be somewhere in the top bar like default zen<br><br>• Now, right click on the sidebar and go to customize toolbar mode, from there drag the extension from the top bar to above essentials (or you can say below the URLbar) it would look a bit weird but press save changes and it should look perfect<br><br>• In my personal opinion, place the bonjourr extension above essentials so you can easily open a new tab by clicking it</p>


---

## Add the extension [Zen Internet by Sameerasw](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) (Optional)

---

## **Customization Tips**

* Prefer fewer animations? In `Nebula-config.css`, reduce the animation or even remove it if you really want.

Enjoy your freshly “zen-ified” browser! If you’d like further tweaks—whether lighter, darker, or more playful—just dive into the CSS or ask ChatGPT for custom snippets. 😊

# 🙌 Credits

Here are some awesome projects that inspired or contributed to this project:
*    🔗 [Lacuna by Tanay-Kar](https://github.com/Tanay-Kar/Lacuna)
*    🌐 [Natsumi Browser by greeeen-dev](https://github.com/greeeen-dev/natsumi-browser)
*    🧠 [ZenZero by sameerasw](https://github.com/sameerasw/ZenZero)
*    🧩 [Advanced Tab Groups by TFFC-Anoms12](https://github.com/TFFC-Anoms12/Advanced-Tab-Groups)
