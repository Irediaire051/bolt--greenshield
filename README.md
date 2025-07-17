# GreenShield Pest Management Website

A professional pest control website built with React, TypeScript, and Tailwind CSS. Features a modern design with comprehensive service information, interactive tools, and booking capabilities.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with beautiful UI/UX
- **Service Categories**: Residential, Commercial, Industrial, and Eco-Friendly solutions
- **Interactive Tools**:
  - Pest Identification Tool
  - Cost Calculator
  - Online Booking System
  - Quote Request Forms
- **Rich Content**: Pest information, testimonials, news articles
- **Professional Design**: Modern aesthetics with accessibility features

## 🛠️ Technology Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Linting**: ESLint

## 📁 Project Structure

```
greenshield-pest-management/
├── public/
│   └── (static assets)
├── src/
│   ├── components/
│   │   ├── Header.tsx              # Navigation header
│   │   ├── Hero.tsx                # Hero section with CTA
│   │   ├── CommonPests.tsx         # Pest information grid
│   │   ├── Services.tsx            # Service offerings
│   │   ├── ServiceCategories.tsx   # Service category cards
│   │   ├── WhyChooseUs.tsx         # Company benefits
│   │   ├── Testimonials.tsx        # Customer reviews
│   │   ├── LatestNews.tsx          # Blog/news section
│   │   ├── Footer.tsx              # Site footer
│   │   ├── QuoteRequestForm.tsx    # Quote request modal
│   │   ├── PestCalculator.tsx      # Cost estimation tool
│   │   ├── PestIdentificationTool.tsx # Pest ID wizard
│   │   └── BookingSystem.tsx       # Appointment booking
│   ├── app/
│   │   └── page.tsx                # Main page component
│   ├── styles/
│   │   └── globals.css             # Global styles and utilities
│   ├── App.tsx                     # Root application component
│   └── main.tsx                    # Application entry point
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── vite.config.ts
```

## 🎯 Key Components

### Core Pages
- **Header**: Responsive navigation with contact info and mobile menu
- **Hero**: Main landing section with value propositions and CTAs
- **Services**: Detailed service offerings with pricing and features
- **Common Pests**: Educational content about pest types and treatments

### Interactive Features
- **Booking System**: Multi-step appointment scheduling
- **Pest Calculator**: Dynamic cost estimation based on user inputs
- **Pest Identification**: Step-by-step pest identification wizard
- **Quote Forms**: Lead generation with comprehensive form validation

### Content Sections
- **Testimonials**: Customer reviews with ratings and photos
- **Why Choose Us**: Company differentiators and certifications
- **Latest News**: Blog articles and educational content
- **Footer**: Contact information and additional links

## 🎨 Design System

### Colors
- **Primary Green**: #059669 (brand color for trust/nature)
- **Secondary Orange**: #EA580C (CTAs and highlights)
- **Accent Blue**: #2563EB (informational elements)
- **Success**: #16A34A
- **Warning**: #CA8A04
- **Error**: #DC2626

### Typography
- **Font**: Inter (clean, professional)
- **Headings**: Bold, hierarchical sizing
- **Body**: Readable line height (1.6)

### Layout
- **Responsive**: Mobile-first design
- **Grid System**: CSS Grid and Flexbox
- **Spacing**: 8px base unit system
- **Shadows**: Subtle depth for cards and modals

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd greenshield-pest-management

# Install dependencies
npm install

# Start development server
npm run dev
```

### Build for Production
```bash
npm run build
npm run preview
```

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px

## ♿ Accessibility Features

- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- Screen reader compatibility
- High contrast color ratios
- Focus indicators
- Reduced motion support

## 🔧 Development Guidelines

### Component Structure
- Use TypeScript for type safety
- Implement proper prop interfaces
- Follow React best practices
- Use custom hooks for complex logic

### Styling Conventions
- Tailwind CSS utility classes
- Custom CSS for complex animations
- Responsive design patterns
- Dark mode support (optional)

### Code Quality
- ESLint configuration
- TypeScript strict mode
- Component documentation
- Consistent naming conventions

## 🚀 Deployment

The application is optimized for deployment on:
- Netlify
- Vercel
- AWS S3 + CloudFront
- Any static hosting provider

Build artifacts are generated in the `dist/` directory.

## 📝 License

This project is proprietary and confidential.

## 🤝 Contributing

Please follow the established coding standards and submit pull requests for review.

## 📞 Support

For technical support or questions, contact the development team.