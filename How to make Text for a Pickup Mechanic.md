How to make UI Text for a Pickup mechanic in Unity 3D 

  

Firstly get the object that you have for the pickup mechanism, and then create a cube on top of the object so that they are overlapping. 

  

Next on the cube that has just been created name it "Press E to Pickup" and then uncheck "Mesh Renderer" and then also check "Is Trigger" within the box collider. 

  

After that create a C# and then name it "ShowUI" and then copy the code below: 

  

Once that has been done, drag and drop the "ShowUi" code into the "Press E to Pickup" that should now show the script within the object 

  

Next Create some text (Create - Legacy - Text) and name it whatever you want 

  

After that, type in the chosen code you would like to appear when wlaking up to the cube and then once done change the "horizontal" and "vertical" overflow to "Overflow!" 

  

finally drag the text into the "UI Object" inside the "ShowUi" script.
