# 🚀 Bilal's Portfolio Website

Welcome to my little corner of the internet! This is where I pretend to be a serious software engineer while secretly being excited about making LEDs blink.

## 🎯 What's This About?

This portfolio website is built with Astro because... well, it's fast, it's cool, and it lets me write less JavaScript (which my future self will thank me for). It features:

- ⚡ **Lightning-fast static site** - Loads faster than you can say "is it responsive?"
- 🌙 **Dark mode** - For those 3 AM coding sessions (we've all been there)
- 📱 **Mobile-friendly** - Looks good on everything from phones to those ancient tablets your parents still use
- 🎨 **Minimal design** - Because I spent more time choosing fonts than building features
- 🤖 **Easily extensible** - Ready for when I inevitably add a blog that I'll update twice

## 🛠️ Tech Stack (The Good Stuff)

- **Astro** - The new shiny thing that makes static sites less static
- **Tailwind CSS** - For when you want to write CSS in your HTML and feel good about it
- **TypeScript** - Because `any` is not a type, fight me
- **GitHub Pages** - Free hosting that actually works
- **MDX** - Markdown with superpowers (unused but ready for when I get ambitious)

## 🏠 Running This Thing Locally

1. **Clone it** (you know the drill):

   ```bash
   git clone https://github.com/MBilalShafi/MBilalShafi.github.io
   cd MBilalShafi.github.io
   ```

2. **Install the dependencies** (warning: may take longer than expected):

   ```bash
   pnpm install
   ```

3. **Fire it up**:

   ```bash
   pnpm run dev
   ```

4. **Visit** `http://localhost:4321` and pretend you're impressed

## 🌐 Live Site

The portfolio is live at **[bilalshafi.dev](https://bilalshafi.dev)** - because custom domains make everything look more professional, right?

## 🎭 Fun Facts About This Site

- The profile picture was taken after my 47th attempt to look "casually professional"
- I spent 3 hours perfecting the shadow on that image (priorities, right?)
- The color scheme was inspired by my coffee cup collection
- There are exactly zero jQuery dependencies (we've evolved)
- The dark mode toggle was the first thing I built because aesthetics > functionality

## 🔧 Behind the Scenes

This site is deployed automatically via GitHub Actions, which means I can push broken code and have it live in under 5 minutes. Modern problems require modern solutions!

The build process:

1. GitHub Actions wakes up
2. Runs `pnpm install` (probably fails once for good measure)
3. Builds the site with `pnpm run build`
4. Deploys to GitHub Pages
5. Sends me an email that I'll check in 3 hours

## 🤓 For the Curious Developers

### Project Structure

```
├── public/           # Static files (including that perfectly cropped profile pic)
├── src/
│   ├── components/   # Reusable components (all 4 of them)
│   ├── layouts/      # Page layouts (singular, because minimalism)
│   ├── pages/        # The actual pages (currently just one)
│   └── styles/       # Global styles (mostly Tailwind imports)
├── astro.config.mjs  # The magic configuration
└── README.md         # This masterpiece
```

### Available Scripts

- `pnpm run dev` - Start the development server (and immediately break something)
- `pnpm run build` - Build for production (cross your fingers)
- `pnpm run preview` - Preview the production build locally
- `pnpm run astro` - Access Astro CLI commands (for when you want to feel fancy)

## 🎨 Customization Tips

Want to make this your own? Here's what you should probably change:

1. **Replace my face** with yours in `public/profile.jpg`
2. **Update the text** to be about you (revolutionary concept)
3. **Change the colors** if you don't like my exquisite taste
4. **Add your own social links** in `SocialLinks.astro`
5. **Deploy to your own domain** (don't steal my 15 minutes of fame)
6. **Set up your DNS** to point to GitHub Pages (if using a custom domain)

## 🐛 Known "Features"

- The theme toggle occasionally has an existential crisis
- Profile image might look slightly different on Internet Explorer (if you're still using IE, we need to talk)
- Some CSS classes are named with the creativity of a tired developer at 2 AM

## 📄 License

MIT License - aka "do whatever you want with this code, just don't blame me when it breaks"

---

Built with ❤️, ☕, and a healthy dose of impostor syndrome.

_P.S. If you found a bug, it's not a bug, it's a feature. If you found a typo... well, that's just embarrassing._
