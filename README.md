# U7-SVG-Star-Animation
 
So in my style sheet, I created three key frame rules and named the animation slide, grow and off set. So the slide animation uses three key frames to create that slide up motion of the stars. Instead of creating the slide movement by animating the star's position, margin, or padding. I used a transform with the translate 3D function in each key frame. The second value in the translate3d function is what translates or moves the element on the y axis. Now translate 3d is a hardware-accelerated function. This makes the animation play a whole lot smoother in the browser. I'm using the rotate and scale transform functions.
To create that pulsing effect in the stars.
I'm also animating the elements opacity to one and fill color to yellow here at 50%.
Right below this rule, the offset animation
animates the circle element's stroke-offset property to zero.
It also animates the stroke opacity to one in the 60% key frame.
So I didn't need to create seven different keyframe rules
to make this animation work.
Like we did earlier,
I'd used animation delay values to create the different animation start times.
So in my SVG styles, I'm setting transform-origin to center,
because all my transforms need to scale and rotate from their center.
And I figured out that the total length of this circle shape is 815 pixels.
So, to create the final line animation.
I set stroke-array and stroke-offset to 815.
Then called that offset key frame animation here in the animation property.
So right below in the star rule.
I gave the star elements a translate 3D of 180 pixels on the y axis.
This is how they're able to slide up from the bottom of the circle.
And then I call the slide and grow animations with the animation property.
I staggered the star animations by giving each element an animation delay,
using an nth-of-type selector.
