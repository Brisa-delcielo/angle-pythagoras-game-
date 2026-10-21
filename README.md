# Angle & Pythagorean Game

A web-based educational game built with HTML5 Canvas and Vanilla JavaScript designed to practice and test geometry, trigonometry, and the application of the Pythagorean theorem on a 2D Cartesian plane.

---

## How to Play

1. **Enter Your Name:** Enter your name or nickname on the start screen to personalize your final certificate.
2. **Analyze the Target:** Each level displays the position of the cannon `(x, y)` and randomly generated targets on the board.
3. **Calculate the Angle:** Review the real-time distance metrics (Leg X, Leg Y, and Hypotenuse/Distance).
4. **Fire:** Enter the calculated angle (between 1° and 179°) and click **FIRE**.
5. **Earn Your Certificate:** Complete all 10 levels by hitting all target points to unlock and download a personalized Certificate of Honor in `.png` format.

---

## Main Features

* **Real-Time Mathematical Feedback:** Live calculations of cannon coordinates, target coordinates, leg lengths, and hypotenuse distance.
* **Progressive Difficulty:** Levels scale up to 4 simultaneous target points on different canvas boundaries.
* **Local Storage Integration:** Persists the player's name locally using `localStorage`.
* **Dynamic Canvas Certificate:** Generates a custom downloadable award upon completing the final level.
* **Zero External Dependencies:** Built with pure HTML5, CSS3, and JavaScript, requiring no bundlers or third-party libraries.

---

## Built With

* **HTML5:** Semantic layout and the `<canvas>` element for graphic rendering.
* **CSS3:** Monochromatic retro layout styling.
* **JavaScript (ES6):**
  * 2D graphic rendering (`CanvasRenderingContext2D`).
  * Basic trajectory movement vectors (`vx`, `vy`).
  * Collision detection using the Euclidean distance formula:
    $$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

