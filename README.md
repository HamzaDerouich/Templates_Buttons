# Animated Buttons

A collection of animated button templates built with HTML, CSS, and JavaScript using keyframes animations.

## Preview

![Button Preview](path-to-image.gif) *(Replace with an actual preview image or GIF)*

## Features

- Smooth animations using CSS keyframes
- Multiple button styles
- Responsive design
- Lightweight and easy to customize

## Technologies Used

- HTML
- CSS (Keyframes animations, transitions)
- JavaScript (Optional: For interactive behaviors)

## Project Structure

Each button template is stored in a separate folder:
```
Animated-Buttons/
│── Template_Button_1/
│   ├── index.html
│   ├── styles.css
│   ├── script.js
│── Template_Button_2/
│   ├── index.html
│   ├── styles.css
│   ├── script.js
│── ...
```

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/animated-buttons.git
   ```
2. Navigate to the desired template folder:
   ```sh
   cd Template_Button_1
   ```
3. Open `index.html` in your browser.

## Usage

To use a button template in your project:

1. Copy the contents of the desired `Template_Button_X` folder.
2. Include the CSS file in your HTML:
   ```html
   <link rel="stylesheet" href="styles.css">
   ```
3. Add a button element with the appropriate class:
   ```html
   <button class="animated-button">Click Me</button>
   ```
4. (Optional) Include JavaScript for additional interactions:
   ```html
   <script src="script.js"></script>
   ```

## Customization

You can modify the animations in `styles.css` by adjusting the `@keyframes` values.

Example animation snippet:
```css
@keyframes bounce {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-10px);
  }
}

.animated-button {
  animation: bounce 0.5s ease-in-out infinite;
}
```

## Contributing

Feel free to fork this repository and submit pull requests with improvements!

## License

This project is licensed under the MIT License.

---

Enjoy coding! 🚀

