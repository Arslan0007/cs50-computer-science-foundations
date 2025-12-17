# Week 0: "Beyond the Box" - Interview Simulation

## 🎮 Play Instantly
**[▶️ Click here to run the simulation on Scratch](https://scratch.mit.edu/projects/1256524609/)**

---

## 🚀 Project Overview
This project is part of my journey through **Harvard University's CS50**. While Scratch is a visual language, I used it to model a real-world challenge in the tech industry: **The "Silo Mentality" vs. "Holistic Engineering."**

In this simulation, the user plays a candidate answering technical and business questions. The goal is to prove that a "Specialist" who understands the whole picture (Business + Ops + Sec) is more valuable than a robot who just writes code.

## 🧠 The Logic Model
I implemented core Computer Science concepts to track "Value" rather than just "Score":

### 1. State Management (Variables)
* **`Silo Mentality`**: Represents working in isolation.
* **`Team Velocity`**: Represents the speed and quality of delivery.
* **The Logic:** These variables are inversely related. Answering with a holistic mindset lowers `Silo Mentality` and boosts `Team Velocity`.

### 2. The Loop (The Questions)
The simulation iterates through three critical domains of modern engineering:
1. **Pipelines:** Choosing Automation over manual fixes.
2. **Monitoring:** Choosing Data Analysis over blind scaling.
3. **Business Value:** Choosing User Feedback over code perfection.

### 3. Event-Driven "Breakthrough"
I used `broadcast` events to trigger visual feedback. As the candidate demonstrates higher-level thinking, the "Box" sprite (representing the limitations placed on engineers) visually cracks, breaks, and finally destroys itself.

### 4. Win Conditions (Hiring Logic)
I programmed a complex hiring decision tree:
* **Perfect Win:** If `Silo Mentality` reaches 0 (Perfect holistic thinking).
* **High Performance Win:** If `Team Velocity` > 60 (High value output), even if the candidate isn't perfect.
* **Fail:** If neither condition is met.

## 🛠 How to Run
### Option A: Web (Recommended)
Click the link at the top of this README to view the project in your browser.

### Option B: Local Source
1. Download `interview_simulation.sb3` from this repository.
2. Open [Scratch](https://scratch.mit.edu/).
3. Go to **File > Load from your computer**.