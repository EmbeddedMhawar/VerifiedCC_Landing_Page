# VerifiedCC Landing Page

A modern, responsive landing page for VerifiedCC - an AI-powered platform that automates carbon credit verification using Hedera blockchain technology.

## 🌟 Features

- **3D Visual Elements**: Interactive sun and leaf animations that create depth and visual interest
- **Responsive Design**: Optimized for all device sizes using Tailwind CSS
- **Modern Animations**: Smooth scroll effects, hover animations, and parallax scrolling
- **Clean Architecture**: Semantic HTML structure with accessibility in mind
- **Performance Optimized**: Lightweight and fast-loading

## 🚀 Built for Hedera Africa Hackathon 2025

This landing page showcases VerifiedCC's innovative approach to solving the multi-billion dollar trust problem in the green energy economy by:

- Automating expensive manual audits ($10,000+ → automated)
- Creating tamper-proof records on Hedera's public ledger
- Using AI agents for autonomous carbon credit trading

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript** - Interactive animations and scroll effects
- **Lucide Icons** - Beautiful, customizable icons
- **Inter Font** - Modern, readable typography

## 📁 Project Structure

```
VerifiedCC_Landing_Page/
├── index.html              # Main landing page
├── verifiedcc-logo.png     # Company logo
└── README.md              # Project documentation
```

## 🎨 Design Features

### 3D Elements

- **Sun Elements**: Animated golden orbs with realistic lighting effects
- **Leaf Elements**: Organic green shapes representing sustainability
- **Parallax Scrolling**: Elements move at different speeds for depth

### Color Palette

- **Desert Sand**: `#FDB813` - Primary accent color
- **Oasis Green**: `#2E8540` - Environmental theme
- **Deep Ocean**: `#003F5C` - Professional dark blue
- **Cloud White**: `#FFFFFF` - Clean backgrounds

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/EmbeddedMhawar/VerifiedCC_Landing_Page.git
```

2. Open `index.html` in your browser or serve it using a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

3. Navigate to `http://localhost:8000` to view the landing page

## 🌐 Deployment Options

### Deploy with Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/EmbeddedMhawar/VerifiedCC_Landing_Page)

#### Manual Vercel Deployment:

1. **Install Vercel CLI:**
```bash
npm i -g vercel
```

2. **Deploy from your project directory:**
```bash
vercel
```

3. **Follow the prompts:**
   - Set up and deploy? **Y**
   - Which scope? Select your account
   - Link to existing project? **N**
   - Project name: `verifiedcc-landing-page`
   - In which directory is your code located? **./`**

4. **Your site will be live at:** `https://verifiedcc-landing-page.vercel.app`

#### Vercel Dashboard Deployment:

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **"New Project"**
3. Import your GitHub repository: `EmbeddedMhawar/VerifiedCC_Landing_Page`
4. Configure project:
   - **Framework Preset:** Other
   - **Root Directory:** ./
   - **Build Command:** (leave empty)
   - **Output Directory:** (leave empty)
5. Click **"Deploy"**

### Deploy with GitHub Pages

1. Go to your repository settings
2. Navigate to **Pages** section
3. Select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Your site will be live at: `https://embeddedmhawar.github.io/VerifiedCC_Landing_Page/`

### Deploy with Netlify

1. Go to [netlify.com](https://netlify.com) and sign in
2. Click **"New site from Git"**
3. Connect your GitHub repository
4. Deploy settings:
   - **Build command:** (leave empty)
   - **Publish directory:** (leave empty)
5. Click **"Deploy site"**

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Key Sections

1. **Hero Section** - Main value proposition with 3D sun and leaf elements
2. **Problem Section** - Highlighting industry pain points with 3D cards
3. **Solution Section** - How VerifiedCC works (3-step process with rounded boxes and arrows)
4. **Value Proposition** - Benefits and call-to-action
5. **Footer** - Contact information and links

## ✨ Latest Updates

- **3D Elements**: Added floating sun and leaf animations with parallax scrolling
- **Rounded Step Boxes**: Transformed the process steps into beautiful rounded containers
- **Connecting Arrows**: Added low-opacity arrows between steps for better flow
- **Enhanced Animations**: Improved hover effects and scroll-triggered animations
- **No Gradients**: Clean design using solid colors instead of gradients

## 🔧 Customization

### Adding New 3D Elements

```css
.custom-3d {
  width: 100px;
  height: 100px;
  background: #your-color;
  position: absolute;
  animation: float 4s ease-in-out infinite;
  box-shadow: 0 0 30px rgba(your-color, 0.3), inset -5px -5px 15px rgba(0, 0, 0, 0.1);
}
```

### Modifying Colors

Update the Tailwind config in the `<script>` section:

```javascript
colors: {
    'your-color': '#hexcode',
}
```

## 🌍 Environmental Impact

This project promotes sustainable technology solutions and represents our commitment to:

- Clean energy adoption
- Transparent carbon credit markets
- AI-driven environmental solutions
- Blockchain technology for trust

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/EmbeddedMhawar/VerifiedCC_Landing_Page/issues).

## 📞 Contact

For questions about VerifiedCC or this landing page:

- GitHub: [@EmbeddedMhawar](https://github.com/EmbeddedMhawar)
- Project Link: [https://github.com/EmbeddedMhawar/VerifiedCC_Landing_Page](https://github.com/EmbeddedMhawar/VerifiedCC_Landing_Page)

---

**Built with ❤️ for the Hedera Africa Hackathon 2025**
