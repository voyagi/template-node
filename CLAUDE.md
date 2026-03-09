# Project Instructions

## Language: TypeScript

## Build & Test

- Build: `npm run build`
- Test: `npm test`
- Lint + format: `npm run check` (Biome)
- Lint + fix: `npx @biomejs/biome check --write .`

## Conventions

- Use `const` by default, `let` only when needed
- Named exports over default exports
- async/await, not .then() chains
- Descriptive variable names, no single letters except loop indices
- Use Biome for formatting and linting (replaces ESLint + Prettier)
- Group imports: external packages, then local modules
