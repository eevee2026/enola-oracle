# ENOLA V2 · Static verification

## Passed
- V2 HTML, CSS and JS files committed to branch v2-preview.
- JavaScript parses successfully.
- The six-card artwork generator is reused from the existing V1 implementation.
- The reference animation was processed from the original 10.3-second user-uploaded MP4: cropped to remove browser chrome, H.264, 360×640, 15 fps, 10.33 seconds.
- Main branch and live V1 homepage remain unchanged.

## Pending
- Upload assets/enola-cover.webp and assets/astrolabe-reference.mp4 into v2/assets/.
- Merge the draft PR and wait for GitHub Pages deployment.
- Verify the live /v2/ page in mobile Safari and Chrome, including touch scrubbing, inertia, core trigger, card reveal and reset.

## Interaction boundary
The dial is a 2.5D video-scrubbing interaction, not a true 3D mechanical model. NFC and WeChat mini-program are not connected.
