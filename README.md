# Final Project Requirements (600 points)

## Part 1 - Simple Web Crawler (250 points)

- No MySQL database, in-memory persistence only.
- Single threaded **only**.
- [Use domain driven design](https://en.wikipedia.org/wiki/Domain-driven_design).
- [Use test-driven development](https://en.wikipedia.org/wiki/Test-driven_development).
- [Implement SOLID priniciples](https://en.wikipedia.org/wiki/SOLID):
    - Single responsibility
    - Open/closed principle
    - Liskov substitution principle (interfaces)
    - Interface segregation (many small interfaces)
    - Dependency injection
- Needs to run on the class server.
- KISS (Keep It Simple Silly)

## Part 2 - Web Crawler with a MySQL database (150 points)

- All the previous constraints.
- The database needs to run on the class database server.

## Part 3 - Simple Search Engine (200 points)

- All the previous contraints.
- Use the database from part 2.

## Rubric

|                  | Excellent                                                                                                    | Good                                                                               | Satisfactory                                                                     | Unsatisfactory [-100%]                                                                                                |
|------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
|                  | *Must also include all “Good” criteria, and no “Unsatisfactory” criteria*                                      | *Must also include all “Satisfactory” criteria, and no “Unsatisfactory” criteria*    |                                                                                  | *Note: Any Unsatisfactory criteria will result in a zero grade for the assignment, and no further grading will be done.* |
| **Delivery**     | ·    Completed 100% of requirements                                                                          | ·    Completed between 99-80% of the requirements.                                 | ·    Completed at least 75% of the requirements.                                 | ·    Completed less than 75% of the requirements.                                                                     |
|                  |                                                                                                              |                                                                                    | ·    Delivered on time, and in correct format.                                   | ·    Not delivered on time or not in correct format (disk, email, Canvas, printout etc.)                              |
|                  |                                                                                                              |                                                                                    |                                                                                  | ·    Does not comply with requirements (does something other than requirements).                                      |
| **Coding Standards** | ·    Excellent use of white space.                                                                           | ·    Good use of white space.                                                      | ·    Includes name, and assignment title.                                        | ·    No programmer name included                                                                                      |
|                  | ·    Creatively organized work.                                                                              | ·    Organized work.                                                               | ·    White space makes program fairly easy to read.                              | ·    Poor use of white space (indentation, blank lines) making code hard to read.                                     |
|                  | ·    Excellent use of variables and constants.                                                               | ·    Good use of variables and constants                                           | ·    Organized work.                                                             | ·    Disorganized and messy                                                                                           |
|                  | ·    No magic numbers.                                                                                       | ·    Minimum line-wrap                                                             | ·    Good  use of variables.                                                     | ·    Uses global variable(s), goto/continue/exit/break (except in switch).                                            |
|                  | ·    Correct identifiers for constants.                                                                      |                                                                                    |                                                                                  | ·    Ambiguous identifiers.                                                                                           |
|                  | ·    No line-wrap                                                                                            |                                                                                    |                                                                                  |                                                                                                                       |
| **Documentation**    | ·    Specific purpose is noted for each function, control structure, input requirements, and output results. | ·    Purpose is noted for each function and control structure.                     | ·    Basic documentation has been completed including a summary of requirements. | ·    No documentation included.                                                                                       |
|                  |                                                                                                              | ·    One sample run included                                                       | ·    Purpose is noted for each function.                                         |                                                                                                                       |
| **Runtime**          | ·    Executes without errors excellent user prompts, good use of symbols, spacing in output.                 | ·    Executes without errors.                                                      | ·    Executes without errors.                                                    | ·    Does not execute due to syntax errors.                                                                           |
|                  | ·    Thorough and organized testing has been completed and output from test cases is included.               | ·    User prompts are understandable, minimum use of symbols or spacing in output. | ·    User prompts contain little information, poor design.                       | ·    Does not execute due to runtime errors (endless loop, crashes etc.)                                              |
| **Testing**          | · 100% code coverage                                                                                         | · 90-80% code coverage                                                             | · 79% code coverage or less                                                      |                                                                                                                       |
| **Efficiency**       | ·    Solution is efficient, easy to understand, and maintain.                                                | ·    Solution is efficient and easy to follow (i.e. no confusing tricks).          | ·    A logical solution that is easy to follow but it is not the most efficient. | ·    A difficult and inefficient solution.                                                                            |
