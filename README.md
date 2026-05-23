# emmanuelbadmus.github.io

My personal website hosted on GitHub Pages.

## Tech Stack
- **HTML5**: Structured semantically for accessibility and SEO.
- **CSS3**: A lightweight, minimalist design with system-native fonts and automatic dark mode support.

## Customization
- **Change Content**: Modify the [index.html](file:///Users/emmanuelbadmus/.gemini/antigravity/scratch/emmanuelbadmus.github.io/index.html) file to update your bio, project links, or contact details.
- **Change Styling**: Modify the [style.css](file:///Users/emmanuelbadmus/.gemini/antigravity/scratch/emmanuelbadmus.github.io/style.css) file to customize colors, fonts, or layout.
- **Raw HTML Only**: If you prefer to have absolutely no design styling at all (pure default browser HTML), delete the `style.css` file and remove the following line from `index.html`:
  ```html
  <link rel="stylesheet" href="style.css">
  ```

## Publishing to GitHub Pages
To publish this website on your GitHub page (`https://emmanuelbadmus.github.io`), follow these steps:

1. Create a repository on GitHub named exactly **`emmanuelbadmus.github.io`**.
2. Run the following commands in this directory:
   ```bash
   # Add your GitHub repository as the remote
   git remote add origin https://github.com/emmanuelbadmus/emmanuelbadmus.github.io.git
   
   # Push your main branch to GitHub
   git push -u origin main
   ```
3. Once pushed, go to your repository settings on GitHub, navigate to **Pages** under the "Code and automation" sidebar, and verify that the build source is set to deploy from the `main` branch.
4. Your website will be live at `https://emmanuelbadmus.github.io`!
