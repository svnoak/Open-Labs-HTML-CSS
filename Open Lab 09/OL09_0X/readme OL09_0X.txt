Check the video and make a webpage that looks like and works as the one there. This video has sound.
Try to solve it first with id and class and then, when you made it work, try to make it without id or class and using only <div> inside <body>

NOTE: There is no way that you will solve this if you start coding directly. You need to use pen and paper to sort out your ideas before coding anything. If you just go ahead and try things on the computer I can assure you it will not work.


Notice that:
    1) All the round divs are perfect circles, regardless of the size of the viewer
    2) The body has a white border and it has a margin of 20px. Always 20px margin, regardless of the size of the viewer.
    3) The round divs take up all the width of the body (minus margin), as you can see
    4) The round circles stick to the bottom and the top of the viewer when scrolling.
    5) In order to have scrolling you need to make sure that the body is big enough. There are maybe other solutions, the only one I could get to work so it looks like the video was: Create one extra-divs above and one extra-div below the round divs. The extra divs should be at least 100vh high. I only worked with it for 25 minutes or so, so maybe there are other solutions.

Try to find out on your own how to make a gradient background.
If you have trouble with that, just forget about it or use this:
background: linear-gradient(0deg, rgba(2,0,36,1) 0%, rgba(0,43,255,1) 100%);