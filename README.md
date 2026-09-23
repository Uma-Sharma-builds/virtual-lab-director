# Virtual Lab Director

An AI-powered virtual physics lab where students adjust experiment parameters, watch real-time simulations, and take AI-generated quizzes to test their understanding.

## Problem Statement
Students often learn physics through passive methods — textbooks and static diagrams — which leaves conceptual understanding weak. Real labs aren't accessible everywhere, and traditional simulations are limited to "watch and observe," with no built-in way to test whether the learning actually happened.

## Solution
Virtual Lab Director lets students adjust experiment parameters (velocity, angle, mass, length, gravity, etc.) and watch the full experiment simulate in real time. Once the simulation completes, AI generates a dynamic quiz based on that specific experiment, instantly testing and reinforcing understanding.

## How It Works
Class → Chapter → Experiment selection → adjust parameters → watch animated simulation → solve AI-generated quiz → get score and feedback.

## Tech Stack
- Frontend/UI: Streamlit
- Simulation & Animation: Pygame, Matplotlib FuncAnimation
- Backend/Logic:** Python
- AI Layer:** OpenAI GPT API
- Deployment:** Streamlit Cloud

## Team
- Krati — Streamlit UI + AI mentor integration
- Harshita & Uma — Physics animations (Pygame/Matplotlib)

## Setup Instructions
\`\`\`bash
git clone https://github.com/Uma-Sharma-builds/virtual-lab-director.git
cd virtual-lab-director
pip install -r requirements.txt
streamlit run app.py
\`\`\`


## Demo
(Add demo video link and live demo link here once ready)
