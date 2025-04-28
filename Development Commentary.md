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


To inform my practical work, I began by identifying key sources that were directly relevant to the game and audio systems I wanted to create. I selected a mixture of games, academic writing, official documentation, and video tutorials, focusing on both creative and technical aspects.

### Game Sources


#### **Inside**

![Inside (2016)](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/304430/31203c10b21261375ba74d5a489f1c7f57d30326/capsule_616x353.jpg?t=1732629579)

*Figure 1*

Inside (2016) is a puzzle-platform game developed and published by Playdead. This was the original inspiration for the game so I thought it would be a good place to start my research. I have actually played the game myself before and really enjoyed the unsettling, minimalist atmosphere. The story is told entirely through the environment and sound design, since there aren't really any cutscenes or narration.
A key feature of the game, in terms of sound, is the lack of dialogue, which allows players to interpret the story in whatever way they like. This puts an emphasis on environmental sounds which need to support the story told by the visuals. Since this is a puzzle game sounds are also responsible for giving the player cues when solving puzzles, clicks to signify mechanisms unlocking or beeps to show the player has failed a puzzle. Cues like these are paired with visual cues such as bright red buttons, which stand out against the bleak, grey environment.

When researching Inside, I learned a lot about the importance of matching sounds and visuals to create a cohesive experience for the player. I want to do a similair thing in my project by working closely with the level designers so our work can compliment each other. Instead of trying to make sound a big focus, I want it to be a subtle enhancer for the player's immersion and understanding of the game.

<br>


#### Portal

![Portal (2007)](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/400/header.jpg?t=1745368554)

*Figure 2*

Portal (2007) is a puzzle-platform game developed and puiblished by Valve. The primary game mechanic includes portals which are used to complete puzzles within test chambers. Unlike Inside, Portal has an AI character called GLaDOS who provides almost all of the dialogue in the game and acts as a guide for the player. This narrator succeeds at building a personality and narrative, without overwhelming the player and becoming tiresome or annoying. In terms of other audio, each test chamber has some subtle ambience such as mechanical hums and machinery noises. These reinforce the atmosphere of a clinical facility.

I took inspiration from Portal's narrator who is able to enhance the story without distracting from the gameplay. I want to take a similair approach with the Scientist character in our game, her voicelines should assist the player and hint to a bigger world without becoming repetitive or annoying. I will need to build her character gradually because she starts off very cold and calculated, and develops empathy for the experiment subject as the game goes on. Milestones such as completing puzzles can help build this bond between the player character and the Scientist.



    
### Academic Sources

<br>

#### Game Audio Mixing: Insights to Improve Your Mixing Performance by Alex Riviere

