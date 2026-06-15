# Project: MyApp

## Commands
- Build: `npm run build`
- Test: `npm test` (run before claiming done)
- Lint: `npm run lint`

## Architecture
- `src/api/` — route handlers only, no business logic
- `src/services/` — business logic, pure functions where possible
- `src/db/` — all database access goes through here

## Hard rules
- Never commit secrets, .env files, or credentials
- Never run destructive git commands (force push, reset --hard)
- Prefer editing existing files over creating new ones
- No new dependencies without asking first

## Code style
- Small functions, single responsibility
- No clever one-liners — clarity beats brevity
- Delete dead code, don't comment it out
