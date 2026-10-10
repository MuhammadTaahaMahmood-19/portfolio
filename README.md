# Muhammad Taaha Mahmood — Personal Portfolio

A four-page personal portfolio created for INFR3120 — Web and Scripting Programming, Assignment 1.

The website presents my background, academic projects, and contact information using HTML5 and CSS3.

## Website and Repository

- Live website: https://muhammadtaahamahmood-19.github.io/portfolio/
- GitHub repository: https://github.com/MuhammadTaahaMahmood-19/portfolio

## Pages

| File | Purpose |
|---|---|
| index.html | Introduction and links styled as navigation buttons |
| about.html | Personal background, photograph, and introductory video |
| projects.html | Five project/report entries with GitHub links |
| contact.html | Contact form with HTML validation and email delivery |

All pages include shared navigation, a contact email, and a copyright footer.

## Technologies

- HTML5 for semantic structure, forms, and video.
- CSS3 for colours, spacing, gradients, and responsive layouts.
- Git and GitHub for version control.
- GitHub Pages for website hosting.
- FormSubmit for forwarding contact-form submissions to email.

No JavaScript or Flexbox is used.

## File Organization

- The four HTML files are stored in the project root.
- css/style.css contains shared website styles.
- css/mobile.css contains mobile styles.
- css/tablet.css contains tablet styles.
- css/laptop.css contains laptop and larger-screen styles.
- images/ contains the profile photograph, video poster, and palette screenshot.
- videos/intro.mp4 contains the introductory recording.
- README.md documents the project.

## Running Locally

Download or clone the repository:

git clone https://github.com/MuhammadTaahaMahmood-19/portfolio.git

Open index.html in a browser and use the navigation links to explore the pages.

An internet connection is required for external GitHub links and FormSubmit. Test contact-form delivery from the published website.

## Responsive Design

The HTML pages load a shared stylesheet and separate viewport stylesheets using media queries in their link elements.

| Stylesheet | Viewport width | Design purpose |
|---|---|---|
| mobile.css | Up to 767px | Compact spacing and a full-width Submit button |
| tablet.css | 768px–1023px | Moderate spacing and larger headings |
| laptop.css | 1024px and above | More spacing and a wider content area |

These breakpoints distinguish narrow, medium, and wide browser windows. Percentage-based widths allow the content to resize between breakpoints, while maximum widths prevent excessively long lines.

The About Me media layout also uses a 768px media query in style.css. The photograph and video stack on narrow screens and appear side by side on wider screens using inline-block.

CSS Grid creates three page rows for the header, main content, and footer. A minimum body height of 100vh keeps the footer at the bottom of short pages. Longer pages scroll naturally.

Images and video retain their proportions as their display widths change.

## Colour Scheme

A custom blue palette was prepared using Adobe's colour palette tool with the Custom harmony setting.

| Colour | HEX | Use |
|---|---|---|
| Deep navy | #0F172A | Body text, header/footer backgrounds, and hover states |
| Royal blue | #1D4ED8 | Headings, buttons, links, and accents |
| Bright blue | #3B82F6 | Form-field borders |
| Pale blue | #DBEAFE | Form backgrounds, borders, and light accents |
| Off-white | #F8FAFC | Main background and light text |
| White | #FFFFFF | Project entries and form container |

The palette combines dark text with light surfaces and blue accents for a consistent appearance.

## Gradients

Two gradients are defined in style.css:

- Header: linear-gradient(to right, #0F172A, #1D4ED8)
  Creates a horizontal transition from navy to royal blue.
- Footer: linear-gradient(135deg, #0F172A, #1D4ED8)
  Creates an angled transition using the same colours.

## HTML Structure and Accessibility Features

- Semantic header, nav, main, footer, and article elements.
- Descriptive page titles and an English language declaration.
- aria-current="page" identifies the active navigation link.
- Descriptive alternative text for the profile photograph.
- Labels connected to form fields through matching for and id values.
- Visible keyboard focus indicators.
- Descriptive project links.
- Native video playback controls and a poster image.

Automated accessibility checks do not establish complete accessibility. Keyboard use and the video's caption/transcript needs also require manual review.

## Contact Form

The form collects a name, email address, cell number, and comments.

- required prevents empty-field submission.
- type="email" checks basic email formatting.
- pattern="[0-9]{10}" requires exactly ten phone-number digits.
- The form uses POST to submit to FormSubmit.
- A hidden _subject field sets the notification email subject.

FormSubmit processes the submitted details and forwards them to:

mtaahamahmood.official@outlook.com

Email activation and a subsequent delivery test were completed successfully.

## Testing

Testing date: October 9, 2026.

| Check | Result |
|---|---|
| W3C HTML validation | All four pages reported as passed |
| W3C CSS validation | All four stylesheets reported as passed |
| W3C Link Checker | No broken links reported in the reviewed run; mailto checking was disabled by the service |
| WAVE | All four pages reported zero errors, contrast errors, and alerts |
| Contact-form delivery | Confirmed after activation |
| Manual mailto check | Pending confirmation |
| Final keyboard and responsive-layout checks | Pending confirmation |
| Spell-check | Pending confirmation |

Validation screenshots were retained separately as supporting evidence.

## Deployment

1. Push the project files to the public GitHub repository.
2. Open the repository's Settings → Pages.
3. Select Deploy from a branch.
4. Choose main and / (root).
5. Save and wait for the Pages deployment to complete.
6. Open the published website and check its pages and assets.

Further pushes to main trigger updates to the deployed website.

## Sources and Assistance

- Adobe colour tools: used to prepare and document the custom palette.
  https://color.adobe.com/create

- FormSubmit documentation: used for the form endpoint, POST submission, email activation, and hidden subject field.
  https://formsubmit.co/

- GitHub documentation: used for repository and GitHub Pages deployment guidance.
  https://docs.github.com/en/pages

- Apple iMovie documentation: used to export and compress the introductory video.
  https://support.apple.com/en-ie/102371

- ChatGPT by OpenAI: provided assistance with HTML/CSS implementation, content wording, troubleshooting, and Git/deployment instructions.
  https://chatgpt.com/

The project descriptions refer to my academic work. The photograph and introductory recording are my own.

## Author

Muhammad Taaha Mahmood

Contact: mtaahamahmood.official@outlook.com