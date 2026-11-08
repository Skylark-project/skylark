
# Skylark

Skylark is a full-stack travel planning and itinerary management application.

Users will be able to create trips, manage day-by-day itineraries, edit activities, and organize their travel plans.

## Technology Stack

- Frontend: React, TypeScript, Vite
- Backend: Python, FastAPI
- Database: PostgreSQL with PostGIS
- Authentication: Amazon Cognito
- Cloud: AWS
- Future features: ArcGIS integration and AI itinerary planning

## Repository Structure

- `frontend/`: React application
- `backend/`: FastAPI application
- `docs/architecture/`: System architecture references
- `docs/decisions/`: Architecture Decision Records
- `.github/`: GitHub templates and workflows

## Local Development

The applications have not been initialized yet.

Planned commands after setup:

### Frontend Setup

Prerequisites: Node.js and npm.

From the repository root:

```bash
cd frontend
npm ci
npm run dev
```

Open the local URL printed in the terminal. Press `Ctrl+C` to stop the server.

### Frontend Checks

Run these commands from `frontend/`:

| Command | Purpose |
|---|---|
| `npm run lint` | Check ESLint rules |
| `npm run typecheck` | Check TypeScript types |
| `npm run format` | Format files with Prettier |
| `npm run format:check` | Check formatting without changing files |
| `npm run build` | Generate production files in `dist/` |
| `npm run preview` | Preview the production build locally |

The frontend currently contains the Vite starter with React, TypeScript, and Tailwind configured. Product pages and custom UI components are not implemented yet.

### Backend

```bash
cd backend
python -m venv .venv
# Activate your virtual environment
pip install -r requirements.txt
uvicorn app.main:app --reload
```

These commands are placeholders until the respective setup issues are completed.

## Development Workflow

1. Select a GitHub issue.
2. Create a feature branch from `main`.
3. Implement and test the change.
4. Open a pull request linked to the issue.
5. Request a teammate's review.
6. Merge after checks and review pass.

See [CONTRIBUTING.md](CONTRIBUTING.md).


