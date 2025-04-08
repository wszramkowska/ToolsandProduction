# Tools and Production
# Development Commentary Template

## Project Outline 


This project is a physics-based puzzle game in which players control a robot suit with a detachable bubble head, called The Last Drop. The project was initially submitted as part of a game jam with the prompt Bubble. Spread across four levels, the game introduces players to various environmental challenges that interact with and change the properties of the bubble. The changing states of the bubble make up the core gameplay behaviour, allowing for unique and evolving puzzle mechanics throughout the game.

Narratively, the game will be told using a mixture of environmental storytelling and voice-over. A key character, an initially detached scientist, observes the robot's progress throughout the tests. As the game unfolds, she begins to notice the robot bubble shows signs of being sentient. By the final level she goes against protocol and frees the bubble out into the larger world. The player should feel the subtle bond developing between the bubble and the scientist over the course of the game.

Although I will be helping with general programming throughout the project, my main focus will be as an audio programmer. I want to create a responsive, high-quality sound experience that support's the games tones and mechanics. Using Unreal Engine's MetaSounds, I will implement physics material driven procedural audio that reacts dynamically to the bubble's state, environmental changes and player interactions. I will be working alongside another audio programmer who will be producing music and ambience, which we will collaborate to implement into the game.

#### Initial Goals

I have a few initial goals for the project with my main focus being on creating a cohesive experience where audio aligns with the visuals, which I can achieve by working closely with level designers. The environmental audio and ambience should support the atmosphere of each of the different levels; summer, spring, autumn and winter. Additionally I want to design and implement sound that reflects the different bubble state to make each mechanic feel more unique. Puzzles should have sound cues which guide the player, letting them know if they are successful or not. To tie the story together I would like to implement voice-over for the scientist character which makes her feel natural and context-aware.


#### Anticipated Challenges

I think the main challenges for this project will come from working in a big group as most of my projects before have been no more than 8 people on a team. Communication and deadlines will be very key to completing the work. The audio has to be cohesive with the gameplay and visuals which means I have to work with the level designers, to finish in a timely manner. Another challenge will be managing the voice-over, which will have to be balanced with the music, ambience and in game sounds. I am unsure how big the script will be but I want to keep the focus on the game audio so the voice-over does not become repetitive or intrusive.

## Research (Suggested Word Count 1,100)

### Methodology
- Identify relevant sources for the project, including articles, documentation, talks, and games.  
- Detail how these sources have informed your practical work and influenced your approach.  

### Game Sources
- Conduct research on games that are relevant to your project. Provide a brief description of each game and the insights it offers.  
- Analyse the game's approach, cross-referencing it with other sources such as articles or talks to support your analysis.  
- Explain how these insights apply to your project and influence your decision-making process.  

#### **Inside**

Inside (2016) is a puzzle-platform game developed and published by Playdead. This was the original inspiration for the game so I thought it would be a good place to start my research. I have actually played the game myself before and really enjoyed the unsettling, minimalist atmosphere. The story is told entirely through the environment and sound design, since there aren't really any cutscenes or narration.


Key features and Insights:
- Environmental Storytelling
    - No use of dialogue.
    - Lighting used to guide player (used against enemies, but also used by enemies).
    - Allows for players to interpret the story in their own way.
- Pacing
    - Gradual introduction of mechanics to allow player to learn.
    - There aren't really any tutorials which deepends player immersion.
- Atmosphere
    - Lighting is harsh, with a lot of spotlights that make the player feel exposed and potentially in danger.
    - Sound contributes to pacing, tension and emotional tone. A lot of it is very echoey to represent how tiny the player is compared to the building he is in.
    - The visuals are very bleak and grey. There isn't much colour in the game which supports the dull, dystopian atmosphere. Colour is used selectively, such as highlighting buttons in puzzles by making them glow red.

    
### Academic Sources
- Research academic papers, books, or articles that provide theoretical guidance for your project. Include a brief summary of each source.  
- Describe how the academic research applies to your project and shapes your design and development decisions.  

As my main focus during this project would be audio programming, I chose a book called Game Audio Mixing by Alex Riviere. This book is an overview of many game audio mixing techniques, processes and workflows. Specifically I looked at sound prioritization, Riviere explains prioritizing is to decide where to place your focus, which sounds are crucial to be heard and which ones can be softened or sacrificed. (Riviere, 2023, p.64). 

