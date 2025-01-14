# **LumbarLagoon**

**Project description:** As part of my Bachelor’s thesis, I developed LumbarLagoon, a prototype exercise-based serious game (exergame) designed to help prevent the onset of lower back pain in healthcare workers. The game incorporates specific exercises carried out within a narrative-driven context.

### Goals

#### Accessibility and Usability

Designed to be used by healthcare workers during work breaks, the game kept to the following design considerations:

- **Device Requirements**:
  - The game should function in limited spaces, such as a break room, without requiring additional equipment like yoga mats.
  - Setup should be simple, avoiding complex or time-consuming requirements such as wearable devices or external equipment.
  - The solution should be scalable, allowing cost-effective implementation for multiple healthcare workers.
  - The device should maintain sufficient accuracy to ensure meaningful recognition of correct exercise performance.
  - Based on these criteria, the Azure Kinect was selected as the hardware device.
- **Time Efficiency**:
  - Given the demanding schedules of healthcare workers, the intervention is designed to be brief and require minimal time for setup and gameplay.

#### Exercise Selection

Interviews with a physiotherapist led to the inclusion of two seated exercises, effective at reducing the risk of lower back pain:

- Lateral flexion
- Trunk rotation

### Short Description of the Game

Building on the thematic elements of FrogZen, LumbarLagoon’s narrative tasks the player with collecting and delivering water to Sir Hopsalot:

- **Collecting water**: Players perform lateral flexions to fill buckets on their shoulders.
- **Delivering water**: Players perform trunk rotations to dodge oncoming boats and prevent spilling water.

Watch a [Demo Video here](https://youtu.be/DFLsVvO5Eu8).

### Technical Aspects

- **Platform**: Windows, paired with the Azure Kinect Device SDK
- **Engine**: Unity3D with C#
- **Motion tracking**:
  - The Azure Kinect was used to detect body postures and ensure exercises (lateral flexion and trunk rotation) were performed correctly and safely.

### My Contribution

I completed the entire development process, including:

- Defining the problem statement
- Researching existing solutions and related work
- Conducting interviews with a physiotherapist
- Planning and designing the game’s layout and UI
- Developing the game from start to finish
- Conducting a preliminary evaluation of the game through interviews with a physiotherapist
