List of TO-DOs
---
1. Mapping the touching events into the models, limit it from the pixel coordinates into the surface coordinators
2. Set the left edge of mobile phone
3. LeapMotion/Right Controller/Remote events --> Events modifications in the other project
4. Experiments design, or random buttons in random area.
---

July 8th
---
## What happened yesterday?

A: Bounds issue with coordinator case

What's your strategy?

A: Ignore this issue first, adding another layer about the coding frameworks outside

## Afternoon Plans:

1. BoundingBox Layer and alignment
2. Touching Visualizations on the virtual screen --> Radius of the finger
3. Tween layeralk;

## Lesson learned
1. The `Renderer.bounds` is already in world space, no need to further transfer it from local to world, but need to make it world to local if needed
2. If we add all the Bounds directly to local frame first, the calculation won't map the model itself but possibly add the frame in the local-frames, thus 45/45 logics may not work as we found
3. So the making sense logic is : a. growing bounds in world space together; b. apply the global results into the local coordinator later

July 7th
---
Tonights:
Try to make the 3's math as in home, no device available
--> Issue: Bounding Box definations, so here we make the local working, and applying the outside holder with a script

Make the event system done
---
So from today I'll start writing the documentations for my SIGCHI process, in a daily process

For now, Let's make a summarize about what I did in last week:

1. Bounding Box based on rendering models
2. Alighment Algrithm to mapping the mobile device into the controller
3. UDP Client to pass the touching events

---

