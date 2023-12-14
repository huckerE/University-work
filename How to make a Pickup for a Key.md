How to make a Pick Up for a Key 

  

First Create a cube or load in your model of a Key if you already have one and call it "Key" and then create a material and drag and drop it onto the key. 

  

Next Thing to do is to give the cube a mesh collider what you will need to do is to go down to "Add Component" and add a mesh Collider and then turn on convex 

  

once thats done do the same with a Box Collider but instead of convex turn on "Is Trigger" 

  

After that is done is go to add compont and then add a "RigidBody" 

 

Next create a Empty Object and name it ItemParent and then move the object to where you would like the item to be held. (Make sure this is infront of the camera where the player is looking) 

  

Create a new script and name it EquipItem and the copy the code below. 

  

 

  

 

Next of all We need to go to the key object and go to the layer drop down and select add layer and name it "Pickup" and then assign the key object so it now has the "Pickup" layer. 

  

  

Lastly get the EquipItem script and drag and drop it under the key object and then drag and drop to assign each of the variables to the correct places which will be: 

  

Key - Key Object 

Item Parent - ItemParent (Transform) 

Pickup Mask - Pickup 

Player Camera – Main Camera (Camera) 

Pickup Target - Key (Transform) 

Pickup Range - 5 

 

 
