# MangaVerse - Modern Manga Reading Website

A beautiful, animated manga reading website built with Next.js that aggregates content from MangaDex.

## ✨ Features

### 🎨 **Modern UI/UX Design**
- **Dark theme** with beautiful gradients and glass effects
- **Responsive design** that works on all devices
- **Custom color palette** with primary orange theme
- **Typography** using Inter font for excellent readability

### 🎭 **Smooth Animations & Micro-interactions**
- **Framer Motion** powered animations throughout the interface
- **Smooth hover effects** with scale and color transitions
- **Gentle tilt effects** on interactive elements
- **Scroll-based animations** that trigger on viewport entry
- **Animated glitch-style** text effects for titles
- **Inertia-based scroll** with smooth transitions
- **Floating elements** in the hero section
- **Staggered animations** for lists and grids

### 🔍 **Manga Search & Discovery**
- **MangaDex search** with comprehensive coverage
- **Advanced filtering** by genre, status, and more
- **Real-time search** with debounced input
- **Popular genres** quick filter buttons
- **Source selection** with visual indicators

### 📚 **Manga Management**
- **Featured manga** showcase with beautiful cards
- **Detailed manga information** including ratings, views, and chapters
- **Genre tags** with hover effects
- **Status indicators** (Ongoing/Completed)
- **Author information** and descriptions

### 🚀 **Performance & UX**
- **Next.js 14** with App Router for optimal performance
- **TypeScript** for type safety and better development experience
- **Tailwind CSS** for utility-first styling
- **Optimized images** with Next.js Image component
- **Lazy loading** and intersection observer for smooth scrolling
- **Mobile-first** responsive design

## 🛠️ Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **State Management**: React Hooks
- **API Integration**: Fetch API with error handling

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd manga-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🚀 Building for Production

```bash
npm run build
npm start
```

## 📁 Project Structure

```
manga-website/
├── app/                    # Next.js App Router
│   ├── globals.css        # Global styles and Tailwind imports
│   ├── layout.tsx         # Root layout component
│   └── page.tsx           # Home page
├── components/             # React components
│   ├── ui/                # Reusable UI components
│   │   ├── AnimatedCard.tsx   # Tilt effect card component
│   │   └── GlitchText.tsx     # Glitch text effect component
│   ├── Navigation.tsx     # Navigation bar with scroll effects
│   ├── HeroSection.tsx    # Hero section with floating elements
│   ├── SearchSection.tsx  # Search interface with source selection
│   ├── FeaturedManga.tsx # Manga grid with hover effects
│   └── Footer.tsx         # Footer with animated links
├── lib/                   # Utility functions
│   └── api.ts            # API integration for manga sources
├── public/                # Static assets
├── tailwind.config.js     # Tailwind CSS configuration
├── next.config.js         # Next.js configuration
├── tsconfig.json          # TypeScript configuration
└── package.json           # Dependencies and scripts
```

## 🎯 Key Components

### **AnimatedCard**
- 3D tilt effect on mouse movement
- Configurable intensity and scale options
- Smooth spring animations
- Glow effect support

### **GlitchText**
- Animated glitch effects for text
- Configurable intensity and duration
- Multiple color layers for authentic glitch look
- Automatic triggering with intervals

### **Navigation**
- Transparent to solid background on scroll
- Smooth backdrop blur effects
- Mobile-responsive hamburger menu
- Animated logo and navigation items

### **HeroSection**
- Floating animated elements
- Gradient backgrounds
- Staggered text animations
- Interactive CTA buttons

## 🔌 API Integration

The website integrates with MangaDex:

### **MangaDex**
- Full API integration based on official OpenAPI specification
- Search functionality with advanced filters
- Manga details and chapters
- Cover art support
- Comprehensive manga metadata

## 🎨 Customization

### **Colors**
Edit `tailwind.config.js` to customize the color scheme:
```javascript
colors: {
  primary: {
    50: '#fef7ee',
    100: '#fdedd6',
    // ... more shades
  },
  dark: {
    50: '#f8fafc',
    // ... more shades
  }
}
```

### **Animations**
Customize animations in `tailwind.config.js`:
```javascript
animation: {
  'fade-in': 'fadeIn 0.5s ease-in-out',
  'slide-up': 'slideUp 0.5s ease-out',
  // ... more animations
}
```

### **Components**
All components are highly customizable through props and CSS classes.

## 📱 Responsive Design

- **Mobile-first** approach
- **Breakpoints**: sm (640px), md (768px), lg (1024px), xl (1280px)
- **Touch-friendly** interactions
- **Optimized layouts** for all screen sizes

## 🚀 Performance Features

- **Code splitting** with Next.js
- **Image optimization** with Next.js Image
- **Lazy loading** for components
- **Intersection Observer** for scroll animations
- **Optimized animations** with Framer Motion

## 🔮 Future Enhancements

- [ ] **User authentication** and profiles
- [ ] **Reading lists** and favorites
- [ ] **Chapter reading** interface
- [ ] **Real-time updates** and notifications
- [ ] **Advanced search filters**
- [ ] **Manga recommendations**
- [ ] **Social features** (comments, ratings)
- [ ] **Offline reading** support
- [ ] **PWA capabilities**

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **MangaDex** for providing the manga API
- **Framer Motion** for amazing animation capabilities
- **Tailwind CSS** for the utility-first CSS framework
- **Next.js team** for the excellent React framework

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub
- Check the documentation
- Contact the development team

---

**Made with ❤️ for manga lovers everywhere**
