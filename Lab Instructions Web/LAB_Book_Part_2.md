**[LAB Book partners up with Practical Tableau Book: Used for Tableau
Desktop Level 2]{.underline}**

**This Lab book is Part 2 of 5 Parts. Part 1 of the LAB BOOK has been
designed for anyone who wants to prepare for Parts 2-5. **

**If you did not take the Tableau Desktop Level 1 class, you should work
your way through this Part 1 Lab Book, to be sure you understand the
concepts taught in that class.**

**Desktop Level 1 Skillset is expected for success in this Desktop Level
2 Class**

**\*\*Please note that the Exercises used in this Part2 Lab Book are
created from scratch. However, there is a "PartTwo.twbx" file in the
Workbooks folder which contains all the solutions.**

**\*\*Also note that the chapters in Part 2 will use the Marks card, in
order to create charts without the "Show Me" wizard.**

Part 2 -- Chart Types

The charts starting on Page 110 and going to Page 193 are considered
"Common Charts", however, they are excellent because they do NOT use the
"Show Me" option. The Solutions for these charts are located in the
Part2 Lab Folder and the file is called "PartTwo\_Common.twbx". You will
learn how to create these charts from scratch, for a particular business
reason. Glance through the arts, and pick and choose or do them all!
However, if you want a challenge, flip to Page 195 (and move down the
Lab Exercises in this book to Chapter 33).

Chapter 19 - Exercise (Highlighted Table) - 3 Minutes -- Book Pages:
110-112

1.  Create a new WORKBOOK. Use the Excel Sample Super Store as your data
    source, Double Click the ORDERS Table to obtain the Dimensions and
    Measures for this Workbook.

2.  Name the Workbook "PartTwo.twbx". (There is a copy of this workbook
    in the WORKBOOKS folder that has the solutions for the labs.)

3.  Rename Sheet1 and call it "Highlight Table". Color the sheet tab if
    desired.

4.  Drag the Order Date field to Column shelf, and using the down arrow
    on the pill, change the Order Date to Month (leave it discrete)

5.  Drag the Sub-Category to the Row shelf.

6.  Drag the Sales Measure to Label card on the Marks shelf.

7.  Change the chart type to "SQUARE" on the Marks shelf.

8.  Drag a second Sales measure to the Color card on the Marks shelf.

9.  Lastly, Click the color card and use the border tool to put a white
    border on your table.

Chapter 20 - Exercise (Heat Map) - 8 Minutes -- Book Pages: 114-117

1.  Get a new Sheet and name it "Heat Map". Color the sheet tab if
    desired.

2.  Drag Order date to Column, leave it discrete, but change it to Month

3.  Drag Sales Measure to Row shelf

4.  Drag Sub-Category to Color

5.  See Page 114 to compare to book. (Notice how messy these lines are
    and in some case are overlapping. The goal will be to create a heat
    map.

6.  Clear the work sheet

7.  Drag the Order Date field to Column shelf and change to discrete
    Month

8.  Drag the Sub-Category to the Row shelf

9.  Drag the Sales Measure to Color card on the Marks shelf

10. Drag a second Sales Measure to the Size card on the Marks shelf

11. Change the chart type on the Marks card to circles. Play with the
    size tool until your chart looks like page 117 in your book.

12. Change the chart type on the Marks care to square, just to see the
    "typical" heat map. Play with the size tool until you like it!

Chapter 21 - Exercise (Dual-Axis/Combination) - 4 Minutes -- Book Pages:
119-123

1.  Get a new Sheet and name it "Dual-Axis". Color the sheet tab if
    desired.

2.  Drag Order date to Column shelf, change it to a "continuous" field.

3.  Drag the Sales Measure to the Row shelf -- Notice the "timeline"
    chart you get.

4.  Drag the Discount Measure to the Row shelf, place it to the right of
    the Sales Measure -- your View just got to be "two rows" of data.

5.  Click the Discount Measure down arrow and choose Measure, Average.

6.  Click the arrow again and choose "Dual Axis". Now both the Sales and
    Average Discount will share your view. Check the picture on bottom
    of Page 121 to check for accuracy. (colors will not match book,
    leave this alone)

7.  Change the chart type of the SALES Measure to "BAR". Notice how fat
    the bars are with version 10 and higher of Tableau, Change the Order
    Date field to Discrete. The bars will get skinnier.

8.  Drag the Category field onto the Column shelf, next to the Order
    Date Pill.

9.  Change the Average Discount chart type to LINE on the marks card.
    Check your final picture with Page 123 of your book.

Chapter 22 - Exercise (Scatter Plot) - 5 Minutes -- Book Pages: 126-128

1.  Get a new Sheet and name it "Scatter Plot". Color the sheet tab if
    desired.

2.  Drag Sales Measure to the Column shelf

3.  Either COPY and PASTE the Profit Ratio Measure from the
    "PartOne.twbx" Workbook or create a new Measure called "Profit
    Ratio". If you are typing the formula from scratch (or you can copy
    the text below), here is the calculation:

