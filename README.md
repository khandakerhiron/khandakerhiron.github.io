# Hiron Khandaker – Personal Website

This repository hosts the source code for my personal academic website, built as a static site and hosted via GitHub Pages at [khandakerhiron.github.io](https://khandakerhiron.github.io).

![Profile Screenshot](hironkhandaker.jpg?raw=true)

## About the Site

The website is designed as a clean, professional portfolio for a graduate student/researcher. It includes:

- Profile photo, name, and institutional affiliation
- Research interest tags (GIS, Machine Learning, Urban Climate, etc.)
- A detailed bilingual bio (English and Bangla)
- Social media links (Facebook, GitHub, LinkedIn, X, ResearchGate, YouTube, Google Scholar)
- Language toggle to switch between English and Bangla bio
- Dark/light theme toggle with persistent user preference
- Responsive layout for all devices
- Footer with copyright notice

## Technologies Used

- HTML5
- CSS3 (custom properties, Flexbox, media queries)
- JavaScript (vanilla, no frameworks)
- [Font Awesome 6](https://fontawesome.com) for icons
- [Google Fonts](https://fonts.google.com) (Inter typeface)
- GitHub Pages for hosting

## File Structure
khandakerhiron.github.io/
├── index.html # Main website (single page)
├── hironkhandaker.jpg # Profile photograph
└── README.md # This file



## Customization

If you wish to adapt this site for your own use:

1. Replace `hironkhandaker.jpg` with your own profile photo (keep the filename or update the `<img src>` accordingly).
2. Edit the `index.html` file:
   - Update the `name`, `institution`, and `tagline` in the HTML.
   - Modify the social media links in the `.social-links` section.
   - Change the bio texts in the JavaScript section (`bioEN` and `bioBN` variables) to your own content.
   - Update the footer year if needed (it's currently set to 2026; you can make it dynamic by uncommenting the JavaScript line).
3. Adjust colors, fonts, or layout by editing the CSS inside the `<style>` block.

## Deployment

Any push to the `main` branch automatically updates the live site via GitHub Pages. No build step is required.

## License

The content of this project (text and images) is © Hiron Khandaker. The code is available for educational purposes; feel free to reuse with attribution.

---

*Last updated: February 2026*