For my project I can apply this logic by prioritising sounds that must always be clear to the player such as; bubble impact, environment and puzzle cues.



### Documentation Sources
- Investigate relevant documentation, tutorials, or instructional videos that provide technical insights into your tasks. Summarise the content and its relevance to your project.  
- Explain how this technical knowledge supports your project work and guides your decision-making process.  

## Implementation (Suggested Word Count 1,100)

### Process
- Provide a step-by-step breakdown of your development process, including key milestones and decisions made throughout the project.  
- Highlight any tools, frameworks, or techniques used, and explain how they contributed to the implementation.  
- Include screenshots, diagrams, or code snippets where relevant to showcase your progress.  

### New Approaches
- Detail any innovative or new approaches you explored during the project.  
- Explain why these approaches were chosen and how they differ from standard practices.  
- Evaluate the success of these approaches, including any challenges faced and lessons learned.  

### Testing
- Document the user testing conducted, specifying the type of tests used (e.g., automated testing, guided user testing, blind testing).  
- Present feedback or issues identified during testing, using graphs, tables, or visual aids to summarise results.  
- Describe how these issues were addressed. If any issues were not resolved, provide a clear justification for leaving them unaddressed.  

### Technical Difficulties
- Identify any technical difficulties encountered during the implementation phase.  
- Provide details on how these issues were diagnosed and resolved.  
- If any difficulties remain unresolved, explain the impact on the project and any mitigation strategies used to minimise their effect.  
- Reflect on what you would do differently in future projects to avoid similar issues.  

## Outcomes (Suggested Word Count 300)

### Source Code/Project Files
- Provide a link to your complete source code or project files.  
- Ensure the link is publicly accessible or shared with the appropriate permissions.  
- Include a brief description of the files provided, highlighting key components or any instructions required to run the project.  

### Build Link
- Share a link to a playable or executable build of your project.  
- Ensure the build is accessible across relevant platforms and is publicly accessible.  
- Include any necessary instructions for running the build, such as system requirements or installation steps.  

### Video Demonstration
- Embed a video or provide a link to a recorded demonstration of your project in action.  
- The video should showcase key features, functionality, and any unique elements of your project.  
- Include a brief commentary or text overlay in the video to explain the different aspects of your project as they are shown.  

## Reflection (Suggested Word Count 500)

### Research Effectiveness
- Assess the usefulness of the research conducted during the project.  
- Highlight which sources (games, academic, documentation) had the most significant impact on your work and explain why.  
- Identify any research gaps or areas where additional information could have improved your project outcomes.  

### Positive Analysis
- Reflect on the successful aspects of the project.  
- Highlight specific elements that worked well, such as technical solutions, creative decisions, or user feedback.  
- Provide evidence to support your analysis, such as test results, screenshots, or user comments.  

### Negative Analysis
- Identify the areas of the project that did not go as planned or could have been improved.  
- Discuss challenges you faced, whether technical, creative, or time-related, and evaluate their impact on the final product.  
- Reflect on any mistakes or missteps and what you learned from them.  

### Next Time
- Outline what you would do differently if you were to undertake a similar project again.  
- Suggest improvements to your workflow, research methods, or implementation process based on your reflections.  
- Consider any new tools, techniques, or approaches you would explore in future projects to achieve better results.  

## Bibliography
- Compile a complete list of all sources referenced throughout your project. This may include articles, journals, videos, games, software, documentation, or any other materials.  
- Ensure all references are formatted according to the university's citation method.  
- Organise your references in alphabetical order. Alternatively, you may separate them by type (e.g., academic sources, games, videos), but consistency is key.  

- Riviere, A. (2023) *Game Audio Mixing: Insights to Improve Your Mixing Performance*, Oxford, Taylor & Francis Ltd  

## Declared Assets
- Provide a detailed list of any third-party assets used in the project.  
- This includes asset packs, music, sound effects, 3D models, textures, scripts, or code from external sources.  
- Declare any use of AI tools (e.g., ChatGPT, GitHub Copilot, Meshy) or pre-existing code. Specify the purpose of these assets/tools and how they were integrated into your work.  
- Ensure you clearly distinguish between your original work and any external contributions to maintain academic integrity.  
