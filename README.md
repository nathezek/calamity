# Calamity

Voice-activated web study platform delivering unfiltered, direct feedback to combat student procrastination and enhance retention through AI-driven active recall and synchronized visualizations.

### ✨ Technologies
- `React`
- `TypeScript`
- `Next.js`
- `Tailwind CSS`
- `Python`
- `FastAPI`
- `Google Cloud Vertex AI (Gemini)`
- `ElevenLabs API`
- `Web Speech API (for voice recognition)`

### 🚀 Features
- Voice-Only Interaction: Users speak queries or commands; platform responds with audio feedback and synced visuals—no manual input required.
- PDF Uploader with Voice Activation: Invoke upload via speech; platform extracts context and integrates into study sessions with commentary.
- Brutal Explanations: AI delivers direct, sarcasm-infused breakdowns of topics, syncing audio with animated visuals (e.g., exploding equations for errors).
- Active Recall Quizzes: Post-lesson drills lock progress on failure, repeating explanations at accelerated speeds until mastery.
- Procrastination Locks: Detects inactivity and freezes the interface, enforcing completion with escalating audio prompts.
- Synchronized Visuals: Audio explanations trigger reactive UI elements, such as pulsing variables or flashing error indicators for mathematical concepts.

### 🎯 Who it is for
- High School Students: To overcome distractions and build foundational knowledge with enforced focus.
- University Students: For tackling complex subjects like mathematics or sciences with personalized, no-nonsense coaching.
- Learners with Motivation Issues: Individuals struggling with burnout or procrastination seeking a tool that demands accountability.

### 📍 Problem Statements (What This Platform Solves)
- Digital Distractions: Constant notifications and multitasking erode focus during study sessions.
- Procrastination Loops: Delays in starting or completing tasks, especially on challenging material.
- Low Motivation and Burnout: Fluctuating drive due to extrinsic pressures and lack of intrinsic engagement.
- Retention and Recall Issues: Forgetting key concepts post-study, leading to poor exam performance.
- Isolation in Learning: Disjointed online experiences that amplify loneliness and reduce productivity.

### 🛠️ Solution (How It Solves Each Problem)
- Digital Distractions: Implements focus modes that lock the interface and mute external notifications, using voice prompts to redirect attention.
- Procrastination Loops: Enforces timed drills and progress locks, preventing skips with escalating audio feedback until tasks are completed.
- Low Motivation and Burnout: Delivers direct, motivational commentary (e.g., "Fix this now or stay average") and gamifies micro-wins without superficial rewards.
- Retention and Recall Issues: Utilizes spaced repetition quizzes with immediate, visual-reinforced corrections to embed knowledge.
- Isolation in Learning: Simulates interactive coaching via voice, creating a "conversational" study environment that feels responsive and engaging.

### 🚦 Running the Project
Clone the repository  
```bash
git clone www.https://github.com/nathezek/calamity  
cd calamity
```
 Backend Setup  
 ```python
# Install dependencies (using uv or pip):  
  uv sync # or pip install -r requirements.txt
  
# Run the backend server:  
  uvicorn main:app --reload  
```
Frontend Setup  
```bash
 cd frontend 
# Install dependencies:  
  bun install # I used bun to create the project and install deps.
# Run the development server:  
  bun dev # Runs on localhost:3000.
```
Open the App  
`Open http://localhost:3000 in your browser.`
