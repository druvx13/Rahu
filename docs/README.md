# Sacred Sanskrit Texts Archive

Welcome to the Sacred Sanskrit Texts Archive, a collection of revered Hindu stotras, kavachams, and mantras. This project aims to provide a clean, accessible, and well-organized digital platform for these sacred scriptures, primarily featuring original Sanskrit texts alongside English translations. Some texts may include additional language translations and interactive features.

## Project Overview

This repository hosts a static website built with HTML, CSS, and JavaScript. The texts are presented in a user-friendly format, designed for spiritual seekers, scholars, and anyone interested in these ancient wisdom traditions.

## Features

*   **Wide Range of Texts:** Includes various hymns and chants dedicated to different deities and spiritual purposes.
*   **Sanskrit Originals:** Presents texts in the original Devanagari script.
*   **Translations:** Primarily English translations, with some texts offering additional languages (e.g., Chinese).
*   **Responsive Design:** Pages are designed to be accessible on various devices using Tailwind CSS.
*   **Interactive Elements:** Some pages include features like theme toggling, collapsible translation sections, and smooth navigation.

## Project Structure

The repository is organized as follows:

```
.
├── LICENSE
├── README.md              # This file
├── index.html             # Main portal page linking to all texts
├── assets/                # Shared static assets
│   ├── css/               # Stylesheets (global and specific)
│   ├── js/                # JavaScript files (global and specific)
│   ├── fonts/             # Font files (e.g., Sanskrit2003.ttf)
│   └── images/            # Images, favicons, etc.
├── texts/                 # Contains all individual sacred texts
│   ├── [text_name_1]/     # Each text has its own directory
│   │   └── index.html     # The HTML file for the text
│   ├── [text_name_2]/
│   │   └── index.html
│   └── ...
└── docs/                  # Additional documentation (if any)
```

*   **`index.html` (Root):** The main landing page that provides navigation to all available texts.
*   **`assets/`:** Contains all static assets like CSS stylesheets, JavaScript files, fonts, and images used across the website.
*   **`texts/`:** This directory houses the individual HTML files for each sacred text, organized into subdirectories named after the text itself (e.g., `texts/rahu_kavacham/index.html`).

## Content

The collection includes, but is not limited to:

*   Rahu Kavacham
*   Angirasa's Hymn to Lord Shiva (Angirasa Krita Shiva Stotram)
*   Vairagya Panchakam
*   Surya Stuti (Kashyapa's Hymn to the Sun God)
*   And many other mantras and stotras.

Each text page typically provides:
1.  The original Sanskrit verse in Devanagari.
2.  An English translation of the verse.
3.  Contextual information or commentary where available.

## Technology Used

*   HTML5
*   CSS3 (primarily Tailwind CSS framework)
*   JavaScript (for interactivity)

## How to View

Since this is a static website, you can view it by:
1.  Cloning this repository to your local machine.
2.  Opening the `index.html` file in the root directory with your web browser.
3.  Alternatively, if hosted (e.g., on GitHub Pages), by navigating to the provided URL.

There are no special build steps required for the core content.

## Future Enhancements (Potential)

*   Adding more texts to the collection.
*   Including audio recitations for mantras and stotras.
*   Expanding translations into other languages.
*   Implementing a search functionality.
*   Standardizing the visual theme and features across all pages for a more consistent user experience.

## License

This project is released into the public domain. See the [LICENSE](LICENSE) file for more details.

## Contributing

While this project is primarily a curated archive, suggestions for new texts, corrections, or improvements to the presentation are welcome. Please feel free to open an issue to discuss any potential contributions.

---

We hope this archive serves as a valuable resource for your spiritual journey and study.
