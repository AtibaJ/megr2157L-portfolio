# A5 – [Design a Snap Fit]

## Modeling

When initially deciding to create a snap fit design I thought I would create a beam design after finding the common Youngs modulus of pla to be 2.4 GPA and a common yield strength of 8,500 psi. I calculated the max allowed strength to be around 2,430 psi. 
After finding this I began to work on my first design the cantilever beam. To find the length of this beam I used the equation L = sqrt(3*y*t/2*e) or the straight beam calculation.  

<figure>
  <img src="IMG_7476.jpeg" alt="image of the cantilever beam" width ="500" height ="500">
  <figcaption><i> Figure 1: This is the first freebody diagram.</i></figcaption>
</figure>  

After designing this though I decided that I didn't like that I decided to create an annular snap fit design. The FBD for both parts 
can be found below.  

<figure>
  <img src="IMG_7477.jpeg" alt="image of the annular fbd parts." width="500" height ="500">
  <figcaption><i> Figure 2: This is my second freebody diagram.  </i></figcaption>
</figure>    

When I was creating this I researched that because of the stiffness of pla it would require a massive force to expand that annular male piece of the part. 
The chosen transverse load was the max of five pounds the max allowed and the coefficient of friction was point zero three (the standard for pla on pla as I researched) and the chosen lead angle for my calculations for my design. 
The axial force I calculated using the transverse expansion mating force being w(cof + tan angle/1-(cof tan angle)) when doing that I got a force of 9.28 lbf which fit the axial load of 5-10 pounds. 
When calculating the length of this I had to consider the hoop's strain I was able to calculate it to be around 0.5 inches but scaled it 
to an inch on both the male part and the female coupling. 

## Stress equations  

When calculating if the stress of this object could fit into the equations there were a lot of considerations to be made. Specifically 
when conserving the undercut which is the piece that connects the male and female parts together. I think this part made it more
difficult than need be but I was able to calculate that strain is equal to 2y/Dh and using this I was able to find the length of 0.5 
to fit the design parameters needed and an inch to scale to fit the 3.5 safety factor. 


## Cad Creations 

The first thing I did in cad was to input my parametric equations to create the part, as shown below  
<figure>
  <img src= "L5_ParaDesign2.png" width = "500" height = "500">
  <figcaption><i>Figure 3: This shows the equations mentioned above and how they helped aid in the creo design.</i></figcaption>
</figure>  

Next I was tasked with creating the right fixtures for the parametric equations to work to begin I created a circle. 
<figure>
  <img src= "L5NewDesign2.png" width = "500" height = "500"> 
  <figcaption><i> Figure 4: This shows off the annular design creation using parametric equations.</i></figcaption>
</figure>  

Then, after checking the parametric equations were correct I had to check the radii of the male part just to be sure.  
<figure>
  <img src="L5Radius.png" width = "500" height = "500"> 
  <figcaption><i> Figure 5: This shows off the radius checking of the male part.</i></figcaption>
</figure>

With both the raidus and the height looking correct I then decided to create a revolve to create a circular shape. 
<figure>
  <img src="L5Revove.png" width = "500" height = "500"> 
  <figcaption><i> Figure 6: This shows the revolve of the male part that will fit inside the coupling</i></figcaption>
</figure>

On the top of that revolve I would extrude as shown by the 19 value and create a lip that would become the coupling part. 
Below the design measurements of the snap fit and the final revolve can be shown below  

## Revolving  

<figure>
  <img src = "revolve piece.png" width = "500" height = "500"> 
  <figcaption><i>Figure 7: This shows the revolve dimension of the part. </i></figcaption>
</figure>  
<figure>
  <img src="L5AnnularSnap .png" width = "500" height = "500"> 
  <figcaption><i> Figure 8: This shows the lip of the annular design.</i></figcaption>
</figure>

To create the female coupling it's a little easier I created a body that had the annual male part as a base and cut it into two pieces 
as shown below.  
<figure> 
  <img src = "L5AnnularSplit.png" width = "500" height = "500"> 
  <figcaption><i> Figure 9: This shows off the cut female part of based on the body of design one</i></figcaption>
</figure>   

<figure> 
  <img src = "L5ExtrudePart1.png" width = "500" height = "500"> 
  <figcaption><i> Figure 10: This shows off the finished cut</i></figcaption>
</figure>

After doing this I was able to create a merging of the two different bodies to create the female cut without having to do 
anything extra. 

<figure>
  <img src = "L5_Assylb.png" width = "500" height = "500"> 
  <figcaption><i> Figure 11: This shows off the assembly of the part using merge tool. </i></figcaption>
</figure>

Before constraining I just wanted to make sure my parametric equations were correct otherwise it would print incorrectly. 

<figure>
  <img src = "L5_ParaDesign2.png" width = "500" height = "500"> 
  <figcaption><i> Figure 12: This shows off the parametric equations 
<figure> 
  
Then I fully constrained the pieces together 

  <img src = "constrainingpiecesL5.png" width = "500" height = "500"> 
  <figcaption><i> Figure 13: This shows off constraint of pieces. </i></figcaption>
</figure>

Finally I imported the files as stl files and put them into prusa slicer 3d. 
<img src = "L5Prusa.png" width = "500" height = "500"> 
  <figcaption><i> Figure 14: This shows off the two pieces in prusa. </i></figcaption>
</figure>

## What went wrong 

Here are some of the answers I had to the questions that pertained to me
<ul>
  <li>The Annular Part wouldn't stay connected, when I connected it it kept trying to tear off and my first print is my only good one</li>
  <li>The Piece wouldn't require supports, when I tried to support the annular part it just woulnd't stay and it wouldn't work for me</li>
  <li>The build orientation was chosen so it would lay as flat as possible on the bed.</li>
</ul>  

## Video of Printing  
This video below shows the printing in the 3d printing. 
<figure>
  <video controls width="500" height="500">
    <source src="L5Video.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <figcaption><i> Figure 15: 3d Print coming alive </i></figcaption>
</figure>  

## What helped create this 
Heres a list of websites that helped: 

<ul>
  <li><a href="https://www.youtube.com/watch?v=QS4LHS7S8o4&t=1s">How to edit bodies in creo</a></li>
  <li><a href="https://community.ptc.com/3d-part-assembly-design-327/subtracting-one-body-part-from-another-body-part-88487">How to remove bodies in creo</a></li>  
  <li><a href="https://community.ptc.com/creo-parametric-tips-390/multibody-how-do-i-position-bodies-131921">Positioning bodies in creo</a></li>  
  <li><a href="https://support.ptc.com/help/creo/creo_pma/r12/usascii/index.html#page/part_modeling/part_modeling/To_Copy_Move_Mirror_or_Pattern_Bodies.html#">How to copy bodies in creo</a></li>
  <li><a href="https://support.ptc.com/help/creo/creo_pma/r12/usascii/index.html#page/part_modeling/part_modeling/to_split_bodies.html">How to spilt bodies in creo</a></li>
  <li><a href="https://www.youtube.com/watch?v=SvI8qrdAr1w">Creating annular snapfits in fusion360</a></li>
</ul>
