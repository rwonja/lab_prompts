# The Ask

I need to design a creative, interactive learning lab for [TOPIC].

Context:
- Students have completed: [PRIOR COURSEWORK]
- Skill level: [BEGINNER/INTERMEDIATE]
- Available time: [1.5-3 hours]

Please help me:
1. Explore 3-4 creative approaches where the lab environment itself demonstrates [TOPIC]
2. Consider how [TOPIC]'s unique properties create learning opportunities
3. Choose the most engaging approach
4. Output a complete Lab Design Specification using the standard template

The specification should be detailed enough that another prompt could implement it without additional context. Below is the Lab Design Specification template to fill out once we have come up with the approach:

# Design Specification Template
```markdown
# Lab Design Specification: [TOPIC NAME]

## Core Concept
**Topic**: [e.g., Tailwind Media Queries]
**Learning Objective**: [What students will be able to do after completion]
**Estimated Duration**: [1.5-3 hours]
**Prerequisite Knowledge**: [What students should already know]

## Chosen Approach
**Framework Type**: [e.g., "Self-Revealing Interface" or "Living Document"]
**One-Line Concept**: [e.g., "Students fix a responsive gallery that 'breaks' at different screen sizes"]

## Meta-Learning Hook
How the lab environment uses the concept being taught:
[e.g., "The lab instructions themselves reflow and reorganize based on viewport width, demonstrating media query breakpoints in real-time"]

## Technical Feasibility
**Complexity Check**: [e.g., "Can the lab be built as described without requiring advanced tools or frameworks?"]
**Feasibility Check**: [e.g., "Can the lab as specified be realistically implemented within 4 days of advanced engineer time?"]

## Prerequisite Files & Resources
- [List any files, libraries, or resources needed to implement the lab, e.g. assets, libraries, CDNs]

## Common Pitfalls
- [List potential implementation pitfalls which might derail the building of the lab. e.g.: Attempting to make the lab too complex, using advanced features that are not supported in the target environment, etc.]

## Student Journey

### Entry Point
- How students first encounter the lab
- Initial state of the environment
- First instruction delivery method

### Progression Mechanics
1. [Challenge 1]: [Description and how it teaches X]
2. [Challenge 2]: [Description and how it teaches Y]
3. [Challenge 3]: [Description and how it teaches Z]

### Feedback Mechanisms
- How students know they're succeeding
- Test integration points
- Visual/interactive feedback

## Implementation Details

### File Structure

  - /lab-name
  - /lessons (if needed)
  - /lab
    - index.html [with specific features]
    - styles.css [with specific features]
    - lab.test.js
  - README.md

### Key Technical Elements
- Specific CSS/HTML/JS features to highlight
- Any special setup requirements
- Testing approach details

### Narrative Elements (if applicable)
- Story/theme
- How narrative integrates with code
- Character/progression elements

## Discovery Moments
Points where students will have "aha!" moments:
1. [Moment 1]: [What they discover]
2. [Moment 2]: [What they discover]

## Constraints & Guardrails
- What students must use/cannot use
- How to prevent common pitfalls
- Scaffolding provided

## Assessment Strategy
- What tests check for
- How mastery is measured
- Self-assessment opportunities
```

# Example meta-learning frameworks for inspiration:

## The Living Document

The lesson HTML/CSS literally demonstrates what it's teaching
Students modify the document they're reading
Example: A CSS lesson where changing values in <style> tags immediately affects the lesson's appearance
"Change the background-color in line 15 to see this box transform"

## The Recursive Lab

Students build tools that help them learn the next concept
JavaScript lab: "Build a simple test runner" → Use it for next lab
CSS lab: "Create a style guide component" → Reference it in future labs
They're simultaneously learning and building their own learning infrastructure

## The Investigative Approach

Hide clues/instructions in comments, data attributes, or console logs
Students must use DevTools to progress
Example: <!-- Your next task is hidden in the CSS file, look for the .secret-mission class -->
Teaches tooling alongside concepts

## The Self-Revealing Interface

Start with a "broken" or "locked" interface
As students complete challenges, new sections unlock/reveal
Could use CSS classes, JavaScript state, or even localStorage
The lab interface itself is part of what they're building

## The Choose-Your-Own-Adventure Lab

Different paths based on student choices/implementations
if (yourSolution.includes('flexbox')) { loadChallenge('flexbox-advanced') }
Adapts to what students are interested in or struggling with

## The Collaborative Canvas

Students contribute to a shared outcome
Each student's solution becomes part of a larger whole
Maybe they each style one component that gets aggregated
Reinforces that programming is collaborative

## The Time-Travel Debugger

Present broken future states
Students must "fix the timeline" by correcting earlier code
Shows cause and effect across files/time
Great for understanding cascade, inheritance, scope

## The Lab-Within-a-Lab

Students encounter and must fix bugs in the testing framework itself
Or improve the lab experience for "future students"
Very meta - debugging the debugger, testing the tests

## The Narrative Environment

Labs that tell a story through code
Comments and variable names carry plot
Example: CSS adventure where each selector "unlocks" story elements
Code becomes literature

## The Morphing Challenge

One file that transforms based on student progress
Start with HTML → Add CSS → It becomes interactive with JS
The same file evolves rather than moving between files
Shows the progressive enhancement philosophy literally

This completely reframes what a "lab" could be! Instead of just varying the amount of hand-holding, we can vary:

Medium of instruction (comments vs console vs visual vs interactive)
Narrative structure (linear vs branching vs emergent)
Relationship to environment (using vs building vs fixing vs exploring)
Social dimension (solo vs collaborative vs competitive)
Meta-level (learning vs learning-to-learn vs building-learning-tools)
