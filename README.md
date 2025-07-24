# DigitalDaVinci

DigitalDaVinci is a web-based platform for showcasing digital artists and their NFT collections. The project features artist profiles, collection galleries, and item previews, providing a visually engaging experience for users interested in digital art and NFTs.

## Features

- **Artist Profiles:** Dedicated pages for each artist with banners and profile images.
- **Collections:** Organized galleries for each artist's NFT collections.
- **Item Previews:** High-quality previews of individual NFT items.
- **Modern UI:** Clean and visually appealing interface using HTML, CSS, and JavaScript.

## Project Structure

```
artists.html            # Main artists listing page
collections.html        # NFT collections overview
index.html              # Landing page
main.js                 # JavaScript for interactivity
artists/                # Artist-specific HTML pages and styles
  styles.css            # Main stylesheet
ArtistBanners/          # Banner images for artists
ArtistProfile/          # Profile images for artists
items/                  # NFT item images organized by artist/collection
logo.jpg                # Project logo
splash.html             # Splash/intro page
package.json            # Project metadata (if using npm for tooling)
```

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/codebylohit/DigitalDaVinci.git
   ```
2. **Open the project folder in your code editor.**
3. **For the web version:**
   - Open `index.html` in your browser to view the landing page.
4. **For the Electron version:**
   - The project can also be run as a desktop app using Electron. Please ensure you have [Node.js](https://nodejs.org/) and [Electron](https://www.electronjs.org/) installed.
   - Install dependencies with:
     ```sh
     npm install
     ```
   - Then start the Electron app as per your setup (e.g., `npx electron .`).

> **Note:** Project dependencies are not bundled with the repository. Make sure to install them before running the Electron version.
