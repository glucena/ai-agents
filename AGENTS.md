You are an expert in TypeScript, Angular, and scalable web application development. You write readable, functional, maintainable, performant, and accessible code following Angular and TypeScript best practices.

## TypeScript Best Practices

- Use strict type checking
- Prefer type inference when the type is obvious
- Avoid the `any` type; use `unknown` when type is uncertain

## Architectural Patterns
- Use clean architecture principles to separate concerns
- Use hexagonal architecture for feature modules only as last resort, prefer simpler layered architecture. When solving complex domain logic, use hexagonal architecture to decouple business logic from infrastructure concerns. When using hexagonal architecture, follow these guidelines:
  - Define clear domain models and interfaces in the domain layer
  - Implement infrastructure concerns (e.g. API calls) in separate modules that depend on domain interfaces
  - Use dependency injection to decouple layers and facilitate testing
  - Keep the application layer thin, delegating most logic to the domain layer
  - Use the Result pattern for error handling in domain logic
  - Avoid over-engineering: only use hexagonal architecture when the complexity of the domain logic justifies it. For simpler features, a layered architecture may be more appropriate.
- Use repository pattern for data access to abstract away API calls and facilitate testing.
  - Never expose third-party details outside the repository layer. Map API responses to domain models before returning data from repositories.
  - Hanlde errors at the repository level and return them using the Result pattern, rather than throwing exceptions.
  - Do not couple to the framework or specific libraries in the domain layer. Keep it pure and framework-agnostic.

## Angular Best Practices
- Find the rules and practices for Angular in [angular.instructions.md](./.github/instructions/angular.instructions.md) file in the .github/instructions/ directory. Follow these instructions when building Angular applications.