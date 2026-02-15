# Sakura - New Year Blessing Bomb 🧧

A high-performance, minimalist New Year blessing engine designed to deliver a massive "burst" of unique greetings directly to the user's screen.

## 🚀 The Philosophy (Linus Style)

"Talk is cheap. Show me the code." This project isn't about fancy frameworks or over-engineered bloat. It's about raw performance, data integrity, and a "good taste" UI.

- **Zero Wait**: No welcome screens, no useless buttons. Load the page, get the blessings. Immediately.
- **Data Integrity**: Uses a Fisher-Yates shuffle algorithm to ensure every single blessing is unique. No duplicates, no collisions.
- **Infinite Stack**: No arbitrary cleanup. The blessings pile up like real-world red envelopes, creating a high-density visual impact.
- **Spartan Design**: Minimalist window-style UI inspired by classic desktop environments.

## 🚀 Deployment (Server-side)

Since this is a pure static project (HTML/CSS/JS), it can be deployed anywhere without a backend.

### 1. GitHub Pages (Recommended)
1. Push this repository to GitHub.
2. Go to **Settings** > **Pages**.
3. Select the `main` branch and `/root` folder, then click **Save**.
4. Your site will be live at `https://<your-username>.github.io/Sakura/`.

### 2. Vercel / Netlify
1. Connect your GitHub repository to Vercel or Netlify.
2. It will automatically detect the static files and deploy them.
3. No build command or install command is needed.

### 3. Traditional Web Server (Nginx/Apache)
Simply upload all files to your server's web root (e.g., `/var/www/html`).
Example Nginx config:
```nginx
server {
    listen 80;
    server_name yourdomain.com;
    root /path/to/Sakura;
    index index.html;
}
```

## 🛠️ Technical Features

- **Burst Engine**: Delivers 20 unique pop-up windows per second until the entire blessing pool is drained.
- **Fisher-Yates Shuffle**: Pre-shuffles hundreds of unique Chinese New Year greetings to ensure non-repeating delivery.
- **Zero Dependencies**: Pure HTML5, CSS3, and Vanilla JavaScript. No React, no Vue, no garbage.
- **Draggable Windows**: Each blessing window is a separate DOM element with basic drag-and-drop support.

## 📦 How to Run

Simply serve the directory using any static web server.

```bash
# Example using Python
python -m http.server 8000
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Created with "Good Taste" by Linus (via AI Assistant).*
