![Darkened Stylus Edited](https://user-images.githubusercontent.com/78914154/191014782-882e8712-0aa4-441a-b7e4-cbb73d9e5fe6.png)

<details>
  <summary align="center">Nexus Mods Theme</summary>
  <br>

<h1 align="center">Preview</h1>

![Main Game Mod Page](https://user-images.githubusercontent.com/78914154/191073321-ef99c710-3985-4971-b2e7-11fc717afae7.png)

<h1 align="center">📌 Information</h1>

### 📥 Installation
Make sure you have the Stylus browser extension installed   
    - **[Chrome Webstore](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)**  
    - **[Firefox Addons](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)**  
After installing, head over to [this link](https://userstyles.world/style/6620/nexus-mods-darkened) and click the "install" button. 
When it redirects you click "Install Stylus" button at the top left of that page.  
    - Optional: **[Nexus no wait](https://greasyfork.org/en/scripts/394039-nexus-no-wait)** | You'll need TamperMonkey extension for this to work.  

### ✅ Features
* ✔️ Good ol' darkness
* ✔️ Optional Scrollbars
* ✔️ Optional Compact Mode
* ❌ Can't change the colours of particular stuff unless you know what you're looking for
* ⭕ Work in progress and "should" stay up-to-date
* 🌟 List > Tiles

<details>
  <summary align="center">📜 Configurable & Extra's</summary>
  <br>

<h3 align="center">⌛ Extra Information</h3>

- You can disable the whole "Compact" section to make Nexus look somewhat normal but with Darkened's colour scheme  
- Switch between the display modes -> Tiles & List on Nexus (Tiles is the best in my opinion)  

<h3 align="center">⌨ Variables</h3>

```css
:root {
    --Hot-Mods: flex;  /* none = off, flex = on | Example: https://www.nexusmods.com/skyrim */
    --Premium-Banner: none; /* none = off, flex = on | Example: https://www.nexusmods.com/eldenring */
    --Collection-banner: flex; /* none = off, flex = on | Example: https://www.nexusmods.com/skyrim */
    --Top-Searchbar-Icon: none;  /* none = off, flex = on */
    --footer-Main: none; /* none = off, grid = on | Stats, Support, etc */
    --footer-social: none; /* none = off, grid = on | Discord, Twitter, Facebook, etc */
    --footer-ToS: none; /* none = off, flex = on | Copyright acts, Terms of Service & Privacy Policy */
    --Wrapper: 1920px; /* Inherit = max-content?, Default: 1340px */
    --Tile-Description-Height: 180px;
    --Mod-Tiles: 4;
    --Mod-Tiles-Home-Page: 7; /* Change this when you're on display mode "List" NOT "Tiles" */
    --Filter-Order: none; /* none = off, inherit = on */
    --Filter-Show-Premium-Only: none; /* none = off, inherit = on */

    /* Normal NexusMods colour imo  */
    --theme-primary: #D98F40;
    --theme-primary-translucent: #da8e35d8;
    --theme-secondary: #b4762c;
    --theme-dark: #C87B28;
}
body.scheme-theme-ReskinBlue { /* Example: https://www.nexusmods.com/skyrim/mods/3863 */
    --theme-primary: #57a5cc;
    --theme-primary-translucent: #57a5ccd8;
    --theme-secondary: #4584a3;
    --theme-dark: #356983;
}
body.scheme-theme-Sepia { /* Example: https://www.nexusmods.com/darksouls3/mods/310 */
    --theme-primary: #a5704f;
    --theme-primary-translucent: #a5704fd8;
    --theme-secondary: #9a7d6b;
    --theme-dark: #604331;
}
```

<h3 align="center">Optional List & Tile version -> change the "--Mod-Tiles" to your liking </h3>

<div align="center">

https://user-images.githubusercontent.com/78914154/191626228-b5b0e9ec-dd0b-4763-a289-f3bf144dc870.mp4

</div>

</details>


<h1 align="center", margin= "0">📷 More Screenshots</h1>

<h4 align="center">(Previews/screenshots may become out-of-date at some point)</h4>

<h3 align="center">Main Page</h3>

![Main Page](https://user-images.githubusercontent.com/78914154/191014886-03e56aec-4291-40fa-8afd-c33daee1d757.png)

<h3 align="center">Main Game Home Page</h3>

![Main Game Home Page](https://user-images.githubusercontent.com/78914154/191014940-bcfc8697-d027-4436-9f24-5823cc89ade1.png)

<h3 align="center">Game Mods Page (Grid)</h3>

![Grid Game mods page](https://user-images.githubusercontent.com/78914154/192757905-672866e6-2af3-43be-a122-b790ced1d6bb.png)

<h3 align="center">Main Game Home Page Compact (Grid)</h3>

![Main Game Home Page Version 2](https://user-images.githubusercontent.com/78914154/192758014-bba9180a-bd5c-4d34-8f3f-78380106c631.png)

</details>
