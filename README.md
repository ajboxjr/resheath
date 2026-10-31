# ReSheath — mobile-first coming soon site

This is a static GitHub Pages site. Upload `index.html`, `favicon.svg`, and the `assets` directory to the root of your GitHub repository, then enable Pages under Settings → Pages.

Features: mobile-first full-viewport splash hero, original ReSheath vector card artwork, subtle floating movement (disabled for visitors who prefer reduced motion), streamlined product details, no front/back gallery.

## Connect subscriptions (required before launch)
The subscribe form saves nothing until it has somewhere to send emails. Create a form at a service such as Formspree, paste its URL into `SUBSCRIBE_ENDPOINT` in `index.html`, and submit a test.

## Adding your product video later
Export a compressed, muted, looping MP4/WebM from Spline or Blender. Add it under `assets/` and replace the `.visual` image container with a video element using `autoplay muted loop playsinline poster="assets/..."`. Keep a static poster image for slower connections and reduced-motion visitors.

## Product claims
Do not claim ReSheath certifies authenticity or replaces official mint packaging. Confirm dimensional compatibility for bars in each size before advertising universal fit.
