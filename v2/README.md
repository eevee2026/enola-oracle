# ENOLA H5 V2 · Reference-first demo

V2 uses the user's original 10.3-second astrolabe reference video as the actual visual sequence. Only the browser chrome in the screen recording is cropped away; the original artwork, composition, colors and motion language are preserved.

## Experience flow
1. Product advertising cover using the original ENOLA product render.
2. Short transition plays the reference animation.
3. The interaction page displays the same video. Touch / pointer movement around the central dial scrubs the original video timeline; release applies inertia and settles.
4. The product-inspired polyhedral core becomes tappable after the orbit stops.
5. One of six original oracle cards is revealed. The V1 card-face artwork generator is reused; the result button is simplified to 再次占星.

## Two binary assets must be uploaded to this folder
- assets/enola-cover.webp
- assets/astrolabe-reference.mp4

The page, styles, and card art generator are text files already in this branch. The two binary assets are supplied separately for upload.

## Technical boundary
This is a 2.5D interaction: the original video is used as a frame sequence and finger movement controls its playback time. It is not a reconstructed 3D model, and NFC / WeChat mini-program integration is not included in this demo.
