# 🧪 Lab 03 – Environment Building + Materials + Lighting + VR Scale

Duration: 2 Hours  
Project Type: Main continuous project (Lab 02 → Lab 09)

---

## Objective

Build a proper VR environment with correct real-world scale, simple materials, and comfortable lighting suitable for VR usage.

---

## Learning Outcomes

By the end of this lab, you will be able to:

- Apply correct real-world scale for VR environments  
- Create and manage basic materials  
- Apply materials to scene objects  
- Configure lighting for VR comfort  
- Design a simple themed environment with props  

---

## Software & Hardware Requirements

- Unity 2022.3 LTS  
- Meta Quest 3 (required)  
- VR project created in Lab 02  

---

## Step 1 – VR Scale Rules (Must Follow)

Use the following real-world scale guidelines when building:

- Door height ≈ **2 meters**  
- Table height ≈ **0.8 meters**  
- Player camera height ≈ **1.6 – 1.7 meters**

Adjust your objects and XR Origin camera height accordingly.

---

## Step 2 – Create Materials

1. Go to:

Assets/_Project/Materials

2. Right click → Create → Material  

3. Create the following materials:

- Mat_Floor  
- Mat_Wall  
- Mat_Prop  

4. Select each material and assign a simple color in the Inspector.

---

## Step 3 – Apply Materials

Drag and apply materials in the Scene:

- Floor → Mat_Floor  
- Walls → Mat_Wall  
- Props → Mat_Prop  

---

## Step 4 – Lighting Setup

1. Select the existing **Directional Light**  
2. Set:

Intensity = 1.0  

3. Add two Point Lights:

Hierarchy → Light → Point Light  

4. Place them near opposite corners of the room  

5. Set for each point light:

Intensity = 2 – 4  
Range = 10 – 15  

Ensure lighting is comfortable (not too dark, not too bright).

---

## Step 5 – Add Theme Props (Minimum 8)

Create at least **8 props** using:

- Cubes  
- Cylinders  

Examples:

- Signs  
- Pillars  
- Crates  
- Beds  
- Consoles  
- Tables  
- Storage boxes  
- Columns  

Place them naturally inside your environment.

---

## Submission Task

Record a **60-second** demo video showing:

- Teleporting or walking inside the environment  
- Proper scale (doors, tables, room)  
- Materials applied  
- Lighting clearly visible  
- All props placed  

Video filename format:

Lab03_<YourITNumber>.mp4

Example:

Lab03_IT21012345.mp4

---

## Submission Requirements

Submit BOTH:

1) Unity project folder (main project)

Folder name format:

Lab03_Project_<YourITNumber>

Example:

Lab03_Project_IT21012345

Upload the full project folder to GitHub.

2) Demo video file

Lab03_<YourITNumber>.mp4

Both items are mandatory.

---

## Next Lab

Lab 04 – Collectable Interactable Objects (Grab + Collector Trigger)

The same project will continue.

---
