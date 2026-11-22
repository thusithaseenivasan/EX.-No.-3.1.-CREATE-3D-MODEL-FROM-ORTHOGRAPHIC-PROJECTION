# EX. No.3.1. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:

## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
1.Create Sketch and select the XY Plane (Front Plane).

<img width="595" height="703" alt="Screenshot 2026-11-20 110926" src="https://github.com/user-attachments/assets/f6296597-821d-4278-843c-72a8a3104f51" />

2.Draw a 2-Point Rectangle starting from the origin with a width of 36 mm and a height of 32 mm.

<img width="571" height="733" alt="Screenshot 2026-11-20 105204" src="https://github.com/user-attachments/assets/71ef76cf-9789-46dd-a835-fba5c7192af7" />

3.Draw a Center Diameter Circle centered exactly on the midpoint of the left vertical edge of the rectangle with a diameter of 32 mm (this creates the R16 curve).

<img width="571" height="733" alt="Screenshot 2026-11-20 105204" src="https://github.com/user-attachments/assets/cc46e317-3a58-46a7-b896-1e27d7c0773f" />

4.Draw a concentric Center Diameter Circle at that same center point with a diameter of 16 mm (Ø16).

5.Use the Trim tool (T) to delete the vertical line segment separating the rectangle and the outer circle to combine them into one profile.

6.Click Finish Sketch in the top right.

<img width="303" height="252" alt="Screenshot 2026-11-20 105244" src="https://github.com/user-attachments/assets/c4bab906-04f8-4003-8748-d4b0a2a1accb" />

7.Select Extrude (E), click your combined profile, extrude it to a width of 40 mm, and set the operation to New Body.

<img width="505" height="605" alt="Screenshot 2026-11-20 101616" src="https://github.com/user-attachments/assets/65f1dff3-44d0-4805-9861-39d035b9320c" />

8.Select Create Sketch and click directly on the top flat surface of your new body.

<img width="595" height="703" alt="Screenshot 2026-11-20 110926" src="https://github.com/user-attachments/assets/a4b5ee9d-b6ca-4491-8efd-d8aa50903a6c" />

9.Draw a 2-Point Rectangle starting from the left rounded end and stretching toward the back face.

10.Use the Sketch Dimension tool (D) to set the distance from both side edges of the part to the rectangle lines to 11 mm (leaving a central slot width of 18 mm).

11.Dimension the back line of this rectangle so it is exactly 11 mm away from the back face of the block (making the total slot length 52 mm - 11 mm = 41 mm).

12.Click Finish Sketch.

<img width="303" height="252" alt="Screenshot 2026-11-20 105244" src="https://github.com/user-attachments/assets/0d99c0d1-ef19-48f2-bcc7-2e4dd950fc02" />

13.Select Extrude (E), click the slot profile you just drew, drag it all the way down through the part, set the operation to Cut, and click OK.

<img width="505" height="605" alt="Screenshot 2026-11-20 101616" src="https://github.com/user-attachments/assets/c1f9e34e-731f-4df9-8489-c02b876129ea" />

14.Select Create Sketch and click on the flat, solid back face of the block.

15.Draw a Center Diameter Circle with a diameter of 18 mm (Ø18).Center the circle on the back face by dimensioning it 20 mm from either side edge and 16 mm from the top edge.

16.Click Finish Sketch.

17.Select Extrude (E), click the circle profile, extrude it outwards by 32 mm, set the operation to Join, and click OK.

18.Finally, use Create Drawing to convert the completed 3D model into a 2D engineering drawing with the required front, top and isometric views.

<img width="335" height="552" alt="Screenshot 2026-11-20 105820" src="https://github.com/user-attachments/assets/63adfbcd-0ec4-40a6-9dc3-d5fd72970e89" />

<img width="476" height="545" alt="Screenshot 2026-11-20 105829" src="https://github.com/user-attachments/assets/f32e93a8-6354-43a1-bbee-f49cd90ba5ba" />

## INPUT:
<img width="956" height="650" alt="Screenshot 2026-11-22 180631" src="https://github.com/user-attachments/assets/ecf9aac2-42d8-4887-bd3b-7e06ea480a73" />

## OUTPUT:
<img width="792" height="390" alt="Screenshot 2026-11-22 181351" src="https://github.com/user-attachments/assets/b14aaa26-3737-4973-9ad2-22a420b3a323" />

## RESULT:
Thus, 3D model is created from orthographic projection.
