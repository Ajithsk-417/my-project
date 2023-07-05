FinEdge Website
This repository contains the source code for the FinEdge website, a single-page website for a fictitious fintech startup. The website is built using the Astro framework and includes components for navigation, home section, about us section, services section, and contact us section.

Table of Contents
Installation
Usage
Dependencies
Contributing
License
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/username/fin-edge-website.git
Navigate to the project directory:

bash
Copy code
cd fin-edge-website
Install the required dependencies:

bash
Copy code
npm install
Usage
Start the development server:

bash
Copy code
npm run dev
This will start the Astro development server and compile the source code. The website will be accessible at http://localhost:3000.

Build the production-ready assets:

bash
Copy code
npm run build
This will generate the optimized static assets for the website in the dist directory.

Dependencies
The FinEdge website relies on the following external dependencies:

Astro - Static site builder - Used to compile the Astro components and generate the static website.
Font Awesome - Version 6.4.0 - Provides icons used in the website's navigation and toggle button.
Structure
The website follows the following structure:

src/layouts/Layout.astro: The main layout component for the website, including the header and footer.
src/components/Home.astro: Component for the home section of the website.
src/components/About.astro: Component for the about us section of the website.
src/components/Service.astro: Component for the services section of the website.
src/components/Contact.astro: Component for the contact us section of the website.
src/main.astro: The main file that imports the layout and renders the different sections of the website.
Features
The FinEdge website includes the following features:

Responsive navigation bar with links to different sections.
Attractive home section with a catchy headline and description.
About us section providing a brief background about FinEdge.
Services section displaying three different financial services offered by FinEdge.
Contact us section with a simple contact form.