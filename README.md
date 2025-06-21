# Basic Calculator

## Overview
This is a simple web-based calculator built with HTML, CSS, and JavaScript. It supports basic arithmetic operations (addition, subtraction, multiplication, and division) with a clean, responsive interface. The calculator features a grid-based button layout, a display screen for user input and results, and a dark theme with an animated gradient background consistent with the provided landing page design.

## Features
- **Basic Arithmetic Operations**: Supports addition (+), subtraction (-), multiplication (×), and division (/).
- **Responsive Design**: Uses CSS Grid for button alignment, adaptable to various screen sizes.
- **Interactive Interface**: Includes buttons for digits (0-9), decimal point, operators, clear (C), and equals (=).
- **Error Handling**: Prevents division by zero with an alert message.
- **Animated Background**: Inherits the dynamic gradient background from the landing page for a cohesive look.
- **Hover Effects**: Buttons change color on hover for better user interaction.
- **Clear Functionality**: Resets the calculator to its initial state with the clear button.

## Technologies Used
- **HTML5**: For semantic structure and content.
- **CSS3**: For styling, including CSS Grid, custom properties (variables), and animations.
- **JavaScript**: For handling user input, calculations, and event listeners.
- **Font Stack**: Uses system fonts (`Segoe UI`, `Tahoma`, `Geneva`, `Verdana`, `sans-serif`) for consistent rendering.

## Setup Instructions
1. **Clone the Repository** (if hosted on GitHub):
   ```bash
   git clone https://github.com/Venkata-Sreenivas/your-repo-name.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd your-repo-name
   ```
3. **Open the Project**:
   - Open `index.html` in a web browser to use the calculator locally.
   - Alternatively, use a local server (e.g., `Live Server` extension in VS Code) for a better development experience.
4. **File Structure**:
   ```
   your-repo-name/
   ├── index.html           # Main HTML file with CSS and JavaScript
   └── README.md           # This file
   ```
   Note: The calculator is self-contained in a single `index.html` file, with inline CSS and JavaScript.

## Hosting
To host the calculator on GitHub Pages:
1. Push the repository to GitHub.
2. Go to the repository settings, enable GitHub Pages, and select the `main` branch (or `gh-pages` if preferred).
3. The calculator will be available at `https://your-username.github.io/your-repo-name`.

## Usage
- **Digits (0-9)**: Click to input numbers.
- **Decimal Point (.)**: Add a decimal to the current number (only one decimal per number).
- **Operators (+, -, ×, /)**: Select an operator to perform a calculation. The calculator stores the first operand and waits for the second.
- **Equals (=)**: Computes the result based on the selected operator and operands.
- **Clear (C)**: Resets the display and internal state to start a new calculation.
- **Error Handling**: An alert appears if you attempt to divide by zero, and the calculator resets.

## Customization
- **Colors**: Modify CSS variables in `:root` (e.g., `--primary-color`, `--button-hover`) to change the color scheme.
- **Button Layout**: Adjust the `grid-template-columns` or `gap` in the `.buttons` class to modify the grid layout.
- **Additional Features**: Extend the JavaScript to include advanced operations like percentage, square root, or memory functions.

## Known Issues
- The calculator supports only basic arithmetic operations; advanced functions (e.g., parentheses, exponents) are not implemented.
- Large numbers or long decimal results may overflow the display (limited by `text-overflow: ellipsis`).
- No keyboard input support; the calculator relies on mouse clicks.

## Future Improvements
- Add keyboard input support for accessibility and convenience.
- Implement additional operations (e.g., percentage, square root, or memory functions).
- Enhance the display to handle long numbers or scientific notation.
- Add unit tests for the JavaScript logic to ensure reliability.
- Integrate with a larger project (e.g., your landing page) by adding a navigation link.

## License
© 2025 My Website. All rights reserved.

## Contact
For questions or feedback, reach out via:
- [LinkedIn](https://www.linkedin.com/in/venkata-sreenivas529/)
- [Instagram](https://www.instagram.com/sreenivas___529/)
- [GitHub](https://github.com/Venkata-Sreenivas)
