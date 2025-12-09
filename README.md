# Local preview and testing

Follow these steps to pull the latest changes (including the new navigation bar) and preview the site locally.

## 1. Get the code
If you do not have the repository yet:
```bash
git clone https://github.com/lindaCai1997/lindaCai1997.github.io.git
cd lindaCai1997.github.io
```

If you already cloned it earlier, update to the latest version:
```bash
cd lindaCai1997.github.io
git pull
```

## 2. Start a local server
Use Python's built-in server to serve the static files (recommended so relative links and the footer include load correctly):
```bash
python -m http.server 8000
```
Keep the terminal open while the server is running.

## 3. Open the site in your browser
Visit:
```
http://localhost:8000/
```

## 4. Check the navigation bar
- The **Main** link returns you to the top of the page.
- The **Blogs** link scrolls to the "Blogs" section (look for the `Blogs` heading near the bottom of the page).
- Hover over links to see the subtle styling cues added in the recent change.

## 5. Stop the server
Press `Ctrl+C` in the terminal where the server is running.
