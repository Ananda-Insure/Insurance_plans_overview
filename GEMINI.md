# Insurance Plans Overview - FWD Agent Landing Page

This project is a responsive landing page for an FWD insurance agent, providing information about insurance plans, agent qualifications, and contact details.

## Tech Stack
- **Frontend:** HTML5, Tailwind CSS (via CDN), Vanilla JavaScript.
- **Styling:** Custom CSS in `style.css` for animations and specific component styling.
- **Icons & Fonts:** Google Fonts (Manrope), Material Symbols Outlined.

## Project Structure
- `index.html`: Main entry point containing the structure and logic.
- `style.css`: Custom styles and animations.
- `asset/`: Directory for images and other static assets.

## Established Conventions
- **Styling:** Primarily uses Tailwind CSS utility classes. Custom animations and specific overrides are handled in `style.css`.
- **Interactivity:** Vanilla JavaScript is used for features like:
    - Smooth scrolling.
    - Hero section 3D/flip animations.
    - Insurance plan filtering.
    - Lightbox for viewing plan details.
- **Assets:** All images should be placed in the `asset/` folder.
- **Responsive Design:** Mobile-first approach using Tailwind's responsive prefixes.

## Key Sections
- **Hero:** Interactive section with 3D image effects.
- **About:** Information about the agent and their qualifications.
- **Plans:** Categorized insurance plans with a filter system.
- **Contact:** Multiple contact methods, including social media and external FWD tools.

## Development Workflow
- Since Tailwind is loaded via CDN with a custom configuration script in `index.html`, no build step is required for CSS.
- Changes can be previewed by opening `index.html` in a web browser.
