# Resume Website

A dark & sleek personal resume website built with HTML, CSS, and vanilla JavaScript.

## Files

- `index.html` — Main page structure and content
- `style.css` — All styles, animations, and responsive layout
- `script.js` — Custom cursor and scroll-reveal animations

## How to Customize

### Personal Info
Open `index.html` and update:
- **Name**: Replace `Alex Morgan` and `AM` initials
- **Job Title**: Find `Senior Software Engineer`
- **Bio**: Update the `.hero-bio` paragraph
- **Stats**: Update years of experience, projects, etc.
- **Location**: Change `San Francisco, CA`
- **Email**: Replace `alex@example.com`
- **Social links**: Update the `href` values in `.social-links`

### Work Experience
Each job is a `.timeline-item` block. Copy/paste to add more. Update:
- Date range in `.timeline-meta`
- Title, company, description in `.timeline-content`
- Tech tags in `.tags`

### Projects
Each project is a `.project-card`. Update title, description, type, and the `href` link.

### Skills
Update the `<li>` items in each `.skill-group`.

### Education
Update `.edu-item` with your school and dates.

## Hosting
Upload all three files to any static hosting service:
- GitHub Pages
- Netlify (drag & drop)
- Vercel
- Any web host

## Adding a Profile Photo
Replace the initials placeholder in the `.profile-img` div with:
```html
<img src="photo.jpg" alt="Your Name" style="width:100%;height:100%;object-fit:cover;" />
```
Add your `photo.jpg` to the same folder.

## Customizing Colors
All colors use CSS variables at the top of `style.css`:
- `--accent`: Gold highlight color (`#c9a84c`)
- `--bg`: Main background
- `--text`, `--text-muted`, `--text-dim`: Text hierarchy
