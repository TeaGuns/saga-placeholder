# TODOS — Saga Stealth Landing Page

Pre-launch items blocked on client response. None are engineering tasks.

## BLOCKING for launch

### 1. Image rights confirmation
The painting at `assets/painting-landscape.jpg` was supplied by the client during design.
Its source and licensing have not been verified. **Cannot ship without written confirmation
from the client that they hold the rights or have a license to use this image.**

## Should-do before launch

### 2. Remove theme toggle before publishing
The "Light / Dark" toggle in the top-right corner is a developer QA helper and must be
removed (or comment-gated) before the page goes live. The toggle button, its CSS class
`.theme-toggle`, and the ~10-line JS block above the canvas animation should all be deleted.

### 3. Higher-resolution painting master
The current image (`assets/painting-landscape.jpg`) is ~1000×668px and 757KB. At the
intended canvas size (1440×900, covering 108% = ~1555×972), this will render slightly soft.
Client to provide a higher-resolution master (minimum 1600×1100 recommended).

### 4. Final domain + OG/Twitter image
Domain must be confirmed before DNS is pointed. Once confirmed, uncomment and fill in the
`og:url`, `og:image`, and `twitter:image` meta tags in `<head>`.

## Completed

### LinkedIn link → Join Us mailto (v2)
Replaced the placeholder LinkedIn link with `Join Us → mailto:team@withsaga.com`.
**Completed:** TeaGuns/tel-aviv-v2

### Favicon (v2)
Added `assets/tf-icon.png` as `<link rel="icon">` and `<link rel="apple-touch-icon">`.
**Completed:** TeaGuns/tel-aviv-v2

### Wordmark SVG (v2)
Replaced Space Grotesk amber text with `assets/saga-logo.svg` inline image, sized to
match the tagline cap height and stacked above "Knowledge is everything."
**Completed:** TeaGuns/tel-aviv-v2
