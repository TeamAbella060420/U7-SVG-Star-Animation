# U7-SVG-Star-Animation
 
So in my style sheet, I created three key frame rules and named the animation slide, grow and off set. So the slide animation uses three key frames to create that slide up motion of the stars. Instead of creating the slide movement by animating the star's position, margin, or padding. I used a transform with the translate 3D function in each key frame. The second value in the translate3d function is what translates or moves the element on the y axis. Now translate 3d is a hardware-accelerated function. This makes the animation play a whole lot smoother in the browser. So next, the grow animation is very similar to the one I created for the badge animation. I'm using the rotate and scale transform functions.
To create that pulsing effect in the stars.
I'm also animating the elements opacity to one and fill color to yellow here at 50%.
Right below this rule, the offset animation
animates the circle element's stroke-offset property to zero.
Just like we did earlier with the Treehouse logo.
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
So like we did earlier in the badge animation.
I staggered the star animations by giving each element an animation delay,
using an nth-of-type selector.
And that's pretty much it.
Now you probably did things a little bit differently, and
that's okay since there's no 100% right way of doing this.
It's just the method I used.
So keep up the good work.
And if you want,
you can share your new animation sequence with other students on our forum.
As you learned throughout this course, SVG animations are fun and interesting.
As web designers, we should be excited about the current state and3:19
future of SVG Animation, because it's an increasingly important part of web design.
The methods I covered should give you lots of new ideas for
using SVG animations in your project.
So to practice what you've learned in this course.
You can replace some of the graphics on your website with SVG,
then add simple animations.
Or try adding other transform functions like translate, and
skew to the animation sequence you created earlier.