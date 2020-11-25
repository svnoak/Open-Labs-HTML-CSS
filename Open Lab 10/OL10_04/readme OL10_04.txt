
Check the video and make a webpage that looks like and works as the one there.

Make sure to center everything in the viewer.

You can make elements rotate with the transform-property.
https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotate

It�s fairly simple to use:
#rotator {
  transform: rotate(45deg);
}

You need to set a transition for that property to get the nice rotating effect. Remember that the property that needs to be �transitioned� is transform, not rotate(). 
(rotate() is actually not a property but a function, like calc())


Note
�deg� is the unit of angles: degrees. In Swedish: grader.
Reminder: 360 degrees makes one whole turn.