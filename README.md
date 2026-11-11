# notes-app-back-end

A small Hapi-based REST API for creating, reading, updating, and deleting notes.

[Repository](https://github.com/MirzaAlbab/notes-app-back-end)

## Features

- Note handlers and routes in src/
- Generated note identifiers with nanoid
- Development and production start scripts
- ESLint configuration

## Technology

`@hapi/hapi` ^21.3.1

## Getting started

Install a Node.js version compatible with Hapi 21.

```bash
git clone https://github.com/MirzaAlbab/notes-app-back-end.git
cd notes-app-back-end
```

```bash
npm install
npm run start-dev
```

The development API listens on `http://localhost:5000`. Use `npm run start-prod` for the production-mode start script in a compatible shell; the server then binds to `0.0.0.0`.

## Development and checks

```bash
npm run lint
```

The `npm test` script is a placeholder. Review `src/routes.js` for the available note endpoints.

## Project structure

- `src/` — Application source

## Project notes

Notes are stored in the in-memory array in src/notes.js and are lost when the process restarts. The configured npm test command is a placeholder.

## License

No root `LICENSE` file was present in the reviewed repository. Consult the repository owner about reuse; dependencies and third-party assets retain their own terms.
