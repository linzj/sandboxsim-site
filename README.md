# SandboxSim website

The product site for SandboxSim, served by GitHub Pages at
https://linzj.github.io/sandboxsim-site/ from the root of `main`.

- `index.html`: home page, Simplified Chinese
- `en/index.html`: home page, English
- `terms.html`, `privacy.html`, `refund.html`: legal pages, Chinese then English (`#en`)
- `style.css`: shared styles, light and dark
- `icon.png`, `favicon.png`: the app icon, from the app's asset catalog
- `demo.mp4`, `demo-poster.jpg`: the Chinese home page's demo, a new machine's window from opening to Setup Assistant (0.14, recorded with ScreenCaptureKit, 24 s, 1280x760)
- `en/demo.mp4`, `en/demo-poster.jpg`: the same in English, the app and the guest both (0.15, a template made with SANDBOX_LANG=en:0, 24 s, 1280x762)

Plain HTML with no build step; `.nojekyll` keeps Pages from running Jekyll.

Support questions go to this repository's issues.
