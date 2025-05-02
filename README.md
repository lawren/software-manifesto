> [!NOTE]
> This document is a reminder (for myself more than anyone) of the magic of software and the profound privilege and responsibility that comes with building it. It attempts to distill my personal dogma and shouldn’t be read as a critique of other perspectives.
>
> I revisit this when I’m feeling burned out, uninspired, or just need to hype myself up for the work ahead. If you’re reading this, I hope it helps you do the same.

## First Principles

Software is a human tool. It exists to solve problems, save time, and ideally, as Marie Condo would say, spark joy. The value of software isn’t in lines of code or shipped velocity. It’s whether someone, somewhere, had a better day because of it.

Most software fails at this. For that matter, most products of any sort fail at this.[^1] Not because teams lack talent, but because we often build for ourselves or for each other, rather than the actual people using what we ship. It’s like designing a kitchen for an Instagram post rather than for _actual_ home cooks who are desperately trying to get dinner on the table while wrangling a toddler.

The trap is easy to fall into. We chase complexity, ship features that dazzle on demos but confuse in practice, and skip research because it doesn’t _feel_ productive. Add to that the pressure from business stakeholders to move fast, cut corners, and stack features, and the result is often a bloated interface wrapped around a shaky foundation.

Deadlines can erode nuance. Feedback loops get throttled. Iteration gets skipped. What you end up with is software that technically works, but doesn’t actually work for the people who rely on it.

We can do better.

## How We Improve

The path forward isn’t mysterious, but it’s rarely followed with discipline. Here’s how we close the gap between good intentions and great products:

### _Always_ start with the user.

Don’t ask users what they want.[^2] Watch what they do. Understand the job they’re hiring your product to do. Treat UX research like debugging for real-world problems, because that’s exactly what it is.

### Teach UX everywhere.

UX shouldn’t be the designer’s job alone. If you write code that touches people, you’re part of the UX. Help engineers understand the “why” behind user behavior, not to replace designers, but to collaborate better with them.

### Prioritize relentlessly.

Every new feature is a trade-off. Simplicity is a prerequisite for reliability and an active choice, not a default. Before you ship anything, ask: Does this make the user’s life better? Not cooler. Not more powerful. Just better. If the answer isn't a clear "yes", resist. These small additions create noise and add complexity to our products, making shipping actual value in the future more difficult.

### Shorten the feedback loop.

Agile isn’t about rituals. It’s about learning fast. Ship small. Validate constantly. Adapt. Treat feedback not as critique, but as compass.

### Tear down the silos.

The best ideas happen when engineers, designers, PMs, marketers, and users all see the same picture. Don’t wait for handoffs. Create shared context early and often.

### Cultivate humility.

Ego kills good products. Stay curious. Let go of the need to be right. The best engineers I know question their own assumptions more than anyone else.

None of this is about perfection. It’s about iteration. Software is never done, and neither is our responsibility to the people who use it.

## Lessons from Open Source

Open source isn’t perfect, but it offers some powerful lessons in how great software can emerge from alignment with real user needs:

- It’s community-driven. Features are added because people need them, not because someone in a corner office had a hunch.
- It’s meritocratic. Good ideas rise to the top, no matter where they come from. Politics matter less than practicality.
- It’s transparent. Progress is visible. Roadmaps are public. Mistakes get made out in the open and fixed just as publicly.
- It’s adaptable. Open source lives or dies by its ability to evolve. That responsiveness is something every team should aspire to.

By channeling some of that mindset (open collaboration, honest feedback, and responsiveness to user signals) we can build software that doesn’t just “work,” but works well.

# Final Thought

Software is powerful. Done right, it can feel like magic, making complex tasks feel simple or gone altogether. It can save people time, the most precious resource in the universe. It can allow them to explore other worlds. It can give them confidence, peace of mind, and empower them in ways that nothing else can. It’s easy to forget that when you’re staring at a Jira board or debugging a flaky test.

We’re not just building systems. We’re building experiences. Every line of code we write nudges someone’s day in one direction or another.

That’s a privilege and a responsibility we oughta take seriously.

[^1]: [The Design of Everyday Things](https://dl.icdst.org/pdfs/files4/4bb8d08a9b309df7d86e62ec4056ceef.pdf)
[^2]: [Two-factor Theory of Emotion](https://en.wikipedia.org/wiki/Two-factor_theory_of_emotion)
