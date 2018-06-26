**[LAB Book partners up with Practical Tableau Book: Used for Tableau
Desktop Level 2]**

**This Lab book is Part 3 of 5 Parts. Part 1 of the LAB BOOK has been
designed for anyone who wants to prepare for Parts 2-5.**

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

**For more help and information about Practical Tableau, please visit
www.ryansleeper.com**

**Part 2 -- Chart Types - ADVANCED**

**Chapter 33 - Exercise (Sequential Path) - 3 Minutes -- Book Page:
195-198**

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

**Chapter 34 - Exercise (Custom Background) -- 5-15 Minutes (depending on
your choice below) -- Book Page: 201-206 - \*\*\*\*Amazing Lab**

1.  Get a new Sheet and name it "Back Image". Color the sheet tab if
    desired.

2.  There are TWO Data Sets for this Exercise. One is the "cords.xlsx"
    data set and the second is the "cords\_complete.xlxs". You can
    choose to do this using either from scratch and create with
    completed dataset. PLEASE OPEN BOTH to look at them and see the
    difference. One is nearly empty and the other is complete. Below
    find both ways to complete Exercise:

**FROM SCRATCH:**

1.  Add the "cords.xlsx" data source (from PartTwo\_Advanced folder)

2.  Add a background image to your view:

    -   Click on Map, Background Images (see the cords dataset and click
        it)

    -   Browse to Baseball Diamond Image in Desktop Level 2 Images
        Folder.

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

**Chapter 35 - Exercise (Custom Polygon)**

This exercise should be skipped as we have seen much of same previously.
If the students want to complete it, they should follow the directions
on pages 207-210. However, they will need to create a custom data set in
excel for the purposes of this lab.

**Chapter 36 - Exercise (Gantt) -- 10 Minutes -- Book Pages: 213-215**

1.  Get a new Sheet and name it "Gantt". Color the sheet tab if desired.

2.  Add a new Data Source called "PROJECTS" -- you can find this in the
    PartTwo\_Advanced Folder

3.  Drag Start Date Dimension to the Column shelf -- Click the arrow
    pointing down on this pill and choose "DAY" (Continuous)

4.  Drag Project Dimension to the Row shelf and Person Dimension next to
    it on the Row shelf

