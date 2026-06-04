# Week 7 — Rapid Prototyping and Concept Development
## Introduction
During the past week's sprint progress has been made on my Data-Driven Visualisation project and in taking my 'prototype' data set to a testable, interactive system with p5.js. This week focused on rapid prototyping, peer critique of ideas generated in week 6 along with iterations and experiments to refine them into a working prototype.

To achieve the overall aim of the project, which is to explore how passive utilisation of digital spaces can degrade our ability to focus, maintain structure and be intentional through motion, behaviour and visual deterioration, throughout the week I have worked at converting my raw statistics into a visualisation that demonstrates our emotional and behaviour experience of distraction. 

To achieve this, I have worked on refining my concept drawings, receiving peer feedback on my concepts, creating an initial working prototype, exploring AI-assisted approaches to prototyping, conducting “what if” testing on prototypes, and producing a better overall vision for what is required for upcoming refinement.

## 1. Concept Sketch Development
I started with a rough idea that I was going to make more explicit the links between the two types of digital behaviour—purposeful behaviour and passive behaviour (i.e. distraction).

With each draft of the rough sketch I continued to refine the visual hierarchy, the way the collapse systems function, the nature of the movement behaviour, and how the interface design would work.

To help in achieving those things, I created a list of visual call-out labels for the different particles that show how they represent structured endorsement versus passive distraction, as well as why the instability increases.

Once I did that, it became clear how the conversation between the two systems would not only identify issues users experience from distractions, but also the stability of their behaviour as time and conditions change.

The peer critique process helped me identify additional areas for improvement, including commonality between the two systems: while there was good contrast between the two systems in terms of the function of visual communication and the successful demonstration of collapse and distraction through visual collapse, certain interactive elements lacked clear separation visually.

![Week 7 Image 1](../assets/week-07/240%20week%207%20img1.png)
*Initial concept sketch exploring purposeful structure versus passive digital distraction.*

![Week 7 Image 2](../assets/week-07/240%20week%207%20img2.png)
*Peer observations and questions used to refine the interaction system.*

### Reflection on Peer Feedback
One very good question from the peer reviews was whether the system would be able to recover from a collapse temporarily as a result of user interaction. This question later influenced my desire to experiment with mouse interactions attempting to restore some order to the structure.

In examining the responses to the peer critiques, I concluded the project to be stronger if the visual systems function from an emotional standpoint rather than statistically. As opposed to presenting statistical data (e.g. screen time), the project is moving toward the representation of instabilities, loss of attention, drift in behaviour, temporary recovery, etc.

Additionally, peer critiques have further validated the notion of simplifying visual communication. In previous rough drafts, I presented too many competing ideas, but in my new draft I've presented more clearly how users interact with each visual system as their behaviour changes.

## 2. Making Sprint — Rapid Prototype

The Making Sprint was when I produced my first real interactive prototype using p5.js. This focused on creating a working particle system by testing out the following: particle behaviours, instability systems, slider-based interactions, and visual collapse. Each prototype had blue particles representing purposefully behaving particles, red particles representing passively behaving particles, and sliders controlling the following: instability (of both the purposefully behaved particles), spread (of passively behaved particles), and intensity (of passively behaved particles).

As the sliders were incrementing, the following occurred:
- Purposeful particles exhibited instability.
- Passive particles spread across the visual space.
- The overall appearance of the system exhibited visual chaos.

My intent was to not make a polished prototype but to create an observable and usable visual representation of the concept.

![Week 7 Image 3](../assets/week-07/240%20week%207%20img3.png)

*The first interactive prototype with respect to testing both parts of behavioural instability and spread.*


## Technical Development
In this week's prototype development, I switched gears and focused on developing the first functional level of the entire interactive system using p5.js. This included particle behaviour, movement systems, interaction systems, and visual hierarchy. 

One of my major breakthroughs this week was separating the systems into their independent sliders: passive intensity (of the passive particles), movement instability (of the purposeful particles), and spread (of the passive particles). This allowed for a more tangible relationship between each variable and provided for better communication of changes in the prototype.

