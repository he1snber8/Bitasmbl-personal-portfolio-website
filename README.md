# Bitasmbl-personal-portfolio-website

Build a static personal portfolio website to showcase your skills, projects, and contact information. This project focuses on responsive design, component structure, and basic interactivity.

## Tech Stack
- Angular

## Requirements
- Create sections for About, Projects, and Contact
- Make the website responsive for different screen sizes
- Include interactive elements such as links and buttons
- Display your projects with titles, descriptions, and links

## Installation
1. Clone the repository:
   bash
   git clone https://github.com/yourusername/Bitasmbl-personal-portfolio-website.git
   
2. Navigate into the project directory:
   bash
   cd Bitasmbl-personal-portfolio-website
   
3. Install dependencies:
   bash
   npm install
   
4. Start the development server:
   bash
   ng serve
   
5. Open your browser and visit `http://localhost:4200`.

No additional environment variables are required for this static project.

## Usage
- Use the navigation menu to switch between the About, Projects, and Contact sections.
- Click on project links to view live demos or source code repositories.
- Resize your browser window or test on different devices to see the responsive layout in action.

## Implementation Steps
1. Scaffold a new Angular application using the CLI (`ng new portfolio-website --style=scss`).
2. Generate core components for each section:
   bash
   ng generate component components/about
   ng generate component components/projects
   ng generate component components/contact
   ng generate component components/navbar
   
3. Configure Angular routing to map routes (`/about`, `/projects`, `/contact`) to their components.
4. Build a responsive layout with Flexbox or CSS Grid and SCSS media queries.
5. Implement the About component with personal biography and profile image.
6. Create a project model and list in the Projects component; use `*ngFor` to display project cards with titles, descriptions, and links.
7. Develop the Contact component with a contact form and clickable social links or mailto buttons.
8. Add a Navbar component with router links and interactive styling (hover, active states).
9. Test responsiveness across mobile, tablet, and desktop breakpoints; refine styles as needed.
10. Optionally deploy to GitHub Pages or a static hosting provider (e.g., Netlify, Vercel).