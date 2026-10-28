# Human or AI? — Visual Perception Experiment Website

This archive contains the complete, production-ready codebase and assets for the **Human or AI?** visual perception experiment.

## Archive Contents
- **`src/`**: All React components, 3D WebGL galleries (`CircularGallery`), landing 3D carousels (`CircularCarousel`), text blur animations, and experiment logic.
- **`src/data/quizData.ts`**: Complete 15-round challenge dataset, explanations, influence factors, and carousel navigation routes.
- **`public/images/`**: High-resolution image assets for all 15 quiz subjects, high-res landing destination cards (`carousel-quiz.jpg`, `carousel-archive.jpg`, `carousel-results.jpg`, `carousel-about.jpg`, `carousel-contact.jpg`).
- **`package.json` & configs**: Vite configuration, TypeScript configs, Tailwind CSS integration.

## Updates in this build:
- **Download Option Removed**: The "DOWNLOAD ZIP" button in the navigation bar and mobile drawer has been removed from the live website interface.
- **Complete ZIP Package**: The full project is packaged with all source files and assets.

## Running Locally:
1. Extract the ZIP archive.
2. Run `npm install` (or `bun install` / `pnpm install`).
3. Run `npm run dev` to launch the local development server at `http://localhost:3000`.
4. Run `npm run build` to create a production bundle in `dist/`.