The prototype was transformed into a clearer model for describing relationships between variables with more effective communication of behavioural change.

While learning how to use p5.js, I began experimenting with ways to develop my prototype using tools that harnessed AI for prototyping. In this way, I was able to use programs like ChatGPT for generating interaction ideas, identifying possible technical issues, and exploring new ways of creating movement and particle behaviour. Throughout this experimentation, I discovered that prompts that were more specific typically produced much more useful or controllable results than those that were broad.

During this time, I developed alternative ways of using:
- Mouse interaction
- Temporary periods of recovery
- Smoother transitions in movement

After creating these various prototypes, I determined that while movement and instability were able to communicate distraction and overload through colour alone, using some type of movement and instability was more effective in creating distracting and overwhelming behaviours in individuals.

![Week 7 Image 4](../assets/week-07/240%20week%207%20img4.jpg)
*Developing interaction systems, movement behaviour, and AI-assisted prototyping workflows in p5.js.*

{IMAGE}!
*Using AI-assisted prototyping to explore interaction systems, particle behaviour, and technical solutions.*

## 3. “What If” Variations

When I shared my prototype with a colleague, they provided a number of other possible directions I could take my prototype.
Some examples include:
- What if the visualisation was immersive and filled the entire screen?
- What if I had made all of the purposeful systems disappear gradually?
- What if I had interacted temporarily to restore focus before the system collapsed again?

Ultimately, I chose to focus on the restoring interaction idea. This variation introduces the idea that through mouse interaction, a user could momentarily restore order in a chaotic environment, thereby representing temporary regained attention before continuing to behave passively, resulting in further destruction of the system's order and stability.

This created a much more dynamic relationship between order and disorder and/or control and collapse.


![Week 7 Image 4](../assets/week-07/240%20week%207%20img4.jpg)
*Variation exploring temporary recovery and interaction-based focus restoration.*

## Reflection on Variations

The "What If" exercise enabled the advancement of the project from a static visual to a more interactive experience with the behaviour of an object.
Instead of the system just collapsing, the addition of temporary recovery created a more accurate representation of how people behave online:
At times focus while distracted and trying to re-gain control.

The ability to offer these variations provided a more human-like interaction compared to taking a more mechanical look at the interaction as linear.

It also reinforced the need for experimenting while prototyping rather than going right to a final polished outcome.


## Independent Study — Project Development
Throughout the class I continued to develop my prototype making it visually clearer.

This involved: 
- Smoother animation,
- Establishing strong hierarchies,
- creating cleaner layouts, and 
- Providing more controlled behavioural interactions. 

Taking into consideration how to develop the following elements:
- Slider labels,
- the effect of instability, and 
- The relationship of purpose and passivity. 

One thing I learned through the process was that excessive movement negatively impacts how easily something is read. By simplifying objects and regulating the intensity of the interactions I was able to create much stronger and more comprehensible experiences.


In parallel to refining the prototype, I continued to experiment with AI-assisted development workflows. I was able to use AI tools in various ways including testing my interaction ideas, refining how movement behaves, and exploring potential ways of creating particle systems. I feel this process has increased my ability to convert conceptual ideas into technical directives. Additionally, I am able to critically evaluate the generated solutions through continued experimentation, testing, and using AI-assisted prototypes will allow me to have more confidence in developing interactive systems to make a connection between technical decisions and the project concept.

## Weekly Reflection

This week has provided great clarity on where the direction of the project is headed. One of the most significant developments is that I have moved away from simply visualising screen time and have instead begun to create an interactive behavioural experience. I was able to show my peers how I began to use rapid prototyping, receive feedback from my peers and experiment with my digital prototype. I discovered that movement, instability, and interaction create a greater sense of distraction than displaying many different visual details. I am also in the process of developing my AI-assisted prototyping workflow where I have learned about how studio-quality prompts affect the generated outcome and how AI can be used as a tool for experimentation, iteration and solving problems.

Overall Week 7 developed the first functional iteration of the visual system as well as creating a more defined conceptual and technical direction for future refinements.

