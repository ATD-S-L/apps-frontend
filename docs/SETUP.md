# Setup Guide

## Prerequisites

- Node.js 18+ ([Download](https://nodejs.org/))
- npm 9+ or yarn 3+ or pnpm 8+
- Git
- Code editor (VS Code recommended)

## Initial Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ATD-S-L/apps-frontend.git
cd apps-frontend
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
```

### 3. Configure Environment

```bash
cp config/.env.example .env.local
```

Edit `.env.local` with your configuration.

### 4. Verify Installation

```bash
npm run dev
```

Visit `http://localhost:5173` (or the port shown in terminal)

## Development Commands

### Development Server
```bash
npm run dev
```

### Building for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

### Testing
```bash
npm run test              # Run tests
npm run test:watch       # Watch mode
npm run test:coverage    # Coverage report
```

### Code Quality
```bash
npm run lint             # Check linting
npm run lint:fix         # Fix linting issues
npm run format           # Format with Prettier
npm run format:check     # Check formatting
```

### Type Checking
```bash
npm run type-check
```

## VS Code Setup

### Recommended Extensions
- ESLint
- Prettier - Code formatter
- TypeScript Vue Plugin (Volar) or React

### Settings
Add to `.vscode/settings.json`:
```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "eslint.validate": ["javascript", "typescript", "typescriptreact"]
}
```

## Troubleshooting

### Port already in use
```bash
npm run dev -- --port 3000
```

### Clear node_modules
```bash
rm -rf node_modules
npm install
```

### Clear cache
```bash
npm cache clean --force
```

## Next Steps

- Read [ARCHITECTURE.md](ARCHITECTURE.md) to understand the project structure
- Check [../CONTRIBUTING.md](../CONTRIBUTING.md) for contribution guidelines
- Review the component documentation in `docs/`