5.  Create a new Calculated Field called "Days" Type in this calculation
    (or use SOLUTION "PartTwo\_Advanced.twbx" and copy. Here is the
    calculation:

> \[Start Date\] -- \[End Date\]

6.  Drag the new Days calculation to the Size card on the Marks shelf.

7.  Drag Person Dimension to Color card on the Marks shelf.

8.  Right Click on x-Axis, Add a Reference Line. Choose these options
    from the pop up:

    a.  Type: Line

    b.  Scope: Entire Table

    c.  Value: Change to "Constant" in the dropdown, then type this into
        the text box: 6/1/2018 12:00:00 AM

    d.  Change line color to RED

9.  Drag Percentage Complete Measure into the Text Card on the Marks
    shelf -- Click on the Label Card and change alignment to CENTER

10. FORMAT the PANE for Percent Complete and change the number format to
    PERCENT with NO Decimal places. Also make the font a bit bigger and
    bold.

11. This chart will look a bit different from the book because of a bit
    of different data. But the overall chart should resemble page 215 in
    your book.

**Chapter 37 - Exercise (Waterfall) -- 5 Minutes -- Book Pages: 218-221**

1.  Get a new Sheet and name it "Waterfall". Color the sheet tab if
    desired.

2.  Drag the Profit Measure to the Rows shelf

3.  Drag the sub-category Dimension to the Columns shelf

4.  RIGHT CLICK the Bottom Axis and choose "FORMAT", Under the HEADER
    Tab, choose ALIGNMENT in the DEFAULT section. Choose the middle "A"
    to turn the Axis data to "Vertical"

5.  Change the chart type to "Gantt" from the Automatic Chart Type on
    Marks shelf

6.  Create a calculated field called "Negative Profit" This is a simple
    calculation: -\[Profit\]

7.  Drag the new calculation to the Size card on the Marks shelf.

8.  Change the SUM(Profit) to a Table Calculation of "Running Total".

9.  Check your Waterfall chart with page 221 in your book.

**Chapter 38 - Exercise (Slope) -- 5 Minutes -- Book Pages: 218-221**

1.  Get a new Sheet and name it "Slope". Color the sheet tab if desired.

2.  Get a new data source. It is called "Slope.xlsx" in the Data Sources
    Folder

3.  Drag the Year Dimension to the Column shelf

4.  Drag the "Measure" Measure to the Rows shelf

5.  Drag the Category Dimension to the Detail card on the Marks shelf

6.  Drag Category Dimension and Measure to the TEXT card on the Marks
    shelf

7.  Format the labels by clicking on the TEXT card. Click on LINE ENDS
    and click all three boxes to show line ends on both sides.

8.  Check your chart with page 226/

**Add a Dual-Axis to slope concept (5 Minutes) -- 226-230**

1.  Get a new Sheet and name it "Slope Dual". Color the sheet tab if
    desired.

2.  Get a new data source. It is called "DualSlope.xlsx" in the Data
    Source Folder

3.  Drag Social Network to Column shelf

4.  Drag Company to Column shelf next to Social Network

5.  Drag Audience to Row shelf

6.  Change the chart type to LINE on the Marks shelf

7.  Click the Color card on the Marks shelf and choose the middle
    "Markers"

8.  Drag a Second Audience to Row Shelf, change the chart type to
    circle. You now have two charts.

9.  Click on the SECOND Audience pill and choose "Dual Axis off the
    list" -- both charts are combined

10. Drag the Company Dimension to Color card on the Mark shelf

11. Check your chart with page 230 to compare.

**Chapter 39 - Exercise (Donut) -- 10 Minutes -- Book Pages: 232-237**

1.  Get a new Sheet and name it "Donut". Color the sheet tab if desired.

2.  Create a new calculation called "Sales Goals -- Actual Sales":
    8000000 -- sum(\[Sales\])

3.  Change the Chart type to "Pie" on the Marks shelf

4.  Create a calculated field called "Placeholder", Calculation: Min(0)

5.  Drag TWO copies of this to the ROWS shelf

6.  Click the arrow pointing down on the second placeholder and choose
    "Dual Axis"

7.  Change the second placeholder chart type to Circle. Play with the
    size to make it smaller and change the color to "white"

8.  Drag Measure Names to Color card on Marks shelf

9.  Drag Measure Values to the "Angle" card (which was created when you
    changed chart type to pie) on the marks shelf

10. Put a filter on Measure names. ONLY include Sales and Sales Goals --
    Actual Sales Measures

11. Format the Chart by making it bigger, adding a border and change the
    colors that you like for Sales and Sales -- Actual Sales

12. Check your chart with page 236 to compare.

13. 

**Chapter 40 Exercise (Funnel) -- 5 Minutes -- Book Pages: 240-246**

1.  Get a new Sheet and name it "Funnel". Color the sheet tab if
    desired.

2.  Get a new Data Source called Players.xlsx -- find this in the Data
    Sources Folder

3.  Drag the "Step" Measure into the "Dimensions" area to convert it to
    a Dimension

4.  Drag the Step Dimension to the Rows shelf

5.  Drag the Players Measure to the Columns shelf

6.  Change the chart type to Area on the Marks shelf

7.  Change VIEW to "Entire View"

8.  Create a calculated field called "Negative Players" , the
    calculation is: -\[Players\]

9.  Drag the new Negative Players Measure to the Columns shelf (Place to
    the LEFT of the Players Measure)

10. Compare picture to page 243 of your book.

11. There are optional exercises on pages 244-246. You can continue if
    desired, however this will involve a change to the data source. To
    keep it simple for class, we will leave it here.

**Chapter 40 Exercise (Pace) -- 15 Minutes -- Book Pages: 248-255**

12. Get a new Sheet and name it "Pace". Color the sheet tab if desired.

13. Get a new Data Source called "Pace.xlsx". Find this in the Data
    Sources folder

14. Create a new Calculation named "% of Goal" : sum(\[Current\]) /
    sum(\[Goal\])

15. Drag this new measure to the Column shelf

16. Drag the "Measure" Dimension to the Row shelf

17. Change the view to "Fit Height"

18. Go to the Analytics Menu and Add a Reference Line (to the TABLE) -
    Change the Value to: Sum of Pace : Minimum, Put in a "Custom" Label
    and type in PACE, Create a red line, slightly fatter.

19. Go back to the Analytics Menu and Add a second Reference Line (to
    the TABLE) -- Change the Value to AGG of GOAL: Maximum, Put in a
    "Custom" Label and type in GOAL, Create a red line, slightly fatter.

20. Create one more Calculated field as follows:

    a.  Name: Pace Score

    b.  Calculation:

> IF \[% of Goal\] / \[Pace\] \>= 1 THEN \"On Pace\"
>
> ELSEIF \[% of Goal\] / \[Pace\] \>= .9 THEN \"Slightly Behind Pace\"
>
> ELSE \"Behind Pace\"
>
> END

21. Drag the new calculation to the Color Card.

22. Check your work with page 253

23. There is a variation on Pages 254-255 if you wish to continue on.
    This will require changing the Data Source

**Chapter 41 Exercise (Pareto) -- 10 Minutes -- Book Pages: 259-263**

1.  Get a new Sheet and name it "Pareto". Color the sheet tab if
    desired.

2.  Use the Orders Sample Superstore BUT go to the Data Source Tab and
    be sure that both the ORDERS table and the RETURNS table are dragged
    into the data area. Then, change the JOIN type to LEFT JOIN (the
    second option)

3.  Go to the Pareto sheet (notice the "Returns" section is now part of
    the Dimensions area.

4.  Create a calculated field called "Returns". Type in this
    calculation: COUNT(\[Returned\] = "Yes")

5.  Drag the Sub-Category Dimension to the Column shelf

6.  Drag the new Returns Measure to the Row shelf -- change the chart
    type to BAR on the Marks shelf

7.  Drag a SECOND Returns Measure to the Rows shelf --Change the chart
    type to LINE on the Marks shelf

8.  Click the SECOND Returns pill on the Rows shelf, then click the
    arrow in the pill and choose "Dual Axis". Both charts have become
    one.

9.  Go to the SECOND Returns Pill and click the and click "Quick Table
    Calculation" -- choose "Running Total"

10. Click the SECOND Returns Pill AGAIN and click "Edit Table
    Calculation". Check the box at the bottom which says "Add Secondary
    Calculation". Change the secondary calculation to "Percent of
    Total". For a picture of this pop up and choices, see page 262 in
    your book.

11. Click the first SORT tool on the toolbar.

12. Check your chart with the picture on page 263 of your book.

**Chapter 41 Exercise (Control) -- 3 Minutes -- Book Pages: 267-269**

1.  Get a new Sheet and name it "Control". Color the sheet tab if
    desired.

2.  Use the Excel Sample Superstore (Orders) Data Source

3.  Drag the Order Date field to the Column shelf. Click the arrow
    pointing down on the pill and choose "Week Number" (Continuous)

4.  Drag the Profit Ratio Measure to the Row shelf

5.  Right click the Profit Ratio Axis and "Add Reference Line"

    a.  Choose "Distribution" as the type

    b.  For the Distribution Value, select Standard Deviation

    c.  Change the factors to -3 and 3 (see page 268 in your book to
        confirm choices)

    d.  Choose the Line option and choose RED for the color

6.  Check page 269 in your book to compare your chart.

> Chapters 44-46: The three remaining charts are variations of charts
> you have already created in this book. Feel free to re-visit anytime
> and use the directions provided in your text book to get through them.
> Since you have previous experience with all the options, the text book
> will be sufficient to get through.
>
> 44 -- Dual Axis Bump
>
> 45 -- Dumbbell
>
> 46 - Jitter
