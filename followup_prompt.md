Please implement this lab according to the following specification:

[PASTE LAB DESIGN SPECIFICATION]

## Implementation Requirements

### Testing Framework
- Use Mocha and Chai for all tests
- Tests should run via `npm test`
- Each challenge should have 3-5 specific tests
- Test messages should be encouraging and educational (not just "Test failed")
- Tests for each section should be specifically targeted or scoped to the relevant section (i.e. later tests should not start passing because an earlier exercise is complete)
- All tests should fail in the default state, and only progressively start to pass as students complete exercises.
- There should be no duplicated test logic. If there are multiple places which are hooking into tests to show feedback, they should all use the same underlying logic.
- Prefer to use specific test IDs for elements rather than attempting to select through nested classes.
- Example: `it('should hide navigation menu on mobile (tip: use hidden class on screens smaller than sm)', ...)`

### Beginner-Friendly Guidelines
- Every code file should start with a clear comment explaining its purpose
- Use descriptive variable and function names
- Include helpful error messages that guide toward solutions
- Provide starter code with clear TODO comments
- Complex concepts should have inline explanations
- Consider adding hints that can be progressively revealed
- Don't be afraid to repeat instructions where they are relevant to the current task (e.g. explaining how to open DevTools or how to run tests)

### Code Structure
- Separate concerns clearly (lab framework vs student work area)
- Include plenty of comments in the lab framework as teaching examples
- Any complex JavaScript should be thoroughly commented (if it is applicable to what the student is learning -- otherwise it should be housed in a portion of hte repo that the student does not need to access)
- All code including HTML and CSS should demonstrate best practices they can learn from

### Progressive Disclosure
- Start with the simplest version of each challenge
- Ensure early wins to build confidence
- Optional "stretch goals" for advanced students
- Clear visual feedback for each small success

### Implementation Priorities
1. Create the overall lab interface first
2. Implement one complete challenge as a reference
3. Build the testing suite with helpful feedback
4. Add the progress tracking system
5. Polish with animations and personality

### Error Prevention
- Validate common mistakes with helpful corrections
- If students use syntax, show correct format
- Catch and explain edge cases
- Never let students get "stuck" without hints

Remember: Students are new to programming. Every error message, comment, and instruction should be written with empathy and clarity. The lab should feel like a helpful friend, not a harsh judge.
