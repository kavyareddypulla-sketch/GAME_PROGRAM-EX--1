# GAME_PROGRAM-EX--1
**EXP:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine**

Aim:
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

Procedure

Create a New Material:

Open Unreal Engine. In the Content Browser, right-click and select Material. Name it M_EffectsDemo. Apply Base Color:

Open the material. Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input. Add Emissive Effect:

Add a Multiply node. Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity). Connect the result to the Emissive Color input. Control Roughness:

Add a Scalar Parameter node and connect it to the Roughness input. Lower values = shinier surface, higher values = rougher surface. Control Metallic Property:

Add a Scalar Parameter node and connect it to the Metallic input. 0 = non-metal, 1 = fully metallic. Save and Apply Material:

Save the material. Apply it to any mesh in the scene (like a sphere or cube) to preview the results.

## Output
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/b2b9f697-2fa8-4074-954c-2cbe056a8ad2" />
<img width="1192" height="791" alt="image" src="https://github.com/user-attachments/assets/42943cfe-7747-4212-98f0-21aadfb4d4b6" />

## Result:
Successfully implemented a material in Unreal Engine showcasing:

• Emissive glow using emissive color and intensity.

• Variable surface roughness to simulate different textures.

• Metallic appearance adjustment to reflect light like real-world metals.

This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
