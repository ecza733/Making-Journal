---
layout: default
---

# Week 09

[← Back to Home](../index.md)

## Documentation 

## 1. Project Statement Development
As the project became more visually resolved, I began thinking about how I would communicate its purpose to an audience. Up until this point I had focused heavily on technical development and environmental design, but I realised that the project also needed a clear conceptual position.

#### The central idea behind the project became:
*How can human memories be transformed into data while still retaining a sense of emotional meaning?*

Rather than presenting data through charts or graphs, I wanted the archive to encourage exploration and discovery. The project began to feel less like a traditional visualisation and more like an interactive data sculpture where viewers could navigate and uncover memories.

#### I also refined the title of the project:

*Happy Place | A Happiness Memory Archive*

This title felt more inviting and emotional than simply calling the project a memory database. It reinforced the idea that the archive was built from real human experiences rather than abstract information.

## 2. Planning the Interaction System
While the visualisation was beginning to work visually, the memories themselves were not yet accessible. The next challenge was figuring out how users would actually interact with the data.

Initially I considered several possibilities:
- Clicking memory orbs
- Triggering interactions through proximity
- Displaying information panels
- Displaying floating text above the orb

After sketching several options, I decided that a simple pop-up interface would provide the clearest experience. When users approached a memory orb, a panel would appear containing the memory text and associated information.
This approach balanced readability with immersion.

## 3. UI Design Development
Before implementing the interaction system, I designed the interface elements that would appear within the archive.
Using Adobe software, I created a series of memory cards that displayed individual memories from the dataset. Each card contained:
- The memory text
- Category information
- Supporting archive information

I also designed the title interface that appears at the top of the archive.
The interface included:
- Project title
- Colour legend
- Explanation of orb sizes
- Information about the HappyDB dataset

![alt text](<../assets/week-09/Screenshot 2026-06-10 161258.png>)
*Screenshot of the making the memory cards on Adobe After Effects*

Creating these interface elements helped establish a stronger identity for the project and made the visualisation easier to understand without requiring additional explanation.

## 4. Blueprint Learning and Interaction Development
The most significant challenge this week involved learning Unreal Engine's Blueprint system.
Because I had limited experience with node-based programming, I initially found the process extremely confusing. I followed several tutorials that attempted to create interaction systems, but many were either outdated, unnecessarily complex, or produced unexpected errors.

One tutorial in particular required a large number of Blueprint nodes and dependencies. After spending a significant amount of time following the instructions, I discovered that the system was not functioning correctly within my project.
This was frustrating because I felt I was spending more time debugging than making progress.

After several unsuccessful attempts, I searched for alternative approaches and eventually found a much simpler tutorial. The new method relied on a smaller number of Blueprint nodes and was significantly easier to understand.
The experience taught me an important lesson about evaluating tutorials critically. Simpler solutions are often more effective than complex ones, particularly when learning new software.

## 5. First Successful Interaction
Eventually I succeeded in creating a functioning interaction system.
When the player approached a memory orb, the corresponding memory card appeared on screen. This was the first moment where the visualisation genuinely felt interactive rather than simply decorative.

![alt text](<../assets/week-09/Screenshot 2026-06-10 191405.png>)
*Interaction of a memory in Unreal Engine*

The interaction transformed the experience because it connected the visual data representation with the human stories behind the data. Viewers could now move through the archive, discover memories, and connect the information displayed on the screen with the visual characteristics of the surrounding orbs.
This was one of the most rewarding milestones in the entire project.

## Independent Study
### Project Development
Following the successful implementation of the interaction system, I focused on scaling the archive.
The next challenge involved creating multiple memory orbs that each displayed different information while maintaining a consistent visual style.

I carefully duplicated the original memory system and modified the associated text and data for each new memory. Because I wanted approximately 40–50 memories to be represented, this process became repetitive and time-consuming.

However, I found that working methodically helped reduce mistakes and made the process more manageable.
As the number of interactive memories increased, the archive began to feel much more substantial. Rather than containing a single example interaction, it now functioned as a larger collection of human experiences.

### Reflection
This week was dominated by technical learning.
The biggest lesson I learnt was that implementation often takes significantly longer than expected, particularly when learning unfamiliar tools. While I initially underestimated the complexity of Unreal Engine's Blueprint system, I ultimately gained a much better understanding of how interactions are constructed.

The experience also reinforced the value of persistence. There were several moments where I considered abandoning certain features due to technical difficulties, but continuing to experiment eventually resulted in a working solution.
By the end of the week, the project had evolved from a static visual environment into an interactive data-driven experience. The archive now contained both visual and textual representations of memory data, creating a stronger connection between the dataset and the audience experience.

### Progress Report
#### Current project status:
- Dataset selected and curated
- Visual mapping system established
- Archive environment created
- Custom memory orb developed
- User interface designed
- Blueprint interaction system functioning
- Multiple interactive memories implemented
#### Remaining tasks:
- Populate remaining memory orbs
- Refine layout and composition
- Improve environmental atmosphere
- Conduct final testing
- Prepare showcase documentation

The project is beginning to feel complete, although there are still opportunities to improve immersion and polish.


## AI Usage Statement

*I used ChatGPT to support the writing process for this proposal by helping me organise my ideas, refine wording, and structure my reflections clearly. The core ideas, topic selection, and project direction are my own. AI was used as a brainstorming and editing tool, but all decisions about the content and design concept were made independently by me.*
