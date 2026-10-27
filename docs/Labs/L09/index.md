# L9 – Laser Cut 

## Design - 

The first thing my partner and I did was decided the variables that we would need for our own parts namely the thickness and kerf measurements, as shown below. 

__Thickness__  
When beginning this part my partner and I began by measuring the wood that we were given from three different points. When measuring 
we got values of 0.10,0.12, 0.10, we got an average value of 0.1117 inches for our piece of wood, as shown below by the pictures of 
the measuring values. The value of 0.117 would now end up being our material thickness variable in the cad parameters. 

__Kerf measurement__   

When putting in a 12 by 12 mm square into the laser cutter, we got a final kerf measurement of 0.009 in, as this was the difference 
in size from the part in our cad and the part when cut with the laser. 

First we added the 12 by 12 square to solid works.  
<figure>
  <img src = "kerf_test1.jpg" width = "500" height = "500">
  <figcaption> Showing the first kerf test</figcaption>
</figure>    

Next we would put this into a pdf to be laser cut, as shown below. 

<figure>
  <img src = "kerf_test2.jpg" width = "500" height = "500">
  <figcaption> Showing the second kerf test file</figcaption>
</figure>    

Last we would cut out this square and test how far off it is. Below is a video of the kerf being laser cut out 

 <figure>
  <video controls width="500" height="500">
    <source src="Kerf_cutting.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</figure>  

After we cut it we just had to measure it as shown below this is our kerf value of 0.004. 

  <img src = "IMG_9797.jpeg" width = "500" height = "500">
  <figcaption> Showing the offset of the wood to the first measurement</figcaption>
</figure>    


After this we could finally being to create our gear ratio. 

First we added the parameters in cad to begin the parametric modeling as shown below. 
<figure>
  <img src = "Screenshot_1.jpg" width = "500" height = "500">
  <figcaption> Showing the first parametric decisions</figcaption>
</figure>    

Next we would begin by creating the size of the base of our part which would be 4 by 3 inches as shown below,

<figure>
  <img src = "Screenshot_2.jpg" width = "500" height = "500">
  <figcaption> Showing the bases width and length</figcaption>
</figure>  

After this we would extrude this base to the desired height already chosen by the thickness of wood in our parametric equation, 

<figure>
  <img src = "Screenshot_3.jpg" width = "500" height = "500">
  <figcaption> Showing the extrude</figcaption>
</figure>  

Because we decided to do a gear ratio in our parts the first thing we would do is to create two different holes with same diameters, the
distance from the center was chosen by the parametric modeling. 

<figure>
  <img src = "Screenshot_4.jpg" width = "500" height = "500">
  <figcaption> Showing the differeing holes</figcaption>
</figure>  

Next we would start on the two differing gears, first we would create a gear smaller gear with a diameter of .88, to do this we would 
with a small circle, inside that circle we would design the fit for the shafts to sit in so the gears can turn. This is shown below.

<figure>
  <img src = "Screenshot_5.jpg" width = "500" height = "500">
  <figcaption> Showing the small gears creation in 2d</figcaption>
</figure>  

As we can't design anything in 2d we would need to extrude this part which will be shown below. 

<figure>
  <img src = "Screenshot_6.jpg" width = "500" height = "500">
  <figcaption> Showing the small gears extrusion</figcaption>
</figure>  

Using solid works we're able to create a pattern on the edge of the same circle that can be later cut to be a complete gear, this can be
seen in the image below. 

<figure>
  <img src = "Screenshot_7.jpg" width = "500" height = "500">
  <figcaption> Showing the small gears pattern</figcaption>
</figure> 

The complete smaller gear. 

<figure>
  <img src = "Screenshot_8.jpg" width = "500" height = "500">
  <figcaption> Showing the small gear</figcaption>
</figure> 

From the smaller gear we can create the larger gear in the same way, we can create a copy of this part and then edit the dimensions so 
no need to completely recreate the part. Below you can see the changing of the diameter from 0.88 to almost double at 1.63 as well as 
a change of the shaft fit diameter to fit the bigger size.

