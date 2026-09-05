# Zibon Portfolio

A modern, responsive beginner Software Engineering portfolio built with plain HTML, CSS, and JavaScript.

## Files

- `index.html` — page content and personal information
- `style.css` — design and responsive layout
- `script.js` — mobile menu, animations, and current year
- `assets/` — profile/project images

## How to customize

Open `index.html` and search for:

- `[YOUR_EMAIL]`
- `[YOUR_GITHUB_LINK]`
- `[YOUR_LINKEDIN_LINK]`
- `[YOUR_RESUME_LINK]`
- `[YOUR_COLLEGE / HSC]`
- `[COLLEGE NAME]`
- `[PASSING YEAR]`
- `[PROJECT_1_GITHUB]`
- `[PROJECT_1_DEMO]`
- `[CERTIFICATE_1_LINK]`

Replace each placeholder with your real information.

### Add a profile photo

Put your image at:

`assets/profile.jpg`

Then find the comment in the Hero section and replace the placeholder avatar with:

```html
<img src="assets/profile.jpg" alt="Zibon">
```

### Add a new project

Copy one `.project-card` in `index.html`, change the title, description, technologies, GitHub link, and demo link, and increment the project number.

### Add a certificate

Copy one `.certificate-card` and replace its name, organization, date, and certificate link.

## Deploy on Vercel

1. Create a GitHub repository.
2. Upload all files and the `assets` folder.
3. Open Vercel and import the GitHub repository.
4. For this static project, no build command is required.
5. Deploy.

After future updates, push your changes to GitHub. Vercel will automatically redeploy the latest version if the repository is connected.

## Important

Only list technologies you actually know or are currently learning. Replace the sample projects with your real projects as you build them.
