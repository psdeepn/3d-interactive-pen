💉 Pen® 3D Interactive Showcase (Unity Experience)

An immersive, real-time 3D training and product exploration experience built in Unity.
Designed for Healthcare Professionals (HCPs) and patient education, this project combines interactive anatomy, guided workflows, and cinematic UI systems.

🚀 Overview

Pen® Reimagined in 3D

This project delivers a fully interactive insulin pen training simulation, allowing users to:

Explore product anatomy
Understand injection workflows
Learn through guided, interactive steps

Built using Unity with real-time rendering, animation systems, and modular architecture.

🎯 Key Highlights
🎮 Real-time 3D interaction
🧠 Guided learning experience (< 8 minutes training)
💡 Click-to-explore product anatomy
🔄 State-driven injection workflow system
📱 Designed for intuitive UX & engagement
🧩 Core Features
🔍 1. Clickable Part Anatomy
Each component is interactable using raycasting
Priority-based selection system
Emission pulse highlighting for user guidance

Scripts:

ClickablePart.cs
ClickManager.cs
🎠 2. 7-Panel Carousel Menu
Swipe + keyboard navigation
Dynamic panel transitions with blur/clear effects
Async animation sequencing

Scripts:

CarouselMenu.cs
DOTween animations
💉 3. Guided Injection Workflow

Step-by-step interactive training:

Prepare Pen
Check Insulin Flow
Select Dose
Inject
After Injection
State machine driven
Fully animated transitions
Progress tracking system

Scripts:

PenManager.cs
✨ 4. Universal Pulse Highlight System
Works across:
MeshRenderer
UI Image
SpriteRenderer
Smooth emission animation using DOTween

Scripts:

UniversalPulse.cs
🏷️ 5. Smart Labels Toggle
Context-aware label visibility
Different UI states based on pen interaction
Staggered animation effects

Scripts:

LabelsToggle.cs
📊 6. Expandable Sidebar Panel
Smooth UI panel expansion
Camera repositioning + model adjustment
Sequenced animation system

Scripts:

PanelToggleController.cs
🛠️ Tech Stack
Tool	Purpose
🎮 Unity	Real-time 3D rendering & interaction
🔷 C#	Core logic, workflows, systems
🎨 Blender	3D modeling & optimization
🖌️ Substance Painter	PBR texturing
🖼️ Photoshop	UI/UX assets
⚡ DOTween	Animation engine
🧠 Architecture

This project follows a modular, scalable Unity architecture:

🔄 State Machines for workflows
🎯 Priority-based interaction system
🎞️ DOTween-driven animation sequencing
🧩 Component-based design (plug & play systems)
📂 Key Scripts
Scripts/
│
├── Interaction/
│   ├── ClickablePart.cs
│   ├── ClickManager.cs
│
├── UI/
│   ├── CarouselMenu.cs
│   ├── PanelToggleController.cs
│   ├── LabelsToggle.cs
│
├── Systems/
│   ├── UniversalPulse.cs
│   ├── PenManager.cs
│
└── Misc/
    ├── FileSizeLogger.cs
    ├── PenController.cs
📊 Product Insights
✅ 85% Patient Confidence
⏱️ < 8 minutes average training time
💉 Up to 80 units dosing
🌱 8kg plastic saved per year (10 patients)
🌍 Environmental Impact

Switching to reusable pen systems significantly reduces waste:

♻️ 8kg plastic saved/year (per 10 patients)
🧴 Equivalent to ~380 plastic bottles
🎯 Target: 30% reduction per patient by 2033
🎥 Demo

👉 Add your demo video here:

https://www.youtube.com/watch?v=YOUR_VIDEO
🧑‍💻 Author

Sai Deepak
Senior Designer & VR Developer

Unity | VR | Interactive Systems
Real-time 3D Experiences
UX-driven product simulations
📌 Future Enhancements
🔗 Smart pen connectivity simulation
📊 Analytics tracking (user learning flow)
🌐 WebGL deployment
🤖 AI-guided assistant integration
📱 Mobile optimization
⚠️ Disclaimer

This project is intended for training and demonstration purposes only.
All product-related claims are backed by referenced clinical studies.

⭐ Support

If you found this project useful:

⭐ Star the repo
🍴 Fork it
🤝 Contribute
