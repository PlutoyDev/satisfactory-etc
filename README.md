# Analyzing and parsing of Satisfactory Save Files (Initial)

This is a small project to analyze and parse Satisfactory save files.

Serves as a foundation for a future project.

## Credits

- Coffee Stain Studios for providing the header file
- moritz-h/satisfactory-3d-map: initial file format analysis

## Environment

This project uses Node.js and TypeScript.

node.js > 18
with corepack enabled via `corepack enable`

## Installation
```bash
pnpm install
```

## Run code
```basg
pnpm start
```

optionally copy your save file to save_files directory and run with
```bash
pnpm start -s <filename>
```
> filename without extension (.sav) and file path