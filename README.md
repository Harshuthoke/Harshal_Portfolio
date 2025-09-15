# Harshal Thoke - Personal Portfolio

This is a personal portfolio website for Harshal Thoke, a Full Stack Developer specializing in Python, cybersecurity, and web development. The site showcases skills, experience, education, projects, and contact information.

## Features

- **Responsive Design:** Works on desktop and mobile devices.
- **Sidebar:** Displays profile, contact info, and social links.
- **Navigation:** Switch between About, Resume, Portfolio, and Contact sections.
- **Portfolio:** Filterable project showcase with links to GitHub repositories.
- **Contact Form:** Send messages via Formspree.
- **Testimonials & Clients:** (Commented out, can be enabled if needed.)
- **Google Maps Integration:** Shows location in Contact section.
- **Docker Support:** Simple Dockerfile for deployment using Apache HTTP Server.

## Technologies Used

- HTML5
- CSS3 ([assets/css/style.css](assets/css/style.css))
- JavaScript ([assets/js/script.js](assets/js/script.js))
- [Ionicons](https://ionic.io/ionicons) for icons
- Google Fonts (Poppins)
- Docker (see [Dockerfile](Dockerfile))

## Getting Started

### Local Development

1. Clone the repository.
2. Open `index.html` in your browser.

### Docker Deployment

To run the site in a Docker container:

```sh
docker build -t harshal-portfolio .
docker run -p 8080:80 harshal-portfolio
```

This uses the [Dockerfile](Dockerfile) to serve the site with Apache HTTP Server.

## Customization

- Update profile info, skills, and projects in [index.html](index.html).
- Add or update images in [assets/images/](assets/images/).
- Modify styles in [assets/css/style.css](assets/css/style.css).
- Update JavaScript interactions in [assets/js/script.js](assets/js/script.js).

## Contact

For inquiries, use the contact form on the site or email: harshuthoke@gmail.com

---

**Live Demo:** _Host the site on GitHub Pages or any static hosting for public access._
