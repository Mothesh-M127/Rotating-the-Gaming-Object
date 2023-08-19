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
Name : Vidya Neela M
Reg no : 212221230120
```
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Rotate : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.up, Vector3.up, 90 * Time.deltaTime);
        gameObject.transform.RotateAround(gameObject.transform.position, transform.right, 40*Time.deltaTime);
    }
}
```

## Output:
![image](https://github.com/Mothesh-M127/Rotating-the-Gaming-Object/assets/94170892/eef72d0e-e5e2-42d5-a64e-79b695492a06)

![image](https://github.com/Mothesh-M127/Rotating-the-Gaming-Object/assets/94170892/1f1c1918-0f14-4fb9-b1bc-16b1244def80)

## Result:
Thus, a 3D application for rotating the gaming objects in unity was executed successfully
