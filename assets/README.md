# Assets Directory

This directory contains all static assets for the Insper ML Group website.

## Structure

- `images/` - Image files
  - `team/` - Team member photos (place profile pictures here)
  - Add other image subdirectories as needed (e.g., `research/`, `logos/`)

## Usage

### Adding Team Photos

1. Place team member photos in `assets/images/team/`
2. Update the HTML to reference the images:

   ```html
   <img src="assets/images/team/member-name.jpg" alt="Member Name">
   ```

### Image Guidelines

- **Profile Photos**: 400x400px, square format, JPEG or PNG
- **Logos**: SVG preferred for scalability, or high-resolution PNG
- **Research Images**: Optimize for web (compress to reasonable file sizes)

## Optimization

Consider optimizing images before adding them:

- Use tools like ImageOptim, TinyPNG, or Squoosh
- Target file sizes: < 200KB for profile photos, < 500KB for other images
