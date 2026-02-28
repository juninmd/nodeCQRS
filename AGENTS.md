```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the creation and maintenance of high-quality AI coding agents within this repository.  Adherence to these principles is crucial for maintainability, testability, and overall project stability.

## 1. DRY (Don't Repeat Yourself)

*   **Code Reuse:**  Strive to create reusable components and functions that can be used across multiple agents or modules.
*   **Modular Design:** Break down complex tasks into smaller, self-contained modules with clear responsibilities.
*   **Abstraction:**  Define abstract interfaces for components to enhance flexibility and reduce code duplication.

## 2. KISS (Keep It Simple, Stupid)

*   **Simplicity:**  Prioritize clarity and ease of understanding over unnecessary complexity.
*   **Minimalism:**  Avoid over-engineering solutions.  Keep the code concise and focused on the essential requirements.
*   **Readability:**  Use consistent naming conventions, indentation, and comments to make the code easy to read and understand.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have a single, well-defined responsibility.
*   **Open/Closed Principle:**  The system should be extensible without modifying the existing code.  (This is addressed through modular design and abstraction).
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients shouldn't be forced to modify abstractions they don't use.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Features:**  Do not implement features that are not currently required by the agent's function.
*   **Focus on Core Requirements:**  Prioritize the implementation of essential functionalities first.

## 5. Testing & Coverage

*   **Unit Tests:** All code must be thoroughly tested through unit tests.
*   **Test Coverage:** Achieve a minimum of 80% test coverage.  Automated tests are essential.
*   **Test Case Design:**  Tests should cover all critical scenarios and edge cases.
*   **Test Data Management:**  Use realistic and controlled test data.
*   **Mocking:**  Use mocks and stubs for testing isolated components, but *never* use mocks as replacements for actual implementations.

## 6. Code Length Limits (180 Lines)

*   **Maximum Code Length:** Each file must not exceed 180 lines of code.
*   **Code Optimization:**  Strive for efficient code that balances readability and performance.

## 7. Project Structure & Documentation

*   **Clear Directory Structure:** Organize files into logical directories (e.g., `src/agents/`, `src/data/`, `src/utils/`).
*   **README:** Include a README file explaining the project's purpose, requirements, and usage.
*   **Docstrings:**  Provide comprehensive docstrings for all functions, classes, and modules to explain their purpose and parameters.
*   **Comments:** Use concise and informative comments to clarify complex logic.

## 8.  Specific Constraints

*   **Data Handling:** Implement clear and consistent data structures for managing agent states and data.
*   **Event Handling:** Design a robust and well-defined event handling system.
*   **Error Handling:**  Implement appropriate error handling mechanisms to prevent crashes and provide informative feedback.
*   **Logging:**  Implement logging for debugging and monitoring.

## 9.  Code Style & Conventions

*   **Consistent Formatting:**  Follow a consistent code style (e.g., using a linter or formatting tool).
*   **Meaningful Names:** Use descriptive and meaningful variable and function names.
*   **Code Clarity:**  Prioritize code readability and maintainability.

## 10.  Future Considerations (Not Requirements)

*   **Version Control:** Utilize a version control system (e.g., Git).
*   **Dependency Management:**  Consider using a dependency management tool (e.g., `pip`).


These guidelines are subject to change as the project evolves.  Regular review and updates are necessary to maintain the quality and consistency of the AGENTS.md file.
```