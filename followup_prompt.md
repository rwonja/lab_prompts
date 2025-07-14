Please implement this lab according to the following specification:

[PASTE LAB DESIGN SPECIFICATION]

## Implementation Requirements

## Overarching Guidelines
- Keep the implementation manageable in complexity
- If a feature is too complex to build out entirely, simplify or remove it (do not leave any "TODO" comments or partial implementations)
- Effort should be focused on the student learning, not on the lab framework (e.g. there is no need to duplicate all of the tests so that they can be run from a lab dashboard as well as from the terminal -- running `npm test` should be sufficient). What exactly constitutes the student's learning will be flexible according to the lab's specification, but the principle is to not over-engineer the lab framework without a clear educational benefit.

### Testing Framework (if applicable)
- Use Mocha and Chai for tests where relevant
- Tests should run via `npm test`
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
- Anywhere a student might get lost (e.g. when they've navigated to a challenge page from an index page), provide a refresher about the goals of the lab and the current challenge, and where their current location fits into the bigger picture. E.g. it might be helpful to explain how to run tests in multiple places, like on the initial README and in every discrete page they might access within the lab itself. Project structure and how all of the pieces fit together (especially what a student is supposed to *do next*) can be a source of confusion, so provide a clear overview in any location where something is expected of the student (which should be pretty much any file which is student-facing).
- Provide a clear entry point to the lab "story" or "workflow", which should begin in the README.md and have clear directions from there on how to proceed. The workflow should then continue to be reiterated in every next step that the student takes (e.g. after running `npm run serve` or opening index.html as appropriate, they should be greeted with an explanation of what happens next and where they are in the workflow).

### Code Structure
- Include a .gitignore file to exclude node_modules and other non-essential files depending on the lab setup
- Separate concerns clearly (lab framework vs student work area)
- Any complex JavaScript should be thoroughly commented (if it is applicable to what the student is learning -- otherwise it should be housed in a portion of the repo that the student does not need to access)
- All code including HTML and CSS should demonstrate best practices they can learn from

### Progressive Disclosure
- Start with the simplest version of each challenge
- Ensure early wins to build confidence
- Optional "stretch goals" for advanced students
- Clear visual feedback for each small success

### Implementation Priorities ()
1. Create the overall lab interface first
2. Implement one complete challenge as a reference
3. Build the testing suite with helpful feedback
4. Add the progress tracking system (if appropriate)
5. Polish with animations and personality

### Error Prevention
- Validate common mistakes with helpful corrections
- If students use syntax, show correct format
- Catch and explain edge cases
- Never let students get "stuck" without hints

Remember: Students are new to programming.
