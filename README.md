```markdown
# E-commerce Platform in Next.js

A modern, responsive e-commerce platform developed as a group project in Lexicon Frontend Development 2025.

![Project Banner](https://via.placeholder.com/1200x400/3B82F6/FFFFFF?text=Lexicon+E-commerce+Platform)

## 📦 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Workflow](#workflow)
- [Sprint Plan](#sprint-plan)
- [API Integration](#api-integration)
- [Contributing](#contributing)
- [Learning Outcomes](#learning-outcomes)
- [Team](#team)
- [License](#license)
- [Contact](#contact)

## 📖 About the Project

This is a group project for the Lexicon Frontend Development 2025 course, aimed at creating a complete e-commerce platform using modern web technologies. The platform displays products from an external API (DummyJSON), is fully responsive, and includes interactive features such as product filtering, dynamic routing, and an admin panel. The project provided hands-on experience working with Next.js 15 App Router, Server and Client Components, and agile teamwork using SCRUM methodology.

### Design and Attribution

The design is based on and adapted from **SHOP.CO - eCommerce Website Template** by Muhammad Bilal Akbar on Figma Community. We have:

- Used the layout structure as a foundation
- Adapted color scheme and typography
- Modified components for our specific needs
- Added our own features and sections
- Used some product images and graphic elements from the original template

**Original Design Credit:** SHOP.CO by Muhammad Bilal Akbar  
**Education:** Lexicon Frontend Development 2025  
**Project Type:** Group Work (4 people)  
**Timeframe:** 4 sprints (4 weeks)

## 🗹 Features

### User Features

- ✅ Homepage with hero section and featured products
- ✅ Product Catalog with responsive grid layout
- ✅ Product Filtering with categories and subcategories
- ✅ Product Details with dynamic routing
- ✅ Search Functionality for products
- ✅ About Us Page with company information
- ✅ Contact Page with form

### Admin Features

- ✅ Admin Panel for product management
- ✅ Create Products via form
- ✅ Edit Products with pre-filled fields
- ✅ Delete Products with confirmation
- ✅ Product List in admin view

### Technical Features

- ✅ Server Components for optimal performance
- ✅ Client Components for interactivity
- ✅ Dynamic metadata for SEO
- ✅ Responsive design for all devices
- ✅ Accessibility optimization (WAVE-tested)
- ✅ TypeScript for type safety
- ✅ Error boundaries and error handling

## ✨ Technologies

### Frameworks & Libraries

- **Next.js 15** - React framework with App Router, server-side rendering (SSR), static generation (SSG), and SEO and performance optimization
- **React 18+** - JavaScript library for building interactive and reusable user interfaces with components and Virtual DOM
- **TypeScript 5.0** - Type-safe JavaScript for better code quality and developer experience
- **Tailwind CSS 3.4** - Utility-first CSS framework for fast and responsive design with predefined classes

### UI Components & Icons

- **Shadcn/ui** - Collection of customizable and accessible React components styled with Tailwind CSS
- **Lucide React** - Open-source library with simple, scalable icons optimized for React and Next.js
- **Sonner** - Toast notifications library for user feedback

### Tools & Quality Assurance

- **ESLint** - Linting for code quality
- **Git** - Version control
- **GitHub** - Code hosting and collaboration
- **WAVE** - Web Accessibility Evaluation Tool for accessibility testing according to WCAG guidelines

### Project Management

- **Figma** - Design and prototypes
- **Trello** - Kanban board for sprint planning
- **Miro** - Retrospectives and brainstorming
- **Teams** - Team communication

### External APIs

- **DummyJSON** - REST API for product data with CRUD support

### Hosting & Deployment

- **Vercel** - Deployment platform

## 🛠️ Installation

### Prerequisites

```bash
Node.js >= 18.x
npm >= 9.x or yarn >= 1.22.x
Git >= 2.x
```

### Step-by-step

1. **Clone repository**
   ```bash
   git clone https://github.com/BlackestDawn/lexicon-ecommerce-groupproject.git
   cd lexicon-ecommerce-groupproject
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```
   or with yarn:
   ```bash
   yarn install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```
   or:
   ```bash
   yarn dev
   ```

4. **Open in browser**
   ```
   http://localhost:3000
   ```

5. **Build for production**
   ```bash
   # Create optimized build
   npm run build

   # Start production server
   npm start
   ```

6. **Code quality**
   ```bash
   # Run ESLint
   npm run lint
   ```


## 🧱 Project Structure

```
lexicon-ecommerce-groupproject/
│
├── src/
│   ├── app/                           # Next.js App Router
│   │   ├── page.tsx                  # Homepage
│   │   ├── layout.tsx                # Root layout
│   │   ├── globals.css               # Global styles
│   │   │
│   │   ├── about/
│   │   │   └── page.tsx              # About page
│   │   │
│   │   ├── contact/
│   │   │   └── page.tsx              # Contact page with form
│   │   │
│   │   ├── products/
│   │   │   ├── page.tsx              # Product list with filter
│   │   │   └── [id]/
│   │   │       └── page.tsx          # Dynamic product detail
│   │   │
│   │   └── admin/
│   │       ├── page.tsx              # Admin overview
│   │       ├── components/           # Admin components
│   │       ├── lib/                  # Admin actions
│   │       └── products/
│   │           ├── page.tsx          # Admin product list
│   │           ├── add-product/
│   │           │   └── page.tsx      # Create product
│   │           └── [id]/
│   │               └── page.tsx      # Edit product
│   │
│   ├── components/                    # Reusable components
│   │   ├── Header.tsx                # Navigation header
│   │   ├── Footer.tsx                # Footer
│   │   ├── Navbar.tsx                # Navigation menu
│   │   ├── Hero.tsx                  # Hero section
│   │   ├── FilterProducts.tsx        # Product filter
│   │   ├── FeaturedProducts.tsx      # Featured products
│   │   ├── CategorySection.tsx       # Category sections
│   │   └── Newsletter.tsx            # Newsletter
│   │
│   ├── data/                          # Data management
│   │   ├── products.ts               # API functions
│   │   └── consts.ts                 # Constants
│   │
│   ├── hooks/                         # Custom React hooks
│   │
│   └── lib/                           # Utilities
│       └── interfaces.ts             # TypeScript interfaces
│
├── public/                            # Static files
│   ├── hero-image.jpg
│   └── ...
│
├── .eslintrc.json                     # ESLint config
├── .gitignore                         # Git ignore
├── next.config.js                     # Next.js config
├── package.json                       # Dependencies
├── tailwind.config.ts                 # Tailwind config
├── tsconfig.json                      # TypeScript config
└── README.md                          # Documentation
```

## 📝 Workflow

### Agile Development with SCRUM

**Daily Activities:**
- Morning standup meetings (15 min)
- Teams for ongoing communication
- Trello for task management

**Sprint Structure:**
- 2-week sprints
- Sprint planning at start
- Sprint review at end
- Sprint retrospective with Miro

**Development Process:**
1. Select task from backlog
2. Create feature-branch from main
3. Develop functionality
4. Commit and push to GitHub
5. Create Pull Request
6. Code review by at least 1 team member
7. Merge to main after approval


## 🔄 Sprint Plan

### Sprint 1 - Basic Structure (Week 1)
**Goal:** Set up project and create basic structure

✅ **Completed:**
- Created Next.js project with TypeScript
- Configured Tailwind CSS
- Designed in Figma
- Selected DummyJSON as API
- Created GitHub repository with branch protection
- Implemented fetch functions for products
- Built homepage with hero section
- Created basic Header and Footer
- Documented in README

**Learning Outcomes:**
- Next.js 15 App Router structure
- TypeScript configuration
- Basic API integration

### Sprint 2 - Dynamic Routing & Interaction (Week 2)
**Goal:** Implement product display and filtering

✅ **Completed:**
- Created product card components
- Implemented dynamic routing for products (`/products/[id]`)
- Built product list with responsive grid
- Developed FilterProducts component
- Implemented Server/Client Component pattern
- Added CTA buttons linking to product page
- Created side navigation for categories
- Integrated category filtering with URL parameters

**Learning Outcomes:**
- Dynamic routing in Next.js
- Server vs Client Components
- State management with URL params
- Responsive design with Tailwind

### Sprint 3 - Admin & Product Management (Week 3)
**Goal:** Create admin panel for CRUD operations

✅ **Completed:**
- Built admin layout and navigation
- Created admin product list
- Implemented "Add Product" form
- Developed "Edit Product" functionality
- Added "Delete Product" with confirmation
- Created dynamic metadata for SEO
- Built contact page with form
- Implemented form validation
- Added success/error messages

**Learning Outcomes:**
- Form handling in Next.js
- Server Actions
- Data mutation
- Optimistic UI updates

### Sprint 4 - Completion & Optimization (Week 4)
**Goal:** Finalize, test and document

✅ **Completed:**
- Merged all features to main
- Code refactoring and cleanup
- Accessibility testing with WAVE
- Fixed accessibility issues
- Optimized image loading
- Implemented error boundaries
- Updated README with complete documentation
- Added code comments
- Performance optimization
- Cross-browser testing
- Mobile responsiveness testing

**Learning Outcomes:**
- Web accessibility (WCAG)
- Performance optimization
- Error handling best practices
- Documentation importance

## 🔌 API Integration

### DummyJSON API

**Base URL:** `https://dummyjson.com/`