![](https://m.media-amazon.com/images/I/71SSS1Ej-mL._AC_UF894,1000_QL80_.jpg)

*Figure 3*

As my main focus during this project would be audio programming, I chose a book called Game Audio Mixing by Alex Riviere as part of my research. This book is an overview of many game audio mixing techniques, processes and workflows. One of the key concepts I focused on was sound prioritization. Riviere explains prioritizing is to decide where to place your focus, which sounds are crucial to be heard and which ones can be softened or sacrificed. (Riviere, 2023, p.64). 



For my project I can apply this logic by prioritising sounds that must always be clear to the player such as; bubble impact, environment and puzzle cues. Less important background sounds, such as subtle ambient noise layers or distant environmental effects, could be mixed at lower levels to avoid cluttering the audio.

This research also influenced how I approach the balance between different types of sounds in a scene. For example when adding voice over to the game, I would have to consider when and how her dialogue would cut throught the environment without overpowering important gameplay feedback.  Using Riviere�s prioritisation method helped me plan the audio layers so that critical sounds always remained clear, and the voice-over enhanced the storytelling without becoming distracting. Overall, this academic research provided a strong foundation for managing the complex layering of sound elements in the project.



### Documentation Sources


#### How To Create A Dynamic Footstep System In Unreal Engine (Tutorial) by Matt Aspland

[How To Create A Dynamic Footstep System In Unreal Engine (Tutorial)](https://www.youtube.com/watch?v=KUhOUkLCfgc&ab_channel=MattAspland)

<iframe width="560" height="315" src="https://www.youtube.com/embed/KUhOUkLCfgc?si=wvDjg0yK6OtVm-Kh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

*Figure 4*

One of the first things I wanted to add to the project in terms of audio was dynamic footsteps which would change the sound of the player character's footsteps based on the surface they were walking on. I used this Youtube tutorial, Aspland explained how to use physics materials and animation blueprints to create a dynamic footstep system.

I thought this would be incredibly useful as I could work on it before the designers were finished with their levels because of how flexible this system is. If designers wanted to add a new surface or change one that was already in the game, the only thing they would have to add is a new physics material, and of course the footstep sounds.

#### Random audio file playback in MetaSound - Unreal Engine 5 Game Audio by Sound Codex

[Random audio file playback in MetaSound - Unreal Engine 5 Game Audio by Sound Codex](https://www.youtube.com/watch?v=2r81xQLqoBg)

<iframe width="560" height="315" src="https://www.youtube.com/embed/2r81xQLqoBg?si=Tt_v3LPiiRkjeglE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

*Figure 5*

After creating the dynamic footsteps I realised I would need to randomise audio throughout the project to keep it more realistic and stop the sounds from being repetitive. For example, if each footstep sounded the same, it would throw the player off as that is not how sound works in real life. 

I looked at another youtube tutorial as I personally find videos to be one of the most helpful methods of learning information. This video by Sound Codex looks at audio containers and how to use them to randomise the sound that plays. It is actually very simple, and again it is another flexible system which allows you to add or remove sounds. You can even change how likely certain sounds are to play by changing their weight.

#### Audio in Unreal Engine 5 Documentation

During the project I also referred to Unreal Documentation. Audio in Unreal Engine 5 provides an overview of UE5's audio framework, explaining features such as Sound cues, Metasounds, audio components and attenuation settings which can all be used to create dynamic and immersive audio experiences.  (Audio in Unreal Engine 5 | Unreal Engine 5.5 Documentation | Epic Developer Community, s.d.).

This documentation was very useful to help me get an understanding of Metasounds, particularly why I should use this over sound cues. Originally I found sound cues easier to implement, however through my research I discovered Metasounds addresses a lot of the issues that sound cues have, and is generally higher performance.

Additionally, the guide reinforced the importance of attenuation and spatialisation, which would help my sounds feel natural within the 3D space.

Overall the documentation is always a helpful guide to refer to however sound is a sense that cannot always be perfectly explained in writing so I mostly referred to it when having technical problems.





## Implementation (Suggested Word Count 1,100)

### Process
- Provide a step-by-step breakdown of your development process, including key milestones and decisions made throughout the project.  
- Highlight any tools, frameworks, or techniques used, and explain how they contributed to the implementation.  
- Include screenshots, diagrams, or code snippets where relevant to showcase your progress.  

#### Optimisation

At the beginning of the project I helped with optimisation by changing blueprints into actor components so they could be reused for future mechanics. I worked on BP_BodyChar which was the body of the player character. I put the SpawnBubble() and PopReset() functions into the Actor Component AC_BubbleController.

<iframe src="https://blueprintue.com/render/l09p1tl8/" scrolling="no" allowfullscreen></iframe>

*Figure 6. Blueprints for Bubble Spawn*


#### Technical Support

To make my audio cohesive with level visuals, I had to work closesly with level designers. Since I was already frequently communicating with them, I also took on a technical support role where I would help designers who were having issues.

Most of this was helping with resolving merge conflicts when pushing in Github. Some conflicts were more difficult to solve than others, but overall I ensured the main branch remained stable and commits would not overwrite any important blueprints.

I also offered help to those who had problems opening the project at home, and created a markdown document of step by step instructions that could help solve their issue.

Here is a link to the tutorial I made to hopefully help build the project successfully at home:
[Unreal For Windows 10](https://github.com/wszramkowska/MyUCA-Notes/blob/main/Unreal%20Windows%2010.md)

#### Voice-Over

I also attended the voice-over recording sessions to provide opinions from the perspective of an audio programmer. Voice-over for the beginning of a level should explain that test chamber, and would therefore be a bit longer. However voice-over for things such as player death should be shorter and have various versions, this is because the player would hear these voice lines more frequently and so they may become repetitive much sooner.

Here is a link to the final voice line recordings and script:

[Final Voice Lines](https://drive.google.com/drive/folders/1uUn62mpLoAL6-yhYoxVH4wV81M607tN_?usp=sharing)

Unfortunately due to time constraints the voice lines were not edited in time and therefore I was unable to implement them into the game. I tested the raw voice lines for player death and created a MetaSound Source which played a random voice line when the player died. I was unhappy with how the voice sounded within the game and chose to cut voice-over and instead focus on ambience and environmental sounds.

#### Dynamic Footstep System

One of the first major components I implemented was a dynamic footstep system which changed the sound of the player character's footsteps depending on the surface they were walking on. 

I did this by creating an AnimNotify event, matching the notify in the animation sequence to play when the foot hits the ground. In the animation blueprint, different sounds play depending on what physical material the character is stepping on. To achieve this, the floor surface must use a material which has a physics material assigned to it. 

This allowed the system to adapt to new surfaces seamlessly, even before the level designs were finalized. If designers wanted to add or modify surfaces in the game, the only requirements were the addition of a new physics material and appropriate footstep sounds, making the system flexible and adaptable.

<iframe src="https://blueprintue.com/render/6sokr1zb/" scrolling="no" allowfullscreen></iframe>

*Figure 7. Blueprints for Dynamic Footstep System*

#### Randomised Audio Playback

Another key feature I implemented was the randomization of sound effects. While creating dynamic footsteps, I realized that repetition could break immersion. To address this, I used Unreal’s MetaSounds system to randomize footstep sounds. By organizing audio clips into containers, I ensured that each footstep sounded unique, mimicking the random nature of real-world sounds. This helped prevent the game from sounding monotonous, and keeping the sound design realistic.

I used this for various sounds through the project such as the dripping of oil and sap, which also play random sounds from a set selection each time they drip, and also for ice breaking.

Creating these Metasound Sources gave the level designers an easy way to add audio that feels more natural, whilst also having access to the original, individual sounds where needed.

#### Audio Research and Editing

Originally me and the other audio developer wanted to make our own sounds for the game however we did not have full levels until quite late and were left with not enough time to accomplish that.

Instead I chose to find audio online and try my best to edit it and match it to our game so everything still sounds coherent. I found most of the sounds on [Freesound](https://freesound.org/), ensuring all of the copyright licenses were Creative Commons and usable for our game. This limited the sounds I could choose and meant I was not always able to find a good match.

I then edited these sounds in Adobe Audition, mostly cutting the audio to the specific parts I needed. I then added all of these into the Unreal Project, creating an organised folder system so designers could find them easily.

#### Audio Implementation

I assisted the designers in implementing some of the more complex audio. For example, in the winter level there are particle systems that blow cold air. The designer was finding it difficult to add the audio into the Niagara particle effect, so I worked around it and timed the audio to match the particle. This allowed me to play it at spawn which matched the audio to the visuals.

#### Intro Video Audio


### New Approaches
- Detail any innovative or new approaches you explored during the project.  
- Explain why these approaches were chosen and how they differ from standard practices.  
- Evaluate the success of these approaches, including any challenges faced and lessons learned.  

### Testing
- Document the user testing conducted, specifying the type of tests used (e.g., automated testing, guided user testing, blind testing).  
- Present feedback or issues identified during testing, using graphs, tables, or visual aids to summarise results.  
- Describe how these issues were addressed. If any issues were not resolved, provide a clear justification for leaving them unaddressed.  

Inititally before the sounds were implemented, I playtested the levels made by our designers. This not only provided feeback for their puzzles and game mechanics, but also allowed me to get a good grasp of each level and the kind of atmosphere I would need to create with audio. I also took note of any assets in teh level which would require sound such as oil dripping, swinging axes and big fans.

I collaborated with other members of my team, specifically the level designers, to conduct playtesting sessions. These sessions involved team members playing through the level as I observed and collected feedback regarding the audio experience.

I received feedback about footstep audio transition between surfaces, sometimes when the player moved from one surface to another the footsteps could sound awkward or out of place. I had a lot of difficulty trying to fix this because the footsteps were free sounds and I didn't have enough technical knowledge in audio editing to create a smoother blend. Given more time I could learn Adobe Audition in more detail and try to edit the sounds more so they would match and transition more easily.



### Technical Difficulties
- Identify any technical difficulties encountered during the implementation phase.  
- Provide details on how these issues were diagnosed and resolved.  
- If any difficulties remain unresolved, explain the impact on the project and any mitigation strategies used to minimise their effect.  
- Reflect on what you would do differently in future projects to avoid similar issues.  

One technical difficulty I encountered when implementing my audio is working with the Niagara Particle System. The winter level of the game had tunnels which blasted cold air, the visuals for this were done using Niagara. When trying to add the sound for this, I attemoted to make an event in the emitter, which I could then call from the tunnel blueprints. However I could not get the events to actually show up and instead I cut the audio perfectly and timed it to the wind blast, then played it when the particle effects were spawned. In the end I was happy with the timing of the audio matching the effects, however I would like to do further research in the future into the Niagara Systems and specifically how to implement audio within them.




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
 

Overall the research I did throughout the project was highly beneficial, specifically the documentation and youtube tutorials I referred to throughout the project. These provided technical guidance, enabling me to design and implement the audio systems effectively. However, there are areas where additional research could have enhanced the project, particularly in interactive sound design and the deeper integration of narrative through audio. While these gaps did not significantly hinder the project, addressing them in future work could further elevate the audio experience and player engagement.

### Positive Analysis

I think a successful part of the project was creating systems that designers could easily use in their levels. The dynamic footstep system only required a physics material and some sounds to use which made the work of level designers much easier. 

The Metasound sources which randomised audio was also made to assist designers, they wouldn't have to program anything to randomise sounds and could instead use these Metasounds, implementing them wherever they needed in their level, or adding them into their blueprints.

Throughout the project I kept good communication with the team and offered my help with technical problems such as github, or building the project.

Overall I think my role in supporting the designers for this project helped in some parts to streamline the production of the game and reduce technical difficulties where possible. 

### Negative Analysis

As it was our first big team project, there was a steep learning curve in efficiency and communication. Whilst some members were consistently communicative, others were less responsive, which occasionally caused an imbalance and made it difficult to coordinate tasks effectively. This led to delays and additional pressure during the final stages of the project.

Another significant challenge was the timing of audio integration. Since audio typically comes at the end of the production pipeline, I was unable to access finished levels until quite late in the project timeline. This limited the amount of time available for implementing, testing, and adjusting the audio to fit the final environments. In some cases, I also had to quickly source or create new sounds to match unexpected design changes, which affected the overall polish of the final product.

Despite these challenges, the experience taught me the importance of early communication and flexible workflows when working on audio in a collaborative project.

### Next Time

If I was to do this project again, I would prioritise setting up clearer communication at the start. Establishing regular meetings or check ins could help production progress. I also think there should be more specific deadlines assigned to individuals or teams, for example level designers having a finalised blockout by a certain week.

Another thing I would do is spend more time learning audio editing software such as Adobe Audition. I didn't have any experience prior to this project, and I didn't fully realise how detailed this software can get until I started working in it. I think not knowing how to efficiently edit audio slowed me down a bit.



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
