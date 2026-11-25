# Interactive Photo Gallery

**[Live Demo](https://dvperks.github.io/portfolio/project-viewer.html?project=4)** | **[Developer Portfolio](https://dvperks.github.io/portfolio/)**

A responsive, searchable photo gallery built with JavaScript, CSS Grid, and SCSS/Sass. The application dynamically generates gallery content, retrieves photo information asynchronously, and provides interactive search filtering and lightbox navigation.

## Features

- Responsive image gallery using CSS Grid.
- Asynchronous loading of photo titles and captions.
- Dynamically generated gallery markup.
- Real-time search filtering by title or caption.
- Interactive lightbox for viewing full-size images.
- Image navigation and caption display.

## Built With

- JavaScript (ES6+)
- HTML5
- CSS3
- SCSS/Sass
- CSS Grid
- Fetch API
- Async/Await
- baguetteBox.js

## Technical Highlights

### Dynamic Content Generation

Gallery elements are generated through JavaScript rather than individually hardcoded into the HTML document.

This approach separates gallery content from its presentation and makes the interface structure easier to maintain.

### Asynchronous Data Loading

Photo titles and captions are retrieved from an external text file using asynchronous JavaScript.

The application uses the retrieved information to construct gallery content and support search functionality.

### Search Filtering

Users can filter displayed images by entering text associated with photo titles or captions.

The gallery updates dynamically in response to search input.

### Responsive Layout

CSS Grid provides a flexible gallery layout that adapts to different viewport sizes.

SCSS/Sass organizes the styling into maintainable source files.

### Lightbox Integration

The application integrates baguetteBox.js to provide full-size image viewing, captions, and gallery navigation.

## Run Locally

Clone the repository:

```bash
git clone https://github.com/DVPerks/Interactive-Photo-Gallery.git
cd Interactive-Photo-Gallery
```

Start a local web server:

```bash
python -m http.server 8000
```

Open http://localhost:8000/ in your browser.

On Windows, `py -m http.server 8000` can also be used.

A local server is recommended because the application retrieves external caption data through the Fetch API.

## Project Structure

```text
├── css/                # Compiled stylesheets
├── scss/               # Sass source files
├── js/                 # Gallery and search functionality
├── photos/             # Photo assets
├── photo_captions.txt   # Photo titles and captions
├── index.html          # Gallery markup
└── README.md           # Project documentation
```

## Development Focus

This project demonstrates asynchronous JavaScript, data-driven content generation, responsive layouts, client-side search filtering, and third-party library integration.

## Project Credits

Originally developed as part of Team Treehouse's Front End Web Development Techdegree.

Lightbox functionality is provided by [baguetteBox.js](https://github.com/feimosi/baguetteBox.js).

## Author

Drake Perkins — Frontend Software Engineer

- [Developer Portfolio](https://dvperks.github.io/portfolio/)
- [GitHub](https://github.com/DVPerks)
- [LinkedIn](https://www.linkedin.com/in/drake-p-0a9472398/)
