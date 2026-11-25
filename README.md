# Poornima Kona — Portfolio

A responsive React + Vite portfolio built with Tailwind CSS, Framer Motion and Lucide React.

## Run locally
1. Install Node.js 18+.
2. In this folder run `npm install`.
3. Run `npm run dev` and open the local URL.
4. Run `npm run build` to create the production build in `dist/`.

## Configure before deployment
- Replace the resume placeholder in `public/` with your actual PDF and name it `Poornima_Kona_Resume.pdf`.
- Add project repository/demo URLs in `src/data.js` only when you have verified URLs.
- Add certificate URLs in `src/data.js` when available.
- For a real contact form, configure a backend or email provider in `src/App.jsx`. The default form validates locally and clearly states that no message was sent.
- The Ask Poornima assistant uses grounded predefined responses. An API endpoint can be added later via `VITE_ASSISTANT_API_URL`; do not expose private API keys in frontend code.
- Add a real profile image at `public/profile.jpg` and update the image source in `src/App.jsx` if desired.

## Deployment
Deploy the generated `dist/` directory to Vercel, Netlify, GitHub Pages (with base-path configuration if needed), or any static host.
