# Ex. No.  3 - PROTOTYPE PART MODEL DESIGN IN 3D PRINTER

### DATE:11.03.2026
## AIM: 
### To prototype the given part model design in 3D Printer.

## REQUIREMENTS:
### ●	3D Printer machine.
### ●	CURA 4.0 Software.
### ●	Autodesk Fusion 360 Software.
### ●	System - Windows 7 or higher, 1 GB RAM.


## Procedure

### Step 1: Open Autodesk Fusion 360
1. Launch Autodesk Fusion 360.
2. Create a new design file.
3. Select Create → New Component to start the gear model design.

### Step 2: Create the Gear Sketch
1. Select Create Sketch on the XY plane.
2. Draw a circle which will act as the base for the gear.
3. Use gear parameters such as number of teeth, pitch diameter, and module.
4. Use the Circular Pattern tool to create repeated gear teeth.
5. Finish the sketch after completing the gear profile.

### Step 3: Extrude the Gear Model
1. Select the completed sketch.
2. Click Create → Extrude.
3. Give the required thickness to the gear body.
4. The gear becomes a 3D solid model.

### Step 4: Save and Export the Model
1. Save the design in Fusion 360.
2. Right click the body.
3. Select Save as Mesh / Export.
4. Export the model as an STL file for 3D printing.

### Step 5: Open the Model in Cura
1. Launch Ultimaker Cura.
2. Click Open File.
3. Import the STL gear model into the Cura workspace.
4. The model will appear on the build plate.
<img width="934" height="576" alt="Screenshot 2026-03-12 141050" src="https://github.com/user-attachments/assets/10fee033-2778-4d09-84c3-ad047262b723" />


### Step 6: Use Pan Option
The Pan option is used to move the view of the model inside the workspace.

Steps:
1. Press and hold the middle mouse button.
2. Move the mouse to navigate around the model.
3. This helps inspect the design from different positions.
<img width="1595" height="932" alt="Screenshot 2026-03-12 141122" src="https://github.com/user-attachments/assets/aa1de5a2-4c20-475d-bc39-b9ecd784d47a" />


### Step 7: Select the Extruder
1. Click the gear model on the build plate.
2. Choose the extruder option from the settings panel.
3. Select either:
   - Left Extruder
   - Right Extruder

This step selects the nozzle that will print the model.
<img width="1593" height="932" alt="Screenshot 2026-03-12 141510" src="https://github.com/user-attachments/assets/7e62b535-0a96-40ee-a86f-cb892d80397d" />

### Step 8: Repair the Model
Sometimes STL files contain mesh errors such as holes, overlapping faces, or non-manifold edges.

Steps:
1. Import the STL model.
2. Cura checks the model automatically.
3. Errors are corrected using automatic mesh repair.

### Step 9: Move the Model
The Move tool is used to position the model on the build plate.

Steps:
1. Select the Move tool from the toolbar.
2. Drag the arrows to move the model along:
   - X-axis
   - Y-axis
   - Z-axis
3. Place the model properly at the center of the build plate.

### Step 10: Rotate the Model
The Rotate tool is used to adjust the orientation of the model.

Steps:
1. Select the Rotate option.
2. Use the rotation circles to rotate along X, Y, or Z axis.
3. Use Lay Flat option to automatically place the model on the build plate.

Proper rotation helps reduce support material, reduce printing material usage, and improve print quality.

### Step 11: Set Printing Parameters
Set the required printing parameters such as:

- Layer Height : 0.2 mm
- Infill Density : 20%
- Printing Material : PLA
- Print Speed : 50 mm/s
- Nozzle Temperature : 200°C

### Step 12: Slice the Model
1. Click Slice.
2. Cura converts the model into G-code instructions.
3. The slicing process calculates material usage, print time, and layer paths.
<img width="1596" height="936" alt="Screenshot 2026-03-12 141547" src="https://github.com/user-attachments/assets/83c848fa-8142-4829-875c-d3f694390e59" />

### Step 13: Save the G-code
1. Click Save to File / Save to SD Card.
2. Transfer the G-code file to the 3D printer.
<img width="939" height="583" alt="Screenshot 2026-03-12 141619" src="https://github.com/user-attachments/assets/5adb22e0-aed5-4c41-920b-d11b1245a820" />

### Step 14: Start Printing
1. Insert the SD card or connect the printer.
2. Select the G-code file.
3. Start the 3D printing process.

## Result
The gear model related to kinematics was successfully designed in Autodesk Fusion 360 and prepared for 3D printing using Ultimaker Cura.

## Output:
<img width="1465" height="749" alt="Screenshot 2026-03-12 143607" src="https://github.com/user-attachments/assets/13a3722e-1bfb-4f16-828b-48020b8dbe51" />


### Name:Shailesh S S 
### Register Number:25007622

## RESULT:
###   Thus a prototype of the given part model is developed using 3D Printer.