> Name: Profit Ratio
>
> Calculation: sum(\[Profit\]) / sum(\[Sales\])

4.  Drag your new "Profit Ratio" Measure to the Row shelf. Notice you
    have only ONE circle. -- This is because you have no "level of
    detail"

5.  Drag the "Product Name" dimension onto the Detail card on the Marks
    shelf. -- Check your picture with page 127 of your book.

6.  Next, we will add TWO RED Reference lines to this chart:

    a.  Right-Click the Profit/Ratio Axis and add a RED REFERENCE line a
        little thicker than the default. See first pic below:

    b.  ![](-media2=.//media/image1.png){width="3.6034722222222224in"
        height="4.966666666666667in"}Right-Click the Sales Axis and add
        a RED REFERENCE line a little thicker than the default. See
        second pic below:

![](-media2=.//media/image2.png){width="3.792361111111111in"
height="4.763888888888889in"}

7.  Check Page 128 of your book for accuracy.

Chapter 23 - Exercise (Tree Map -- Four Ideas) - 15 Minutes -- Book
Pages: 131-135

Tree Map 1

1.  Get a new Sheet and name it "Tree Map1". Color the sheet tab if
    desired.

2.  Drag Profit Ratio Measure to Color card on Marks shelf

3.  Drag Sales Measure to Size card on Marks shelf -- Notice you have
    the foundation of a Tree Map, with NO Detail.

4.  Drag Country and State Dimensions to Detail card on Marks shelf.
    Compare your first Tree Map to page 132 in your book.

Tree Map 2

1.  Duplicate the "Tree Map1" sheet. Leave name as is. Leave color as is
    (if you colored it)

2.  Add the Sub-Category dimension to the Rows Shelf.

3.  If your chart is really small, get your mouse near the right side of
    the chart and find the double-edged mouse and dotted line, in an
    effort to make your chart wider. See pic below for where to put your
    mouse:

    a.  ![](-media2=.//media/image3.png){width="4.254717847769029in"
        height="4.254717847769029in"}

4.  Look at page 133 in your book to see that your chart looks similar
    to the book.

Tree Map 3

1.  Duplicate the "Tree Map2" sheet. Leave name as is. Leave color as is
    (if you colored it)

2.  Move the State dimension from the Detail Card to the Label Card.

3.  Click the Color card and Edit the colors. Change the STEPS to "2".
    This will make any profits for sub-category that are negative, will
    be RED. It will also make any profits for sub-category that are
    positive, will be NAVY.

4.  Check page 134 in your book for validation of how your chart will
    look.

Tree Map 4

1.  Duplicate the "Tree Map3" sheet. Leave name as is. Leave color as is
    (if you colored it)

2.  Drag a second Sub-category into the FILTER card.

3.  Turn ALL the sub-category off

4.  Choose the first sub-category (Accessories). Continue to play with
    this filter by taking checks on and off sub-categories. Try one or
    more of these on your view.

5.  Check page 135 in your book for how your chart should look.

Chapter 24 - Exercise (Sparklines) - 8 Minutes -- Book Pages: 138-144

1.  Get a new Sheet and name it "Sparklines". Color the sheet tab if
    desired.

2.  Drag Measure Names to the Row shelf, Drag Measure Values to the Row
    shelf next to it. -- Change the view to "Fit to Height" - Look at
    page 138 and check your chart to be sure it looks like the book.

3.  RIGHT-CLICK the Order Date field and choose the GREEN (continuous)
    Month (4th from bottom). Notice the sparklines already running
    across your view.

4.  Make the width of the graph smaller by taking your mouse to the
    right most side of the graph and dragging it in to approximately
    half the size it was. This will make your sparklines "pop".

