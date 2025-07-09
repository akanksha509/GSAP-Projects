# Zentry Interactive 

A cutting-edge interactive portfolio website featuring immersive 3D animations, smooth scrolling effects, and interactive elements powered by GSAP. Built with React and Tailwind CSS.

**Live Demo:** (https://zentry-interactive.vercel.app)

> Experience the full interactive animations and 3D effects in the live demo!

##  Features

- **Advanced GSAP Animations** - Complex timeline animations with ScrollTrigger
- **3D Interactive Elements** - Mouse-following parallax effects and 3D transformations
- **Smooth Scrolling** - Buttery smooth scroll-triggered animations
- **Responsive Design** - Fully responsive across all devices
- **Video Integration** - Interactive video previews with custom controls
- **Modern UI/UX** - Clean, gaming-inspired interface with hover effects
- **Audio Integration** - Background audio with visual indicators
- **Floating Navigation** - Dynamic navbar with scroll-based visibility
- **Bento Grid Layout** - Modern card-based feature showcase

## Tech Stack

- **React 18** - Modern React with hooks
- **GSAP 3** - Professional-grade animations
- **Tailwind CSS** - Utility-first styling
- **Vite** - Fast build tool and dev server

## Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/akanksha509/GSAP-Projects.git
   cd GSAP-Projects/Zentry
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## Project Structure

```
Zentry/
├── public/
│   ├── img/                   
│   ├── videos/                 
│   ├── audio/                 
│   └── fonts/                  
├── src/
│   ├── components/
│   │   ├── About.jsx           # About section with clip animations
│   │   ├── AnimatedTitle.jsx   # Reusable animated title component
│   │   ├── Button.jsx          # Interactive button component
│   │   ├── Contact.jsx         # Contact section
│   │   ├── Features.jsx        # Bento grid features showcase
│   │   ├── Footer.jsx          # Footer with social links
│   │   ├── Hero.jsx            # Hero section with video carousel
│   │   ├── Navbar.jsx          # Floating navigation
│   │   ├── Story.jsx           # Interactive story section
│   │   └── VideoPreview.jsx    # 3D video preview component
│   ├── App.jsx                 
│   ├── main.jsx                
│   └── index.css               
├── tailwind.config.js          
├── vite.config.js              
└── package.json                
```

## Key Animations

### Scroll-Triggered Animations
- Hero video clip path reveal
- About section image expansion
- Title word-by-word animations
- Feature cards entrance effects

### Interactive Animations
- 3D hover effects on components
- Mouse-following parallax
- Video transition effects
- Button hover transformations

## Deployment

### Build Commands
```bash
# Development
npm run dev

# Production build
npm run build

# Preview production build
npm run preview
```
