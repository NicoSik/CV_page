# CV Page

A professional, responsive, bilingual CV/Resume page for Nicolai Sikora hosted on GitHub Pages.

## 🌐 View Live

Visit the CV at: https://nicosik.github.io/CV_page/

## 🌍 Bilingual Support

This CV supports both English and Norwegian languages with a simple toggle button:
- Click the language button in the top-right corner to switch between languages
- The selected language preference is saved automatically in your browser
- All content (work experience, education, skills, projects) is fully translated

## 📝 Content

This CV includes:
- **Personal Information**: Contact details and professional title
- **Professional Summary**: Brief overview of expertise and focus areas
- **Work Experience**: Teaching assistant roles, grading positions, and professional work
- **Education**: Master's and Bachelor's degrees from the University of Oslo
- **Skills**: Programming languages, web technologies, databases, and tools
- **Projects**: Project cards with screenshots/cover images, a per-card image carousel and a click-to-enlarge lightbox
- **Languages**: Norwegian, English, and Polish proficiency

## 🎨 Customization

To update the CV content:

1. Edit `index.html` and modify both the English (`.lang-en`) and Norwegian (`.lang-no`) sections
2. (Optional) Modify `style.css` to change colors, fonts, or layout
3. Profile picture: `images/profile.jpg` (square, shown on the page) and `CV_picture.jpg` (used for link previews)
4. Project images live in `images/projects/`. To add or replace one, drop the file there and add an `<img>` inside
   the project's `.project-media` block in `index.html`. Several `<img>` tags in one block become a carousel
   automatically; add `<span class="media-count">1 / N</span>` to show a counter. The `alt` text is used as the
   caption in the enlarged view.

## 🚀 GitHub Pages Setup

This repository is configured to use GitHub Pages. To enable it:

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch (usually `main` or `master`)
4. Click "Save"

The CV is published at https://nicosik.github.io/CV_page/ within a few minutes.

## 📱 Features

- **Bilingual**: Toggle between English and Norwegian with one click
- **Sticky navigation**: Section links in the top bar, highlighting the section you are reading
- **Dark mode**: Theme toggle that follows the system setting by default and remembers your choice
- **Project filters**: Filter projects by technology; skills used in a project link straight to it
- **Image gallery**: Per-project carousel and a click-to-enlarge lightbox (arrow keys / Esc)
- **Copy email**: One-click copy button next to the email address
- **Language Persistence**: Remembers your language preference
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Print-Friendly**: Optimized CSS for printing (profile picture hidden in print)
- **Professional Layout**: Clean, modern design with accent colors
- **Easy to Update**: Simple HTML structure with clear language sections
- **SEO Friendly**: Proper meta tags and semantic HTML

## 🎨 Color Scheme

The color scheme uses:
- Primary text: #111 (Near black)
- Accent: #3a67e4 (Blue)
- Muted text: #444 (Dark gray)
- Border: #ddd (Light gray)
- Background: #fff (White)

Feel free to change these in the `style.css` file by modifying the CSS variables in `:root`.

## 📄 License

This CV template is free to use for personal purposes.