<figure>
  <img src = "Screenshot_9.jpg" width = "500" height = "500">
  <figcaption> Showing changing to a larger gear</figcaption>
</figure> 

Next, we would have to change the pattern as again we'd have to size them up to fit inside the larger gear, as shown below the pattern is 
changed. 

<figure>
  <img src = "Screenshot_10.jpg" width = "500" height = "500">
  <figcaption> Showing changing to a larger gear pattern</figcaption>
</figure> 

As the thickness is also parametrically designed we don't need to change anything there and the final larger gear can be shown below. 

<figure>
  <img src = "Screenshot_11.jpg" width = "500" height = "500">
  <figcaption> Showing finshed larger gear</figcaption>
</figure> 

Next we would have to begin the designing of the shafts for the two separate gears. The values for the the shafts are chosen by the inner
shafts by the two gears we previously created as shown below. 
<figure>
  <img src = "Screenshot_12.jpg" width = "500" height = "500">
  <figcaption> Showing the start of the  shaft</figcaption>
</figure> 

Next, we would extrude this part as shown below. 

<figure>
  <img src = "Screenshot_13.jpg" width = "500" height = "500">
  <figcaption> Showing the shaft extrusion</figcaption>
</figure> 

The next things we're doing is creating holes that fit the original cut outs on the plate so we could slot those in for our shafts to 
flow without creating friction. We would create a hole with the dimeter we had in the original two holes on the sitting plate, then add
the values for the shaft in the middle similar to the gear as shown below. 

<figure>
  <img src = "Screenshot_14.jpg" width = "500" height = "500">
  <figcaption> Showing the first slotting hole</figcaption>
</figure> 

Next we would use the parametric thickness to extrude this part, as shown below. 

<figure>
  <img src = "Screenshot_15.jpg" width = "500" height = "500">
  <figcaption> Showing the first slotting hole extrude</figcaption>
</figure> 

Afterwards we would being to assemble the parts together to get a feel of how they should fit in the final design, starting with the 
shafts and constraining it. 

<figure>
  <img src = "Screenshot_16.jpg" width = "500" height = "500">
  <figcaption> Showing the shafts fitting together pt1</figcaption>
</figure> 

<figure>
  <img src = "Screenshot_17.jpg" width = "500" height = "500">
  <figcaption> Showing the shafts fitting together pt2</figcaption>
</figure> 

<figure>
  <img src = "Screenshot_18.jpg" width = "500" height = "500">
  <figcaption> Showing the shafts fitting together pt3</figcaption>
</figure> 

<figure>
  <img src = "Screenshot_19.jpg" width = "500" height = "500">
  <figcaption> Showing the shafts fitting together pt4</figcaption>
</figure> 

<figure>
  <img src = "Screenshot_20.jpg" width = "500" height = "500">
  <figcaption> Showing the shafts fitting together pt5</figcaption>
</figure> 



Next, we would put these on the plate and check how it fits together first we have to add these parts, starting with our plate, 
and creating a new assembly.

<figure>
  <img src = "Screenshot_21.jpg" width = "500" height = "500">
  <figcaption> Showing the start of the final assembly </figcaption>
</figure> 

Next we would have to slot in the holes that translate the rotation from the shafts to the gears. 

<figure>
  <img src = "Screenshot_22.jpg" width = "500" height = "500">
  <figcaption> Showing the holes being slotted in </figcaption>
</figure> 

Afterwards we add our actual shafts, 

<figure>
  <img src = "Screenshot_23.jpg" width = "500" height = "500">
  <figcaption> Showing the shafts being added</figcaption>
</figure> 

Then the driver gear, 

<figure>
  <img src = "Screenshot_24.jpg" width = "500" height = "500">
  <figcaption> Showing the driver being added</figcaption>
</figure> 

Lastly the secondary gear, 
<figure>
  <img src = "Screenshot_25.jpg" width = "500" height = "500">
  <figcaption> Showing the last gear being added and finishing the assembly</figcaption>
