# Modern Portfolio Website

A stunning, responsive portfolio website built with Next.js, Tailwind CSS, and Framer Motion. This website showcases professional work, skills, and contact information with beautiful animations and a modern design.

![Portfolio Preview](https://images.unsplash.com/photo-1460925895917-afdab827c52f?w=1200&h=630&fit=crop)

## ✨ Features

- **Responsive Design**: Fully responsive layout that looks great on all devices
- **Dark/Light Mode**: Theme toggle with system preference detection
- **Smooth Animations**: 
  - Fade-in effects
  - Typing animation
  - Scroll-triggered reveals
  - Hover interactions
- **Modern UI Components**:
  - Hero section with parallax effect
  - Project showcase grid
  - Contact form
  - Animated navigation
- **Performance Optimized**:
  - Static site generation
  - Optimized images
  - Minimal bundle size

## 🚀 Tech Stack

- **Framework**: Next.js 13
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Typography**: 
  - Playfair Display (headings)
  - Poppins (body text)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/ianmuriuki/Portfolio-Example.git
```

2. Install dependencies:
```bash
cd portfolio-website
npm install
```

3. Create a `.env` file in the root directory and add your environment variables:
```env
# Add any required environment variables here
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📁 Project Structure

```
├── app/
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx          # Home page
├── components/
│   ├── nav-menu.tsx      # Navigation menu
│   ├── theme-toggle.tsx  # Theme switcher
│   └── ui/               # UI components
├── lib/
│   └── utils.ts          # Utility functions
└── public/
    └── assets/           # Static assets
```

## 🎨 Customization

### Themes
The website supports both light and dark modes. Colors can be customized in:
- `app/globals.css`: CSS variables for theme colors
- `tailwind.config.ts`: Tailwind configuration

### Content
Update your personal information in:
- `app/page.tsx`: Main content, projects, and contact details
- `app/layout.tsx`: Site metadata
- `components/nav-menu.tsx`: Navigation links

## 📱 Responsive Design

The website is responsive across all devices:
- Mobile: 320px and up
- Tablet: 768px and up
- Desktop: 1024px and up
- Large screens: 1280px and up

## ⚡ Performance

The website is optimized for performance:
- Lazy loading of images
- Component-level code splitting
- Static site generation
- Optimized fonts with next/font
- Minified CSS and JavaScript

## 🚀 Deployment

This website can be deployed to any static hosting platform. For Netlify:

1. Push your code to GitHub
2. Connect your repository to Netlify
3. Configure build settings:
   - Build command: `npm run build`
   - Output directory: `out`

## 📄 License

This project is licensed under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

Muriuki Ian - [ianmuriuki.inc@gmail.com](mailto:ianmuriuki.inc@gmail.com)

Project Link: [https://github.com/ianmuriuki/Portfolia-Example](https://github.com/ianmuriuki/Portfolio-Example)

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Lucide Icons](https://lucide.dev/)
- [Unsplash](https://unsplash.com/) for images