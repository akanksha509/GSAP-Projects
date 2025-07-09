# SPYLT 

A modern React website for SPYLT protein drinks featuring smooth GSAP animations, responsive design, and immersive user experiences.

## Demo

**Live Demo:** [SPYLT](https://gsap-projects-omega.vercel.app/)

> Experience the full interactive animations and smooth scrolling effects in the live demo!

## Features

- **Smooth Scroll Animations** - GSAP ScrollTrigger and ScrollSmoother
- **Interactive Flavor Slider** - Horizontal scrolling product showcase  
- **Video Integration** - Hero background videos and testimonials
- **Responsive Design** - Mobile-first approach with breakpoint-specific animations
- **Split Text Animations** - Character and word-level text reveals
- **Clip Path Animations** - Creative geometric transitions
- **Pin Sections** - Scroll-triggered pinned content areas
- **Video Hover Controls** - Play/pause on hover in testimonials

## Tech Stack

- **React 18** - Modern React with hooks
- **GSAP 3** - Professional-grade animations
- **Tailwind CSS** - Utility-first styling
- **Vite** - Fast build tool and dev server
- **React Responsive** - Responsive design hooks

### GSAP Plugins Used
- ScrollTrigger
- ScrollSmoother
- SplitText

## Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/akanksha509/GSAP-Projects.git
   cd GSAP-Projects/SPYLT
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
SPYLT/
├── public/
│   ├── images/                
│   ├── videos/                 
│   └── fonts/                  
├── src/
│   ├── components/             
│   │   ├── ClipPathTitle.jsx   
│   │   ├── FlavorSlider.jsx    
│   │   ├── FlavorTitle.jsx     
│   │   ├── NavBar.jsx          
│   │   └── VideoPinSection.jsx 
│   ├── constants/
│   │   └── index.js            
│   ├── sections/              
│   │   ├── BenefitSection.jsx  
│   │   ├── FlavorSection.jsx   
│   │   ├── FooterSection.jsx   
│   │   ├── HeroSection.jsx     
│   │   ├── MessageSection.jsx  
│   │   ├── NutritionSection.jsx 
│   │   └── TestimonialSection.jsx 
│   ├── App.jsx                 
│   ├── index.css              
│   └── main.jsx               
├── tailwind.config.js         
├── vite.config.js            
└── package.json               
```

## Key Animations

### Scroll-Triggered Animations
- Hero section rotation and scaling
- Flavor slider horizontal scroll (desktop)
- Split text character reveals
- Clip-path title reveals
- Video circular expand

### Interactive Elements
- Testimonial video hover play/pause
- Smooth scroll transitions

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
