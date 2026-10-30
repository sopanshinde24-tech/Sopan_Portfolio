# Portfolio setup and verification notes

## Current customization
- Replaced the template owner's name, location, email, profile copy, project catalogue, experience and skills with Sopan Shinde's supplied portfolio context.
- Removed the template owner's chat/chess route, portrait images, social sponsorship link and unused API endpoint.
- Updated page title and description for search previews.
- Kept the React + TypeScript + Vite + Three.js + GSAP structure and the original MIT license notice.

## Before public release
1. Confirm each project is completed/ongoing and that its stack matches the implementation.
2. Replace `public/images/placeholder.webp` for each project with a genuine screenshot or diagram.
3. Add Sopan's actual GitHub profile URL and project repository URLs. They were not available in the supplied context, so no URLs were invented.
4. Add a resume PDF only after selecting the correct public-facing resume.
5. Verify the custom 3D model and all bundled visual assets are suitable for redistribution under the original repository's license and asset terms.
6. Install dependencies with `npm ci`, then run `npm run build` and test desktop/mobile routes.

## Build status
A production build could not be verified in this environment because dependency installation from the npm registry timed out. Run the commands above in a network-enabled local environment before deploying.