**Endpoints Used:**

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/products` | GET | Fetch all products |
| `/products/category/{category}` | GET | Fetch products by category |
| `/products/{id}` | GET | Fetch specific product |
| `/products/search?q={query}` | GET | Search products |
| `/products/categories` | GET | Fetch all categories |

**Categories:**
- **Men:** mens-shirts, mens-shoes, mens-watches
- **Women:** womens-dresses, womens-shoes, womens-bags, womens-jewellery, womens-watches
- **Accessories:** sunglasses

**Example Request:**
```typescript
const response = await fetch('https://dummyjson.com/products/category/mens-shirts');
const data = await response.json();
```

## 🤝 Contributing

Want to contribute to the project?

### Steps for Contributing:

1. **Fork the project**
   ```bash
   git clone https://github.com/YOUR-USERNAME/lexicon-ecommerce-groupproject.git
   ```

2. **Create a feature-branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **Make your changes**
   ```bash
   git add .
   git commit -m "Add: Amazing feature"
   ```

4. **Push to your fork**
   ```bash
   git push origin feature/amazing-feature
   ```

5. **Create a Pull Request**
   - Go to GitHub
   - Click "New Pull Request"
   - Describe your changes clearly
   - Wait for code review

### Design Attribution:
If you use graphic elements, please respect that the design is based on SHOP.CO template by Muhammad Bilal Akbar.

## 👨‍🏫 Learning Outcomes

### Technical Skills

**Frontend:**
- Next.js 15 App Router and Server Components
- TypeScript for type-safe development
- Tailwind CSS for responsive design
- Async/await and Promise handling
- RESTful API integration
- Component-based architecture
- React Hooks (useState, useSearchParams, usePathname)
- Mobile-first responsive design
- Web Accessibility (WCAG)

**Tools & Processes:**
- Git workflow and version control
- Collaboration on GitHub with Pull Requests
- Agile development with SCRUM
- Sprint planning and backlog management
- Retrospectives and continuous improvement
- Debugging and problem-solving

## 👥 Team

This project was developed by:

| Name | GitHub | 
|------|--------|
| Federico Barberi | [@fdrcbrbr](https://github.com/fdrcbrbr)
| Isabelle Wincrantz | [@Discokatten](https://github.com/Discokatten)
| Alexander Stauch | [@BlackestDawn](https://github.com/BlackestDawn)
| Lorenzo Dastoli | [@Looziolooz](https://github.com/Looziolooz)

**Course:** Lexicon Frontend Development 2025  

## ™️ License

This project was developed for educational purposes as part of Lexicon Frontend Development 2025.

**License:** CC0 1.0 Universal  
The project is available to the public and can be used, modified, and distributed freely.


**Repository:** https://github.com/looziolooz/lexicon-ecommerce-group-project

**Live Demo:** [https://lexicon-ecommerce-group-project.vercel.app/]

## 🙏 Acknowledgments

- Lexicon for education and support
- Muhammad Bilal Akbar for SHOP.CO design template on Figma Community
- DummyJSON for free API
- Next.js Team for excellent documentation
- Open Source Community for tools and libraries

## 📄 License & Attribution

**License:** CC0 1.0 Universal  
This project was developed for educational purposes as part of Lexicon Frontend Development 2025.

**Design Attribution:**  
Design based on SHOP.CO - eCommerce Website Template by Muhammad Bilal Akbar.  
We have adapted and modified the design for our specific project needs.

---

**Created with ❤️ by Lexicon Frontend Development 2025**
```


