# Sacred Sanskrit Texts Archive

Welcome to the Sacred Sanskrit Texts Archive, a curated collection of revered Hindu stotras, kavachams, mantras, and other philosophical texts. This project aims to provide easy access to these ancient scriptures in a well-organized digital format.

## How to Access the Texts

All texts are hosted online and can be viewed directly via GitHub Pages:

**[https://druvx13.github.io/Rahu/](https://druvx13.github.io/Rahu/)**

The main page at the link above serves as a portal to all available texts. Each text is presented on its own page, often including the original Sanskrit verses (in Devanagari script or transliterated) and translations where available.

## Repository Structure

The repository is organized as follows:

*   `index.html`: The main portal page that links to all individual texts. This is the page you see at the GitHub Pages link above.
*   `README.md`: This file, providing information about the project.
*   `LICENSE`: Contains the license information for this project (currently MIT License).
*   `assets/`: Contains shared assets used by the portal page.
    *   `assets/css/style.css`: Global stylesheet (currently minimal as most styling is inline or via Tailwind CSS).
    *   `assets/fonts/Sanskrit2003.ttf`: A font used for displaying Sanskrit characters, particularly the 'ॐ' symbol on the main portal.
*   `texts/`: This directory houses all the individual sacred texts. Each text is contained within its own subdirectory.
    *   `texts/[text_name]/index.html`: Each subdirectory (e.g., `texts/rahu_kavacham/`) contains an `index.html` file that displays the specific text. These pages may have their own specific styling and assets.
*   `docs/`: Contains additional documentation related to the project.
    *   `docs/README.md`: Original documentation (may be outdated or merged here).
    *   `docs/structure.md`: Document describing the original structure (may be outdated or merged here).

## About the Texts

This collection includes a variety of texts, such as:

*   **Stotras:** Hymns of praise and devotion to various deities.
*   **Kavachams:** Protective hymns considered as spiritual armor.
*   **Mantras:** Sacred utterances or syllables with spiritual power.
*   **Suktas:** Vedic hymns.
*   **Philosophical Texts:** Verses and expositions on spiritual concepts like Brahman, Vairagya (detachment), etc.

Each text page aims to provide an authentic representation. Some texts include translations in English or other languages.

## Technical Details

*   The portal page (`index.html`) and individual text pages are built with HTML and styled using Tailwind CSS.
*   Some pages may use custom fonts for Devanagari script or specific aesthetic purposes.
*   The site is statically hosted on GitHub Pages.

## Contributing

Contributions are welcome! If you would like to contribute, please consider the following:

*   **Adding new texts:**
    1.  Create a new subdirectory under `texts/` for the new text (e.g., `texts/new_text_name/`).
    2.  Inside this new directory, create an `index.html` file for the text content. You can use existing text pages as a template for structure and styling.
    3.  Ensure the text is accurately transcribed. Include original Sanskrit if possible, along with transliterations and translations if available.
    4.  Update the main `index.html` in the root directory to add a new card linking to your new text.
*   **Fixing errors or improving existing texts:** If you find any typos, inaccuracies, or have better translations, please feel free to submit a pull request or open an issue.
*   **Improving the portal or site functionality:** Suggestions or contributions to enhance the user experience are also welcome.

When contributing, please try to maintain a similar style and structure to the existing pages.

## License

This project is in public domain and is licensed under The  Unlicense - see the [LICENSE](LICENSE) file for details. The content is provided for educational and spiritual purposes.
