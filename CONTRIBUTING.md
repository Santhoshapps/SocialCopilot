# Contributing

Thanks for your interest in contributing! Suggestions and improvements are welcome.

## How to Contribute

1. **Fork** the repository
2. **Create a branch** for your change:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** and commit with a clear message:
   ```bash
   git commit -m "Add: short description of change"
   ```
4. **Push** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request** and describe what you changed and why.

## Development Setup

```bash
npm install
cp .env.example .env.local   # fill in your Base44 credentials
npm run dev
```

## Guidelines

- Keep changes focused — one feature or fix per PR.
- Follow existing code style (ESLint config is included).
- Components live in `src/components/`, pages in `src/pages/`.
- Never commit secrets, API keys, or `.env.local` files.
- Test your changes in the browser before submitting.

## Reporting Issues

Found a bug or have a suggestion? Open an issue with:
- A clear title
- Steps to reproduce (for bugs)
- Expected vs. actual behavior

## Code of Conduct

Please follow the [Code of Conduct](CODE_OF_CONDUCT.md) in all interactions.
