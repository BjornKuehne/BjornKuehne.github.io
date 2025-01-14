# FrogZen

**Project description:** For my Bachelor’s thesis, I developed a gamified mindfulness mobile app, FrogZen, aimed at mitigating stress in healthcare workers. After completing development, I conducted a qualitative study involving 19 healthcare workers at a hospital in Glasgow, yielding substantially positive results.

### Goals

#### Scope and Approach

The app was designed to align with my expertise and intentionally avoided delivering structured or formal therapy. Instead, I adopted an informal approach utilizing concepts such as:

-	Mindfulness practice
-	Attention Restoration Theory
-	Distraction Therapy

#### Design Goals

- **Accessibility and Suitability**: Tailored to healthcare workers, the app was designed with the following considerations:
  - **Ease of use**: The app had to be easy to pick up and easy to put down, accommodating the busy schedules of healthcare workers
    - A mobile platform was chosen since over 90% of healthcare workers own smartphones
    - Content was designed to be engaging but not demanding, enabling value through short interactions
  - **Intuitive UI**: The user interface was kept simple and intuitive to eliminate learning curves.
  - **Appropriate gamification**: Gamification was included to make the mindfulness techniques more engaging, without making it into a serious game, so as not to inadvertently present unwanted challenges during the workday.
- **Informal tone**:
  - To address the stigma among healthcare workers surrounding mental health support, the app avoids any clinical language and uses a light-hearted, informal tone.
  - The app should serve as an additional informal tool for stress relief, not as a substitute for formal therapy, as this would be difficult to achieve within the scope of my thesis.

### Short Description of the App

Core Features:

1. **Mindful Frog Companion**
    - Users interact with a chatbot, “Sir Hopsalot,” set in a tranquil natural environment.
    - Sir Hopsalot engages users in playful, mindful conversations about their day, interests, or previous conversation topics.
    - The frog persona minimises the risk of the uncanny valley effect and fosters familiarity.
2. **Interactive Breathing Exercise**
    - An interactive guided breathing exercise based on the box breathing technique helps reduce physiological stress symptoms.
3. **Gamified Creative Expression Activity**
    - Inspired by Google’s “Quick, Draw!” AI experiment, this activity allows users to draw while Sir Hopsalot playfully guesses their creation.

Watch a [Demo Video here](https://youtu.be/RrvcG253V2Y).

### Technical Aspects

- **Platform**: Android mobile application
- **Engine**: Unity3D with C#
- **Chatbot Functionality**:
  - Implemented using the OpenAI Unity package to make chat completion requests to the OpenAI API.
  - Chat history and engineered prompts to maintain desired content and tone in responses from the OpenAI agent are stored locally on the device.
- **Drawing Recognition**:
  - Microsoft Azure’s Cognitive Services: Computer Vision API is used to generate captions for user drawn images
  - The captions are passed to OpenAI’s chat completion endpoint to formulate playful guesses.
  - Note: at the time of implementation, only GPT-3.5 was available. Future work could use GPT-4’s image processing capabilities to streamline the process.

### My Contribution

I completed the entire development process, including:

- Defining the problem statement
- Researching existing solutions and related work
- Planning and designing the app’s layout and UI
- Developing the app from start to finish
- Conducting a comprehensive evaluation of the app with end-users
