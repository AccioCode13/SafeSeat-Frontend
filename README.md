# 🛡️ SafeSeat
_India’s railway booking platform with women’s safety first_

SafeSeat intelligently allocates train seats to provide secure, comfortable, and optimized travel experiences for women passengers. This repository contains the frontend (TypeScript + Vite) for the SafeSeat project.

---

## Table of Contents
- About
- Features
- Demo
- Tech Stack
- Project Structure
- Setup & Development
- Usage
- Contributing
- Roadmap
- License
- Contact

---

## About
SafeSeat is designed to improve safety and comfort for women travelling by train by prioritizing seat allocation and offering a streamlined booking flow. The frontend in this repo focuses on UI, user flows, and communicating with the backend seat-allocation services.

## Features
- Seat allocation optimized for women’s safety
- Responsive UI built with TypeScript
- Pages and components split for easy extension
- Simple onboarding and booking flows

## Demo
Add screenshots or a short GIF showing the main flows (search, seat allocation, booking). Place images in `public/` and reference them here. Example:

![App screenshot](public/train.png)

## Tech Stack
- TypeScript
- Vite (dev server / build)
- React (assumed from .tsx files)
- CSS for styling

(See `package.json` for exact dependencies.)

## Project Structure
SafeSeat-Frontend/
│
├── public/             # static assets (images, index.html)
│   ├── train.png
│   └── index.html
│
├── src/                # application source
│   ├── components/     # reusable components
│   ├── pages/          # route pages
│   ├── App.tsx
│   └── main.tsx
│
└── package.json

---

## Setup & Development
Prerequisites: Node.js (>= 14) and npm or yarn.

1. Install dependencies

```bash
npm install
```

2. Run the dev server

```bash
npm run dev
```

3. Build for production

```bash
npm run build
```

4. Preview production build

```bash
npm run preview
```

Notes: If you use yarn, replace `npm` with `yarn` accordingly.

## Usage
- Open http://localhost:5173 (or the URL printed by the dev server)
- Use the UI to search trains, select journeys, and test seat allocation flows.

## Contributing
Contributions are welcome. Please:
1. Fork the repo
2. Create a branch for your feature: `git checkout -b feat/your-feature`
3. Commit changes with a clear message
4. Open a pull request describing your changes

Add a `CONTRIBUTING.md` for more detailed guidelines (code style, linting, tests).

## Roadmap
- Integrate backend API for real-time seat allocation
- Add authentication and user profiles
- Improve accessibility and mobile UX
- Add E2E tests

## License
Add a license file (e.g., MIT) and update this section.

## Contact
If you have questions or want to collaborate, open an issue or reach out to the maintainers.

---

Thank you for working on SafeSeat — a product that focuses on safer travel for women.