5.  Right click any of one of the LEFT Axis (Your measures). Take the
    check box OFF the "Include Zeros" box, in an effort to get rid of
    the zeros on your view.

    a.  Now remove any lines that do not help your view. Click on FORMAT
        menu and choose "Lines". Then format by taking ALL the lines off
        the sheet, rows and columns. This will give your sparklines a
        clean background.

6.  Click the COLOR card and choose your desired color for your
    sparklines.

7.  Check Page 144 to see that it is similar (except for color) to the
    Sparkline chart on that page.

Chapter 25 - Exercise (Small Multiples) - 5 Minutes -- Book Pages:
148-151

1.  Get a new Sheet and name it "Small Multiples". Color the sheet tab
    if desired.

2.  Drag the Region field onto the Column shelf

3.  Drag the Segment field onto the Row shelf

4.  Drag the Sales Measure onto the Row shelf, next to Segment

5.  Check page 149 to check your progress.

6.  RIGHT-CLICK the Order Date field onto the Column shelf and choose
    the green (continuous) month option (4th from bottom)

7.  There are some formatting options on the bottom of page 151 that
    will make your chart look nicer. Give any/all a try, as desired. To
    Format the Font for the remaining headers, go to Format Menu and
    choose "Font". This will allow you to make the remaining headers
    larger.

8.  Check page 151 to see if your chart appears as the picture in the
    book.

Chapter 26 - Exercise (Bullet Graphs) - 15 Minutes -- Book Pages:
154-159

1.  Get a new Sheet and name it "Bullet". Color the sheet tab if
    desired.

2.  Create TWO calculated fields. You can create the first one, then
    duplicate it and change the value within it, and the name:

> Calc 1: Name: This Year's Sales, Calc: If YEAR(\[Order Date\]) = 2018
> THEN Sales END
>
> Calc 2: Name: Last Year's Sales, Calc: If YEAR(\[Order Date\]) = 2017
> THEN Sales END

3.  Drag "This Year's Sales" Measure onto the Column shelf

4.  Drag sub-category to the Row shelf

5.  Drag "Last Year's Sales" Measure to the Detail card on the Marks
    shelf

6.  Change the view to "Fit Height"

