# UniRoute Global Group - Modern Education Consultancy Platform

![UniRoute Global Logo](https://lh3.googleusercontent.com/aida-public/AB6AXuDzmLh9QBSb5t4Z905_dS8OIZOUTheUNuRNn4nFOt_hM1p-gIR_NGr5e7Q7DB887BTRO6X8CCfRQucoKGrWuulZwZ-5o_zihEFKlpjE79McagrhHZDQOcHXaBK8kJBdP-IgwZe1reKCOW3ik-R2RBWNtFnOCMrTt53WGuHou_jbdKcTC5H5rFoTyKFu9TyOWnyJmKbIVNx9cqTeqBEi1ELStEYmQgpp69kIpDQt3xKcLILNcULDnWDSX4BjQ7Ya2zLjec1-HzPpFqjC)

UniRoute Global Group is a premium, responsive web platform designed for Kenya's leading education consultancy firm. The platform connects ambitious students with global academic excellence, providing a seamless interface to explore programs, find scholarships, and book consultations with ICEF-certified experts.

## 🚀 Key Features

- **Dynamic Program Discovery**: A comprehensive search and filter interface for undergraduate and postgraduate opportunities across the UK, USA, Canada, Australia, and Europe.
- **Rich User Experience**: Modern, aesthetic design with liquid-smooth transitions, hover effects, and a glassmorphism-inspired UI.
- **Dark Mode Support**: Context-aware styling with a persistent theme toggle for optimal viewing in any environment.
- **Scholarship Portal**: Dedicated section for merit-based funding and international scholarship guidance.
- **Success Stories**: Interactive testimonials showcasing real student placements and outcomes.
- **SEO Optimized**: Semantic HTML5 structure with optimized meta tags and heading hierarchy.
- **Responsive Architecture**: Pixel-perfect layout across mobile, tablet, and desktop devices.

## 🛠 Technology Stack

- **Core**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Utility-first framework via CDN)
- **Typography**: Plus Jakarta Sans (Main Display), Inter (Sans)
- **Icons**: [Material Design Icons](https://fonts.google.com/icons)
- **Forms**: [Formspree](https://formspree.io/) for serverless contact form handling.

## 📁 Project Structure

```bash
.
├── index.html          # Landing Page (Hero, Partners, CTA)
├── programs.html       # Program Search & Filter Interface
├── about.html          # Company Profile, Mission, and Team
├── testimonies.html    # Success Stories and Student Feedback
├── profiles.html       # Detailed Consultant/University Profiles
├── contact.html        # Lead Generation & Contact Form
└── .git/               # Version Control System
```

## 🎨 Design System

The project utilizes a curated color palette and typography scale defined in the Tailwind configuration:

| Semantic Color | Hex Code | Purpose |
| :--- | :--- | :--- |
| **Primary** | `#F26522` | Brand orange, CTA buttons, highlights |
| **Secondary** | `#003087` | Brand navy, navigation, hero backgrounds |
| **Background Light** | `#F9FAFB` | Light mode surface color |
| **Background Dark** | `#0B1120` | Dark mode surface color |

### Custom Tailwind Config
Each page includes a synchronized configuration script:
```javascript
tailwind.config = {
    darkMode: "class",
    theme: {
        extend: {
            colors: {
                primary: "#F26522",
                secondary: "#003087",
            }
        }
    }
}
```

## ⚙️ Getting Started

As a static project, no build step is required.

### Local Development
1.  **Clone the repository**:
    ```bash
    git clone <repository-url>
    ```
2.  **Serve the files**:
    You can use any local development server. For instance, using Python:
    ```bash
    python3 -m http.server 8000
    ```
    Or using [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code.

3.  **Access the site**:
    Open `http://localhost:8000` in your web browser.

## 🌍 Deployment

The platform is optimized for static hosting providers such as:
- **Vercel**: Simply push to GitHub and connect the repository.
- **Netlify**: Drag and drop the directory or use the CLI.
- **GitHub Pages**: Deploy via the `main` branch or a `docs/` folder.

## 🤝 Contributing

1.  Identify a feature request or bug.
2.  Create a new branch (`feature/amazing-feature` or `fix/critical-bug`).
3.  Ensure all HTML files maintain the shared navigation and footer components.
4.  Verify performance and responsiveness before submitting a Pull Request.

---

*© 2026 UniRoute Global Group. All rights reserved.*
