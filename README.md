# Navigation Hub

A beautiful, modern personal navigation hub that organizes your favorite websites and tools in an intuitive, searchable interface.

![Navigation Hub Preview](https://img.shields.io/badge/Status-Active-brightgreen)

## ✨ Features

- **Modern Design**: Clean, glass-morphism inspired interface with smooth animations
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Search Functionality**: Quickly find any link with real-time search (Ctrl/Cmd + K)
- **Categorized Links**: Organized into logical categories for easy navigation
- **Custom Icons**: Beautiful emoji and symbol icons for each link
- **Local & External Links**: Support for both local pages and external websites
- **Easy Configuration**: Simple JavaScript configuration for adding/editing links

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/QuellaMC/Navigation-Hub.git
   cd Navigation-Hub
   ```

2. Open `index.html` in your web browser or serve it with a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## 🛠️ Customization

### Adding New Links

Edit the `navigationData` array in `index.html` to add your own links:

```javascript
{
    category: "Your Category",
    links: [
        {
            title: "Your Site",
            url: "https://yoursite.com",
            description: "Description here",
            icon: "🌟"
        }
    ]
}
```

### Categories

The hub comes with pre-configured categories:
- **Tools**: Productivity and utility tools
- **Social Media**: Social networking platforms
- **Development**: Coding and development resources
- **Local Pages**: Internal pages and tools

### Local Tools

The project includes a local tool:
- **What To Eat**: A restaurant spinner tool (`./tools/eats.html`)

## 📱 Responsive Design

The navigation hub is fully responsive and includes:
- Mobile-optimized grid layouts
- Touch-friendly interface
- Adaptive font sizes
- Smooth animations and transitions

## 🎨 Styling

The interface features:
- Glass-morphism design with backdrop blur effects
- Gradient backgrounds
- Smooth hover animations
- Clean typography using system fonts
- Professional color scheme

## ⌨️ Keyboard Shortcuts

- `Ctrl/Cmd + K`: Focus search box

## 🌐 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📄 File Structure

```
Navigation-Hub/
├── index.html          # Main navigation hub
├── tools/
│   └── eats.html      # Restaurant spinner tool
└── README.md          # This file
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🚀 Deployment

You can easily deploy this to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting

Simply upload the files or connect your GitHub repository to your preferred hosting service.

## 📞 Support

If you have any questions or suggestions, please open an issue on GitHub.

---

Made with ❤️ by [QuellaMC](https://github.com/QuellaMC)
