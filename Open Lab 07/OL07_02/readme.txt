Please follow these steps:

    1) Use the index.html code. You are not allowed to make any changes to it. You are specifically NOT allowed to add classes or ids to it.
    2) Make it look like a grid. See image 1
        ? The width of the grid is 60vw.
        ? Note that all cells are exactly square (height = width). Regardless of viewer width
        ? The font sizes depend on the height of the viewer (hv)
    3) As you can see each cell has a border, which results in the borders between cells being double. 
    We do not want this. We want all borders to be simple. 
    This can be fixed by giving the grid (main) a border and the cells only border right and bottom. 
    The double-borders happen now on along the right and bottom borders of the grid. See Image 2. 
    We don�t want that either, how can we avoid that?
    4) Center the grid and the title. Image 3.
    5) Color even and odd cells. Image 4.
        ? Do it with only two new selectors (check the available pseudo-classes)
        ? Do it with one new selector (think specificity!)
    6) Cells should change background-color to black when hovered (Image 4b) and to white while clicked on.
    7) Every time a cell is clicked the whole grid (main) gets a black border of width 5vw. video1. Tip: If you click on an element, all its parents also �get the click� (and become :active)�. all the way to <html>
    8) Why do you think that the whole grid becomes larger when we add a border to it? We haven�t changed the width! (Check your notes on box-model)
    9) We want to avoid that the grid becomes larger. It should take up as much space as before (including the border). video2.
    10) When we click on 13 it turns red, not white. video3.
    11) 
    12) 
    13) Hand in only the last css file, the one that contains all the steps.
