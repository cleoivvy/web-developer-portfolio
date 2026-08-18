# Web Developer Portfolio

This is a simple static website. You can edit it with any code editor such as VS Code, Sublime Text, or Notepad++.

## Files

- `index.html` - page content, sections, project samples, links, and text
- `styles.css` - colors, spacing, layout, typography, and responsive design
- `script.js` - mobile menu behavior

## How to edit locally

1. Open this folder on your computer:

   `C:\Users\clara\Documents\Codex\2026-07-06\i\outputs\web-developer-portfolio`

2. Open the folder in your editor.

3. Open `index.html` in your browser to preview the website.

4. Edit `index.html` to update:

   - Your name
   - Job title
   - Bio
   - Project names
   - Work sample descriptions
   - Live site links
   - GitHub/code links
   - Email address
   - Social links

5. Edit `styles.css` to update:

   - Colors
   - Font sizes
   - Spacing
   - Section backgrounds
   - Card styles

6. Refresh the browser after every change.

## Important places to customize

### Name and title

Search in `index.html` for:

`Jordan Blake`

Replace it with your own name.

### Email

Search for:

`hello@jordan.dev`

Replace it with your own email address.

### Projects

Search for:

`Flow With Pride`

The first project is already filled in with your Flow With Pride NGO website.

Search for:

`Add Your Next Project`

Then replace the placeholder project cards with your other real projects when you are ready.

Each sample card has:

- A project title
- A project type
- A short description
- A live website link
- A code/GitHub link

### Links

Search for:

`href="#"`

Replace each `#` with your real project URL or GitHub URL.

Example:

```html
<a href="https://your-project.com">Live site</a>
<a href="https://github.com/yourname/your-project">Code</a>
```

## Adding screenshots

Put your project image inside the same folder, for example:

`project-one.png`

For the Flow With Pride sample, copy your screenshot into the `assets` folder and name it:

`flow-with-pride-screenshot.png`

For the Sparkle Hub Cleaning sample, the screenshot should be in the `assets` folder and named:

`sparkle-hub-preview.png`

Then replace this:

```html
<div class="sample-preview">
  <span>Screenshot</span>
</div>
```

With this:

```html
<div class="sample-preview">
  <img src="project-one.png" alt="Screenshot of Project Name One" />
</div>
```

Then add this to `styles.css`:

```css
.sample-preview img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

## Opening the site

Double-click `index.html`, or right-click it and choose your browser.

Because this is a static website, you do not need npm, Node.js, or a server to edit it.
