---
layout: default
---

# Week 06 - Data Exploration and Initial Project Planning

[← Back to Home](../index.md)

## Introduction

The first phase of the Data-Driven Visualisation project for DES240 began this week. The main focus was on clarifying the project's objective, identifying potential datasets to use, finding visual precedents through research, and the technical/conceptual structure of the final interactive artefact.

In my project, I am investigating how the constant use of your phone turns into a passive behaviour that slowly erodes your attention span, the way you structure your thoughts and your ability to plan and carry out your actions. I would like to see how the design and the visual representation of data associated with screen time for a variety of uses could convey emotional and behavioural consequences caused by the use of screens through motion, instability, and collapse.


## 1. Data Exploration

### Data Source
The primary dataset for this project will be the screen time I recorded for my phone over a period of time, with the following data points captured timestamps, duration of each session, app categories, intended vs unintended screen time usage (purposeful vs passive usage), number of times each session was interrupted and the amount of time spent on the phone.

The data will initially be recorded manually and then transferred to an interactive visual behaviour (animation) using a p5.js system.

The overall data will be structured categorically into:
purposeful actions (navigating, studying, messaging)
passive actions (scrolling, using short form content, entertainment)
intensity values
duration pattern

The goal of the project is to communicate the behavioural patterns of the data through visualisations of the data in terms of instable motion, structural collapse, dispersed distraction, temporary recovery.

### Limitations and Biases
The major limitation in your data is that it's self-reported which means it has a lot of personal bias and less statistical reliability, but this limitation also supports your project idea as the goal of this project is to show lived behavioural experiences rather than to measure them objectively using scientific methodology.

Additionally, the purposeful and passive behaviours are sometimes very ambiguous, depending on the context, and this ambiguity has also been an important conceptual consideration because it illustrates how behaviours can be psychologically tangled together rather than clearly defined, thus creating an opportunity for this type of glitch-system visualisation to be effective.

![Week 6 Data Categories](../assets/week-06/240%20week%206%20img1.jpg)

*Initial data structure separating purposeful and passive digital behaviour.*

## 2. Visual Research and Precedent Study

### Reference 1 — Data Moshing / Glitch Visualisation
I have been very attracted to using glitches to provide visual communication of instability and overload rather than providing neat and clean statistical data. The goal is to then take the concept of visualisation and show that the visualisation is also emotionally a representation of distraction and loss of control.

This has lead me in the direction of creating an experiences-based system rather than creating a traditional dashboard.

## Reference 2 — Generative Particle Systems

I am also interested in using particles to create interactive systems as they allow behaviour to develop dynamically over time. I would like to use this technique by allowing passionate interactions to continue to grow to overwhelm purposeful structures.

This has been a primary motivation towards rethinking my perspective to design in relation to systems behaviour rather than static visual design.

## Reference 3 — Interactive Installation Works
My interest in interactive digital art installations has made me think about how people participate as an audience rather than just reading. I was curious about the user experience of experiencing behavioural collapse through their interaction with a piece, not just being entertained. This led me to create a more responsive p5.js environment as opposed to static visual graphics.

## Reference 4 — Screen-Time Dashboards
I looked at the current traditional screen-time dashboards to help me see what they lack that I wish to avoid in my project. A lot of current dashboards show information in the form of graphs and percentages while not displaying any of the emotional effects or cognitive effects of behaviours. This helped to drive my project toward a different metaphorical and experiential way of representing behaviours.

## Reference 5 — Experimental Data Art
Experimental data-based artworks have assisted in my interest in abstraction and atmosphere. These artworks show that data visualisation can communicate feeling, ambiguity, and tension as opposed to only communicating clarity. This also inspired me to begin to create a combination of readable systems with emotional representations that create an emotional language.

## 3. Project Planning and Skills Roadmap
### Initial Concept
The artefact that I am planning to create is an interactive p5.js visualisation of how passive digital behaviours affect a structured visual environment. The left side of my interface depicts purposeful behaviours: stability, structure, readability, and intentional interaction; while the right side of my interface depicts the passive behaviours: distraction, instability, overload and collapse. The goal is the progressive destruction of the overall structure of the system through the increased level of passive intensity in an interactive way, whereby at a basic level, the progressive destruction will result in visual effects such as shake, spread of particles, collapse of hierarchy, visual noise, and degradation of readability.

The end of the project will also include exploration of temporary restoration through intentional interaction.

![Week 6 Image 2](../assets/week-06/240%20week6%20img2.png)

