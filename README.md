## Name : Samy AIT ALLA

# Global Street Food Favorites

Single-page Vue app highlighting street food dishes from around the world. Browse titles, flip to see descriptions, and navigate through the collection with previous/next controls driven by Vue data binding.

## Features

- Uses Vue 3 CDN to manage state and binding without a build step.
- Consumes a separate data file that lists each street food entry (title, description, image, note, and reference link).
- Toggle between showing a dish title and its description by clicking the featured card.
- Previous/Next buttons cycle through all entries while keeping the image and note in sync.
- Responsive layout with card imagery and local assets stored in the `img` directory.

## Live Demo

See github repo : https://github.com/Samy2700/Advanced_Web_Project.

## Getting Started

1. Clone or download this repository.
2. Open `index.html` directly in your browser (no build tooling required).
3. Click anywhere on the food card to switch between the name and description, and use the navigation buttons to explore each dish.

To update the content, edit the array in `data/foods.js` and add any additional images to the `img` folder.
