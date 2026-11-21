# Agent instructions

## Project
Smart Campus Room Availability checks room availability using fictional
data and a fixed demo time. React components live in `src/components`.
Time, availability and room filtering rules live in `src/lib`.

## Setup and verification
Use `npm ci` to install the versions recorded in `package-lock.json`.
Run `npm test`, `npm run lint`, `npm run typecheck`, and `npm run build`
after changes. Use `npm audit` and `npm audit --omit=dev` to review
dependencies.

## Working rules
Start reviews in read-only mode. Label findings as confirmed,
unverified, or unsupported and cite source files or command output.
Keep business rules in `src/lib` and add tests for bug fixes.
Ask for human approval before changing dependencies or merging changes.
Do not run destructive commands, publish or deploy the project,
or access or share secrets or real personal data.