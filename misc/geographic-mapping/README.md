# geographic-mapping (164 solves, 429 points)

## Description
Find the coordinates of each location!

Flag format: flag{picture1 latitude,picture1 longitude,picture2 latitude,picture2 longitude}, all latitudes and longitudes to the nearest THREE decimal digits after the period. No spaces in the flag.

Example format: flag{12.862,48.066,-13.477,-48.376} The challenge author will not confirm individual locations, nor check your decimal digits. Three decimal digits gives a range of ~111 meters.

![picture1.png](picture1.png) ![picture2.png](picture2.png)

## Solution
Disclosure: I play Geoguessr (google if you've never heard it), so I did have a slight advantage, but these are definitely doable regardless. We can see in both that they have flags, so we can narrow the country down. 

### Picture 1
With a bit of google, we can confirm that the flag is of `Malta` (just reversed left to right). We are also given a compass in the bottom left as the picture is pulled from Geoguessr, which shows that we are looking directly North, with the water out to the East. Thus, we can narrow our search down significantly to the area below. 

![](coast.jpg)

Now, we just have to search using the satellite option on Google Maps; we can tell that the southern part is too empty and dry, and we also know there is a significant amount of beach next to the road, so it cannot be directly on the water. Eventually, we find the location in Quarry's Wharf, with the coordinates (


