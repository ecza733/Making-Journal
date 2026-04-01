---
layout: default
---

# Week 04

[← Back to Home](../index.md)

## Documentation 
## *Experiment 4: Artificial Intelligence*

### Activity 1: Local AI with Ollama
In this activity, I downloaded and ran the Qwen3:1.7b model locally on my computer using the terminal. I explored how a locally hosted AI responds to prompts about my previous experiments, asking for visualisation ideas and code snippets. Compared to cloud-based AI like ChatGPT, the experience felt slower but more intimate, since no data left my computer. I noticed limitations in depth and creativity, but the trade-off was full data privacy and control. This activity helped me appreciate that AI can be a tool for experimentation and ideation, but the output still requires human judgement to make meaningful, creative connections.

### Activity 2: Cloud AI with NotebookLM
Here, I created a NotebookLM notebook with my course work, practitioner sources, and personal observations. I framed the AI with a short context document describing my interests and curiosities. I then used the chat to analyse patterns, identify provocations, and propose design outcomes from my sources. Listening to the Audio Overview was particularly revealing: the AI highlighted unexpected connections and summarized my work in ways I hadn’t consciously noticed, though it occasionally misinterpreted or overlooked nuances. This showed me how AI can surface insights and gaps in my own thinking, but also reinforced that interpretation still needs a human perspective.

#### Overall Reflection
Both activities highlighted the practical and ethical trade-offs of AI. Local AI prioritizes sovereignty and privacy, while cloud AI offers richer analysis and synthesis. Engaging with these tools expanded my understanding of how AI can support creative design workflows without replacing human judgment, and emphasized the importance of curation, context, and reflection in using AI effectively.

## Independent Study: AI-Assisted Data Exploration

Choose a public dataset about life in Aotearoa New Zealand and use cloud-based AI tools to explore, interpret, and represent the data. The challenge is to go beyond a single prompt, working through sustained dialogue with the AI, directing its decisions, and critically evaluating its outputs.

### Step 1: Find a Dataset

Browse the open data catalogue at catalogue.data.govt.nzLinks to an external site. and find a dataset that interests you. Look for something with a downloadable CSV file that is small enough to upload into a cloud AI tool (aim for under 10MB, or a few thousand rows).

Choose something you find genuinely interesting. The data should relate to a real aspect of life in Aotearoa that you would want to explore further.

My chosen data: https://opendata-christchurchcity.hub.arcgis.com/datasets/ChristchurchCity::recycling-collection-opendata/explore

### Step 2: Understand the Data

Upload your CSV into a cloud AI tool (e.g. CoPilot, Gemini, NotebookLM, ChatGPT) and have a conversation about it. Ask the AI to explain what is in the dataset: what the columns mean, what the values represent, how much data there is, and what is missing or incomplete.

Consider:

What stories might this data contain?
What questions could it answer?
What biases or gaps are present?
Who collected this data, and for what purpose?

![alt text](<../assets/week-04/Screenshot 2026-04-01 234058.png>)

Output: "This dataset contains 165 rows and 9 columns, each representing a specific recycling collection schedule entry. At its core, it appears to document how a municipal recycling system operates over time. Each row is uniquely identified by a RecyclingCollectionID, which functions like a primary key and ensures that every record can be distinguished clearly. The dataset is relatively clean overall, with only small pockets of missing data, suggesting it was structured for operational or administrative use rather than exploratory analysis.

The columns describe different aspects of recycling collection. StatusDescription indicates whether a schedule is active or inactive, which helps track changes in services over time. TypeDescription refers to the type of recycling being collected, such as general recycling, organic waste, or glass, giving insight into how waste streams are categorized. StartTimeDescription specifies when collection begins, although a few entries are missing, suggesting either incomplete records or cases where timing is standardized and not explicitly recorded. FrequencyDescription explains how often collection occurs, such as weekly or fortnightly, which is particularly important for understanding service patterns and how they influence public behaviour.

