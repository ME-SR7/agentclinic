# AgentClinic Roadmap

Implementation proceeds in small, reviewable slices. Each phase should leave the application buildable and provide a clear piece of user-visible or foundational value.

1. **Confirm the starting point** - Keep the TypeScript project building and add a minimal server entry point with a health response.
2. **Run the server locally** - Add Express, a start script, and basic configuration for local development.
3. **Create the first page** - Add a responsive clinic landing page with navigation and clear entry points for agents and staff.
4. **Set up persistence** - Add SQLite, connection and configuration handling, and a small data-access layer.
5. **Define core records** - Create and initialize tables for agents, ailments, therapies, and appointments.
6. **Show agents** - Add a staff-facing agent list backed by SQLite, with a basic agent detail view.
7. **Show care information** - Add ailments and therapies to the agent detail experience.
8. **Book an appointment** - Add an appointment form with server-side validation and persistence.
9. **Review appointments** - Add a staff view for upcoming appointments and their status.
10. **Polish the core experience** - Improve empty, loading, and error states; check responsive layouts and accessibility across the main flows.
