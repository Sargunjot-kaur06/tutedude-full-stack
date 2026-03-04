# Task 4 – Image Container with Gradient Button

This project creates a fixed‑size container with an image and a gradient button, perfectly centered in the viewport without scrollbars. It demonstrates precise mathematical layout using `vw`/`vh` units and `box-sizing: border-box`.

## How to Run

1. **Download the files**  
   Ensure you have both `index.html` and `style.css` in the same folder.

2. **Open the HTML file**  
   - Double‑click the `index.html` file.  
   - Alternatively, right‑click and choose “Open with” your preferred browser (Chrome, Firefox, Edge, etc.).  
   - The page will open in your default web browser.

No server or build process is required – it’s pure HTML/CSS.

## Files

- `index.html` – Contains the document structure and the image source.
- `style.css` – Contains all styling rules, including the gradient backgrounds and the exact spacing calculations (25% left/right margins, 10% top/bottom margins).

## Expected Result

A landscape image fills the top portion of a white‑bordered box. Below it, a button with a yellow‑red‑green gradient background sits near the bottom, with the container’s gradient background visible in the small gap. The entire page fits exactly in the browser window – no scrolling.

## Notes

- The image URL is currently a placeholder; you can replace it with any image link.
- The button text can be changed by editing the `<button>` tag in the HTML.
- All measurements respect the `border-box` model, so the 2px border does not increase the container’s total size.
