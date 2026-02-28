```markdown
# AGENTS.md File Guidelines

These guidelines outline the specific requirements and best practices for development within the AGENTS.md repository. Adherence to these principles is crucial for maintaining a clean, maintainable, and robust codebase.

## 1. DRY (Don't Repeat Yourself)

*   All code should have a single, well-defined purpose.
*   Avoid duplication of functionality across multiple files.
*   When multiple implementations of a concept are needed, create a separate file for each.
*   Refactor existing code to eliminate redundant patterns.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize clarity and readability over complex or obscure solutions.
*   Use the simplest possible solution that meets the current requirements.
*   Avoid unnecessary complexity.
*   Strive for minimal code with maximal impact.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be open for extension but closed for modification.  New features should be added via new code, not by altering existing code.
*   **Liskov Substitution Principle:**  Subclasses must be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be forced to depend on implementation details that it does not use.
*   **Dependency Inversion Principle:** High-level modules (classes) should not depend on low-level modules (classes).  They should interact through abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Implement only what is absolutely necessary *now*.
*   Avoid premature implementation of features.
*   Refactor code to eliminate unnecessary code.
*   Focus on completing the core functionality.

## 5. Code Structure & File Size

*   **Maximum File Size:** 180 lines of code.
*   **File Organization:**  Each file should represent a distinct, logical unit of functionality.
*   **Naming Conventions:** Use consistent naming conventions (e.g., camelCase for variables/functions).
*   **Comments:** Provide clear, concise comments where appropriate to explain complex logic or non-obvious decisions.  Avoid redundant commenting.

## 6. Testing & Coverage

*   **All Development Must Be Productive:**  Coding should be driven by the need to deliver value.
*   **Only Mocking for Tests:**  All implementation details *must* be mocked and isolated for testing.  No real data should be used.
*   **Test Coverage Target:**  Minimum 80% of code must be covered by automated tests.
*   **Unit Tests:**  Comprehensive unit tests should be written for all functions and classes.  Each function/class should have at least one unit test.
*   **Integration Tests:**  Integration tests should verify the interaction of different components.
*   **End-to-End Tests:**  End-to-end tests should simulate real user interactions.
*   **Test Data Management:**  Ensure test data is carefully designed and managed.

## 7. Specific Considerations (AGENTS.md - placeholder, adapt as needed)

*   **Data Models:** Ensure data models are well-documented and follow established patterns.
*   **API Design:**  Consider design patterns for APIs (e.g., REST, GraphQL) to promote reusability and maintainability.
*   **Error Handling:** Implement robust error handling and logging.
*   **Configuration Management:**  Establish a clear strategy for managing configuration data.
*   **Documentation:**  Provide clear and concise documentation for all APIs and data models.



These guidelines are intended to foster a consistent and high-quality development process within the AGENTS.md repository.  Regular review and updates to these guidelines are encouraged.
```