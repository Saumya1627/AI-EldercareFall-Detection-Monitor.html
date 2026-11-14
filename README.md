# AI Eldercare — Fall Detection Monitor

🔗 **Live Demo:** [Launch Interactive Prototype](https://saumya1627.github.io/AIR-WRITE/)

An intelligent elderly healthcare and safety monitoring prototype designed to detect falls, analyze movement patterns, and manage real-time caregiver escalations.

### Key Features
* **Multi-Source Monitoring:** Supports uploaded video footage, live webcam feeds, and built-in simulated scenarios (walking, sitting, stair tumbles, and recovery).
* **Real-Time Activity & Posture Classification:** Tracks movement transitions, body tilt, and downward velocity at 10 Hz with automated scene-cut detection.
* **Escalation State Machine & Voice Check-In:** Progresses through `Normal` → `Unusual` → `Possible Fall` → `Notified` states with a 20-second rolling evidence buffer and simulated resident voice check-in prompts.
* **Built-In Self-Diagnostics:** Includes 22 automated self-tests and 7 end-to-end scenario checks to validate pipeline reliability.

> **Disclaimer:** *This is a frontend simulation and heuristic prototype built for demonstration purposes. It does not provide medical diagnoses or contact emergency services.*
