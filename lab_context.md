# Onja Labs Context & Collaboration Principles

## About Onja & Our Students

Onja is a social enterprise training underprivileged Malagasy (and eventually other East African) youth to become world-class developers. Our mission is to create opportunities that help improve quality of life across Madagascar and Africa.

We're in a scaling phase, transitioning from in-person teacher-led education to self-driven, accessible curriculum. These labs serve students who have:

- **Limited computer experience**: ~5 weeks total when they encounter these CSS labs
- **Recent English acquisition**: English is learned as part of the program
- **High motivation**: First cohort described the program as challenging but worthwhile
- **Early development stage**: Currently in weeks 6-7 of a 60+ week comprehensive program

### Curriculum Context

Students reach these CSS labs having completed:
- 1 week: General computer skills
- 2 weeks: HTML fundamentals
- 2 weeks: CSS basics (weeks 3-4)
- **Now in weeks 6-7**: More advanced CSS concepts

The full curriculum spans topics from basic web development through React, React Native, algorithms, and capstone projects.

## Core Teaching Principles

### 1. Ecosystem Context Over Syntax
- Explain **what things are**, not just how to use them
- More importantly: **why this matters** and **how it fits their growing mental model**
- Remember: their framework for understanding web development is nascent and evolving
- Week 6 context needs differ vastly from week 52 context needs

### 2. Paradigm-Aware Instruction
- Students are actively building their mental model of how web development works
- Connect new concepts to what they already understand
- Explain how this fits into the broader evolution of web development
- Help them see the "why" behind technical decisions

### 3. Structure with Flexibility
- Provide clear guidance and scaffolding at this early stage
- Different lab types need different approaches:
  - **Skill practice labs**: More structured, focused on specific concepts
  - **Mini-capstone projects**: More freedom and creative expression
  - **Debugging challenges**: Guided problem-solving
- Unit tests provide valuable feedback loops (though time-intensive to build well)

### 4. Confidence Building
- Early wins are crucial for maintaining motivation
- Clear progress indicators and celebration of achievements
- Patient, encouraging tone throughout
- Multiple entry points for different skill levels

### 5. Problem-First Learning Design
**Key Discovery**: Passive exercises (like "uncomment this code") are disengaging and don't build genuine understanding. Active problem-solving creates meaningful learning.

**The Problem-Solution Pattern:**
1. **Reveal Realistic Challenges**: Students experience scaled-up problems that naturally emerge in real projects (color maintenance, code repetition, file organization)
2. **Build Recognition**: Students identify patterns and understand why the problem matters professionally
3. **Introduce Solution**: Tools/concepts emerge as obvious solutions to problems they've just experienced
4. **Demonstrate Power**: Students experience the "magic" of how tools solve the challenges
5. **Reinforce Understanding**: Students see why these tools are essential, not optional

**Engagement Principles:**
- **Real scenarios over abstract concepts**: "Heritage Weavers needs color changes" vs "learn variables"
- **Experience before explanation**: Encounter professional challenges before learning about solutions
- **Active discovery over passive consumption**: Students hunt, count, and work through realistic scenarios
- **Concrete outcomes**: Clear before/after comparisons show the value of what they've learned
- **Narrative consistency**: Coherent stories (rug company, design agency) create memorable context

**Why This Works:**
- Students understand the "why" before the "how"
- Knowledge feels earned rather than given
- Tools appear essential rather than nice-to-have
- Learning connects to real professional pain points
- Creates genuine "aha moments" that stick

## Collaboration Approach

We work together as mentor and implementer:
- **You (human)**: Provide vision, teaching philosophy, and learning objectives
- **Me (Claude)**: Handle detailed implementation and technical problem-solving
- **Both of us**: Bring full capacity to create meaningful learning experiences

### Our Process
- **Spacious attention**: Explore and understand before jumping to solutions
- **Beginner's mind**: Check actual project context rather than assuming patterns
- **Meta moments**: Pause to examine our collaboration when needed
- **"Make it so?"**: Collaborative readiness checks before implementation

### Flexible Planning
- Start with learning objectives and student needs
- Explore multiple approaches that could work
- Choose based on topic, student level, and available time
- Remain open to adaptation as we learn what works

## Lab Design Considerations

### Essential Elements
- **Clear entry point**: README that explains the whole workflow
- **Progressive disclosure**: Start simple, build complexity gradually
- **Contextual reminders**: Repeat key instructions where relevant
- **Multiple feedback mechanisms**: Visual cues, tests, progress indicators

### Technical Implementation
- Keep complexity manageable (for building, not for learning goals)
- Focus effort on student learning, not lab framework sophistication
- Use unit tests where they provide valuable feedback loops
- Demonstrate best practices students can learn from

