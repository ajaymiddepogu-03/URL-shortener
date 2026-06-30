# URL Shortener

## Project Description
This is a simple URL Shortener web application built using HTML, CSS, and JavaScript. It allows users to enter a long URL and generates a random short URL for display. This project is designed for learning front-end web development concepts.

## Features
- Enter a long URL.
- Generate a random short URL.
- Click the displayed short URL to open the original website.
- Responsive and user-friendly interface.
- Built using pure HTML, CSS, and JavaScript.

## Technologies Used
- HTML5
- CSS3
- JavaScript (Vanilla JS)

## Project Structure
```
URL-Shortener/
│── index.html
│── README.md
```

## How It Works
1. Enter a valid URL in the input box.
2. Click the **Shorten URL** button.
3. A random 6-character code is generated.
4. The application displays a short URL in the format:
   ```
   https://short.ly/abc123
   ```
5. Clicking the generated link opens the original URL.

## Note
This project is a front-end demonstration only. The generated short URL is **not stored in a database** and is **not a real shortened link**. Every time the page is refreshed, previously generated URLs are lost.

## Future Improvements
- Integrate a backend using Node.js, PHP, or Python.
- Store URLs in a database such as MySQL or MongoDB.
- Generate permanent short URLs.
- Add Copy to Clipboard functionality.
- Track the number of clicks for each shortened URL.
- Validate URLs before shortening.

## Author
Developed by **Ajay Middepogu**
