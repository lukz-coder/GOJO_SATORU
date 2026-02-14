# Jujutsu Kaisen: Gojo Satoru — Cursed Technique Visualizer

**SAT0RU SYSTEM** is an interactive WebAR experience that brings Gojo Satoru's limitess cursed techniques to life using your webcam and hand gestures. Powered by **Three.js** and **MediaPipe Hand Tracking**.

![Demo](https://github.com/justHman/GOJO_SATORU/raw/main/demo.gif)
*(Note: Add a demo gif if available)*

## ✨ Features & Techniques

Using advanced particle systems and post-processing (Bloom, Shake), the system visualizes:

### 🔴 Cursed Technique Reversal: RED (赫)
*   **Effect:** A violent, jagged red sphere of repulsive force.
*   **Trigger:** Extend **Left Index Finger**.
*   **Visuals:** White-hot core, red lightning sparks, screen shake.

### 🔵 Cursed Technique Lapse: BLUE (蒼)
*   **Effect:** A chaotic blue sphere of attractive force.
*   **Trigger:** Extend **Right Index Finger**.
*   **Visuals:** Electric Blue + Cyan vortex, implosion effect.

### 🟣 Hollow Technique: PURPLE (茈)
*   **Effect:** The ultimate destruction technique composed of Blue and Red.
*   **Trigger (Fusion):** Bring **Left & Right Index Fingers** together to merge Red and Blue.
*   **Trigger (Charge & Fire):** Hold **3 Fingers** (Thumb, Index, Middle) on one hand to charge the Purple Ball, then **Snap** to fire.
*   **Visuals:** Massive Purple sphere, high intensity bloom, debris particles. Firing direction depends on hand used.

### 🌌 Domain Expansion: UNLIMITED VOID (無量空処)
*   **Effect:** A metaphysical domain of infinite information.
*   **Trigger:** **Cross Fingers** (Index + Middle) on either hand.
*   **Visuals:**
    1.  **Warp Speed Intro:** Uninterruptible hyperspace travel with horizontal light streaks.
    2.  **Black Hole:** A massive accretion disk and event horizon forms in the center.
    3.  **Background:** Camera dims to black to emphasize the cosmos.

## 🛠️ Installation & Usage

1.  **Clone the repository**
    ```bash
    git clone https://github.com/justHman/GOJO_SATORU.git
    cd GOJO_SATORU
    ```

2.  **Install dependencies** (optional, for package-lock.json)
    ```bash
    npm install
    ```

3.  **Run the project**
    *   Simply open `index.html` in a modern browser (Chrome/Edge recommended).
    *   OR run a local server:
        ```bash
        npx http-server .
        ```

## ⚙️ Configuration

You can customize effects in `config.js`:
*   **Particle Counts**: Adjust `BALL_COUNT` for performance.
*   **Colors & Sizes**: Tweak `RED`, `BLUE`, `PURPLE` settings.
*   **Warp Speed**: Change `warpSpeed`, `warpDuration` in `VOID` section.

## 🤝 Contributing

Pull requests are welcome!

## 📜 License

[ISC](LICENSE)