</figure> 


__Parameter Data__ 

<table>
<tr>
  <th> 
    Variable Name
  </th>
  <th>
    Value (in)
  </th>
  <th>
    Unit Source (measured or chosen) 
  </th>
  <th>
    What it controls  
  </th>
</tr>

<tr>
  <td>Thickness</td>
  <td>0.1117</td>
  <td>Measured (Step 1)</td>
  <td>The thickness of the material </td>
</tr>

<tr>
  <td>Kerf</td>
  <td>0.009</td>
  <td>Measured (Step 2)</td>
  <td>The amount of material blown away by the laser</td>
</tr>

<tr>
  <td>Clearance</td>
  <td>0.002</td>
  <td>Chosen (Step 4)</td>
  <td>This controls how tight the parts will be too each other</td>
</tr>

<tr>
  <td>Slot width</td> 
  <td>0.5 radius</td>
  <td>Chosen</td>
  <td>This controls how large the holes created to slot in the plates are</td>
</tr>

<tr>
  <td>Hole's Distance</td>
  <td>1.125</td>
  <td>Chosen</td>
  <td>This controls the distance of holes for the base plate</td>
  
</tr>

</table>

## Manufacturing/Process Research

__Paragraphs__ 

Laser cutting works by using a high powered computer controlled laser beam through optics to melt and burn away at a chosen material, 
while an auxiliary gas blows away at any debris left. This is a viable manufacturing process because it is extremely accurate, rapid 
production cycles and very smooth finishes without need for another tool. 

We can compare laser cutting to 3d printing in a sense, laser cutting unlike the additive manufacturing of 3d printing is very quick 
which is perfect for mass production. Another benefit of laser cutting is it is more versatile, as most materials can be cut out through
laser cutting unlike 3d printings filaments. When a company may need materials with differing structural materials laser cutting is the 
best option. Lastly the control laser cutting gives you is also better than the typical Fdm printing we've been using as we can create 
more variables for a more custom fitting part. 

__Photos__

After designing the parts in solid works we created a drawing and then uplodaded that drawing as a pdf to be used to upload to the laser
cutter as shown below. 

<figure>
  <img src = "Screenshot_26.jpg" width = "500" height = "500">
  <figcaption> Showing the parts in solidwords drawing</figcaption>
</figure> 

<figure>
  <img src = "Screenshot_27.jpg" width = "500" height = "500">
  <figcaption> Showing the parts in pdf file uploaded to laser printing software</figcaption>
</figure> 

__Videos__
The videos of the parts being laser cut had to be cut down in order to fit with the 25 mbs or less requirement in github. As the audio 
was already scrubbed this was the only option my partner and I saw. 

 <figure>
  <video controls width="500" height="500">
    <source src="Kit_cutting.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</figure>  

 <figure>
  <video controls width="500" height="500">
    <source src="Kit_cutting2.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</figure>  

 <figure>
  <video controls width="500" height="500">
    <source src="Kit_cutting3.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</figure>  

__Other Questions__ 

As you can see our parts were arranged that way in order to save the most amount of wood as possible, we didn't feel a need to cut out
or waste wood by putting in in the middle and arranging the pieces anywhere on the wood so it was chosen to have the pieces in the top 
left corner. 

The air quality and ventilation from the printing was great as can be shown in the video. Whenever we printed out a part you could see 
a fire be pit down before it could even start. As well as the smoke would be sucked through the vents before it began to cloud the laser 
cutter too much we would say both the air quality and ventilation were great. Though the edge was a bit burned I think it comes from the
fact it was a laser printed part. 



__Laser Process Record__
<table> 
  <th>Setting</th>
  <th>Kerf Coupon</th>
  <th>Cut</th>

<tr>
  <td>Laser Cutter Number</td>
  <td>1</td>
  <td>1</td>
</tr>

<tr>
  <td>Material type</td>
  <td>Wood</td>
  <td>Wood</td>
