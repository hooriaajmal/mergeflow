# MergeFlow - Collaborative DevOps Platform

A modern, responsive landing page for MergeFlow, a GitHub-like SaaS platform that streamlines code reviews, CI/CD, and team workflows with a delightful developer experience.

## 🌟 Features

### Interactive 3D Globe
- **Realistic Earth Visualization**: Features a beautiful 3D rotating globe with realistic textures
- **Dark/Light Mode Support**: Seamless theme switching with optimized globe visibility
- **Smooth Animations**: Continuous rotation with connection arcs between major cities
- **Responsive Design**: Adapts to different screen sizes and devices

### Modern UI/UX
- **Clean Design**: Modern, professional interface with smooth transitions
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Accessibility**: Proper ARIA labels and keyboard navigation support
- **Performance**: Optimized with Tailwind CSS and efficient Three.js rendering

### Key Sections
- **Hero Section**: Compelling headline with interactive 3D globe
- **Features**: Four key product features with icons
- **Testimonials**: Customer success stories and feedback
- **Pricing**: Three-tier pricing structure (Free, Pro, Enterprise)
- **Call-to-Action**: Clear conversion opportunities

![Hero](https://github.com/hooriaajmal/mergeflow/blob/main/mergeflow.png)

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required - everything is loaded via CDN

### Installation & Running

1. **Clone the repository**
   ```bash
   git clone [<your-repository-url>](https://github.com/hooriaajmal/mergeflow)
   cd mergeflow
   ```

2. **Run locally**
   ```bash
   # Using Python (recommended)
   python3 -m http.server 8000
   
   # Or using Node.js
   npx serve .
   
   # Or using PHP
   php -S localhost:8000
   ```

3. **Open in browser**
   ```
   http://localhost:8000/index.html
   ```

### File Structure
```
mergeflow/
├── index.html         # Main application file
└── README.md          # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Three.js**: 3D graphics library for the interactive globe
- **JavaScript (ES6+)**: Modern JavaScript for interactivity
- **WebGL**: Hardware-accelerated 3D rendering

## 🎨 Design Features

### Theme System
- **Automatic Detection**: Detects user's system preference
- **Manual Toggle**: Sun/moon icon for manual theme switching
- **Persistent Storage**: Remembers user's theme preference
- **Smooth Transitions**: Elegant theme switching animations

### 3D Globe Features
- **Realistic Textures**: High-quality earth textures with proper land/water visibility
- **Dynamic Lighting**: Adaptive lighting for both light and dark modes
- **Connection Arcs**: Animated arcs connecting major global cities
- **Performance Optimized**: Efficient rendering with proper frame rates

### Responsive Design
- **Mobile-First**: Optimized for mobile devices
- **Tablet Support**: Responsive layout for tablet screens
- **Desktop Experience**: Full-featured experience on larger screens
- **Touch-Friendly**: Optimized for touch interactions

## 📱 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ⚠️ Internet Explorer (not supported)

## 🎯 Key Features Highlighted

### One-click Deployments
Streamline your deployment process with automated workflows and audit trails.

### Policy-based Reviews
Automate approvals with branch rules, code owners, and comprehensive checks.

### Unified Insights
Get actionable metrics for DORA, flaky tests, and release health monitoring.

### Integrations
Connect with GitHub, GitLab, Slack, PagerDuty, and your favorite tools.

## 💰 Pricing Tiers

### Free
- Up to 3 users
- Private repositories
- Basic insights

### Pro ($19/user/month)
- Unlimited repositories
- Policy checks
- Advanced insights
- Slack + PagerDuty integration

### Enterprise (Custom)
- SSO/SAML, SCIM
- On-premise / VPC deployment
- 24/7 support with SLA
- Dedicated Customer Success Manager

## 🔧 Customization

### Modifying the Globe
The 3D globe can be customized by editing the Three.js configuration in the JavaScript section:

```javascript
// Add new connection arcs
addArc([latitude1, longitude1], [latitude2, longitude2], color);

// Modify globe rotation speed
globeGroup.rotation.y += t * 0.25; // Adjust the 0.25 value
```

### Theme Customization
Colors and styling can be modified in the Tailwind configuration:

```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        brand: {
          // Custom brand colors
        }
      }
    }
  }
}
```

## 📈 Performance

- **Fast Loading**: Optimized assets and efficient code
- **Smooth Animations**: 60fps globe rotation and transitions
- **Memory Efficient**: Proper cleanup and resource management
- **SEO Friendly**: Semantic HTML and proper meta tags

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- **Three.js**: For the amazing 3D graphics library
- **Tailwind CSS**: For the utility-first CSS framework
- **Three-Globe**: For inspiration on globe implementations
- **Heroicons**: For the beautiful SVG icons

## 📞 Support

For support, email support@mergeflow.com or join our Slack channel.

---
