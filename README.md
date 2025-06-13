# NPC Emotion Weaver
**NPC Emotion Weaver** is a visual tool for designing and mapping the emotional states of Non-Player Characters (NPCs). Inspired by the Fuzzy Emotion Mapping System (FEMS), it helps you externalize and explore an NPC's internal landscape by visualizing how their emotions relate, resonate, and shift. This version is enhanced with AI-powered features to assist in character development.

#### **Core Concepts**

The map is built from a few key visual elements:

* **NPC Core Node:** The central gray circle labeled "NPC" represents the character's core self or current emotional state. All other emotional states radiate from this center.
* **Emotional States (Aspects):** Each colored circle is an "Aspect"—a specific emotional influence, memory, motivation, or mood.
* **Transitions:** Arrows drawn between Emotional States represent the flow and triggers that cause an NPC's emotions to shift from one state to another.

#### **Reading the Visual Language of the Map**

Each property of an Emotional State has a specific meaning, allowing you to understand the NPC's inner world at a glance. 

* **Text Label:** The name of the emotion, thought, or influence (e.g., "Resentful," "Hopeful," "Loyalty to the Crown").
* **Size (Intensity):** The size of a circle indicates its emotional intensity. A larger circle feels more present and strong, while a smaller one is more subtle or in the background. 
* **Distance from Core (Relevance):** A state's distance from the central NPC Core shows its relevance. Closer states are more pressing and active, while farther states are more distant, repressed, or less conscious. 
* **Color (Emotional Tone):** Colors represent the fundamental emotional tone of a state, based on a fixed palette for consistency. 
    * **Green:** Grounded, safe, calm, or healing. 
    * **Yellow:** Alertness, curiosity, tension, or new ideas. 
    * **Red:** Stress, conflict, pressure, or overwhelm. 
    * **Gray:** Numbness, confusion, or disconnection. 
    * **Blue:** Calm, reflection, peace, or insight. 
    * **Purple:** Deep or complex feelings like awe, grief, or transformation. 
* **Connection to NPC Core:** The line connecting a state to the NPC Core shows its influence.
    * **Solid Line:** A strong, clear influence. 
    * **Dashed Line:** A subtle, weaker, or uncertain connection. 
* **Aura Symbol (Modifier):** Optional symbols add another layer of meaning to a state. 
    * **🔒 Blocked:** The emotion is suppressed or inaccessible. 
    * **🌀 Spiraling:** The emotion is obsessive or stuck in a loop. 
    * **💧 Fading:** The emotion is diminishing or easing. 
    * **🌱 Emerging:** The emotion is new, developing, or growing. 
    * **🪨 Fixed:** The emotion is deeply ingrained, stubborn, or feels unchangeable. 
    * **⚡ Conflicted:** The NPC has internal conflicts about this state.
* **Waveform (Volatility):** A waveform shows the internal "feel" of an emotion. The amplitude (height) of the wave indicates how strongly this is felt. 
    * **Stable (Sine Wave):** Represents emotional resonance; a smooth, stable feeling. 
    * **Volatile (Sawtooth Wave):** Represents emotional dissonance; a sharp, jarring, or unstable feeling. 

#### **Key Features & Interactions**

* **Basic Interaction:**
    * **Pan:** Click and drag the background to move around the map.
    * **Zoom:** Use the mouse wheel or the **+** / **-** buttons to zoom in and out.
    * **Edit Text:** Double-click any state (or the NPC Core) to quickly edit its text label.
* **Emotional State Controls:**
    * **Add Emotional State:** Creates a new state on the map.
    * **Starter Vocabulary:** Use the "Show Starter Vocabulary" button to access lists of emotions, motivations, and triggers to help you get started.
    * **Edit Panel:** Click on a state to select it. The panel on the left will update to show all of its properties (text, size, color, etc.) for you to edit.
* **AI-Powered Assistance (✨):**
    * *Requires a Google AI API Key, which can be set in the "API Key Settings" menu.*
    * **Elaborate on State:** The AI provides deeper insight into a selected emotion, describing potential internal thoughts and observable behaviors.
    * **Suggest Dialogue Snippet:** The AI generates a sample line of dialogue that the NPC might say while in the selected emotional state.
    * **Generate NPC Emotional Profile:** The AI provides a holistic summary of the entire map, identifying patterns, core conflicts, and potential narrative arcs.
    * **Suggest Transition Labels:** When creating a transition between two states, the AI can suggest potential triggers or causes for that specific emotional shift.
* **Data Management:**
    * **Save/Load Map:** You can save your entire map as a `.json` file to your computer and load it back into the tool later.
    * **Export as PNG/SVG:** Export a static image of your current map view for use in documents, presentations, or other tools.
