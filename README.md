# apps-frontend

Professional frontend application for the ATD-S-L ecosystem.

## Stack

- **Framework**: React / Vue / Svelte (TBD)
- **Language**: TypeScript
- **Styling**: TBD (Tailwind, CSS Modules, styled-components, etc.)
- **Build Tool**: TBD (Vite, Webpack, Next.js, etc.)
- **Testing**: Jest + React Testing Library / Vitest
- **Package Manager**: npm / yarn / pnpm

## Project Structure

```
src/
  ├── components/     # Reusable UI components
  ├── pages/          # Page components / routes
  ├── hooks/          # Custom React hooks
  ├── utils/          # Utility functions
  └── styles/         # Global styles and theme
public/              # Static assets
tests/
  ├── unit/           # Unit tests
  ├── integration/    # Integration tests
  └── e2e/            # End-to-end tests
config/              # Build and environment configuration
docs/                # Documentation
```

## Getting Started

### Prerequisites
- Node.js (v18+)
- npm / yarn / pnpm

### Installation

```bash
npm install
# or
yarn install
# or
pnpm install
```

### Development

```bash
npm run dev
```

### Testing

```bash
npm run test
npm run test:coverage
```

### Building

```bash
npm run build
npm run preview
```

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License - see [LICENSE](LICENSE) file for details.
