# FitFlow Redesign

Redesign of the FitFlow fitness-tracking app, addressing declining retention 
and ratings through AI-powered workout plans, social community features, 
and improved nutrition tracking.

## Tech Stack
- Frontend: React Native (iOS, Android, Web)
- Backend: Node.js / NestJS (API gateway)
- AI Service: Python / FastAPI (workout personalization, computer-vision nutrition logging)
- Database: PostgreSQL (core data), Firestore (real-time features)
- Cache: Redis
- Auth: Firebase Auth

## Project Structure
See folder layout above. Supporting documentation (tech stack comparisons, 
decision matrix, architecture diagram, ADR) is in /docs.

## Documentation
- [Tech Stack Summary](docs/tech-stack-summary.md)
- [Comparison Matrix](docs/comparison-matrix.md)
- [Architecture Diagram](docs/architecture-diagram.png)
- [ADR-001: Technology Stack Decision](docs/adr-001-tech-stack.md)

## Getting Started
1. Clone the repo: git clone <repo-url>
2. Install frontend deps: cd frontend && npm install
3. Install backend deps: cd backend && npm install
4. Install AI service deps: cd ai-service && pip install -r requirements.txt
