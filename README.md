# Luxury Watches & Jewellery Reselling Website

An informational website for a high-end watch and jewellery reselling company.  
**Live Demo**: [Coming Soon](#)  
**Status**: In Development

---

## Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Design System](#design-system)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Deployment](#deployment)
- [AI Instructions](#ai-instructions-for-code-generation)
- [License](#license)

---

## Project Overview
A **non-e-commerce website** focused on showcasing:
- Company story and services (reselling, authentication, repairs).
- Curated collections of luxury watches and jewellery.
- Educational content (blogs, care guides, industry trends).

---

## Tech Stack
| Category       | Tools/Libraries                                                                 |
|----------------|---------------------------------------------------------------------------------|
| **Frontend**   | React.js, Next.js, Tailwind CSS                                                 |
| **Backend**    | Firebase (Firestore), Strapi (Headless CMS)                                     |
| **Hosting**    | Vercel/Netlify                                                                  |
| **Analytics**  | Google Analytics                                                                |
| **AI Tools**   | Cursor (GPT-4), Windmill (Backend Workflows)                                   |
| **Version Control** | Git, GitHub                                                               |

---

## Design System
### Typography
| Element         | Font                     | Usage Example                          |
|-----------------|--------------------------|----------------------------------------|
| **Logo**        | Edwardian Script         | Brand logo in header/footer            |
| **Headings**    | Playfair Display         | Page titles (e.g., "About Us")         |
| **Subheadings** | Cormorant Garamond       | Section titles (e.g., "Our Services")  |
| **Body Text**   | Lato/Montserrat          | Paragraphs, descriptions               |

### Color Palette
| Color          | Hex       | Usage                                   |
|----------------|-----------|-----------------------------------------|
| **Primary**    | `#db5879` | Buttons, accents, highlights            |
| **Secondary**  | `#000000` | Text, borders                           |
| **Background** | `#ffffff` | Page/section backgrounds                |

### Logos
| Type               | Usage Context                          | Example File       |
|--------------------|----------------------------------------|--------------------|
| **Icon Logo**      | Mobile header, favicon, social media   | `icon-logo.svg`    |
| **Typography Logo**| Desktop header, print materials        | `text-logo.svg`    |

### Layout Guidelines
- **Whitespace**: Minimalist design with ample padding/margins.
- **Responsive Grid**: 12-column grid for desktop, 4-column for mobile.
- **Image Style**: High-resolution product images with soft shadows.

---

## Features
### Pages
1. **Homepage**  
   - Hero section with rotating product highlights.
   - Quick links to Services, Catalog, and Blog.
2. **About Us**  
   - Company history, mission, and team bios.
3. **Services**  
   - Reselling, authentication, and repair process details.
4. **Product Catalog**  
   - Image gallery with filters (brand, material, era).
5. **Blog**  
   - Articles on trends, care tips, and authentication guides.
6. **Contact**  
   - Form, location map, and social media links.

### Components
- Responsive navigation bar (with logo switching for mobile/desktop).
- Newsletter subscription form.
- Interactive image carousel.

---

## Setup Instructions
```bash
# Clone the repository
git clone https://github.com/yourusername/luxury-watches-website.git

# Install dependencies
npm install

# Configure environment variables (create .env file)
cp .env.example .env

# Start development server
npm run dev