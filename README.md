<img width="957" alt="Screenshot 2023-08-24 233811" src="https://github.com/VarshaAjith1110/Rotating-the-Gaming-Object/assets/94222288/2dde7f6d-417b-458c-9f47-dc1306a471ba"><img width="955" alt="Screenshot 2023-08-24 233727" src="https://github.com/VarshaAjith1110/Rotating-the-Gaming-Object/assets/94222288/b01a7231-84af-4a0f-8d07-a65eb8f240d9"># Rotating-the-Gaming-Object

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


```
## Output:
<img width="955" alt="Screenshot 2023-08-24 233727 - Copy" src="https://github.com/VarshaAjith1110/Rotating-the-Gaming-Object/assets/94222288/e99686d1-dbca-49e4-a9f2-1b02fd8964f0">
<img width="955" alt="Screenshot 2023-08-24 233727" src="https://github.com/VarshaAjith1110/Rotating-the-Gaming-Object/assets/94222288/e40ec02e-86df-47ae-a104-3154c941e550">


## Result:
Thus,the 3D application for rotating the gaming objects in unity is developed successfully
