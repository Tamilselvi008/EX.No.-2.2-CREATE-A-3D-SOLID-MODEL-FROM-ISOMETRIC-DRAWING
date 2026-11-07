# EX.No.-2.2 CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## Date :14-10-2026

## AIM: 

To create a 3Dmodel from the given isometric drawing using fusion 360 tool. 

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload
   
PROCEDURE:

1. Open Fusion and create a **New Design**.
2. Set the design units to the units used in your assignment, such as millimetres.
3. Save the file with a suitable name.
4. In the Browser, expand **Origin** and select the **horizontal plane** for the base sketch.
<img width="1920" height="1010" alt="Screenshot (146)" src="https://github.com/user-attachments/assets/09779e85-8f9b-4605-beb8-2c0e6bdef03b" />

### 2. Draw the base profile

1. Select **Create Sketch**.
2. Choose the horizontal plane.
3. Select **Create → Circle → Center Diameter Circle**.
4. Click to place the centre of the first circle and enter **36 mm** for its outside diameter, which is equivalent to a radius of 18 mm.
5. Draw the second outside circle on the opposite side of the plane. Align the two circle centres along the same horizontal axis.
6. Draw a concentric circle inside each outside circle and set each inner circle to **16 mm diameter**.
   <img width="1920" height="1004" alt="Screenshot (215)" src="https://github.com/user-attachments/assets/cc55935d-ddde-4715-8b80-77ea6ec4dfb5" />

8. Select **Create → Line** and draw the two straight tangent lines joining the outside circles, one along each side, to form the obround base outline.
9. Use **Trim** to remove any overlapping or unwanted line segments so the outer boundary is closed and both inner holes remain separate profiles.
10. Use **Sketch Dimension** to set the distance between the circle centres to **56 mm**, if that is what your 56 mm measurement refers to. If your drawing measures 56 mm between the straight tangent sections instead, dimension that distance accordingly.
11. Check that the sketch shows one closed outer base profile and two circular inner profiles.
12. Select **Finish Sketch**.
13. <img width="1920" height="1008" alt="Screenshot (217)" src="https://github.com/user-attachments/assets/2eeb25bc-224a-4a1e-b0fa-e7fd1abdbddc" />


### 3. Extrude the base

1. Select the base region between the outer outline and the two holes.
2. Choose **Create → Extrude**.
3. Enter the base thickness specified in your drawing.
4. Set the operation to **New Body** if this is the first solid feature.
5. Select **OK**. The two 16 mm circles should remain open through the base.
<img width="1920" height="1022" alt="Screenshot (219)" src="https://github.com/user-attachments/assets/40b00b5f-56c1-4bcb-9d22-74774cd9322e" />

### 4. Sketch the upright and horizontal arm

1. Select the appropriate top face of the base and choose **Create Sketch**.
2. Use **Rectangle → Two-Point Rectangle** to draw the first rectangle for the upright support.
3. Place it where the vertical support meets the base, using the reference image to guide its position.
4. Draw the second rectangle for the horizontal arm, extending from the upright toward the end that will carry the top boss.
5. Make sure the rectangles touch or overlap where they meet so the extruded features can form one connected part.
6. Use **Sketch Dimension** to set their widths, lengths, and positions according to your drawing.
7. Select **Finish Sketch**.
8. <img width="1920" height="1033" alt="Screenshot (223)" src="https://github.com/user-attachments/assets/08dc2fa8-893f-475c-ad15-b8da25469c3f" />


### 5. Extrude the upright and arm

1. Select the rectangular profile or profiles for the support and arm.
2. Choose **Create → Extrude**.
3. Enter the required extrusion height or thickness, following the orientation shown in the reference.
4. Set the operation to **Join** so the new material attaches to the base.
5. Select **OK**.
6. Inspect the model to confirm the upright and arm are joined to the base.
7. <img width="1920" height="1024" alt="Screenshot (222)" src="https://github.com/user-attachments/assets/90e82918-72ff-47da-a6a2-a6989e997bd5" />


### 6. Add the front chamfer

1. Choose **Modify → Chamfer**.
2. Set the chamfer type to **Two Distance**.
3. Select the front edge or edges that create the sloped face shown in the reference.
4. Enter the two chamfer distances from your drawing.
5. Check the preview to ensure the chamfer slopes in the intended direction and does not remove too much material.
6. Select **OK**.
7. <img width="1920" height="1004" alt="Screenshot (229)" src="https://github.com/user-attachments/assets/3d9654ad-903e-407c-ab48-753c63a98645" />


### 7. Sketch the top boss

1. Select the T-shaped top face at the end of the horizontal arm and choose **Create Sketch**.
2. Select **Create → Circle → Center Diameter Circle**.
3. Draw the larger circle and set its diameter to **30 mm**.
4. Draw a second concentric circle and set its diameter to **20 mm**.
5. Position the circles over the end of the arm as shown in the reference.
6. If your sketch needs connecting geometry between the circular boss area and the T-shaped surface, use the **Line** tool to draw it. Keep the profile closed and avoid extra overlapping lines.
7. Select **Finish Sketch**.
8. <img width="1920" height="1019" alt="Screenshot (225)" src="https://github.com/user-attachments/assets/aeb831c3-bb55-424c-b36c-3f1bc14f9d17" />


### 8. Extrude the boss

1. Select the ring-shaped profile between the 30 mm and 20 mm circles.
2. Choose **Create → Extrude**.
3. Enter the boss height specified in your drawing.
4. Set the operation to **Join**.
5. Select **OK**. The 20 mm centre should remain open as the boss bore.
6. <img width="1920" height="1002" alt="Screenshot (228)" src="https://github.com/user-attachments/assets/fa2084c0-3ee3-4513-bd01-f80b41dd5160" />


### 9. Check and save the model

1. Orbit the model and compare it with the reference image.
2. Confirm that the base has two open mounting holes, the upright and arm are connected, the front chamfer forms the intended slope, and the top boss has a clear central opening.
3. If the centre opening did not remain open during the boss extrusion, select its circular face and use **Create → Extrude → Cut** to cut through the boss.
4. Save the design.
<img width="1920" height="1014" alt="Screenshot (207)" src="https://github.com/user-attachments/assets/0e8c484f-3f39-4131-bc20-fd218d19d488" />

Input:
[image](https://user-images.githubusercontent.com/113594316/198523331-05ace360-502b-4569-b9b4-31c60e3cd554.png)

Output:
<img width="1920" height="990" alt="Screenshot (208)" src="https://github.com/user-attachments/assets/c5defc04-9592-4e54-b444-9853198aa3bb" />

## RESULT: 
Thus, the 3D model is created from given isometric drawing.


