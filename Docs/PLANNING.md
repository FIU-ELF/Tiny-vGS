# Planning

The first part of creating a tiny ground station is figuring out if you have clear line of sight to the satellite. Pick a few locations to place a tripod ([Hardware BOM](/Docs/SAT_HARDWARE_BOM.md)) and get a rough order of magnitude for whether you can run power to the location and point to the satellite. For the GOES weather satellite, this means the satellite is to the south (if you live in the northern hemisphere) and to the north (if you live in the southern hemisphere). 

Criteria for site location:

1. Clear line of sight to the satellite.
2. Ability to run power (extension cord can reach).
3. Safety first (no one will trip or get hit by the small dish).

Tools to figure out where you need point, use the following tools:

1. Dishpointer
2. Pointing app like look4sat

# Dishpointer

The dishpointer app (<https://www.dishpointer.com>) has long been used by satellite planners to understand where to point an asset. In this case, using Florida International University, we can see that the satellite GOES-16 has to be pointed at an elevation of 59.3 and an azimuth of 168.2

<p align="middle">
    <img src="/Docs/Images/Plan/FIU.PNG" alt="Dishpointer" width="60%" height="60%">
</p>
<p align="middle">
      <img src="/Docs/Images/Plan/Pointing.PNG" alt="Dishpointer" width="60%" height="60%">
</p>

Dishpoint also has the ability to download your pointing parameters as a Google XML file to visualize in Google Earth. Sometimes, the azimuth or elevation may surprise you when implementing the solution. 59.3 degrees doesn't seem like a lot, but it is up there in the sky! This will vary for your location.

<p align="middle">
    <img src="/Docs/Images/Plan/GOES_ge.PNG"  width="50%" height="50%">
    <img src="/Docs/Images/Plan/GOES_ge2.PNG"  width="50%" height="50%">
</p>

# Look4Sat

Depending on your location, the view to the satellite can be obstructed by natural or man-made objects. If so, you may have to adjust your location accordingly. In the real world, such "site surveys" happen all the time. There are various tools available to help determine if blockage is a concern.
<p align="middle">
      <img src="/Docs/Images/Plan/Viewtogoes.jpg"
         width="60%" height="60%">
</p>

Applications for the phone, like "Look4sat," allow the user to use their phone to point in the real world and understand line of sight obstructions. In the above tree line case, it may mean the difference between receiving a signal or not. The application has some limitations, for example, GOES-16 frequencies aren't listed. For pointing, however, the application works great!

<p align="Center">
    <img src="/Docs/Images/Plan/Look4sat.jpg" width="20%" height="20%">
</p>
  




