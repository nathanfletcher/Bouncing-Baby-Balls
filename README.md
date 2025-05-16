# Bouncing Baby Balls

## Description

"Bouncing Baby Balls" is an interactive web application that simulates colourful balls bouncing within a confined space. This is mainly to keep focus of your young one focused and help with gentle sensory stimulation. It allows parents to customise the animation, including the number and size of balls, and features sound effects for collisions and optional background music. I built it for my nephews and nieces, and kids, so I would be updating it as I learn more about how to safely guide attention and neural stimulation.

**Key Features:**

*   **Interactive Animation:** Watch balls bounce and collide realistically.
*   **Customization via Modal (🔧):**
    *   Set the number of red and black balls (0-10 each).
    *   Adjust the ball size (radius).
    *   Toggle "Boop" sound effects for collisions.
    *   Play background music by providing a URL.
*   **Collision Physics & Sound:** Balls collide with each other and the canvas walls, triggering "boop" sounds using Tone.js.
*   **User Controls:**
    *   **Start / Stop ⏯️:** Toggles the animation (also `Spacebar`).
    *   **Randomize:** Resets the animation with a new random set of balls.
    *   **Configure (Esc) 🔧:** Opens a modal for detailed settings.
    *   **Full Screen:** Toggles full-screen mode for the animation canvas.
*   **Responsive Design:** The canvas adapts to different window sizes.

---

## Screenshots

This is a great place to showcase your application! Consider adding screenshots like:

1.  **Main Animation View:**
    *   <img width="1353" alt="Screenshot 2025-05-16 at 3 10 31 PM" src="https://github.com/user-attachments/assets/a4454ffd-83f9-4ec3-b686-58f9849320e1" />

    `<!-- !Main Animation View -->`

2.  **Configuration Modal:**
    *   <img width="1331" alt="Screenshot 2025-05-16 at 3 15 23 PM" src="https://github.com/user-attachments/assets/0ebe02be-6afd-4ca6-b15f-59f81c9fefe5" />

    `<!-- !Configuration Modal -->`

3.  **(Optional) Full Screen Mode:**
    *   <img width="1719" alt="Screenshot 2025-05-16 at 3 16 05 PM" src="https://github.com/user-attachments/assets/27a4dbe8-5ae8-48cc-ab19-aafe7a3118c6" />

    `<!-- !Full Screen View -->`

---

## How to Run Locally

This application is a single HTML file and can be run directly in your web browser.

1.  **Download/Save:**
    *   Ensure you have the `index.html` file.

2.  **Open in Browser:**
    *   Simply open the `index.html` file with any modern web browser (e.g., Google Chrome, Mozilla Firefox, Safari, Microsoft Edge).
    *   You can usually do this by double-clicking the file, or right-clicking it and selecting "Open with..." and choosing your preferred browser.

3.  **Interact:**
    *   Once loaded, click the **"Start / Stop ⏯️"** button or press the **`Spacebar`** to begin the animation.
    *   Use the other control buttons to randomize, configure, or enter full-screen mode.
    *   Press the **`Esc`** key to open or close the configuration modal.

**Requirements:**

*   A modern web browser with JavaScript enabled.
*   An internet connection is needed for:
    *   Loading the Tone.js library (from a CDN).
    *   Playing background music if you provide an online URL.
    *   Loading the "Inter" font from Google Fonts.

---

## Project Structure

*   `index.html`: The main file containing all HTML structure, CSS styles, and JavaScript logic.

---

#### ToDo:
*  Add an interruption of some sort to break lengthy screen times
