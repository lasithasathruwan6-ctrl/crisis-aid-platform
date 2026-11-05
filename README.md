# Crisis Aid Platform

**SE205.3 Software Architecture Coursework 2026**
AI-Powered Humanitarian Crisis Management and Aid Coordination Platform

A multi-organisation platform for coordinating emergency assistance, shelters, volunteers, resources, donations and AI-assisted (human-approved) decision-making during disasters.

## Tech Stack
| Layer | Technology |
|---|---|
| Backend | ASP.NET Core Web API (C#, .NET 10) |
| Database | SQL Server |
| Frontend | React / Angular / Vue (TBD) |
| API Docs | Swagger / OpenAPI |
| Architecture | Modular Monolith |

## Repository Structure
```
/backend    ASP.NET Core solution
/frontend   Web client
/database   SQL scripts (schema, seed data)
/docs       Report, diagrams, Postman collection
```

## Team
| Member | Name | GitHub | Area |
|---|---|---|---|
| 1 | Lasitha Sathruwan | @lasithasathruwan6-ctrl | Architecture, Security, Auth, Admin |
| 2 | | | Database, Requests, Human-in-the-loop |
| 3 | | | AI services, Resources |
| 4 | | | Notifications, Mapping, Async |
| 5 | | | Shelters, Volunteers |
| 6 | | | Citizens, Donations, QA |

## Prerequisites
- .NET 10 SDK
- SQL Server (+ SSMS)
- Node.js (LTS)
- Git

## Getting Started
```bash
git clone https://github.com/lasithasathruwan6-ctrl/crisis-aid-platform.git
cd crisis-aid-platform
git checkout <your-branch>
```

### Backend
```bash
cd backend/CrisisPlatform.Api
dotnet run
```
Swagger UI: https://localhost:<port>/swagger *(update when ready)*

### Database
Run scripts in `/database` in order. *(to be added)*

### Frontend
```bash
cd frontend
npm install
npm start
```
*(to be added)*

## Configuration
Secrets are never committed. Use `dotnet user-secrets` or `appsettings.Development.json` (git-ignored).
*(connection string, JWT key, email and map API keys to be documented)*

## Test Credentials
*(dummy accounts per role to be added)*

## API Information
Base URL: `/api/v1`. Swagger documents all endpoints. Postman collection in `/docs`.

## Git Workflow
- No direct pushes to `main`; use feature branches + Pull Requests.
- Branch naming: `feature/m<number>-<topic>`.
- Every member commits with their own GitHub account.

## Known Limitations
*(to be updated before submission)*
