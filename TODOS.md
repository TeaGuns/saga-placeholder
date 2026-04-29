# TODOS — Saga Stealth Landing Page

Pre-launch items blocked on client response. None are engineering tasks.

## BLOCKING for launch

### 1. Image rights confirmation
The painting at `assets/painting-landscape.jpg` was supplied by the client during design.
Its source and licensing have not been verified. **Cannot ship without written confirmation
from the client that they hold the rights or have a license to use this image.**

### 2. LinkedIn URL
The LinkedIn link currently has a placeholder `href`. Client must provide the final URL.
Until then, the link is non-functional.

## Should-do before launch

### 3. Higher-resolution painting master
The current image (`assets/painting-landscape.jpg`) is ~1000×668px and 757KB. At the
intended canvas size (1440×900, covering 108% = ~1555×972), this will render slightly soft.
Client to provide a higher-resolution master (minimum 1600×1100 recommended).

### 4. Favicon + final domain
Page needs a favicon. Client to decide on a favicon (simple lettermark or solid square
in `#0e0c08` works). Domain must be confirmed before DNS is pointed.

## Nice-to-have

### 5. Wordmark SVG
The "Saga" text is currently rendered in Space Grotesk amber (`#ffb766`). The spec notes
the client will supply an SVG wordmark later. When it arrives, swap the `<span>Saga</span>`
for the SVG mark, sized to match a 36px cap height.
