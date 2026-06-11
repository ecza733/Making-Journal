---
layout: default
---

# Week 08

[← Back to Home](../index.md)

## Documentation 

## 1. Progress Reflection
As the project developed, I began shifting away from the idea of creating a highly detailed archive environment and instead focused on the visualisation itself. While researching references and experimenting in Unreal Engine, I realised that a complex environment could distract from the data. The memories themselves needed to become the focal point of the experience.

At this stage I had already selected and categorised approximately 50 memories from the HappyDB dataset into four groups: Family, Friends, Achievement, and Exercise. My next challenge was determining how these memories could be represented visually in a way that communicated information while remaining simple and intuitive.
This led me to focus on developing a visual language for the archive.

## 2. Data Mapping Experiments
The first design decision involved determining how data attributes would be represented visually.
I wanted users to understand the archive without needing to read large amounts of text. Instead of displaying raw numbers, I aimed to encode information directly into the appearance of the memory objects.

I developed the following mapping system:
- Family memories = Pink
- Friend memories = Green
- Achievement memories = Blue
- Exercise memories = Yellow

Additionally, I used age data to influence orb size.
- Younger participants = Smaller orbs
- Older participants = Larger orbs

This meant each memory simultaneously communicated multiple pieces of information before any interaction occurred.
Through this process I became increasingly interested in data humanism and the idea that data does not always need to appear as numbers, charts, or graphs. Instead, the information becomes embedded within visual form.

## 3. Orb Development
Initially I downloaded and imported a premade orb model.
The intention was to use these objects as representations of individual memories throughout the archive. However, I quickly encountered an unexpected issue.
I wanted the floor to be reflective in order to create the illusion of an infinite space. While testing different materials, I discovered that the imported orb model was not reflecting correctly within the environment.

![alt text](<../assets/week-08/Screenshot 2026-06-10 170125.png>)
*Screenshot of Unreal Engine; imported orb model not appearing on the reflective floor*

To troubleshoot this problem I experimented with lighting settings, material properties, and reflection settings. However, after spending a significant amount of time attempting to fix the issue, I decided it would be more efficient to create my own memory orb.
I followed several tutorials exploring emissive materials and glowing effects.
Creating my own orb ultimately provided greater flexibility and visual consistency. The new design also aligned more closely with the dreamlike atmosphere I wanted to create.

## 4. Environment Development
While earlier versions of the project focused on architectural spaces, I gradually reduced the amount of environmental detail.
The archive evolved into a dark void-like space with a simple circular platform positioned at its centre.
This decision emerged from experimentation rather than planning. As I removed environmental elements, I found that the memories became significantly more prominent. The contrast between the glowing orbs and the black background strengthened the visual impact of the data and created a stronger sense of mystery and discovery.
The circular platform also helped organise the experience spatially by creating a central point around which memories could be distributed.

## Independent Study
### Reflective Summary
One of the most significant realisations this week was that simplicity often communicates data more effectively than complexity. Initially I was focused on creating an elaborate archive environment, but through experimentation I discovered that reducing visual noise made the data easier to understand and more visually engaging.

The process of creating custom orbs also taught me the importance of flexibility when working with unfamiliar software. Although the imported asset initially seemed like the easier option, building my own solution ultimately resulted in a stronger outcome.

I also became more confident using Unreal Engine's material system. While I still encountered frequent technical challenges, I felt increasingly capable of experimenting independently rather than relying entirely on tutorials.

### Project Development
This week's development focused on populating the archive with memory orbs and refining their visual appearance.
Once the colour system and orb design had been established, I began placing memories within the environment. The memories were arranged according to category clusters while maintaining a degree of randomness to create a more natural composition.

![alt text](<Screenshot 2026-06-10 194654.png>)
*Screenshot of beginning placements of orb memories in Unreal Engine* 

To strengthen the illusion that the archive extended beyond the visible dataset, I also duplicated and positioned additional memory orbs throughout the surrounding space. Many of these orbs were intentionally placed out of reach or higher above the viewer, creating the impression that the visible memories were only a small part of a much larger archive.

By the end of the week, the project had moved beyond experimentation and started to resemble a complete interactive visualisation.


## AI Usage Statement

*I used ChatGPT to support the writing process for this proposal by helping me organise my ideas, refine wording, and structure my reflections clearly. The core ideas, topic selection, and project direction are my own. AI was used as a brainstorming and editing tool, but all decisions about the content and design concept were made independently by me.*
