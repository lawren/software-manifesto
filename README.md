> [!NOTE]
> This is mostly a note to self. A personal reminder of why I build software, how I try to do it well, and the privilege and responsibility baked into the job. It’s not a manifesto to convert anyone else, though if you’re here, you might find it useful when you’re burned out, stuck in Jira hell, or just need a reason to care again.

<br>

## First Principles

Software is a human tool. It’s not an abstract exercise in cleverness, it’s a wrench to turn a bolt in someone’s actual life. It should solve real problems, save real time, and, if we’re lucky, spark a little joy along the way. The value isn’t in the lines of code or the speed you slammed “deploy”. It’s whether someone, somewhere, had a measurably better day because of what you shipped.

Most software fails at this. Hell, most products do.[^1] Not because the people building them are bad at their jobs, but because we fall into the trap of building for ourselves, or worse, for each other. That’s how you end up with a kitchen designed for an Instagram instead of the stressed-out parent trying to get spaghetti on the table before the toddler starts gnawing on a shoe.

The trap is seductive. Complexity feels like progress. We crank out features that look slick in a demo but turn into molasses in production, gumming up everything else around it. We skip research because it doesn’t feel like “real work.” Then the business side piles on, demanding you move faster, cut corners, pack in more. Before long, you’ve got a shiny, bloated interface draped over a rickety foundation.

Deadlines sand the nuance off decisions. Feedback loops stall. Iteration gets skipped. You ship something that technically works, but doesn’t work for the human beings depending on it.

We can do better.

<br>

## How We Improve

There’s no mystery to building good software. The hard part is having the discipline to actually follow the obvious rules.

### Start with the user, always.

Unless you want to end up building an SUV with a cupholder in every possible surface, don’t just ask users what they want.[^2] Watch what they do. Figure out the job they’re hiring your product to do. UX research is debugging reality. Treat it that way.

### Spread UX literacy everywhere.

If your code touches humans, you’re doing UX. Engineers who understand the “why” behind user behavior don’t replace designers, they make their work land better.

### Prioritize like a zealot.

Every new feature is a deal with the devil. Simplicity isn’t the default state, it’s a hard-won choice. Before you add anything, ask, “Does this make life better?” Not cooler, not more powerful, not more “engaging”; just better. If the answer isn’t a clear yes, drop it. Otherwise, you’re adding noise now and pain later.

### Collapse the feedback loop.

Agile isn’t standups and story points. It’s about learning faster than you can guess wrong. Ship small, validate often, adapt without ego. Treat feedback like a compass, not a judgment.

### Smash the silos.

The best work happens when everyone sees the same picture early. That means engineers, designers, PMs, marketers, and yes, actual users. Skip the ceremonial handoffs. Build shared context fast and keep it alive.

### Cut features, not corners.

When resources get tight, the temptation is to rush and tape things together. That debt comes due. It always does. The better move is to shrink scope. Build less, but build it right. Reliable architecture, clear interfaces, and tests that actually mean something aren’t “nice to have”. They’re the multiplier on every future project.

Customers remember how your product made them feel, not how many bullet points you crammed into the release notes.

### Cultivate humility.

Ego quietly kills more products than bad code. Question your assumptions. That messy, weird code you’re dying to rewrite? It probably exists for a reason. Understand it before you gut it. I’ve rewritten things I shouldn’t have and paid for it later.

And one day, someone will look at your most elegant solution and think, “what the hell is this?” Leave them breadcrumbs. Document your trade-offs. Write with empathy for the next poor soul who has to read your work.

Perfection isn’t the point. Progress is. Software is never finished, and neither is our responsibility to the people who use it or the ones who have to maintain it.

<br>

## Lessons from Open Source

Open source isn’t flawless, but it nails a few things we’d be smart to steal:

- **Community-driven.** Features land because they’re needed, not because someone’s gut said so in a boardroom.
- **Meritocratic.** Good ideas win more than politics.
- **Transparent.** Progress, mistakes, and fixes are all out in the open.
- **Adaptable.** It survives or dies by how quickly it can evolve.

The best open source projects stay lashed to actual needs, not hypothetical ones. They collaborate openly, accept feedback without flinching, and evolve at the speed of reality.

<br>

## Final Thought

Done right, software feels like magic. It makes hard things easy or makes them disappear entirely. It gives people time back, which is the most valuable thing any of us have. It can give them confidence, peace of mind, or the power to do something they couldn’t do before.

It’s easy to forget that when you’re elbows-deep in a flaky test or staring down a Jira backlog. But every line of code tips someone’s day in one direction or another.

That’s not just a job. That’s a superpower and a privilege.

<br>

<br>

[^1]: [The Design of Everyday Things](https://dl.icdst.org/pdfs/files4/4bb8d08a9b309df7d86e62ec4056ceef.pdf)
[^2]: See Marty Cagan’s _Inspired_ or Jobs’ commentary on product design. Users don’t always know what they want—but their behavior will show you what they need.
