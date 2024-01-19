# Analog Clock Naruto

An analog clock with a Naruto theme for your project.

![Analog Clock Naruto]( https://alwindonald.github.io/analog-clock-naruto/)

## Installation

You can easily integrate the analog clock into your project by following these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/analog-clock-naruto.git
    ```

2. **Include the Required Files:**

    Include the necessary files in your project:

    - `analog-clock-naruto.js`
    - `analog-clock-naruto.css`
    - `naruto-theme.css`

3. **Add HTML Markup:**

    Include the clock in your HTML file:

    ```html
    <link rel="stylesheet" href="analog-clock-naruto.css">
    <link rel="stylesheet" href="naruto-theme.css">
    <script src="analog-clock-naruto.js"></script>

    <div id="analog-clock"></div>
    ```

4. **Initialize the Clock:**

    Initialize the clock in your JavaScript file:

    ```javascript
    // Make sure the DOM is ready
    document.addEventListener('DOMContentLoaded', function () {
        // Initialize the clock
        AnalogClockNaruto.init('analog-clock');
    });
    ```

## Customization

You can customize the appearance and behavior of the analog clock by modifying the provided CSS files or by creating your own styles.

## License

This analog clock is licensed under the [MIT License](LICENSE).

