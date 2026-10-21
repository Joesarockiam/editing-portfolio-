# Joes Arockiam — Video Editor Portfolio

A responsive, single-page portfolio website built with HTML, CSS, and JavaScript.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser. For the best local development experience, serve the folder with VS Code Live Server or run `python -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Included
- Responsive dark cinematic design with violet accents
- Uploaded portraits (if available in the environment)
- Interactive project filters and video preview modal
- Google Drive portfolio folder link
- Contact links: `joesarockiam@gmail.com`, `+91 93458 83907`
- WhatsApp contact shortcut
- Contact form that prepares an email draft (no backend required)
- Arival.ai digital marketing experience section
- Reduced-motion support and basic keyboard accessibility

## Add your actual video projects
Open `index.html` and find `const projects = [...]` near the bottom. Replace the example titles/descriptions with your real work. For an individual Google Drive video, set `url` to a link such as:
`https://drive.google.com/file/d/YOUR_REAL_FILE_ID/view`

The website will use a Google Drive preview iframe for valid file links. Ensure each video has viewer permissions suitable for your intended audience. If a video cannot be embedded, the modal still provides a link to the portfolio folder.

The current project cards are editable placeholders, not claims about completed client projects. Replace them with your real work before publishing.

## Personal images
The site expects:
- `assets/profile-grey-shirt.jpeg`
- `assets/profile-creative.jpeg`

These are the two photographs supplied in the conversation. If either image is missing, place the corresponding image in `assets/` using the expected filename.

## Customize
- Update project data in `const projects`.
- Update services and experience copy directly in `index.html`.
- Update contact details in the contact section and form handler if they change.
- Social links can be added in the footer once you provide the correct profile URLs.

## Deploy
You can deploy this static website to GitHub Pages, Netlify, Vercel, or any static web host. No build step is required.
