# AgentClinic Tech Stack

## Application

- **Language:** TypeScript for application code.
- **Runtime:** Node.js.
- **Server framework:** Express with TypeScript. Express is widely used and lightweight, and supports adding HTTP APIs and server-rendered routes incrementally.
- **Database:** SQLite for persistent application data, including agents, ailments, therapies, and appointments.
- **Browser experience:** A responsive web interface that works in modern browsers.

## Implementation guidance

- Keep TypeScript checks enabled and build through the project's TypeScript compiler.
- Keep database access behind a small persistence layer so routes do not depend on SQL details.
- Validate incoming data at the server boundary and return clear errors.
- Add dependencies only when a concrete roadmap phase needs them.

## Current starting point

The repository currently has a minimal TypeScript setup with a `build` script. Framework, database, and UI dependencies can be added in the phases that introduce them.