</tr>

<tr>
  <td>Nominal thickness</td>
  <td>1/8 in</td>
  <td>1/8 in</td>
</tr>

<tr>
  <td>Measured thickness (mean, in)</td>
  <td>1.117</td>
  <td>1.117</td>
</tr>

<tr>
  <td>Speed</td>
  <td>20%</td>
  <td>20%</td>
</tr>

<tr>
  <td>Power</td>
  <td>100%</td>
  <td>100%</td>
</tr>

<tr>
  <td>Frequency</td>
  <td>20%</td>
  <td>20%</td>
</tr>

<tr>
  <td>Number of passes</td>
  <td>4</td>
  <td>1</td>
</tr>

<tr>
  <td>Focus method and how confirmed it	</td>
  <td>Auto focus | confirmed by Lowered the laser head until the spacer block slid snugly between the nozzle tip and the top surface of the measured material sheet without pinching </td>
  <td>Auto focus | confirmed by Lowered the laser head until the spacer block slid snugly between the nozzle tip and the top surface of the measured material sheet without pinching </td>
</tr>

<tr>
  <td>Air assist on? Exhaust on?</td>
  <td>Yes | Yes </td>
  <td>Yes | Yes </td>
</tr>

<tr>
  <td>How you set origin and alignment</td>
  <td>Top-left corner of sheet using laser pointer jog</td>
  <td>Top-left corner of sheet using laser pointer jog</td>
</tr>

</table>

## Lessons Learned 


__Process Log__ 

<table>
  <th> Date and Time</th>
  <th> Time spent</th>
  <th> What changed</th>

  <tr>
    <td>10/24/26</td>
    <td>6 hours</td>
    <td>Cad drawings began and completed, creation of the gears and shafts and uploading them as a pdf file into the laser printing software and documentation began </td>
  </tr>

  <tr>
    <td>10/25/26</td>
    <td>4 hours</td>
    <td> Talks about how we want to do the documention moving forward and how we can test on the upcoming monday</td>
  </tr>

  <tr>
    <td>10/26/26</td>
    <td>5 hours</td>
    <td>The kerf values being fully tested, as well as the values for the wood actually being fact checked. The final kit was also fully printed out here. Documentation was being completed </td>
  </tr>
</table>

__mistakes__ 

One mistake we made was having to press one of the pieces of our print out, we assume this is because of a value of the vector of the 
laser but it didn't go fully through down to the bottom. Another mistake was a bad connection on the kerf connection to our plate as we had to glue it to make sure it didn't fall. As this was our final print we didn't get the chance to really change anything since the part
still worked once it was out.

__List of resources used__ 

<ol>
  <li>Wood</li>
  <li>Laser Printer</li>
  <li>Glue stick</li>
  <li>Calipers</li>
  <li>Ruler</li>
</ol>

__4 Questions to answer__ 
<ol>
  <li>The measured values different from the nominal values of wood at our thickness. If we had just assumed these values we could've damaged
the machine by making the laser go down more than it may need to or the cut could've been off. If we assumed the kerf value our pieces 
wouldn't have moved at all since it was important to know how much material could be blasted away in the process of lasering.</li> 
  <li>Taguchi’s quality loss function states that quality is not a simple any deviation from the target value incurs a cost with loss growing
    deviation increases if we were to use our gears as an example if we were to be off the tolerance the part could wobble and not sit tight. If we were
    to mass produce this it could break warrenty and create safety concerns or even damage the brand of who ever produced it</li>
  <li>A shelf I once had was laser cut from a piece of ply wood, if the kerf was messed up it would mean that nothing in the product could work the fits 
  would either be too small or too large if the kerf isn't accounted for.</li>
  <li>If given one more cut I would probably change the clearance on the gears themselves. The reason I would change this is because I think it would be 
  interesting to find the maximum clearance that the gears would allow for. We used a safe comfortable medium in our design and I think exploring would 
  be interesting.</li>
</ol>
