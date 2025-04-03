# Simple 2-File Link-in-Bio Template ✨

Create a clean, beautiful, and responsive link-in-bio landing page with just **two files**: `index.html` and `style.css`. Perfect for Instagram, Twitter, TikTok, or anywhere you want to share multiple links without complex setups.

This template is easily customizable via CSS variables, allowing for different themes with the same HTML structure.

## What it looks like

See the template in action with two different styles:

**1. Default Gradient Theme:**
![Default Gradient Theme Screenshot](https://ibb.co/gFMhKH1N)

**2. You Can Also Go with Dark Theme:**
![Dark Tech Theme Screenshot](https://ibb.co/yF5rqQ0r)

## Features

*   **Minimalist:** Built with only `index.html` and `style.css`. No frameworks, no JavaScript needed.
*   **Easy Customization:** Modify colors, fonts, and layout quickly by editing CSS variables. Create entirely new looks just by changing the styles!
*   **Responsive:** Looks great on desktops, tablets, and mobile devices.
*   **Profile Section:** Space for profile picture, name/brand, and a short bio.
*   **Link Buttons:** Clear buttons for your important links.
*   **Social Media Icons:** Optional footer section for social profiles (uses Font Awesome).
*   **Lightweight & Fast:** Loads quickly.
*   **Deploy Anywhere:** Host easily on GitHub Pages, Netlify, Vercel, or any static web host.

## Getting Started

1.  **Download/Clone:** Get the files from this repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
    Or download the ZIP file. You'll primarily work with `index.html` and `style.css`.

2.  **Open Locally:** Open the `index.html` file in your web browser to preview the page.

## Customization

Customizing the template involves editing the HTML for content and the CSS for appearance. Look for comments marked `<!-- ☆ CUSTOMIZE: ... -->` in `index.html` and `/* --- ☆ CUSTOMIZATION VARIABLES --- */` in `style.css`.

### 1. Content (`index.html`)

*   **Page Title:** Change the `<title>` tag.
*   **Profile Picture:** Replace `placeholder-profile.jpg` in the `<img>` tag. Place your image file in the same directory or provide the correct path.
*   **Profile Name:** Edit the text inside the `<h1>` tag.
*   **Profile Bio:** Edit the text inside the `<p>` tag.
*   **Links:**
    *   Edit the `href="..."` for each `<a>` tag within the link list (`<ul class="links">`).
    *   Change the link text.
    *   Add or remove `<li>...</li>` items.
*   **Social Media Icons:**
    *   Edit the `href="..."` for each social link `<a>` tag in the footer (`<footer class="socials">`).
    *   Ensure the Font Awesome link is in the `<head>` if using icons.
    *   Add/remove icons using Font Awesome classes (e.g., `<i class="fab fa-github"></i>`).

### 2. Appearance (`style.css`)

*   **Easy Themeing:** The easiest way to change the look is by modifying the CSS variables within the `:root { ... }` block at the top of `style.css`. *You can create completely different themes (like the demos above) just by changing these variables.*
    *   `--background-start`, `--background-end`: Gradient background colors.
    *   `--card-background`: Main card background color and transparency.
    *   `--text-color`, `--heading-color`: Text colors.
    *   `--button-background`, `--button-text-color`, `--button-hover-background`: Button styling.
    *   `--social-icon-color`, `--social-icon-hover-color`: Social icon styling.
    *   `--font-family`: Font choice (ensure it's imported or web-safe).
    *   `--card-shadow`, `--card-border-radius`, `--button-border-radius`, `--profile-pic-size`, `--profile-pic-border`: Adjust shadows, corners, and sizing.
*   **Advanced Styling:** Modify the CSS rules below the variables section for finer control.

## Deployment

Host this static site easily and often for free:

*   **GitHub Pages:** Push your `index.html`, `style.css`, and image files to a GitHub repo and enable Pages in settings.
*   **Netlify / Vercel:** Drag and drop your project folder or link your Git repository.
*   **Other Static Hosts:** Cloudflare Pages, Surge.sh, standard web hosting, etc.

## License

This project is licensed under the MIT License.

---

*Built simply, for easy sharing. BY Bilbo-22 and Gemini*

