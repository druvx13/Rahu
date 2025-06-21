# Project Structure Documentation

This document outlines the directory and file structure for the Sacred Sanskrit Texts Archive project.

## Root Directory

```
.
├── LICENSE                # Project license (Unlicense)
├── README.md              # Main project overview, setup, and information
├── index.html             # Main portal page linking to all texts (the home page)
├── assets/                # Directory for all shared static assets
└── texts/                 # Directory containing all individual sacred text pages
└── docs/                  # Directory for project documentation (like this file)
```

## `assets/` Directory

Contains all static assets shared across the website.

```
assets/
├── css/
│   └── style.css          # Global stylesheet for common styles, portal page styles
├── js/
│   └── main.js            # Global JavaScript (if any, currently placeholder)
├── fonts/
│   └── Sanskrit2003.ttf   # Local copy of the Sanskrit2003 font
└── images/
    └── favicon.ico        # Favicon for the website (currently a placeholder link)
```

## `texts/` Directory

This is the core content directory. Each sacred text is organized into its own subdirectory.

```
texts/
├── [text_name_1]/         # Example: rahu_kavacham
│   └── index.html         # The HTML file for this specific text
├── [text_name_2]/         # Example: angirasa_shiva_stotram
│   └── index.html
└── ...                    # Other texts follow the same pattern
```

**Naming Convention for Text Subdirectories:**
*   Lowercase.
*   Words separated by underscores (`_`).
*   Name should be descriptive of the text contained within (e.g., `rahu_kavacham`, `surya_stuti`).

## HTML File Specifics

*   **Main `index.html` (Root):**
    *   Serves as the central navigation hub.
    *   Links to each `index.html` file within the `texts/[text_name]/` subdirectories.
    *   Uses assets from the `assets/` directory (e.g., `assets/css/style.css`).
*   **Individual Text HTML Files (e.g., `texts/rahu_kavacham/index.html`):**
    *   Contain the Sanskrit text, translations, and any specific styling or JavaScript for that text.
    *   Link to shared assets using relative paths (e.g., `../../assets/fonts/Sanskrit2003.ttf`, `../../assets/css/style.css` if global styles are applied).
    *   Currently, most use CDN links for frameworks like Tailwind CSS and Font Awesome. This could be localized into `assets/` in the future.

## Rationale for this Structure

*   **Clarity:** Separates content (`texts/`) from presentation assets (`assets/`) and documentation (`docs/`).
*   **Maintainability:** Easier to manage and update individual texts or shared assets.
*   **Scalability:** Simple to add new texts by creating a new subdirectory in `texts/`.
*   **Reduced Redundancy:** Aims to have a single canonical version of each text.
*   **Central Navigation:** The root `index.html` provides a clear entry point and overview of all available content.