Other columns provide more detailed scheduling information. ScheduleDescription offers a human-readable explanation of the schedule, like “every second Monday,” while WeekNumber indicates where the collection falls within a multi-week cycle. DayDescription specifies the day of the week for collection, and ValidFrom records when a particular schedule became effective. These fields together create a temporal structure, allowing the dataset to capture not just what happens, but when and how it changes. However, there are small gaps across these columns, including missing values in start times, schedule descriptions, week numbers, days, and validity dates, which introduce minor inconsistencies.

From a data quality perspective, the dataset is fairly robust but not perfectly standardised. Some fields rely on descriptive text rather than structured formats, which can make analysis more difficult. The absence of strict formatting suggests the data may have been designed for internal use or public readability rather than computational efficiency. Despite this, the dataset still provides a strong foundation for understanding service patterns.

Looking beyond the structure, the dataset tells subtle but compelling stories. It reflects the rhythms of a city’s infrastructure—how waste collection is scheduled in alignment with weekly routines and operational constraints. Through the ValidFrom column, it is also possible to trace how recycling services evolve over time, revealing shifts in policy, sustainability priorities, or resource allocation. Although it does not include behavioural or environmental outcomes, it indirectly shapes them; the frequency and timing of collections influence how people manage their waste in everyday life.

There are also important limitations and biases. The dataset lacks geographic information, meaning it cannot reveal whether certain areas receive better or worse service. It also does not include data on waste volume or participation rates, so it cannot measure the effectiveness of the system. Additionally, the reliance on human-readable descriptions introduces ambiguity and reduces analytical precision. These gaps suggest that the dataset prioritises operational scheduling over deeper evaluation or equity analysis.

Overall, this data was most likely collected by a local government or municipal authority as part of an open data initiative. Its purpose is likely to support transparency, enable public access to recycling schedules, and integrate with digital services such as reminder apps. While it may seem straightforward, the dataset ultimately represents more than just logistics. It captures how an invisible system quietly organises daily life, shaping behaviours and routines at a city-wide scale, even though it was not designed with that narrative in mind."

### Step 3: Design Multiple Representations

Ask the AI to produce a visualisation of the data, but don't accept the first output. Direct the AI: specify the form, the visual encoding, the audience, the story you want to tell. Iterate through at least three distinctly different representations of the same data. These could be code-based (e.g. p5.js or HTML), textual, visual, or even prompts for physical/analogue translations.

For each version, make deliberate design decisions about what to change. You might vary the format (chart, map, interactive page, narrative text), the visual encoding (colour, size, position, shape), or what subset of the data to foreground.

### Step 4: Critically Evaluate

Look at the representations you've produced and reflect on the AI's design choices:

What did the AI default to? (e.g. bar charts, blue colour schemes, generic titles)
What did you have to override or redirect?
What assumptions did the AI make about the data or the audience?
Which representation is the most interesting, and why?
What would you do differently if you were building this without AI?
Document Your Process
To capture the full scope of your practice, each entry in the Making Journal must include a mix of visual and textual evidence, such as sketches, screenshots, GIFs, diagrams, process notes, instructions and reflections.

Items on the course Reading List for this week include the introduction to Data Feminism by Catherine D'Ignazio and Lauren F. Klein, and a talk by Kirikowhai Mikaere on Māori data sovereignty. Engage with both of these and draw on them in your reflections.

### Reflection:

What dataset did you choose, and why?
How did AI tools help you understand the data? What did they miss?
What design decisions did you make in directing the AI, and what did you learn from this process?
How do the different representations of the same data change what a viewer might understand?
What questions do D'Ignazio and Klein's ideas raise for your work with this dataset?
How does Mikaere's framing of data as a strategic asset for Māori development challenge or inform how you think about the dataset you chose?
What was your experience of working with AI as design tool?
What would you develop further with more time?
Any other reflections?


## AI Usage Statement

*I used ChatGPT for prompting and brainstorming ideas for visual mappings, but experimentation, creative direction, and final visual design are my own work. AI was a supportive tool, not a substitute for my creative decisions.*