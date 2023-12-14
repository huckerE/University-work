How to make a chest Opening mechanic 

  

  

The tutorial shown will show you how to create a chest that you can open by pressing a key 

  

(highly recommended that you import or create the model form a 3D modelling software such as Blender or Maya before you start this and make sure the Top and the Bottom are both separate) 

  

Firstly, import your chest model into the scene and make sure they have both parts under a Parent object 

  

Next create some materials to give them colour and then drag and drop them in to the places you want them to go 

  

Next give the Top and Bottom pieces of the chest a Mesh collider and give them both convex's and make them provide contacts. 

  

After that, given the parent object a box collider and set that as "is Trigger" and then edit the collider so that it is covering the whole of the chest and a bit extra in front of the chest. 

  

Time to animate go ahead and start to animate the chest lid opening (make sure the animation is created from the parent object) and make sure that after you create it you turn off "Loop Time". 

  

Next, go into the animator, right click, hover over "Create State", then click "Empty" and name that "Idle". 

  

Once that has done right click the idle panel and click "Set as Layer Default State" and then make a transition from idle to Chest Open 

  

  

After that you go to the parameters tab and then click the plus, select "Trigger", and call it ChestOpen and then go into the transition connecting the idle and Chest Open together and add a new condition by pressing the plus (this should come up saying ChestOpen as the condition). 

  

Next create a new script and call it ChestOpen and copy the code below 

  

  

Lastly drag and drop the script ChestOpen into the parent Object and the drag and drop the parent Object under Animator inside the ChestOpen script. Finally drag and drop the script ChestOpen into the parent Object and the drag and drop the parent Object under Animator inside the ChestOpen script. 

 

 
