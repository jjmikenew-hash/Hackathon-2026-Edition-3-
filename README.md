Collabr 🎓



Collabr is an app designed specifically for university students. It solves the universal pain point of random, unbalanced group assignments by allowing students to recruit, match, and collaborate based on verified work ethic, technical skills, and schedule compatibility.

🚀 The Vision

Group projects shouldn't be a gamble. Collabr creates a merit-based networking environment siloed by university domains. Whether you are looking for a reliable backend developer for a hackathon, a meticulous researcher for a term paper, or just someone who actually shows up to meetings on time, Collabr helps you find partners who match your drive.

✨ Core Features

Walled-Garden Networks: Authentication is strictly tied to university domains (e.g., @osu.edu). You only match with active students on your specific campus.

The "Work Ethic" Engine: Say goodbye to toxic 1-5 star peer reviews. Collabr tracks objective reliability metrics, such as Project Completion Rates and average response times.

Verified Skill Badges & Core Competencies: Post-project endorsements award predefined, constructive tags (e.g., Documentation Expert, Team Anchor, Clutch Under Pressure) to highlight a user's specific strengths.

Integration Showcase: Let your work speak for itself by linking external portfolios directly to your profile, including GitHub repositories and Figma files.

Availability Heatmaps: A visual schedule grid ensures you only match with peers who share your preferred working hours (no more morning people clashing with night owls).

Free Agent Mode: Don't have a project idea? Toggle this status to signal to other teams that you are actively looking to be recruited for an open role.

No-Fault Divorce Protocol: Matched teams can mutually agree to disband within the first 48 hours of a project without suffering any negative impact on their tracked work ethic scores.

🛠 Technical Architecture

Collabr was built with a strong focus on backend stability and contract-driven design to ensure user data and matching metrics remain accurate and protected.

Contract-Driven System Design: Core functions (like updating work-ethic scores) rely on strict preconditions and postconditions to ensure algorithmic integrity.

Representation Invariants: The database architecture protects user profiles from breaking, ensuring ratings never drop below baseline algorithms or exceed maximum thresholds.

Algorithmic Data Structuring: Utilizes hash tables and optimized data structures to efficiently silo users by university domain and major, allowing for instant O(1) profile lookups.

Component-Based UI: The frontend is decoupled from the backend logic, allowing the matching engine to be rigorously unit-tested independently of the user dashboard.

Advanced Unit Testing: Comprehensive JUnit test fixtures verify complex edge cases, such as simultaneous mutual triggers of the No-Fault Divorce protocol.



🧠 Lessons Learned

Building Collabr reinforced the difficulty of translating subjective human behavior (like "hard work") into objective database metrics. It taught us how to ruthlessly scope features, implement strict representation invariants, and utilize user feedback to pivot our core mechanics mid-development.
