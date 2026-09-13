# ServiceHub

ServiceHub is an enterprise service-management platform with a React/TypeScript workspace and a Spring Boot API. It supports customer request submission, employee assignment and fulfilment, administrative visibility, payments, JWT authentication, OpenAPI documentation, and a SOAP billing adapter.

## Run locally

1. Start MySQL: `docker compose up -d db`
2. Run the API: `cd backend && mvn spring-boot:run`
3. Run the dashboard: `cd frontend && npm install && npm run dev`

The API is served at `http://localhost:8080/api`; Swagger is available at `/swagger-ui.html`.

## Demo roles

The UI runs with realistic in-memory demo data until it is connected to the API. The API exposes role-based endpoints under `/api/requests`, `/api/auth`, `/api/payments`, and `/api/admin`.
