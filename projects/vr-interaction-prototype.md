# 👁️ VR Interaction Prototype

Modular VR interaction prototype built with Unity 6 using the 3d Universal Rendering Pipeline.  Exploring gaze-based interaction, accessible navigation, and early universal-design principles.

## 🧠 Concept

This prototype explores how VR interactions can be made intuitive, comfortable and accessible.  It combines gaze-based interaction, animated feedback, spatial audio cues, and multiple navigation modes, including locomotion and teleportation with vignettes, to reduce simulator sickness.

The name of the project is 'Reality is Blurry' and the long-term goal is to evolve this into a game that raises awareness of visual impairment and includes features that support players with low vision.

## 🧩 My Role

- Built gaze-based interaction using XR Interaction Toolkit
- Added animated and audio feedback to reinforce user intent
- Implemented locomtion, teleportation, and vignette-based comfort settings
- Designed interaction logic with modularity and accessibilty in mind
- Prototyped early universal-design features for low-vision players
- Debugged collider issues, timing problems, and interaction edge cases

## 🛠️ Tech Stack

Unity • C# • XR Interaction Toolkit • OpenXR • Meta Quest Developer Hub • Spatial Audio • Animator Controller

## 🔧 Process

### Goal

Create VR interaction system that feels intuitive, comfortable and accessible, whilst laying groundwork for future game that tackles visual impairment in novel ways.

### Constraints

- Must work on standard VR hardware without eye-tracking
- Needs to minimise simulator sickness
- Interactions must be obvious for players with varying visual abilities
- Prototype must remain modular for future expansion

### Approach

- Used XR Interaction Toolkit for consistent interaction patterns
- Implemented gaze-based selection using raycasts + timed activation
- Added animation and sound cues to reinforce feedback
- Integrated locomotion & teleport with distinct vignette comfort modes
- Structured logic into modular components for easy iteration

### Key Decisions

- Feedback is multimodal (animation + sound) to support low-vision users
- Interaction scripts are modular to support future accessiblity features

## 🎥 Media

<figure style="margin-bottom: 24px;">
  <img src="/assets/images/vr-interaction-prototype/interaction-diagrams.png" alt="Early diagrams of interaction techniques">
  <figcaption style="text-align: center; font-size:0.9em; color:#666;">
    Sketch diagrams of interaction techniques
  </figcaption>
</figure>

<figure style="margin-bottom: 24px;">
  <img src="/assets/images/vr-interaction-prototype/gaze-interaction-in-unity.gif" alt="Demo of VR game">
  <figcaption style="text-align: center; font-size:0.9em; color:#666;">
    Gaze interaction, helmet animation state control, vignette
  </figcaption>
</figure>

## ⭐ Reflections

### What worked

- Gaze interaction felt intuitive and required no controlller precision
- Multimodal feedback improved clarity for all users
- Teleportation + vignettes offer clear signs to tackle simulator sickness
- Modular scripts made iteration fast and clean, as well as readable code for later updates

### What I'd improve

- Add haptic feedback for controller users
- Expand accessibility options (visual contrast modes, audio descriptions)
- Improve animation blending for smoother transitions
- Add dwell state to gaze interaction for improved gameplay
- More environmental cues for low-vision navigation

### What I learned

- Accessbility must be baked into interaction design from the start
- Gaze-based systems require careful timing to avoid accidental or overly frequent activation
- XR rigs can be fine-tuned but can cause a variety of mishaps if not properly understood
- Modular architecture pays off immediately in VR protyping and bug-fixing
