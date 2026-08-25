<img src="./logo_light.png#gh-dark-mode-only" alt="Project logo" width="200"> <img src="./logo_dark.png#gh-light-mode-only" alt="Project logo" width="200">

# **OpenSCUBA**

### **Overview**
The presented project consists of a [Three.js](https://threejs.org/)-based interactive 3D SCUBA diving experience. It takes inspiration from the [*Endless Ocean*](https://nintendo.fandom.com/wiki/Endless_Ocean_(series)) series by [ARIKA](https://en.wikipedia.org/wiki/Arika) and aims to be an open-source alternative that captures its characteristic chill underwater style and vibe.

Further details about the project's features and their implementation are available in the [technical report](./report.pdf).

### **How to Play**
The project is runnable directly from the browser at this [link](https://sapienzainteractivegraphicscourse.github.io/final-project-astrographics_industries/).

The **controls** are the following:
- Use the **Mouse Cursor** to look around;
- Hold the **Left Mouse Button** to move;
- Press the **F key** to turn the flashlight on/off;
- Press the **H key** to show/hide the FPS counter.

Any type of feedback is greatly appreciated!

### **How to Build and Run Locally**

1. **Install Node.js** (skip if already installed)
   
   1. Follow the [official installation instructions](https://nodejs.org/en/download).

   2. Verify that Node.js is installed correctly:
      ```bash
      node --version
      ```

2. **Clone the Repository**
    - HTTPS:
        ```bash
        git clone https://github.com/SapienzaInteractiveGraphicsCourse/final-project-astrographics_industries.git
        ```
    - SSH:
        ```bash
        git clone git@github.com:SapienzaInteractiveGraphicsCourse/final-project-astrographics_industries.git
        ```

3. **Enter the Repository Folder**
    ```bash
    cd ./final-project-astrographics_industries
    ```

4. **Install the Required Dependencies**
   ```bash
   npm install
   ```

5. **Run the Local Server**
   ```bash
   npx vite
   ```

6. **Open the App in a Browser**

   Navigate to [`http://localhost:5173`](http://localhost:5173).

   If the terminal displays a different port, navigate to the URL shown there instead.

### **Assets Credits**
#### 3D Models
- **Scuba Diver:** "[Nanando diver - Underwater](https://skfb.ly/oH88H)" by Marco Lopez, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).

- **Marine Creatures:**
    - "[Emperor Angelfish (Update v2)](https://skfb.ly/pGOW6)" by Mikhail Nesterov, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
    - "[coral fish](https://skfb.ly/JKRo)" by polyplant3d, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
    - "[Model 99A - Whale Shark](https://skfb.ly/oLzqI)" by DigitalLife3D, licensed under [Creative Commons Attribution-NonCommercial](http://creativecommons.org/licenses/by-nc/4.0/).
    - "[Killer Whale](https://skfb.ly/6SI7C)" by Trouvaille, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
    - "[Manta Ray Birostris](https://skfb.ly/FDy8)" by Violaine, licensed under [CC Attribution-NonCommercial-ShareAlike](http://creativecommons.org/licenses/by-nc-sa/4.0/).
- **Scenery:**
    - "[William H McAllister Tugboat 1963](https://skfb.ly/pzBq8)" by garyle802, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
    - "[fish tank ornament](https://skfb.ly/oU7xw)" by kokfyt, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
    - "[Rock Mountain with cave (realistic version)](https://skfb.ly/pK9UN)" by Jungle Jim, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
    - "[Artificial reef, Prado, Marseilles, France](https://skfb.ly/6WUwU)" by Septentrion, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
    - "[Stránská rock 1](https://skfb.ly/69Zp7)" by 3dhdscan, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
    - "[NGI 000 - WP_A_8989](https://skfb.ly/pAA9X)" by VIRKM, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
    - "[Kelp Plant](https://skfb.ly/6yDHp)" by maxliebscher, licensed under [CC Attribution-NonCommercial-ShareAlike](http://creativecommons.org/licenses/by-nc-sa/4.0/).
    - "Flat Large Rock" (used as corals base rock), generated with Meshy AI.
    - **Corals:**
        - "[Giant barrel sponge monitoring DAX-AQS1-2019](https://skfb.ly/6SK6T)" by Lauren Olinger PhD, licensed under [Creative Commons Attribution-NonCommercial](http://creativecommons.org/licenses/by-nc/4.0/).
        - "[Pocillopora eydouxi](https://skfb.ly/AwTZ)" by thehydrous, licensed under [Creative Commons Attribution-NonCommercial](http://creativecommons.org/licenses/by-nc/4.0/).
        - "[Coral Piece](https://skfb.ly/6BG6y)" by Sharon Kunne, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
        - "[Fan Coral Med](https://skfb.ly/oyyOH)" by Valery\.Li, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
        - "[crescent moon coral](https://skfb.ly/oSIDX)" by gavinpgamer1, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
        - "[Spined Sea Coral](https://skfb.ly/6wBzZ)" by RubaQewar, licensed under [Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).

#### Sounds
- **Music:**
    - "Deep Ocean Dream", generated with Suno AI (Model v4).
- **Sound Effects:**
    - "[Underwater Deep](https://pixabay.com/sound-effects/film-special-effects-underwater-deep-572427/)" by u_xg7ssi08yr from Pixabay.
    - "[Scuba_bubbles.mp3](https://freesound.org/s/634225/)" by sbvitug, licensed under [Creative Commons 0](https://creativecommons.org/publicdomain/zero/1.0/).
    - [Loading Screen UI Click](https://pixabay.com/sound-effects/film-special-effects-video-game-bonus-323603/) by Universfield from Pixabay.
    - [Splash Sound](https://pixabay.com/sound-effects/nature-water-splash-02-352021/) by Universfield from Pixabay.
    - [Flashlight Click](https://pixabay.com/sound-effects/film-special-effects-flashlight-102291/) by morganpurkis (Freesound) from Pixabay.

### **Licensing**
This project is licensed by its author under the [Creative Commons Attribution-NonCommercial-ShareAlike](http://creativecommons.org/licenses/by-nc-sa/4.0/) license: anyone is free to use and edit it, provided that the proper credits are given and that no commercial use is made from it.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Cc-by-nc-sa_icon.svg/120px-Cc-by-nc-sa_icon.svg.png" alt="drawing" width="100"/>