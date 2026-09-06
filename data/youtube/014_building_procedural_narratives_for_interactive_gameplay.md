Emily Short discusses the design and scoping challenges of building highly responsive, procedural interactive narratives based on game state, using her work on Fallen London as a primary case study.

## Building Procedural Narratives For Interactive Gameplay

## Chronological Chapter Breakdown

### The Concept of Procedural Storylets
Emily introduces the foundational concept behind her approach to interactive narrative: the "storylet." Unlike traditional linear storytelling, a storylet is an independent piece of content triggered dynamically based on complex in-game conditions.
> **"essentially this is a way of thinking about any piece of story content... triggered by something going on in the world state of the game so that might be has the player intentionally triggered this have they paid some sort of cost"**
*Deep Analysis:* The transition from linear scripting to procedural storylets marks a fundamental shift in game writing, requiring systems-level thinking. By decoupling narrative beats from a fixed timeline and tying them to variable world states, designers can create highly reactive games that feel deeply personalized. However, this flexibility introduces significant structural complexities in tracking how and when these modular pieces should surface to the player.

### The Daunting Challenge of Narrative Scoping
Producers accustomed to linear development often find procedural narrative systems terrifying because the sheer volume of required content is difficult to predict. Early naive approaches to solving this problem often resulted in a massive, unmanageable matrix of content requirements.
> **"it feels much more frightening generally to producers especially than a nice linear narrative... I've got this big bag of different bits of content and it's going to correspond somehow to the game State I don't exactly know like how much of this we're going to need"**
*Deep Analysis:* The core tension in non-linear game development lies between creative ambition and production constraints. When every variable change demands a corresponding narrative reaction, the scope can quickly spiral out of control. Emily emphasizes that an unchecked combinatorial explosion of content not only blows up budgets but can actively dilute the core themes of the game if the connections aren't carefully curated.

### Strategies for Analyzing State Space
To manage the chaotic potential of procedural storytelling, Emily proposes structural strategies to organize game states. She advocates for focusing on meaningful oppositions, resource distributions, and "racing clocks" to identify moments where narrative interventions are genuinely required.
> **"what stats can we put in opposition to one another and what can we say in an interesting way about sort of the comparison of this approach versus that one"**
*Deep Analysis:* This represents a masterclass in narrative constraint. Instead of trying to account for every possible permutation of the game's variables, designers should identify the intersections that hold the most dramatic weight. Techniques like tracking racing clocks (e.g., injury versus impending doom) ensure that the narrative system only spends development resources on scenarios that naturally generate high tension and player engagement.

### Case Study: Fallen London's Railway Expansion
Emily details a specific challenge she faced while working on the browser game Fallen London. An endgame railway expansion allowed players to make sweeping, permanent choices about the game's geography and politics—choices that the development team initially thought they'd never have to narratively resolve.
> **"we wanted to build this in a way that the player could create a sort of long-term difference in the the world... we thought you'll make up all this stuff... and then we'll just give you a light epilog... well surprise a few years later our players wanted more content"**
*Deep Analysis:* This anecdote perfectly illustrates the dangers of accumulating "narrative debt" in a live-service game. By providing players with immense agency without planning the systemic infrastructure to handle the long-term consequences, the team cornered themselves. The subsequent need to build a reactive system for an immensely divergent world state forced them to innovate on their procedural delivery mechanisms.

### Utilizing Ternary Plots for Faction Alignment
To handle the sprawling permutations of player loyalty to three distinct railway factions, the team employed ternary plots. This mathematical visualization helped identify overarching player intent rather than strictly calculating the exact numerical distribution of their stats.
> **"we approach this as a turnery plot... we're trying to look at what is our overall percentage of assignment to a particular stat type... we didn't just want to say you know oh you're mostly committed to this... we wanted to think of what is narratively Meaningful here"**
*Deep Analysis:* Applying a concept from physical chemistry (phase states) to narrative design is brilliantly unconventional. It solves a crucial problem in systemic storytelling: reducing continuous, messy player data into discrete, actionable narrative profiles. By defining "narratively meaningful zones" within the ternary plot, the team could write targeted, evocative content without having to author an impossible number of edge-case scenarios.

### Exploiting Precarious World States for Emergent Drama
During the iteration phase, the team focused on identifying naturally volatile combinations of game states. By targeting these precarious overlaps, they could trigger compelling narrative events without requiring the player to expend resources to advance the plot manually.
> **"where are there precarious World states that if the player brings those about we should have some sort of special thing fire off so if you've got an ideology for your whole city where everybody's aligned... but you've got a leader installed in that City who has an opposing ideology"**
*Deep Analysis:* This highlights the ultimate goal of procedural narrative design: emergence. When the system itself recognizes the inherent contradictions in a player's choices (e.g., a conservative leader in a radical city) and automatically generates friction, the world feels genuinely alive. This moves the game away from simply being a reactive vending machine of story and transforms it into a dynamic, proactive participant in the player's experience.

## Key Quotes & Context
- "we need to decide in game when and how to serve those elements" (Discussing the challenge of serving procedural content dynamically based on current context.)
- "how do we understand the total Spa State space of our game rather than a bunch of IND idual stats" (Emphasizing holistic evaluation of game state over basic integer tracking.)
- "partway through production you realize that there are all kinds of ways that world State can be influencing multiple pieces of world State" (Describing the iterative nightmare of poorly planned procedural systems.)
- "we had a bunch of default story lights that we know we need to have happen in any kind of story that we're playing in this world" (Highlighting the necessity of baseline content alongside highly variable moments.)

## Conclusion & Takeaways
Emily Short's presentation provides an invaluable framework for tackling the overwhelming complexity of procedural narrative design. By shifting the focus from creating a storylet for every possible stat permutation to identifying narratively meaningful zones and precarious world states, designers can deliver highly responsive, personalized stories without succumbing to combinatorial explosion. Her practical applications in Fallen London demonstrate that with careful planning—utilizing concepts like ternary plots and racing clocks—it is possible to build sustainable, scalable interactive narratives that deeply respect player agency.
