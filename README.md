# EX No.3.2. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:16-11-2026
## AIM:
To create a 3D solid model of the given Arched Bearing Bracket from its 2D 
orthographic views using Autodesk Fusion 360.
## REQUIREMENTS:
Operating System: Windows 10/11 (64-bit) or macOS 
Processor: 64-bit processor (Intel Core i5/i7 or AMD Ryzen 5/7 equivalent) 
RAM: 8 GB minimum (16 GB recommended) 
Graphics: DirectX 11/12 compatible GPU with 2 GB+ VRAM 
Software: Autodesk Fusion 360 (with active internet connection)
## PROCEDURE:
Step 1: Initial Setup 
Open Autodesk Fusion 360 and start a new design (File > New Design). 
Expand Document Settings in the Browser tree and verify that the active units are 
set to Millimeters (mm).
<img width="1007" height="481" alt="Screenshot 2026-11-20 212008" src="https://github.com/user-attachments/assets/1b4d84cd-5b37-4511-acfa-8c634dd5ff7c" />
Step 2: Create the Central Arched Body (Front View) 
1.Select Create Sketch and choose the XZ Plane (Front plane). 
2.Use the Line tool (L) to draw a horizontal baseline of 220 mm centered at the 
origin (110mm on each side). 
3.Select Create > Arc > Center Point Arc, click the origin (0, 0) as the center, and 
draw a semicircle of radius 110 mm (R110) connecting the two ends of the baseline. 
4.Draw the inner rectangular slot at the bottom center: 
Draw two vertical lines of 60 mm upward at 60 mm to the left and right of the origin 
(total width 120 mm). 
Connect their top endpoints with a horizontal line of 120 mm and trim (T) the middle 
segment of the baseline to leave a single closed arch profile.
<img width="1017" height="838" alt="WhatsApp Image 2026-11-15 at 22 48 44" src="https://github.com/user-attachments/assets/0421cc94-9720-43ae-828e-94cf8c95e056" />
Step 3:Extrude 
1.Click Finish Sketch. 
2.Select Extrude (E), click the closed arch profile, set Direction to Symmetric and 
Measurement to Whole Length, enter 150 mm, and click OK.
<img width="1581" height="852" alt="WhatsApp Image 2026-11-15 at 22 53 43" src="https://github.com/user-attachments/assets/02ebc88e-8ad4-4448-ad20-d4c97a52f70d" />
Step 4: Cut the Top Center Hole 
Select Construct > Offset Plane, choose the XY Plane, enter 110 mm upward 
(tangent to the top of the arch), and click OK. 
Select Create Sketch on this new construction plane. 
Draw a Circle (C) of diameter 20 mm (Ø20) centered at the origin (0, 0) and click 
Finish Sketch. 
Select Extrude (E), select the Ø20 circle, set Operation to Cut, set Extent Type to To 
Object, click the top inner ceiling face of the 60 mm slot, and click OK.
<img width="1411" height="922" alt="WhatsApp Image 2026-11-15 at 22 54 42" src="https://github.com/user-attachments/assets/e6f13054-7b19-493f-828e-69b275746803" />
Step 5: Create the Base Lugs (Top View) 
Select Create Sketch and choose the XY Plane (Bottom plane). 
Draw two circles of diameter 120 mm (R60) centered at 150 mm to the left and right 
of the origin (center-to-center distance 300 mm). 
Draw horizontal tangent lines connecting the top and bottom quadrants of both R60 
circles into the central body to form two closed side lug profiles. 
Inside each R60 circle, draw a concentric hole circle of diameter 40 mm (Ø40). 
Click Finish Sketch. 
Select Extrude (E), select both side lug profiles (excluding the Ø40 inner circles), set 
Operation to Join, enter a height of 30 mm upward, and click OK.
<img width="1409" height="837" alt="WhatsApp Image 2026-11-15 at 22 55 44" src="https://github.com/user-attachments/assets/bab47681-48cd-4ae4-8c51-d5ef03df5b1c" />
<img width="1458" height="741" alt="WhatsApp Image 2026-11-15 at 22 55 57" src="https://github.com/user-attachments/assets/f6b3704e-05ff-49dd-85d2-e170068e029a" />
<img width="1600" height="768" alt="WhatsApp Image 2026-11-15 at 22 56 06" src="https://github.com/user-attachments/assets/95366066-e5f2-4111-8d6f-486b0470d110" />
## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198823540-38a1b79a-1f68-4876-add9-adf59b98b386.png)

## OUTPUT:
<img width="948" height="672" alt="Screenshot 2026-11-15 222821" src="https://github.com/user-attachments/assets/d2a63ccf-f3e5-4495-b7c6-57201da7b5d1" />
<img width="788" height="557" alt="Screenshot 2026-11-15 220628" src="https://github.com/user-attachments/assets/883b6bd9-bd46-4dd7-96db-3424af468bcc" />



## RESULT:
Thus, 3D model is created from orthographic projection.