*Initial concept sketch exploring the relationship between passive digital behaviour and system collapse.*


## Skills Roadmap
### Priority Skills to Learn
- p5.js interaction systems
- Slider and UI controls
- Particle behaviour and animation
- AI-assisted prototyping and development
- Prompt engineering for creative coding
- Debugging and refining AI-generated code

The main priorities was getting familiar with p5.js and improving my AI prompts for vibe coding

## Next Steps
Phase two of the project will be about improving the current p5.js prototype's interaction design, particle dynamics, and visual hierarchy. I'm also going to keep working on my AI-powered workflow by creating better quality prompts, refining generated code better, and utilizing artificial intelligence as a tool for quickly prototyping and testing new concepts. I will keep testing, refining, and obtaining feedback to continue to enhance the communication of the project's key concepts.

## Proposal Consultation Reflection

During the proposal review I discovered that while the raw data is an important part of this project, it is the social and emotional responses from users of digital distractions that will be the main point of interest within our project.

The other important aspect of the consultation was that the users wanted to see the experience of using the data visualisation, as opposed to simply having it be a traditional dashboard experience. As a result of this discussion, my focus has shifted to concepts of interaction, fluidity and the embodied experience of our users.

Additionally, the consultation allowed me to understand how to strengthen our project by viewing the use of a phone while an individual is doing something else (e.g. driving) as a force that is destabilizing the entire system rather than simply displaying data through numbers.

In light of these discussions, I have placed more focus on interaction design, behavioural metaphors, visual hierarchy, user experience.

Finally, the consultation highlighted the need for better documentation and continued reflection in my journal entries. Previously, I've relied heavily on screen shots with little to no explanation around how or why I have made the choices I did. As a result of this, moving forward, I want to include the following elements for each experiment:

- What was changed,
- How was it changed,
- What was effective,
- How does this experiment relate back to the overall project direction.

![Week 6 Image 3](../assets/week-06/240%20week%206%20img%203.png)
*Proposal consultation notes focusing on interaction, behavioural metaphor, and experiential visualisation.*

## Technical Skill Building

This week, I started exploring p5.js systems related to particles, sliders and movement behaviours, with a focus on developing understanding of how AI can assist during prototyping. My first few experiments were focused on establishing some form of visual differentiation between purposely and passively created digitalbased movement behaviour through motion, interactivity and instability.

Through both experimentation with p5.js and AI assisted coding, I assessed my attempts to explore particle systems via generative visuals, visually spreading out particles across a two-dimensional plane, and establishing a mechanism for controlling interactive intensity of the particle systems. During this time, I discovered that communicated by way of structural breakdown, movement communicated more effectively than colour alone.

The prototype also revealed technical difficulties as many of the interactions between particles and motion became visually overwhelming too quickly making readability more difficult and creating confusion when reading the system. This reinforced the importance of creating an appropriate balance between the visual clarity and the expressive behaviour of the prototype.

These first stages of experimentation led me to create future-proofed prototypes while at the same time develop my skills with p5.js and learn how to make optimise use of AI as a prototyping, testing and iterative design tool.

![Week 6 Image 4](../assets/week-06/240%20week%206%20img%204.png)
*Early p5.js prototype testing behavioural instability and distraction spread.*

## Initial Concept Prototype

I started to build on my previous sketches that mapped out my concept and created a first prototype to investigate how potentially passive use of phones alters the passive way we enter into structure by exploring ways i.e. through

- the motion of particles
- controls for interaction
- separation in space
- how to represent the gradual collapse over time of the amount of increase in distraction created by an increase in attentional over-load.

Although both sketches were rough, the tests demonstrated the core conceptual theme: Over time, the extent to which passive use of digital devices (phone, tablet, computer) distracts us from focused attention increases. 

The prototype set the stage for future refinements with:

- increased controls over the amount of interaction
- more consistent behaviour from the prototype
- clearer hierarchies and 
- intent to be able to recover.

## Weekly Reflection

This week's work has transitioned from my original concept to laying the groundwork for a fully-interactive prototype. Through ongoing experimentation with p5.js and AI-assisted prototyping, I have been exploring using movement, instability, and visual disruption to communicate passive use of digital devices over traditional data displays.

One of the biggest takeaways so far has been that behavioural and interactive elements communicate distraction far better than simple numerical data alone. In addition to developing my skills using p5.js, I have also improved the flow of my AI-assisted workflow by refining prompts, testing them out, and iterating on those results.

Overall, I believe that Week 6 has established the overall concept and scientific foundation for continued development.