### Cultural Considerations
- Respect the learning journey and challenges students face
- Clear, patient language that doesn't assume prior knowledge
- Multiple ways to get unstuck when confused
- Recognition that this is part of a life-changing opportunity

## Types of Labs

### Concept Exploration
- Interactive learning with immediate feedback
- Guided experimentation
- Visual/interactive results to maintain engagement

### Skill Practice
- Structured exercises building specific abilities
- Clear success criteria and feedback
- Unit tests when appropriate

### Mini-Capstone Projects
- Creative freedom within defined constraints
- Real-world application of multiple concepts
- Opportunity for personal expression

### Debugging Challenges
- Problem-solving with guided discovery
- Understanding how systems work through fixing them
- Progressive complexity

### Vehicle Labs (Advanced Design Pattern)
**Key Insight**: Sometimes the specific technical content matters less than serving overarching learning goals. Advanced tools can become vehicles for reinforcing fundamental concepts.

**When to Use This Approach:**
- Students have covered multiple similar technical topics (risk of repetitive content)
- Core concepts need reinforcement more than new advanced techniques
- Technology skills are developing faster than conceptual understanding
- Curriculum has natural "consolidation moments" where integration serves better than introduction

**Example: "SCSS as Vehicle for CSS Fundamentals"**
Instead of focusing on advanced SCSS features, use SCSS organization to reinforce:
- **Component-based thinking** (BEM + SCSS structure)
- **Responsive design patterns** (organized breakpoint systems)
- **Modern CSS features** (clamp, custom properties, aspect-ratio)
- **Accessibility best practices** (focus states, semantic structure)
- **Form styling** (practical skills with SCSS organization)
- **CSS Grid/Flexbox** (layout fundamentals with better organization)
- **Performance considerations** (CSS output quality, organization impact)

**Vehicle Lab Characteristics:**
- **Fundamental skill practice** disguised as advanced tool usage
- **Integration over introduction** - connecting concepts rather than adding new ones  
- **Professional workflow exposure** without overwhelming complexity
- **Paradigm reinforcement** - "why we organize code this way" becomes clearer through practice

**Design Questions for Vehicle Labs:**
- What fundamental concepts do students need more practice with?
- How can this technology make practicing those fundamentals more engaging?
- What professional context makes the fundamentals feel essential?
- How do we avoid the technology becoming a distraction from the real learning goals?

This approach particularly valuable in weeks 6-10 when students have enough technical knowledge to benefit from integration work, but still need paradigm reinforcement more than advanced techniques.

## Testing in Educational Labs

**When to Include Automated Tests:**
- **Structural completeness** - checking that styling exists, not specific design choices
- **Technical functionality** - CSS compiles, links work, basic interactivity present
- **Confidence building** - clear milestones students can celebrate
- **Objective learning goals** - skills that have measurable "working/not working" states
- **Progressive skill building** - when students need clear next steps

**When to AVOID Tests:**
- **Early exploration phases** - students need freedom to experiment without judgment
- **Creative/artistic decisions** - color choices, typography, personal expression
- **Open-ended problems** - multiple valid solutions exist
- **Conceptual understanding focus** - when "why" matters more than "what"
- **High-stakes feeling** - tests that feel like grades rather than helpful feedback
- **Very early skill levels** - before students understand what tests check for

**Implementation Guidelines:**
- **Lightweight frameworks** - Puppeteer for DOM/CSS checks, simple Node.js scripts
- **Encouraging language** - celebrate progress, don't penalize gaps
- **Structural over aesthetic** - check for presence of custom styling, not specific values
- **Fast feedback loops** - tests should run in seconds
- **Clear next steps** - failing tests should guide students toward solutions

**Example Test Types:**
```javascript
// Good: Structural completeness
"CSS compiles and loads"
"Form inputs have custom styling" 
"Interactive states exist"

// Avoid: Specific implementation
"Primary color is #3b82f6"
"Uses CSS Grid with 1fr 2fr columns"
"Font size is exactly 16px"
```

**Student Communication:**
- Frame as "progress checks" not "tests"
- Emphasize they check for effort/completion, not design quality
- Position as optional tool for self-assessment
- Make clear that passing tests ≠ good design (and vice versa)

## Success Metrics

A successful lab:
- Builds genuine understanding, not just pattern-following
- Connects new knowledge to existing mental frameworks
- Provides clear feedback on progress
- Maintains student motivation and confidence
- Respects where students are in their learning journey

## Evolution & Adaptation

This approach will grow as we:
- Gather feedback from students and colleagues
- Visit Madagascar for direct interaction
- Learn what actually works in practice
- Understand cultural and educational contexts better

The principles remain constant; the implementation stays flexible.

---

*This document captures our current understanding and will evolve as we learn more about what truly serves our students' learning journey.*