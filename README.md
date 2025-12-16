![CodeRabbit Pull Request Reviews](https://img.shields.io/coderabbit/prs/github/Ayush04-C/Apple-Web-Clone?utm_source=oss&utm_medium=github&utm_campaign=Ayush04-C%2FApple-Web-Clone&labelColor=171717&color=FF570A&link=https%3A%2F%2Fcoderabbit.ai&label=CodeRabbit+Reviews)


# Apple MacBook Pro Clone

A stunning, interactive clone of Apple's MacBook Pro product page built with modern web technologies. This project showcases advanced 3D rendering, smooth animations, and responsive design to create an immersive user experience.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-0AE46A?style=for-the-badge&logo=greensock&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 🌟 Features

- **Interactive 3D MacBook Models** - Fully rotatable 3D models with customizable colors and sizes
- **Smooth Animations** - Professional-grade animations powered by GSAP
- **Responsive Design** - Optimized for all device sizes
- **Immersive Scrolling Experience** - Pinning and scrubbing effects throughout the page
- **Dynamic Content Loading** - Video textures and dynamic model switching

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| [React 19](#react-components) | Core framework for building UI components |
| [Three.js](#3d-rendering) | 3D rendering and WebGL integration |
| [@react-three/fiber](#3d-rendering) | React renderer for Three.js |
| [@react-three/drei](#3d-rendering) | Useful helpers for Three.js |
| [GSAP](#animations) | High-performance animations and scroll effects |
| [@gsap/react](#animations) | React plugin for GSAP |
| [Tailwind CSS](#styling) | Utility-first CSS framework |
| [@tailwindcss/vite](#styling) | Tailwind CSS integration with Vite |
| [Zustand](#state-management) | Lightweight state management |
| [Vite](#build-tools) | Fast build tool and development server |


## 📁 Project Structure

```
src/
├── components/
│   ├── models/           # 3D model components
│   ├── three/            # Three.js utilities
│   ├── Features.jsx      # Feature showcase section
│   ├── Footer.jsx        # Page footer
│   ├── Hero.jsx          # Hero section with video
│   ├── Highlights.jsx    # Product highlights
│   ├── NavBar.jsx        # Navigation bar
│   ├── Performance.jsx   # Performance section
│   ├── ProductViewer.jsx # 3D product viewer
│   └── Showcase.jsx      # Product showcase
├── constants/            # Application constants
├── store/                # Zustand state management
├── App.jsx              # Main application component
├── index.css            # Global styles
└── main.jsx             # Entry point
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone <repository-url>

# Navigate to the project directory
cd apple-web-clone

# Install dependencies
npm install

# Start the development server
npm run dev
```

### Build for Production

```bash
# Build the project
npm run build

# Preview the production build
npm run preview
```

## 🎯 Key Components

### [React Components](#react-components)

The application is structured into modular React components, each responsible for a specific section of the page:

- **[NavBar](./src/components/NavBar.jsx)** - Navigation header with Apple branding
- **[Hero](./src/components/Hero.jsx)** - Opening section with title video
- **[ProductViewer](./src/components/ProductViewer.jsx)** - Interactive 3D MacBook viewer
- **[Showcase](./src/components/Showcase.jsx)** - Product showcase with pinned scrolling
- **[Performance](./src/components/Performance.jsx)** - Performance metrics visualization
- **[Features](./src/components/Features.jsx)** - Feature highlights with 3D integration
- **[Highlights](./src/components/Highlights.jsx)** - Product specification highlights
- **[Footer](./src/components/Footer.jsx)** - Page footer with legal links

### [3D Rendering](#3d-rendering)

The project leverages Three.js through React Three Fiber for 3D rendering:

- **Model Components** - Auto-generated GLTF models with dynamic coloring
- **Studio Lights** - Consistent lighting setup for 3D scenes
- **Model Switcher** - Smooth transitions between MacBook sizes
- **Presentation Controls** - Interactive model rotation and positioning

### [Animations](#animations)

GSAP powers all animations and scroll-triggered effects:

- **Scroll Triggers** - Pinning and scrubbing effects for immersive scrolling
- **Timeline Sequences** - Coordinated animations across components
- **Model Transitions** - Smooth switching between 3D models
- **DOM Animations** - Fade-ins, position shifts, and opacity changes

### [State Management](#state-management)

Zustand provides lightweight state management for:

- **Color Selection** - Tracking user-selected MacBook colors
- **Size Selection** - Managing MacBook size preferences
- **Texture States** - Handling dynamic video textures for features
- **Global Reset** - Resetting to default states

### [Styling](#styling)

Tailwind CSS with custom configurations provides:

- **Utility Classes** - Rapid UI development with predefined classes
- **Custom Utilities** - Flex helpers, positioning, and typography
- **Component Styles** - Scoped styling for each section
- **Responsive Design** - Mobile-first approach with breakpoints

### [Build Tools](#build-tools)

Vite provides lightning-fast development:

- **Hot Module Replacement** - Instant updates during development
- **Optimized Builds** - Production-ready bundles
- **ES Module Support** - Native ES module handling

## 🎨 Design Highlights

1. **Immersive Scrolling** - Sections pin and animate as users scroll
2. **Interactive 3D Models** - Users can rotate and customize MacBook appearances
3. **Dynamic Content** - Video textures update based on selected features
4. **Responsive Masonry** - Adapts layout for all screen sizes
5. **Gradient Effects** - Apple-inspired gradient borders and text effects

## 📱 Responsive Features

- Mobile-optimized layouts with touch-friendly controls
- Adaptive 3D model scaling for different viewports
- Scroll-aware animations that work on all devices
- Flexible grid systems for content presentation


# Preview

<img width="1900" height="868" alt="image" src="https://github.com/user-attachments/assets/fef4c65f-7b4d-4dd2-a2a7-9313cdcdbe43" />


## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

