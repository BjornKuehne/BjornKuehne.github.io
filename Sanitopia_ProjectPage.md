# Sanitopia

---

**Project description:** As part of my Guided Research project, I designed, implemented, and evaluated *Sanitopia*, a serious game for teaching medical students and healthcare trainees the principles of clinical environmental cleaning. The project explored how game-based learning and augmented reality can support infection prevention and control training.

---

<div style="display: flex; justify-content: center;">
  <img width="600" src="images/Cleaning Minigame Regular.png" alt="Sanitopia AR Bathroom Cleaning Minigame">
</div>

---

<div style="display: flex; justify-content: center;">
  <img width="600" src="images/Example MC Panel.png" alt="Example Quiz Panel">
</div>

---

### Goals

The objective was to create a serious game that:

- Teaches the core principles of clinical environmental cleaning
- Supports infection prevention and control training in an interactive way
- Compares a standard mobile version with an augmented reality version
- Uses learning principles such as retrieval practice, immediate feedback, dual coding, Bloom’s Taxonomy, and the method of loci
- Provides practical minigames where players apply cleaning knowledge in a simulated patient room
- Evaluates usability, technology acceptance, and learning outcomes through a pilot study

---

### Short Description of the Project

*Sanitopia* is a mobile serious game designed to teach environmental cleaning procedures in healthcare settings. The game places the player in a simulated patient room and teaches them how to identify high-touch surfaces, follow correct cleaning and disinfection procedures, and apply basic infection prevention principles.

The game consists of two main stages:

1. **Learning Stage:**  
   The player progresses through four short lessons placed at different hotspots in a virtual patient room. These lessons cover:
   - General principles of environmental cleaning
   - Cleaning and disinfection of medical equipment
   - Cleaning materials, PPE, and product labels
   - Bathroom hygiene, high-touch surfaces, and hand hygiene

   Each lesson contains information panels, multiple-choice questions, ordering tasks, and immediate feedback.

2. **Application Stage:**  
   The player then applies this knowledge through three minigames:
   - **High-Touch Surface Minigame:** Identify common high-touch surfaces in a patient room.
   - **Cleaning Minigame:** Perform the correct cleaning and disinfection procedure in the correct order.
   - **Mopping Minigame:** Mop a patient room using a sensible clean-to-dirty route while regularly rinsing the mop.

Two versions of the game were developed: a regular mobile version and an AR version. In the AR version, the player’s real-world movement and device rotation are used to navigate the virtual patient room, creating a stronger sense of spatial presence.

A pilot study with 8 medical students compared the two versions. Both versions received positive usability and acceptance scores, although the regular version performed better in usability and learning gain. The results suggested that AR can increase contextual realism, but also introduces interaction complexity that needs to be carefully managed.

---

<div style="display: flex; justify-content: center;">
  <img width="600" src="images/Mopping Minigame Regular.png" alt="Sanitopia Mopping Minigame">
</div>

---

<div style="display: flex; justify-content: center;">
  <img width="600" src="images/Example Info Panel2.png" alt="Example Info Panel">
</div>

---

### Technical Aspects

- **Platform:** Android
- **Engine:** Unity3D with C#
- **AR Frameworks:** AR Foundation and ARCore XR Plug-in
- **Project Type:** Serious Game / Educational Game / AR Training Application
- **Target Group:** Medical students and healthcare trainees
- **Evaluation Methods:**
  - Pre- and post-questionnaires
  - System Usability Scale (SUS)
  - Technology Acceptance Model (TAM)
  - Normalized learning gain

**Core Systems:**

- Lesson and quiz system
- Multiple-choice and ordering-based question logic
- Hotspot-based patient room navigation
- Minigame framework
- High-touch surface identification system
- Step-based cleaning procedure system
- Inventory/action system for cleaning tools and PPE
- Mopping scoring system based on cleaning order
- Immediate feedback and summary screens
- AR plane detection and anchor placement
- AR camera movement and orientation mapping

---

### My Contribution

I was responsible for the entire project, including:

- Researching clinical environmental cleaning and infection prevention training materials
- Designing the game concept and learning structure
- Mapping learning objectives to game mechanics
- Designing both the regular and AR versions of the game
- Implementing the full application in Unity
- Implementing the lesson system, quiz system, and feedback logic
- Implementing all three minigames:
  - High-touch surface identification
  - Cleaning and disinfection procedure
  - Patient room mopping
- Implementing the AR mode using AR Foundation and ARCore
- Designing the virtual patient room and placing learning hotspots
- Creating and adapting all instructional content and quiz questions
- Designing the evaluation study
- Recruiting and testing participants
- Analysing the pilot study results using SUS, TAM, and normalized learning gain
- Writing the final research paper

---

### Reflection

This project combined several areas I am interested in: serious games, healthcare training, AR, and learning design. One of the main challenges was making the game educationally meaningful while keeping the interaction simple enough for mobile and AR use.

The comparison between the regular and AR versions was especially useful. While AR seemed promising because environmental cleaning is highly spatial, the pilot study showed that AR does not automatically improve learning. Limited field of view, movement in AR, and more complex interactions introduced usability issues that may have reduced the learning benefit.

A key takeaway was that AR serious games need very careful interaction design. The technology can improve immersion and contextual realism, but only if it does not distract from the learning task. The project also showed the importance of expert input when designing healthcare training content, especially when trying to go beyond introductory material.
