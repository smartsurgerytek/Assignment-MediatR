# Take-Home Assignment: MediatR Unit Testing

## Objective

The goal of this assignment is to assess your ability to write unit tests for a message-handling system using MediatR, a popular .NET library for in-process messaging. You will demonstrate your understanding of handling different types of messages, implementing error handling, and adhering to best practices in software engineering and documentation.

## Assignment Tasks

You are required to write a unit test for a hypothetical application using MediatR:

1. Request/Response (or Notification) Test

- Scenario: Write a unit test for a request/response message that is dispatched to a single handler. The test should verify that the handler processes the request correctly and returns the expected response.

- Requirements:
  - Create a request and a corresponding handler.
  - Ensure the handler returns a correct response when processed.
  - Implement error handling to manage potential exceptions thrown by the handler.
  - Document the test, explaining the purpose and the approach.

## Guidelines

- Framework: Use xUnit for your unit tests.
- Error Handling: Your tests should gracefully handle and assert the occurrence of exceptions where necessary.
- Documentation: Each test method should have comments explaining the purpose of the test and any specific logic used to achieve the testing goals.
- Best Practices: Follow SOLID principles, maintain clean and readable code, and ensure your tests are deterministic.

## Setup Instructions

- Fork the Repository: Fork the official MediatR repository located at https://github.com/jbogard/MediatR to your personal GitHub account. This will be your working repository for the assignment.
- Clone Your Fork: Clone the forked repository to your local machine to begin working on the assignment.

## Submission

- Deadline: Please complete the assignment and push your changes to your forked repository within 48 hours from the time this assignment was given.
- Submission: Once you have completed the assignment, please send the URL of your public repository to our company's submission email or through the provided submission link.

_Good luck, and we look forward to reviewing your submission!_
