# Prettier 3.7.0 Bug Reproduce

Issue link: <https://github.com/prettier/prettier/issues/18353>

## Reproduce Steps

1. Clone this repository
2. cd into the `web` directory
3. Run `pnpm install` to install dependencies
4. Open the entire repository in VSCode (not just the `web` directory)
5. Open any file inside the `web` directory. E.g., `web/tsconfig.json`
6. Open the command palette (CTRL/CMD + SHIFT + P) and run `Format Document With...` -> `Prettier - Code formatter`
