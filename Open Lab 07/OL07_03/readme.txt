Please follow these steps:

    1) Check out the video and make a page that behaves like that one.
        ? The grid is always in the middle, regardless of the viewer size
        ? All the texts are always in the middle of the boxes
        ? The text in the title changes from ”MPP rules!” to ”MPP swings!” when we click on any of the cells
    2) You are not allowed to use classes or ids. Also, you are not allowed to use any tags other than <div> and <span> inside <body>. And don’t cheat by placing elements outside of <body>! Never place visible elements outside of body!
    3) Tips:
        ? Advanced selectors only work ”downwards” in the html-file. So the title that changes must be further down than the cells in the HTML-code BUT still be placed above in the page. I suggest you use a grid and the grid-area property for the grid items.
        ? Also… how the h*ll are we going to change the text (HTML-content) with CSS? Well, we don’t know how to do that (it’s perhaps doable with ::after and ::before but we haven’t studied them in this course). It’s anyhow probably easier to just hide/show elements. Tips (although I think you have already heard about this):
            ? this CSS rule display: none makes elements invisible
            ? what value of display makes them visible again? (Which of all the possible values is the one you need for your elements? That depends on which tags you used for the elements that are shown/hidden


About the CSS property display:
I don’t especially like w3schools asa tool for reference because it is a bit incomplete and sometimes gets some details wrong. But in this case it’s probably better than MDN for you:
https://www.w3schools.com/CSSref/pr_class_display.asp