7.  Right-Click the x-Axis (This Year's Sales), and "Add Reference Line"

8.  In the Reference Line pop up box:

    a.  Change the Scope to "Per Cell"

    b.  Change the value to "Last Year's Sales"

    c.  Change the Label to "None"

    d.  Change the line to RED and make it a bit thicker

9.  Click "OK"

10. The first part of your bullet graph is complete

11. For a second time, Right-Click the X-Axis (This Year's Sales), and
    "Add Reference Line"

12. In the Reference Line pop up box:

    e.  Change the type of reference line to "Distribution"

    f.  Change the "Scope" from Per Pane to Per Cell

    g.  Change the "Computation Value" by Clicking the arrow down and
        next to "Percentage of", change the value to "Last Year's Sales"

    h.  Change the label to "none"

    i.  Check the box that says "Fill Below" (for shading on the 60% and
        80% distribution)

    j.  Click "OK"

13. Be sure to visit the Size card on the marks shelf and slide to the
    left to make the blue bar chart lines a bit skinnier. This will
    allow the shading to show through.

14. Check page 159 to see how your chart compares to the book.

> Chapter 27 - Exercise (Stacked Area) - 4 Minutes -- Book Pages:
> 162-167

1.  Get a new Sheet and name it "Area". Color the sheet tab if desired.

2.  Drag Order Date to Column shelf and Change to Month (Still Discrete)

3.  Drag the Sales Measure to the Row shelf

4.  Drag the Sub-Category to the Color (you now have a line graph --
    check page 162 for validation)

5.  Change the chart type on the Marks shelf to "Area" -- you now have
    the picture on page 163.

6.  Click the down arrow on the Sales pill and choose "Quick Table
    Calculation" and pick "Percentage of Total" -- this will allow
    percentage trends to show up for the many sub-categories in the left
    Axis.

7.  To change the left Axis to reflect ALL the percentages, Click the
    down arrow on the Sales pill once again. Choose "Compute Using" off
    the menu and choose "Table(down)".

8.  Now your area chart reflects 100% of the values for sub-category.
    Check Page 167 to see how your chart "stacks up" to the one in the
    book.

> Chapter 28 - Exercise (Histogram) - 4 Minutes -- Book Pages: 172-173

1.  Get a new Sheet and name it "Histogram". Color the sheet tab if
    desired.

2.  Right-Click the Quantity Measure and Create a Bin. Change the "Size"
    of the bin to 2 and click OK

3.  Drag the newly created bin (which will be located in the DIMENSION
    AREA to the Column shelf

4.  Drag the "Quantity" measure to the Row shelf

5.  Click the green quantity pill's down arrow and choose "Measure" and
    pick "Count" off the list.

6.  Notice the "ranges" that sales have been split into. -- Check page
    171 in your book to validate the look of your chart.

7.  For some different views, feel free to "edit" the bin and change the
    range to any numbers (1, 3, 4, etc.) The higher your number goes,
    the less "ranges" you get.

Chapter 29 - Exercise (Box and Whisker) - 3 Minutes -- Book Pages:
177-181

1.  Get a new Sheet and name it "Box Whisker". Color the sheet tab if
    desired.

2.  Drag sub-category dimension to Column shelf

3.  Drag Sales Measure to Row shelf

4.  Drag Order Date to Detail card on Marks shelf. Click the arrow
    pointing down and choose "Month" (Still discrete)

5.  Right-Click the Y-Axis and choose "Add Reference Line" -- The
    default "IQR" settings will be ideal.

6.  Lastly, using the Size card, make the bars and circles smaller by
    dragging it to the left until desired.

7.  Check page 181 for finished map to compare yours.

Chapter 30 - Exercise (Symbol Map) - 3 Minutes -- Book Pages: 177-181

1.  Get a new Sheet and name it "Symbol Map". Color the sheet tab if
    desired.

2.  Double click the Postal Code Dimension -- see the "auto map" appear

3.  Drag the Sales Measure onto the Size card in the Marks Shelf

4.  Click on the Color card in the Marks shelf and play with the opacity
    and borders. You can make your map "pop" with these.

5.  Check page 185 (top) to compare yours.

Chapter 30 - Exercise (Map-Box Map) - 10 Minutes -- Book Pages: 185-186

1.  Get a new Sheet and name it "Map Box Map". Color the sheet tab if
    desired.

2.  Go to [www.mapbox.com/maps](http://www.mapbox.com/maps) (while
    leaving Tableau Open)

3.  Scroll down and click on/select the "San Francisco" Map

4.  Click the "View Live Map" link

5.  Copy the URL

6.  Go back to Tableau and click on the "Map" menu.

7.  Choose Background Maps, then Map Services

8.  Click the "Add" button and choose "Map Box:

9.  In the pop-up, give the "Style" a name -- example: Colorful

10. Paste the URL you got into the URL field

11. Click into one of the empty fields below so that Tableau populates
    the fields.

12. Click OK

13. See your new Colorful map in the dialog box and click "Close"

14. Double click the STATE Dimension. It will have your new Colorful Map
    on the background. Also, go back to the "Map" menu and choose
    "Background Maps". The new Colorful Map background appears in the
    menu as a choice.

15. Check page 186 (bottom) to compare yours.

Chapter 30 - Exercise (Filled Map) - 2 Minutes -- Book Page: 189

1.  Get a new Sheet and name it "Filled Map". Color the sheet tab if
    desired.

2.  Double click the STATE Dimension and get the default map

3.  Click on chart type from the Marks shelf "Automatic" section and
    choose "Map" -- map will now be filled with color.

4.  Drag the Region Dimension into the Color card on the Marks shelf.
    The map will now be "Regionalized"

5.  Compare page 189 with yours

Chapter 30 - Exercise (Dual Axis Map) - 5 Minutes -- Book Page: 192-193

1.  Get a new Sheet and name it "Dual Axis Map". Color the sheet tab if
    desired.

2.  Double click the STATE Dimension and get the default map

3.  Add the SALES Measure to the Size card on the Marks shelf

4.  Add the Country and City Dimensions to the Detail card on the Marks
    shelf

5.  Click the Color card on the Marks shelf and change the color to
    something that will stand out -- Black is the best, though your book
    uses white

6.  Drag a SECOND Latitude Pill onto the Rows shelf

7.  Remove the Sales and City pills from the Marks card

8.  Add the Region Dimension to the Color card

9.  Change the chart type to "Map"

10. Click on the SECOND latitude pill on the Rows shelf and choose "Dual
    Axis"

11. Although they become one map, the filled map is covering the symbol
    map. -- Reverse the order by dragging the second Latitude pill in
    front of the first one.

12. Check page 193 to compare yours

PAGE 195 - The Remaining Charts for this chapter are considered
ADVANCED. They are in the PartTwo folder, in a workbook called
"PartTwo\_Advanced.twbx". Please feel free to do as many as you
can/desire, or save them for a later time when you want a challenge. Be
sure to understand the Business Reason for each chart!

Chapter 33 - Exercise (Sequential Path) - 3 Minutes -- Book Page:
195-198

1.  Get a new Sheet and name it "Sequential Path". Color the sheet tab
    if desired.

2.  Open a new Data Source (Click on Data Menu, choose new Data Source)
    (Page 197 in the book shows you how to create this data source in
    excel up at the top. For the purpose of time, this excel sheet has
    been created for you)

3.  Choose Excel and choose the "StopStart.xlsx file located in the Lab
    Files under "Part 2".

4.  Right click the "Stop" Measure and choose "Convert to Dimension"

5.  Drag YOUR Longitude field onto the Columns shelf (not the generated
    longitude field)

6.  Drag YOUR Latitude field onto the Rows shelf (not the generated
    latitude field)

7.  In the "Automatic" chart type section, choose "Line" as your type --
    this will add a "Path" card to the Marks shelf

8.  Drag your Stop Dimension into the new Path card on the Marks shelf

9.  Compare your chart to page 198

Chapter 34 - Exercise (Custom Background) -- 5-15 Minutes (depending on
your choice below) -- Book Page: 201-206 - \*\*\*\*Amazing Lab

1.  Get a new Sheet and name it "Back Image". Color the sheet tab if
    desired.

2.  There are TWO Data Sets for this Exercise. One is the "cords.xlsx"
    data set and the second is the "cords\_complete.xlxs". You can
    choose to do this using either from scratch or with the complete
    dataset. PLEASE OPEN BOTH to look at them and see the difference.
    One is nearly empty and the other is complete. Below find both ways
    to complete Exercise:

FROM SCRATCH:

1.  Add the "cords.xlsx" data source (from PartTwo\_Advanced folder)

2.  Add a background image to your view:

    -   Click on Map, Background Images (see the cords dataset and click
        it)

    -   The Pop up box needs to be completed as follows: (be sure that
        there is both and X and a Y entry by using dropdown)

        -   X Position: 0 Left, 500 Right

        -   Y Position: ) Bottom, 500 Top

3.  Open the Data Source in Microsoft Excel -- keep it open in the
    background

4.  Drag the X Measure to the Columns shelf

5.  Drag the Y Measure to the Rows shelf

6.  See your image on the view.

7.  We will "find" the positions for each player on the field by using
    the "Annotation" pointer:

    -   Right click the view and choose "Annotate" and then "Point".

    -   By default you will see the pop up with X and Y points.

    -   Click OK and go back to your View

8.  Drag the Position Dimension onto the Detail card on the Marks shelf.

    -   You will see your background picture.

    -   Use the "Point" and drag it around to each "position" on your
        image. Record these points in your Excel (cords) Spreadsheet.

    -   Right click the cords data source and choose "Refresh"

    -   See each point with the coordinates

    -   Delete the Annotation

        Create with COMPLETE Data Source:

<!-- -->

1.  Add the cords\_complete.xlsx data source (from PartTwo\_Advanced
    folder)

2.  Add a background image to your view:

    a.  Click on Map, Background Images (see the cords\_complete dataset
        and click it)

    b.  The Pop up box needs to be completed as follows: (be sure that
        there is both and X and a Y entry by using dropdown)

        i.  X Position: 0 Left, 500 Right

        ii. Y Position: ) Bottom, 500 Top

3.  Drag the X Measure to the Columns shelf

4.  Drag the Y Measure to the Rows shelf

5.  Drag the Position Dimension onto the Detail card on the Marks shelf.

\*\*\*\*Either way you complete it, do this final format:

Drag the Y field into the COLOR card on the Marks shelf, choose a
palette (something with red would be good) -- compare your chart with
page 206 in the book. In addition, you can also drag the Position
Dimension onto the Text card on the Marks shelf to see the positions
labeled.

Chapter 35 - Exercise (Custom Polygon) - 3 Minutes -- Book Page: 208-210

1.  Get a new Sheet and name it "Polygon". Color the sheet tab if
    desired.

2.  
