# Avinash Watgure Portfolio

A modern, responsive portfolio website showcasing data science and analytics projects. Built with React, TypeScript, Vite, and Tailwind CSS.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Project Filtering**: Filter projects by category (Machine Learning, Analytics, Dashboards)
- **Modern UI**: Clean and professional design with smooth animations
- **Fast Performance**: Optimized with Vite for lightning-fast loading
- **SEO Optimized**: Proper meta tags and structured data

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS, shadcn/ui components
- **Build Tool**: Vite
- **Routing**: React Router DOM
- **Deployment**: GitHub Pages

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Page components
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
└── main.tsx           # App entry point
```

## 🚀 Deployment to GitHub Pages

### Prerequisites
- GitHub account
- Node.js (v18 or higher)
- npm or yarn

### Step 1: Prepare Your Repository

1. **Push your code to GitHub**:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Navigate to `Settings` → `Pages`
   - Under "Source", select `GitHub Actions`
   - Click `Save`

### Step 2: Automatic Deployment

The project is configured with GitHub Actions for automatic deployment:

1. **Push changes to main branch**:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push origin main
   ```

2. **Monitor deployment**:
   - Go to your repository → `Actions` tab
   - Watch the "Deploy to GitHub Pages" workflow
   - Wait for it to complete (usually 2-3 minutes)

3. **Access your site**:
   - Your portfolio will be available at: `https://[your-username].github.io/avinash-portfolio-online-main/`

### Step 3: Custom Domain (Optional)

To use a custom domain:

1. **Add custom domain**:
   - Go to repository `Settings` → `Pages`
   - Enter your domain in "Custom domain" field
   - Click `Save`

2. **Update Vite config**:
   ```typescript
   // vite.config.ts
   base: mode === 'production' ? '/' : '/',
   ```

## 🏃‍♂️ Local Development

### Install Dependencies
```bash
npm install
```

### Start Development Server
```bash
npm run dev
```

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run build:prod` - Build for production with production mode
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run deploy` - Build and prepare for deployment

## 🎨 Customization

### Adding New Projects
1. Edit `src/components/Projects.tsx` or `src/pages/Projects.tsx`
2. Add new project object to the `projects` array
3. Include `category` property for filtering

### Styling
- Modify `tailwind.config.ts` for theme customization
- Update component styles in respective `.tsx` files
- Global styles in `src/index.css`

## 🔧 Troubleshooting

### Common Issues

1. **Build fails**:
   - Check Node.js version (should be 18+)
   - Clear node_modules and reinstall: `rm -rf node_modules && npm install`

2. **GitHub Pages not updating**:
   - Check GitHub Actions tab for deployment status
   - Ensure changes are pushed to main branch
   - Clear browser cache

3. **Routing issues**:
   - Ensure base URL is correctly set in `vite.config.ts`
   - Check that React Router is properly configured

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

**Built with ❤️ by Avinash Watgure**
