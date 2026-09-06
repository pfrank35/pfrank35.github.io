# Portfolio / GitHub Pages

A simple living portfolio for school projects, experiments, and personal work.

## Files

- `index.html` — main portfolio page
- `style.css` — all styling

## Adding a project

The easiest way is to duplicate a project card in `index.html`:

```html
<article class="project-card">
  <a href="project-name.html" class="project-image">
    <img src="images/project-name.jpg" alt="Description of project">
  </a>
  <div class="project-info">
    <div class="project-meta">
      <span>2026</span>
      <span>•</span>
      <span>Fabrication</span>
    </div>
    <h3>My New Project</h3>
    <p>A short description of the project.</p>
    <a class="text-link" href="project-name.html">View project →</a>
  </div>
</article>
```

Create an `images` folder for project photos.

For a larger project, create a separate page such as `project-name.html`. This lets you document:

- What the project was
- The original assignment/problem
- Research
- Sketches and iterations
- Process photos
- Code/CAD files
- What went wrong
- What you learned
- Final result
- Links to GitHub or other files

## GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and `style.css`.
3. Add an `images` folder if needed.
4. In GitHub, open **Settings → Pages**.
5. Under the build/source settings, select the `main` branch and `/ (root)`.
6. Save.

Your site should then be available at your GitHub Pages address.

## First things to customize

Search `index.html` for:

- `Pierce Franklin`
- `YOUR_EMAIL@example.com`
- `YOUR_USERNAME`
- `Project Title`
- `Interactive Experiment`
- `Physical Prototype`

Replace those with your actual information and projects.
