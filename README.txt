Synk.ai — Light, Minimal Landing (Desktop-first)

What this is:
- Pure HTML + Tailwind (via CDN), no build step.
- Auto-play reveal animations on scroll (no sound, no forms).
- Placeholder PNGs you can replace with your own MP4s/PNGs later.

Deploy in 30 seconds (Netlify Drop):
1) Go to https://app.netlify.com/drop
2) Drag the entire 'synk-ai' folder onto the page.
3) Netlify gives you a live URL instantly.

Replace placeholders (assets/):
- hero.png      → hero.mp4 or your own hero image (keep same name if replacing image)
- chaos.png     → grid of fragmented travel apps
- demo.png      → screenshot or poster frame of your demo
- network.png   → abstract AI-network background
- before.png    → “before” comparison
- after.png     → “after” comparison

Switch to MP4 later:
Use:
<video autoplay muted playsinline loop src="./assets/hero.mp4" class="w-full h-auto object-cover"></video>

Continuous deploys (GitHub → Netlify):
- Create a repo, upload index.html + assets folder.
- In Netlify: Add new site → Import from GitHub → pick repo.
- Build command: (leave blank)
- Publish directory: /

Customize:
- Colors: CSS vars in <style> (accent #2563eb / #60a5fa).
- Sections: HERO, OLD WORLD, SYNK IN ACTION, UNDER THE HOOD, BEFORE/AFTER, VISION, FOOTER.
- Font: Inter (Google Fonts).
