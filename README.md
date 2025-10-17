# CAPTCHA Solver Demo

This project provides a simple, single-file web application demonstrating a client-side CAPTCHA challenge and a mock solver interface. It's built with HTML, JavaScript, and styled using Tailwind CSS for a responsive design.

## Features

*   **Responsive UI:** Styled with Tailwind CSS for optimal viewing on various devices.
*   **Dynamic CAPTCHA Image:** Displays an image either from a `url` query parameter or defaults to a local `sample.png`.
*   **User Input:** An input field for users to enter their CAPTCHA solution.
*   **Verification Logic:** Client-side validation against a predefined solution (for demonstration purposes).
*   **Clear Feedback:** Provides immediate feedback on whether the CAPTCHA was solved correctly.

## How to Use

1.  **Save the files:** Save `index.html`, `README.md`, `LICENSE`, and `sample.png` into the same directory.
2.  **Open `index.html`:** Open the `index.html` file in your web browser.
3.  **Default Image:** By default, it will display the `sample.png` image.
4.  **Custom Image (via URL):** You can also specify a custom image URL using the `url` query parameter. For example:
    `index.html?url=https://example.com/some_captcha.png`
    *(Note: For security and browser limitations, external images might require CORS headers on the server serving the image, or the browser might block it.)*
5.  **Enter Solution:** Type "ADURS" (case-insensitive) into the input field and click "Submit CAPTCHA".

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **JavaScript:** Client-side logic for dynamic content and verification.
*   **Tailwind CSS:** Utility-first CSS framework for styling and responsiveness.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.