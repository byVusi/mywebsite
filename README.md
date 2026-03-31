# Vusi Mathonsi | Educator & Mentor

A modern, responsive personal website for an educator and mentor, built as a **single-page application (SPA)** using **HTML, CSS, and vanilla JavaScript**.

This site showcases professional experience, teaching philosophy, and custom-built tools for educators — all within a clean, elegant, and performance-focused design.

---

## ✨ Features

- **Single Page Application (SPA)**
    - Smooth navigation between sections without page reloads
    - Dynamic page title updates
    - Scroll-to-top behavior on navigation

- **Responsive Design**
    - Mobile-first approach
    - Hamburger menu for smaller screens
    - Flexible grid layouts

- **Modern UI/UX**
    - Elegant typography using _Lora_ and _Montserrat_
    - Soft shadows, gradients, and subtle animations
    - Consistent spacing system (4-point scale)

- **Interactive Components**
    - Animated navigation underline
    - Timeline with active state highlighting
    - Card hover effects
    - Mobile menu animation

- **Custom Sections**
    - Home (Hero + Personal Overview)
    - Philosophy (Core teaching principles)
    - Experience (Professional timeline)
    - Resources (Tools for teachers)

---

## 📁 Project Structure

```
project-root/
│
├── index.html # Main application file (HTML + CSS + JS)
├── assets/
│ └── images/ # Image assets (placeholders, logos, etc.)
│
└── README.md # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/byVusi/mywebsite.git
```

### 2. Open the project

Simply open `index.html` in your browser:

```bash
cd your-repo-name
open index.html
```

Or double-click the file

> ⚠️ No build tools or dependencies required - this is a fully static project.

## 🧠 How It Works

### 1. SPA Navigation

Navigation is handled via JavaScript:

- Sections are toggled using the .active class
- Each navigation link has a data-target attribute
- The navigateTo(pageId) function:
    - Hides all sections
    - Displays the selected section
    - Updates the page title
    - Scrolls to the top
    - Closes the mobile menu (if open)

### 2. Styling System

The project uses <strong>CSS variables (design tokens)</strong> for consistency:

```css
:root {
	--primary-900: #0f172a;
	--accent-main: #d97706;
	--space-4: 1rem;
}
```

<strong>Includes:</strong>

- Color system (primary + accent)
- Spacing scale (4-point system)
- Typography hierarchy
- Layout widths

### 3. Components

🧭 <strong>Navigation</strong>

- Sticky navbar
- Active link highlighting
- Mobile hamburger menu

🧱 <strong>Cards</strong>

- Reusable card layout
- Hover animations
- Used across multiple sections

📊 <strong>Timeline</strong>

- Alternating layout (left/right)
- Active state on scroll
- Responsive fallback for mobile

🔘 <strong>Buttons</strong>

- Primary (filled)
- Outline (bordered)
- Hover transitions

📸 <strong>Assets</strong>

Replace placeholder images in:

`assets/images/`

<strong>Recommended:</strong>

- Profile image
- Teaching/mentorship images
- Logos (certifications, etc.)

## 🛠 Customisation

### 1. Update Content

Edit directly in `index.html`:

- Hero text
- About section
- Experience timeline
- Resource links
- Update Contact Info

Search for:

```html
mailto:hello@vusimathonsi.co.za
```

### 2. Add New Sections

Create a new `.page-section`

Add a corresponding nav link:

```html
<a class="nav-link" data-target="new-section">New Section</a>
```

Ensure the id matches:

```html
<div id="new-section" class="page-section"></div>
```

## 📱 Responsive Breakpoints

- <strong>Mobile:</strong> < 768px
- <strong>Tablet/Desktop:</strong> ≥ 768px
- <strong>Wide layouts:</strong> ≥ 980px

## 📌 Future Improvements

- Add routing with URL hashes (`#home`, `#experience`)
- Integrate a CMS or JSON-based content system
- Add animations (e.g., Framer Motion / GSAP)
- Improve accessibility (ARIA roles, keyboard navigation)
- Add dark mode toggle

## 📄 License

All Rights Reserved

## 👤 Author

Vusi Mathonsi <br>
Maths Teacher | Housemaster | Mentor <br>
<em>Building Excellence. Rooted in Character.</em>

## 💡 Inspiration

Built to reflect:

- Clarity in teaching
- Strong mentorship values
- Clean, purposeful design
