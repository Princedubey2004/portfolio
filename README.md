# Portfolio Website

A modern, responsive portfolio website built with React. Showcase your projects, skills, and contact information with a beautiful and professional design.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Built with Tailwind CSS and DaisyUI for a sleek interface
- **Smooth Animations**: Enhanced user experience with Framer Motion animations
- **Project Showcase**: Display your projects with detailed descriptions and images
- **Blog Section**: Share your thoughts and articles
- **Contact Form**: Integrated contact form for easy communication
- **Dark Theme**: Modern dark theme with customizable colors

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository or download the project files

```bash
git clone <your-repo-url>
cd portfolio-website
```

2. Install dependencies

```bash
npm install --legacy-peer-deps
```

3. Start the development server

```bash
npm start
```

The application will open at `http://localhost:3000`

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## Project Structure

```
src/
├── components/     # Reusable React components
├── pages/         # Page components
├── hooks/         # Custom React hooks
├── Utils/         # Utility files and data
└── assets/        # Images and static assets
```

## Key Features

- **Home**: Landing page with hero section
- **About**: Personal information and skills
- **Projects**: Portfolio of your work
- **Blog**: Blog posts and articles
- **Contact**: Contact form and information

## Technologies Used

- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [React Router](https://reactrouter.com/) - Declarative routing for React
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [DaisyUI](https://daisyui.com/) - Component library for Tailwind CSS
- [Framer Motion](https://www.framer.com/motion/) - Animation library for React
- [React Icons](https://react-icons.github.io/react-icons/) - Icon library
- [EmailJS](https://www.emailjs.com/) - Email service integration

## Customization

### Update Personal Information

1. Edit `src/pages/About/index.js` to update your personal details
2. Edit `src/pages/Contact/index.js` to update contact information
3. Update `src/Utils/Items.js` to add your projects
4. Update `src/Utils/blogs.js` to add your blog posts

### Styling

- Main styles: `src/index.css`
- Component styles: Individual CSS files in component folders
- Tailwind config: `tailwind.config.js`

### Colors and Theme

Edit `tailwind.config.js` to customize the color scheme and theme.

## License

MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
