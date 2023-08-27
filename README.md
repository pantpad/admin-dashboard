# admin-dashboard

## Step 1: Set up and planning V
Set up your HTML and CSS files with some simple dummy content, just to make sure you have everything linked correctly.
Set up your Git repository (refer to past projects if you need a refresher).
Download a full-resolution copy of the project design file and get a general idea for how you’re going to need to lay things out in your HTML document.

## Step 2: Layout V
Start by writing out the HTML elements for the sidebar, header and main-content containers.
In your CSS file, apply Grid properties until you have this basic layout built.

## Step 3: Nesting
Taking it one section at a time, begin nesting child elements under the parent elements in the HTML. Remember that you can keep making grid containers within grid containers.
In the sidebar, use more grids to lay out the navigation and branding sections.
In the header, use more grids to lay out the search bar, user info and buttons.
For the main-content, use more grids to lay out the projects, announcements and trending items.
Fill out some dummy content and placeholder images so you can position all of your grid items.

Make the main-content container flex, so when scaling down the announcements and trending go to the bottom.
Working on the announcement and trending tab.
    Make 2 flex rectangle. make them wrap as rows. DONE
    Create announcement and trending using grid! DONE
    Make projects layout take as much space needed while costraining the rectangles to a lesser size. DONE
    TOMORROW
        work on the header + aside
        lay everything decently
        change font
        add box shadows
        make project card better
        finish trending tab
    HEADER
        make same padding on left and right DONE
        TRY making header just by using a single grid DONE
        Put facsimil items inside grid cells DONE
        Apply background for debugging purposes. DONE
        Make all the items inside each grid cell align correctly DONE
        Make header responsive after a certain amount DONE
        GRID LAYOUT BLUEPRINT: https://prnt.sc/rZSMgwiVIS28
        Improve header layout when responsive
        Make second row of the header grid align
        Introduce FONT-AWESOME icons.
        Remove background
    ASIDE
        TODO GRID LAYOUT BLUEPRINT -> https://prnt.sc/BTc-DW5IbLKf
        Wrap the grid inside a container max 600px height and width: 100%;
        Create aside using grid. 1 column 3 rows of auto. autoflow row;
        Each row will have 1 item of
            "display:grid;"
            2 columns (16px, 1fr)
            auto-flow row.
            align-content:center;
                fill the grid using icon + h4
        



## Step 4: Gather assets
Once you have your grid layout complete you can either recreate the dashboard example above or style your own design.
Check out some color palettes from Tailwind.
All of the icons and more can be downloaded as SVGs from Material Design Icons.
Choose your own fonts! The design example uses Roboto, which is available with Google fonts.

## Step 5: Some tips!
When building the layout, apply background colors or borders to your containers to help you visualize your grid.
It’s up to you whether to use pixels, fr units or both for your grid tracks.
This project does not have to be responsive, but if you’d like to you can expand or shrink the project cards section when resizing the browser window.
You don’t have to make a pixel perfect match with the design example. Consider this an opportunity to practice your CSS skills with your own designs.
Don’t forget to push your finished dashboard to GitHub. Use GitHub Pages to publish it to the world!


