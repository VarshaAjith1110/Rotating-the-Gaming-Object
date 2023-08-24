# Rotating-the-Gaming-Object

## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:
### Step1:
Start
### Start2:
Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Expno1)
### Start3:
Click Hierarchy -> 3DObject -> Cylinder
Hierarchy -> 3DObject -> Capsule
Hierarchy -> 3DObject -> Text
Hierarchy -> Effects -> Particle system
### Start4:
Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Cylinder)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Cylinder to the plane and release the mouse

Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Capsule)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Capsule to the plane and release the mouse

### Start5:
Click Hierarchy -> DirectionalLight
Inspector -> Change the color to white (255,255,255)

### Start6:
Create a folder name Coding and create a C# file to add the coding in it.

### Start7:
To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Start8:
Stop

## Program:
```
Name: Varsha Ajith
Reg no: 212221230118
```
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class SCRIPT1 : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
       transform.RotateAround(Vector3.right,Vector3.up,60*Time.deltaTime); 
    }
}
```
## Output:
<img width="177" alt="Screenshot 2023-08-24 233106" src="https://github.com/VarshaAjith1110/Rotating-the-Gaming-Object/assets/94222288/4d889ca0-3bae-411d-acdf-eaf6218125c5">
<img width="173" alt="Screenshot 2023-08-24 233154" src="https://github.com/VarshaAjith1110/Rotating-the-Gaming-Object/assets/94222288/e08fa5ba-bdc3-4864-a9f2-c19a26a1f7ab">

## Result:
Thus,the 3D application for rotating the gaming objects in unity is developed successfully
