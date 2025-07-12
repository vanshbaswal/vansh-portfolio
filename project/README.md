# Vansh Baswal - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Data Scientist and AI Enthusiast.

## 🌟 Features

- **Modern Design**: Dark theme with animated stars and waves
- **Responsive Layout**: Works perfectly on all devices
- **Interactive Elements**: Smooth animations and hover effects
- **Professional Sections**: Hero, About, Skills, Projects, Blog, Resume, and Contact
- **Animated Background**: Twinkling stars and flowing waves
- **Contact Form**: Ready for integration with form services
- **Social Links**: Direct links to LinkedIn, GitHub, Instagram, and email

## 🚀 Technologies Used

- HTML5
- CSS3 (with animations and gradients)
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts (Inter)

## 📁 Project Structure

```
project/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript functionality
├── public/             # Assets directory
│   ├── vansh image.jpg # Hero profile image
│   └── My Resume.pdf   # Resume file
└── README.md           # This file
```

## 🛠️ Local Development

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd project-bolt-sb1-mgtxubme/project
   ```

2. **Start local server**:
   ```bash
   # Using Python (recommended)
   python -m http.server 8000
   
   # Or using Node.js
   npx serve .
   ```

3. **Open in browser**:
   ```
   http://localhost:8000
   ```

## 📤 Deployment to Netlify

### Method 1: Deploy from GitHub (Recommended)

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git push origin main
   ```

2. **Deploy on Netlify**:
   - Go to [netlify.com](https://netlify.com)
   - Click "New site from Git"
   - Connect your GitHub account
   - Select your repository
   - Set build settings:
     - **Build command**: Leave empty (static site)
     - **Publish directory**: `project` (or root if you move files)
   - Click "Deploy site"

### Method 2: Drag & Drop

1. **Prepare files**: Make sure all files are in the `project` directory
2. **Drag folder**: Drag the `project` folder to Netlify's deploy area
3. **Get URL**: Netlify will provide a live URL instantly

## ⚙️ Customization

### Colors and Theme
- Edit `styles.css` to change colors, gradients, and animations
- Main colors are defined in CSS variables at the top of the file

### Content
- Update `index.html` to modify text content
- Replace images in the `public/` directory
- Update social media links in the navigation and footer

### Animations
- Modify star animation in `script.js`
- Adjust wave animation in `styles.css`
- Customize button and hover effects

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

## 📞 Contact

- **Email**: vanshbaswal2005@gmail.com
- **LinkedIn**: [Vansh Baswal](https://www.linkedin.com/in/vansh-baswal-61b90b292)
- **GitHub**: [vanshbaswal](https://github.com/vanshbaswal)
- **Instagram**: [@thevanshbaswal](https://www.instagram.com/thevanshbaswal/)

---

**Note**: Make sure to update the resume file path and social media links before deployment. 