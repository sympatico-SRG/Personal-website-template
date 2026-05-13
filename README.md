# Minimal Line-Art Personal Website Template

A clean, minimalist personal website template for portfolios, resumes, personal branding pages, and GitHub Pages deployment.

This template uses a warm paper-like background, black line-art visuals, rounded cards, sticky navigation, expandable experience sections, and a lightweight static HTML/CSS/JavaScript structure.

## Preview

After enabling GitHub Pages, your demo URL will look like:

```text
https://your-username.github.io/your-repository-name/
```

Local preview:

```text
index.html
```

## Features

- Minimal warm paper-style visual design
- Black line-art / engineering sketch aesthetic
- Responsive layout for desktop and mobile
- Sticky top navigation
- Back-to-top button
- Expandable cards for detailed experiences
- Sections for profile, education, projects, research, student work, honors, skills, and contact
- Pure static implementation: no build tools, no framework, no backend
- Ready for GitHub Pages, Netlify, Vercel, or any static hosting service

## File Structure

```text
.
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── avatar-line-art.png
    ├── hero-engineering-lineart.png
    ├── project-hand-device.png
    └── project-sorting-machine.png
```

## Quick Start

1. Download or clone this repository.
2. Open `index.html` in your browser.
3. Replace the sample content with your own information.
4. Replace images in `assets/` if needed.
5. Deploy to GitHub Pages or another static hosting platform.

## Customize the Content

Most text content is in `index.html`.

Common items to replace:

| Placeholder | Replace With |
| --- | --- |
| `Ruille Suen` | Your name or public display name |
| `哈佛大学` | Your school or organization |
| `Engineering Sciences` | Your major, role, or field |
| `your.email@example.com` | Your public contact email |
| Research cards | Your research, internship, or work experience |
| Project cards | Your projects, competitions, or portfolio pieces |
| Student work cards | Your leadership, organization, club, or volunteer experience |
| Honors section | Your awards and certificates |
| Skills section | Your tools, languages, interests, and strengths |

## Customize the Images

Image assets are stored in:

```text
assets/
```

You can replace:

- `avatar-line-art.png` with your own avatar
- `hero-engineering-lineart.png` with your preferred hero illustration
- Project images with illustrations related to your own work

Recommended style:

- Black line art
- Warm ivory or transparent-looking background
- No readable private information
- No logos unless you own the rights
- Keep file sizes reasonably small for faster loading

## Expandable Card Format

Research, project, and student-work sections use expandable cards.

Each card usually contains:

- A short summary visible by default
- Tags or keywords
- A collapsible detail area
- Detail modules such as background, goal, method, contribution, outcome, and reflection

This structure works well for resumes because it keeps the page clean while still allowing deeper reading.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `assets/`
3. Open repository `Settings`.
4. Go to `Pages`.
5. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. Wait 1-3 minutes.

Your website will usually be available at:

```text
https://your-username.github.io/repository-name/
```

## Update the Website

After editing files locally:

```bash
git add .
git commit -m "Update website content"
git push
```

GitHub Pages will redeploy automatically after the push.

## AI-Assisted Workflow

This template was created with AI assistance. AI helped with:

- Information architecture
- Portfolio copy structure
- Visual direction
- HTML/CSS/JavaScript implementation
- Expandable card design
- README organization
- Prompt template drafting

You can use AI to adapt this template to your own background. Always review generated content for accuracy, privacy, and tone before publishing.

## Reusable AI Prompt

Use this prompt with your own resume, project notes, or portfolio materials:

```text
I want to create a personal portfolio website based on a minimalist line-art static website template.

Please help me organize my information into clean website copy and section content.

Style requirements:
- Minimal, refined, and professional
- Warm paper-like background
- Black line-art visual style
- Rounded cards and thin borders
- Portfolio-like, not a generic resume page
- Readable on both desktop and mobile

Website sections:
- Hero: name, short positioning statement, keywords, avatar or line-art image
- About: education, field, strengths, and personal focus
- Research / Internship / Work: expandable cards
- Projects / Competitions: expandable cards
- Student work / Leadership / Volunteer experience: expandable cards if relevant
- Honors: key awards highlighted, other awards grouped
- Skills and interests: grouped by category
- Contact: public email or links

Expandable card requirements:
- Default view: short summary
- Expanded view: detailed modules
- Suggested modules: background, goal, method, role, contribution, result, reflection
- Keep the writing specific, truthful, and not exaggerated

Please generate website-ready content based on the following information:

[Name]
Fill in your name.

[Education / Role]
Fill in your school, major, role, or current identity.

[Personal Positioning]
Describe how you want people to remember you.

[Research / Internship / Work Experience]
Paste your experience here.

[Projects / Competitions]
Paste your projects here.

[Leadership / Student Work / Club Experience]
Paste your organization or activity experience here.

[Honors / Certificates]
Paste your awards here.

[Skills / Interests]
Paste your skills, tools, languages, and interests here.

[Contact]
Paste your public contact information here.
```

## Privacy Notes

Before publishing, check that the site does not expose sensitive personal information.

Recommended:

- Use a public email instead of a private phone number
- Avoid exact home address, student ID, private account IDs, or non-public project names
- Replace sensitive project names with generalized names if needed
- Review images for hidden personal information

## License

You can add a license depending on how you want others to use this template.

Common choices:

- MIT License for open reuse
- No license if you do not want to grant reuse rights by default
