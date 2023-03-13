# modern WP Toolbar - 4D WritePro Toolbar
 Modded 4D WP Toolbar with more features and colored icons
 
 

**See releases on the right side to download the specific version matching to** 

• 4D v18r3 = v19.x

• 4D v19r3

• 4D v19r5 = v20.x

• 4D v19r8 = v20.x


WP Toolbar as a timesaver, here is my modern interpretation of the 4D Write Pro Toolbar, based on the original source from 4D (https://github.com/4d/4D-WritePro-Interface)

v19r8+ = v20:
<img width="1030" alt="Toolbar v19r8 blue" src="https://user-images.githubusercontent.com/6436037/214587622-d376cc95-5657-49cd-af8a-da21eeae79c9.png">

<img width="1030" alt="Toolbar v19r8 green" src="https://user-images.githubusercontent.com/6436037/214587649-e15833a6-38cf-416f-a78b-f03672439127.png">

v19r5+:
<img width="1030" alt="Toolbar v19r5 green" src="https://user-images.githubusercontent.com/6436037/188864848-b28a4df5-8c9e-4fa6-ac45-ea076cf8fe5c.png">

v19r3+:
<img width="1030" alt="Toolbar v19r3 blue" src="https://user-images.githubusercontent.com/6436037/188858113-04efc91c-a95d-4947-b945-33cf14827506.png">

v18r3+ =v19.x:
<img width="1030" alt="Toolbar v18r3 red" src="https://user-images.githubusercontent.com/6436037/188858156-bf668a3b-14e1-4f95-91ff-ce4058a6aab2.png">

**Changes:**
 
    • arrangement of the icons according to my needs
    • remove the light blue toolbar style
    • font PopUp as hierarchic PopUp
    • font PopUp also shows the subfonts
    • font PopUp shows the last used fonts in the document
    • customize table and cell formats to selectively set frames on the left, top, right, bottom.
    • and a few more small adjustments

I have added some color sets with Photoshop. So everyone can choose a favorite color


![1](https://user-images.githubusercontent.com/6436037/188857277-8714225f-9cd1-49de-baed-6060dd6dff4a.png)

To replace the color, simple replace inside the component - resources - Images the folder Toolbar1 and/or Toolbar2 with the matching folder from the other color toolbars folder
Then you have to compile the source again and build as component

**To test my source, just run this sample form:**

<img width="550" alt="4D test form" src="https://user-images.githubusercontent.com/6436037/188857922-9e63a460-b2e5-4fcd-a472-03d7b43caa58.png">

**Screenshots:**

Extended table formatting commands:
<img width="744" alt="Bildschirmfoto 2023-01-25 um 15 34 16" src="https://user-images.githubusercontent.com/6436037/214591179-d15b919a-6b5f-4ada-87f4-9e4a29ce2b26.png">

Hierarchic font popup menu:

![4](https://user-images.githubusercontent.com/6436037/188858034-141812b8-da2d-48f3-b522-299257a835cb.png)

default 4D WP Toolbar:
![tbdef](https://user-images.githubusercontent.com/6436037/188858211-6522a2f9-bd55-463c-b15b-4c351619f8b9.png)

4D WritePro interface offers a set of palettes and a toolbar, which allow end users to easily customize a 4D Write Pro document.

A 4D developer can easily implement these palettes in his application. Thus the end user can handle all 4D Write Pro properties such as: fonts, text alignment, bookmarks, table layout, frames, ...

For more details, read the 4D WritePro Interface documentation (https://doc.4d.com/4Dv18/4D/18/Entry-areas.300-4575458.en.html#4607368) and the 4D Blog (https://blog.4d.com/?s=Write+Pro)

Documentation to compile a component for 4D: (https://developer.4d.com/docs/en/Desktop/building.html#build-component)


## How to use the new modern WP Toolbar in your 4D database or project


    Please note v19rXX versions do not match v19.XX 4D versions. If you are using v19.5, 
    then you need to download the latest v18rxx version from me.
    A Github account is not necessary.

1. Download from **Releases** my WP Toolbar Source for your matching 4D v19 version.
 
   • https://github.com/ArminDeeg/modern-WP-Toolbar---4D-WritePro-Interface/releases

2. Open the **modern 4DWritePro Toolbar.4DProject** project file 

3. Compile the source

<img width="224" alt="compiler" src="https://user-images.githubusercontent.com/6436037/222237569-f8a9c654-e9b8-4d5c-8f44-215d91422d88.png">


4. Create the component from the project source: open **Build Application**... command in the **Design** menu of 4D

<img width="295" alt="Build Application" src="https://user-images.githubusercontent.com/6436037/222238022-7ee9ed41-6cae-4d0b-9357-eb19b2e558f3.png">

   
   -a) Name the component as you like, for example like this
   
   -b) Create the component
   
   <img width="839" alt="create component" src="https://user-images.githubusercontent.com/6436037/222238778-58aa7417-8681-4022-8e4d-ee5234153dd6.png">

5. Copy the created component into your active “Components” folder
 <img width="816" alt="copy component" src="https://user-images.githubusercontent.com/6436037/222239975-6cec0b70-c287-4c05-886d-2efff5db1aeb.png">
 
 <img width="466" alt="Bildschirmfoto 2023-03-01 um 20 09 14" src="https://user-images.githubusercontent.com/6436037/222240210-edc9c145-6228-4333-b79a-9cada67309ba.png">

 
6. Open your 4D project or binary database in source mode

7. Open the desired form where the WParea widget with the WP Toolbar is located.
(You can create preconfigured 4D Write Pro areas using the 4D Write Pro objects found in the Object library)

<img width="515" alt="WPwidget" src="https://user-images.githubusercontent.com/6436037/224719440-c01f8690-b1a8-4d8d-bf12-c995ae8297a7.png">

8. Select the 4D Write Pro Toolbar widget and assign the **WPmodern_Toolbar** (modern WritePro Toolbar) as input form

<img width="956" alt="WPtoolbarform" src="https://user-images.githubusercontent.com/6436037/224718949-a05e6408-cac4-427f-b189-13c86f4e61a0.png">

9. Change the **WP UpdateWidget** method to  **WPmodern UpdateWidget** 

<img width="438" alt="WPareamethod" src="https://user-images.githubusercontent.com/6436037/224719343-79b4a7c0-fca2-4440-97d2-bf5b77025d6d.png">


Thats it
