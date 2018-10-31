**LAB Book partners up with Practical Tableau Book: Used for Tableau
Desktop Level 2**

**This Lab book is Part 1 of 5 Parts. Part 1 has been designed for
anyone who wants to prepare for Parts 2-5. If you did not take the
Tableau Desktop Level 1 class, you should work your way through this
Part 1 Lab Book. This will ensure you understand the concepts taught in
that class.**

***Desktop Level 1 Skillset is expected for success in this Desktop
Level 2 Class***

**\*\*\*Please note, all exercises will be created from scratch.
However, the SOLUTION files for this Lab Book are located in the
Workbooks folder^1** **and named "PartOne.twbx".**

**Part 1** --

**Chapter 8 - Exercise (Bar Chart Options) - 10 Minutes -- Book Pages:
35-37 (top)**

1.  Create a new workbook and use the Excel Sample Superstore, ORDERS
    table:

![](/media/part1image1.png)

2.  Rename Sheet 1 to "Bar Chart Options" (which will also change the
    title of the page to "Bar Chart Options" -- Additionally: right
    click the sheet tab and choose "color" off the menu. (\*note: these
    colors are your preference, but back at work, you may consider using
    them to differentiate departments, or sheets vs. dashboards, or
    projects, etc.)

![](/media/part1image2.png)

3.  SAVE Entire Workbook to your desktop. Name the file:
    "**PartOne.twbx**"-- you will use this workbook throughout Part One
    of Practical Tableau Book (Pages 3-101).

4.  Once you have the steps above opened, you will try each of the FIVE
    bar chart options discussed in your book on pages 35 and 36. Please
    follow the steps below to complete these five options:

**Option 1** -- Double Click the SALES Measure. Result: plain blue bar
chart -- click the undo button

\*\*\*\*

**Option 2** -- Left Drag your SALES Measure to the row --Result: same
blue bar chart as above -- click the undo button

\*\*\*\*

**Option 3** -- Click ONCE on the SALES Measure, Go to the SHOW ME Box
and select the bar chart (3rd row, 1st column) -- Notice the bar
chart by default is horizontal. Also Note that the Show Me Wizard
changed the position of your SALES Field. It is now located in the
Column Shelf.

-   Find the "SWAP" tool on the toolbar (or press **CTRL + W**)

![](/media/part1image3.png)

-   Additionally: Click the swap tool again to watch it toggle back and
    forth between horizontal and vertical. (Notice your SALES measure
    moving back and forth between Column and Row Shelves.

-   CLEAR THE WORKSHEET: (Find "CLEAR" tool and click or press
    ALT\_SHIFT\_BACKSPACE)

![](/media/part1image4.png)

\*\*\*\*

**Option 4** -- Change to a bar chart using the MARKS SHELF:

-   Drag ORDER Date dimension to the Column shelf, Drag SALES measure to
    Rows shelf (see picture on Page 36 of your book).

-   Go to the MARKS Shelf and Choose BAR CHART from the options:

![](/media/part1image5.png)

-   (Notice that when you use the MARKS shelf, as opposed to the "SHOW
    ME" Wizard, your SALES and ORDER DATE field remain in place. As you
    learn more about Tableau, you will rely less and less on the Wizard
    and learn to use the MARKS Shelf to create your charts)

-   CLEAR the Worksheet

\*\*\*\*

**Option 5** -- Right-Drag the SALES measure to the Rows shelf. (Result:
See picture on Page 37 of your book.)

-   This result gives an option to choose an aggregate. Choose
    MEDIAN(SALES), Choice \# 2 from List. A right click in Tableau can
    offer quicker options than going through many menus to get the
    desired result.

**SAVE THE WORKBOOK and keep this worksheet open for next exercise.**

**Part 1 - Chapter 8 - Exercise (Bar Chart Analytics) - 5 Minutes (Book
Page: 37)**

Continuing with MEDIAN(Sales) on Row shelf:

1.  Drag Region dimension to the Columns shelf.

2.  Drag a second Region dimension to the Color card on the Marks shelf.

3.  Select the the Analytics tab in the Side bar.

4.  Under "Custom", Choose "Reference Line" -- then drag and drop on top
    of TABLE

![](/media/part1image6.png)

5.  You will see the screen below. Pick "Median" from the computation
    dropdown.

6.  Choose a line color from the Line Dropdown:

![](/media/part1image7.png)

7.  Repeat these actions twice more, once to depict MINIMUM and once to
    depict MAXIMUM:

Your final result should look like this:

![](/media/part1image8.png)

8.  SAVE YOUR WORKBOOK

**Chapter 9 - Exercise (Line Graphs/Axes/Dates) - 10 Minutes- (Book Pages
41-46)**

1.  Add a new sheet to your workbook. Name the Sheet "Line Graphs" and
    additionally, change the color if desired.

2.  Double-click Sales measure (to bring it to Row shelf.)

3.  Right-drag the Order Date dimension to the Column shelf. From the
    Drop Field pop-up menu, choose the GREEN (Continuous) MONTH(Order
    Date) - 4^th^ from bottom of the list. Click OK.

4.  Click on the Color card in the Marks shelf and choose the middle
    (All) marker located at the bottom of the color editor.

    -   **Notice** that the SORT tools are not available for the Order
        Date Field. Continuous fields cannot be sorted.

    -   **Notice** that Tableau associates time with Line Charts by
        default.

> See picture on page 41 of your book to confirm result.

5.  Drag the "Ship Mode" dimension to the Row.

    -   Notice that the pill only goes in FRONT of the Sales Measure.
        You cannot move it afterward. A dimension always precedes a
        measure in a view; a dimension sets the granularity or "level of
        detail" in which the aggregation is performed. This "breaks up"
        the aggregation in the view into the different/unique Ship
        Modes, presented here as separate rows.

    -   Notice that each Axis has the same range.

6.  To change this, right click any SALES axis field (left side of
    view), and choose "Edit Axis".

7.  Under Range, choose "Independent Axis Ranges for each row or Column"

    -   Check result with page 44 picture in your book.

8.  Go to the GREEN -- Order Date pill and click the plus sign twice to
    see how the built-in hierarchy for Date type fields in Tableau
    works. Also, you can DRILL UP by clicking the undo tool, to go
    backwards.

9.  Next, remove the GREEN Order Date pill from the Column shelf
    (Right-click a white part of the Column shelf and choose "CLEAR
    SHELF".

10. Double-click the ORDER DATE dimension to the Column shelf. Leave it
    blue (discrete). Notice it CAN be sorted. We did not filter this for
    months, so note the plus sign starts on the YEAR option. . You can
    click the hierarchy plus signs all the way through to the DAY. Then,
    you can click the plus signs and drill back down. The main
    difference is that you can SORT Discreet fields.

![](/media/part1image9.png)

11. Additionally, feel free to use plus signs and sort tools to practice
    with DATES and HEIRARCHIES.

12. Save the workbook.

    **Chapter 10 - Exercise (Level of Detail and Scatters) - 5 Minutes --
    Book Pages: 49-50**

<!-- -->

1.  Get a new worksheet, name it "Level of Detail" and color the tab if
    desired.

2.  Create a new calculated field called "Profit Ratio".

<!-- -->

a)  Start this calculation by clicking on the "Analysis" menu and then
    "Create Calculated Field" -- or, you could RIGHT click on a white
    area in the Meaures area and "Create Calculated Field" 0r you could
    right mouse click an existing measure and create a calculated field.

b)  Then type in : SUM(\[Profit]\) / SUM(\[Sales]\)

   a.  OR you could also DRAG the fields into the calculation window.
       If you do this, please note the orange arrow pointing down.
       Tableau will place your dragged object where this arrow appears.

c)  Click "OK"

<!-- -->

3.  Drag the Sales Measure to the column.

4.  Drag the new Profit Ratio measure to the Row shelf.

5.  Check the picture on page 48 of your book for the result.

6.  Next, drag the "Customer Name" field into the "Detail" card on the
    Marks Shelf. Notice how much more detail is in your chart.

    a.  MORE DETAIL MORE LEVELS?

    b.  Drag Segment onto the Color card

    c.  Drag Sales onto the Size card

    d.  Drag Category onto the Shapes card

       Be sure to hide the Show Me box by clicking the words "Show Me.
       This will enable you to see associated reference legends (color,
       size, shape type) encoded in the view." Compare your results to
       page 50 in your book. Take the time to hover over the chart and
       see all the details available in the tool tips.

   **Chapter 11 - Exercise (Filtering Dimensions and Measures) - 5
   Minutes -- Book Pages: 54-59**

<!-- -->

1.  Get a new worksheet, name it "Filter Dim" (color if desired).

2.  Drag the Customer Name dimension to the Rows shelf.

3.  Drag the Sales measure to the Column shelf.

4.  Once the bar chart appears, CTRL + Click the first three names that
    begin with A (in your book, they use "C" names, but the point can be
    made with any name)

5.  Click on Exclude from the pop-up.

6.  Once you see the names are excluded, also notice that the Filters
    Shelf has a "Customer Name" filter. Click the arrow pointing down on
    the Customer Name pill in the Filters shelf and choose "Edit filter"

7.  The point is that the two ways to filter dimensions both work. Now,
    Click the "Wildcard" tab in the Filter window. Click on "Starts
    With" and type a capital "A" in the search box and click the
    "Exclude" check box.

8.  You have now been successful in excluding all the names beginning
    with the letter "A".

9.  Next, drag the Sales Measure into the Filter shelf. The Filter Field
    \[Sales] pop-up has values which are aggregates. Choose SUM,

10. Setting the Filter to Range of Values (default), change the lower
    number to 10,000.00. Click OK

11. Sort in Descending Order

12. Click the "T" (Show Mark Labels) tool on the toolbar to show all the
    mark values in the view.

13. Your chart should look like page 59 in your book.

**Chapter 12 - Exercise (Calculated Fields) - 5 Minutes -- Book Pages:
 62**

1.  Get a new worksheet, name it "Calcs" (color if desired)

2.  Create a calculated field named "Orders": COUNT(\[Order Id\])

3.  Drag this new Orders Measure onto the Rows

4.  Right Click your new calculated field and choose "Duplicate"

5.  Notice Tableau has given you a "Copy" of this calculation. Right
    Click it and choose "Rename" -- Name it "Count Orders Distinct".

6.  Edit this calculation to show: COUNTD(\[Order Id\]).

7.  Drag the new Count Orders Distinct measure onto the Rows, next to
    your first calculation.

8.  Go to the "Show Me" option and choose the first "Text Table" tool
    (1st tool in row, 1st tool in column)

9.  See the difference between Count Order and Count Order Distinct.
    What does this mean? -- That order ID's may sometimes contain more
    items (i.e., Product Names), therefore the OrderID is repeated when
    there is multiple line items. However, with a CountD function, it
    will only show ONE DISTINCT OrderID, regardless of how many line
    items were in that order.

 **Chapter 12 - Exercise (AOV -- Average Order Value) - 10 Minutes --
 Book Pages: 63**

1.  Get a new worksheet, name it "Conditions" (color if desired)

2.  Create a new calculation in your preferred way. Name it "AOV" to
    stand for sumAverage Order Value.

3.  The Calculation is as follows:

 SUM(\[Sales]) Count Orders Distinct

 \*\*Note!!! There are no parentheses around "Count Orders Distinct".
 Normally, this would cause an error in Tableau. But, since Count
 Orders Distinct is actually a calculated field which is already
 aggregated, there is no issue.

 \*\*\*You will use this calculation in the next exercise.

 **Chapter 12 - Exercise (Aggregating Calculated Fields) - 10 Minutes --
 Book Pages: 65-67**

1.  Continue with your "Conditions" Worksheet.

2.  Create a new calculation in your preferred way. Name it
    "Sub-Category Segment"

    a.  Type in this calculation: (or use the workbook "PartOne.twbx"
        and copy the calculation from it. You can either edit it to open
        it and copy and paste the calculation details, or you can right
        mouse click the entire calculation and copy it, then paste it
        into your workbook.

    b.  Below is the calculation, if you prefer to type it:

 IF \[Sub-Category\] = \"Copiers\"

 OR \[Sub-Category\] = \"Machines\"

 OR \[Sub-Category\] = \"Supplies\"

 THEN \"My Sub-Categories\"

 ELSE \"Other\"

 END

 \*\*The calculation appears in capital letters, but this has no
 significance. It just makes it easier to read. These key words are NOT
 case-sensitive.

3.  Drag Sub-Category dimension to the Row shelf.

4.  Drag the new Sub-Category Segment calculated dimension to the Row
    shelf, next to your first pill.

5.  Drag the new AOV measure to the Text card on the Marks shelf.

6.  Format this measure as Currency (Standard).

**Chapter 13 - Exercise (Table Calculations) - 5 Minutes -- Book Pages: 69-74**

1.  Create a new Worksheet named "CrossTab" (color if desired).

2.  Drag the Order Date dimension onto the Column Shelf.

3.  Click the arrow pointing down on the Order Date pill and change this
    to the SECOND "Month" option in the menu -- now your order date will
    be continuous (not sortable)

4.  Drag the SALES measure into the row. You now have a line chart.

5.  Drag a second SALES measure into the row, to the right of the one
    you have. Notice you have TWO line Charts.

6.  Click on the second SALES pill in the row and click the arrow
    pointing down. Choose Quick Table Calculation, then choose
    Difference (second option)

7.  While this pill is selected, go to the Marks shelf and choose "BAR"
    for the chart type for this pill. Now your second row on the chart
    is showing difference in SALES.

8.  Drag a third SALES measure onto the color card on the Marks shelf.

9.  Click on Color, Click on Edit Colors. Choose "Orange and Blue
    Diverging", then click the check box in front of "Stepped Color",
    change the number from 5 to 2.

10. Click on ok.

11. Check your results. It should look similar to the chart on page 74.

**Chapter 14 - Exercise (Parameters) - 5 Minutes -- Book Pages: 76-79**

1.  Create a new Worksheet named "Params" (color if desired)

2.  Create a new parameter by clicking on drop-down menu to the right of
    Dimensions heading in the Data side bar.

3.  Check Page 77 as you create this parameter. Here are the options you
    will use:

    -   Name: Algebra Parameter

    -   Data Type: Integer

    -   Current Value: 1

    -   Allowable Values: Range

    -   Minimum: 1, Maximum: 20, Step-Size: 1

4.  Click "OK"

5.  Create a new calculation, name it Algebra Equation. Type in:
    MIN(2) \* \[Algebra Parameter]

    -   Additionally, you can drag your new parameter in from the Data
        sidebar.

6.  Click OK.

7.  Drag the Algebra Equation calculated field to the Text card on the
    Marks shelf

    -   Notice the number 2 appears in your VIEW.

8.  Select the Algeba Parameter at the bottom of the Side bar,
    right-click it, and choose "Show Parameter Control"

-   You may need to hide the "SHOW ME" gallery, as the parameter control
    appears beneath it on the right side of the worksheet canvas area.

9.  When you change the parameter number either by typing or dragging
    the slider, the value in your VIEW changes dynamically.

10. Change the size of the font used by the Algebra Equation pill in
    view to 24 points.

**Chapter 15 - Exercise (Sets) - 15 Minutes -- Book Pages: 81 - 88**

1.  Create a new Worksheet named "Sets Filter" (color if desired)

 **WAY ONE to Create Sets**

a.  Drag SALES measure to Column

b.  Drag Customer Name dimension to Row

c.  Under the Customer Name header in the view's canvas, click on the
    first customer, "Aaron Bergman"

d.  Shift-click on the customer name, "Aleksandra Gannaway", in the
    header region.

e.  In the pop-up box, choose the option "Create Set"

f.  Name the set "First 20 Customers"

g.  Drag the new Set onto the Rows shelf, to the right of the Customer
    Name pill.

-   Notice that the first 20 customers are "IN" the first 20 Set and the
    rest are "OUT" of the set.

h.  Right-click on the IN/OUT(First 20 Customers) pill (Set), choose
    Edit Aliases: change In value to "1st 20 Customers; change the Out
    values to "Rest of Customers".

i.  Undo the Aliases, if desired.

**WAY TWO to Create Sets**

a.  Right-click the Customer Name dimension in Data side bar, Choose
    Create, and Create Set off the menu.

b.  See the pic on Page 83 to compare what you are looking at.

c.  Click Cancel (we are just looking at a different way to make a set)

**USING SETS FIVE WAYS**

1.  WAY ONE - FILTER

    a.  Drag your newly created "First 20 Customers" onto the Filter
        Pane. Notice your VIEW now only has these Customers.

    b.  SORT in Descending order

    c.  Drag the SALES Measure onto the Label card in the Marks shelf

    d.  Compare your chart to the top of Page 84.

2.  WAY TWO - CLUSTER

    e.  Create a new worksheet named "Sets Cluster" (color as same color
        of WAY ONE Set)

    f.  Drag your new Set onto the Color card on Marks shelf

    g.  Drag Customer Name to the Detail card on the Marks shelf

    h.  Drag the Sales measure to the Column

    i.  Drag the Profit Ratio Measure to the Rows

3.  WAY THREE -- Side by Side Customer/Cluster

    j.  Duplicate your "Sets Cluster" worksheet by Right Clicking and
        Choosing "Duplicate" off menu

    k.  Rename the Sheet to "Sets Calc"

    l.  Drag First 20 Customers Set to the Column Shelf.

    m.  Click on the COLOR card and choose "Edit Colors"

    n.  Change mark type to Circle; add a dark border around the mark.

    o.  Click on the "IN" (or '1st 20 Customers') data item and
        associate it to the red(ish) color to the right. Then click OK

    p.  Compare your chart to the picture on the top of Page 86.

4.  WAY FOUR and FIVE -- Dimension and Hierarchy

    q.  Create a new worksheet named "Sets Hierarchy" (color as same
        color as the rest of "Sets" sheets.

    r.  Click on Customer Name Dimension

    s.  Ctl-click on Segment dimension and the "First 20 Customers" set.

    t.  Right-click, select Hierarchy, then Create Hierarchy

    u.  Name it "Custom Hierarchy."

    v.  Re-order the custom hierarchy just created to show the following
        order: First 20 Customers, Segment, Customer Name.

    w.  Drag SALES measure to Column shelf

    x.  Drag new Custom Hierarchy to Row

    y.  Check picture on top of page 87 to compare

    z.  THEN, Click the plus sign on the hierarchy, Click the descending
        sort button, compare your chart to picture at the bottom of page
        87 -- yours may vary a bit, but the point is that the First 20
        Customers show up and are "in" the SET

    a.  THEN, Click the plus sign one last time, compare your picture to
        page 88. You got three different views as a result of this
        hierarchy.

**Chapter 16 - Exercise (Level of Detail Expressions (LOD)) - 10 Minutes
 -- Book Pages: 90-92**

1.  Create a new Worksheet named "LOD" (color if desired)

2.  Drag SALES measure to the Column shelf.

3.  Drag Category dimension to the Row shelf.

4.  Click the Show Mark Labels ("T") tool on the toolbar to see the
    Sales amounts as labels at the end of each bar.

5.  Change Fit screen settings to show Entire View.

 Compare to top of page 90 in book.

6.  Drag Sub-Category dimension to row, next to Category

7.  Compare to bottom of page 90 in book.

8.  Create a new calculation named "Exclude Sub-Category"

 Here is the calculation:

 { EXCLUDE \[Sub-Category]: SUM(\[Sales]) }

9.  Drag this to the Column shelf, next to SALES

10. Create another calculation named "Divide Sales by Exclude Sub
    Category"

 Here is the calculation:

 SUM(\[Sales])/SUM(\[Exclude Sub-Category])

11. Drag that calculated field as the last pill on the column shelf.

12. Check your charts with top and bottom of page 92 in book.

 **Chapter 17 - Exercise (Dashboards and Distribution) - 10 Minutes --
 Book Pages: 96-100**

1.  Create a new Worksheet names "Map" -- color if desired

2.  Double-click the State dimension to quickly create a symbol map

3.  Go to the SHOW ME Wizard and choose the SECOND Map on the SECOND
    row. This is a choropleth (or 'Filled') map and will "color in" each
    State.

4.  Drag the REGION Dimension to the Color card on the Marks shelf.

5.  Drag a SECOND Latitude Measure to the row, next to the first
    Latitude Measure -- you will get two charts

6.  Click on the second Latitude measure to select it and change the
    chart type to "Pie"

7.  Still selecting the second Latitude pill in the Rows shelf, drag the
    Sales measure to the Size card on the Marks shelf.

8.  Drag a second Sales measure to the color card -- Edit the colors and
    choose "Blue Light"

9.  Change second Latitude pill to present itself as a "Dual Axis".

10. Increase the Size settings for the pie marks.

 NEXT

11. Create a new DASHBOARD (either use menu DASHBOARD or the middle tool
    on the sheets tabs) name it "Sales Dashboard"

12. Drag the new Map worksheet onto the Dashboard -- notice it takes up
    the entire space.

13. Drag the Cross Tab worksheet under the map. Notice it takes up the
    entire BOTTOM Space.

14. Drag the Bar Chart Options sheet to the right bottom so that it
    shares the bottom half of the dashboard with your Table Calcs sheet.

15. Check the picture on Page 97 to be sure your Dashboard compares to
    this one -- note: the Bar Chart Options we created here differs from
    that in the book.

16. Save the workbook.

17. Create a Saved Data Source file for possible use with other Labs:

    a.  Select the Data menu choice and select Orders (Sample --
        Superstore) connection.

    b.  Select Add to Saved Data Sources

    c.  Save in the default (My Tableau Repository) directory; save as
        "My Superstore Data Source."

**THE TOPICS IN THE PART 1 EXERCISES WERE COVERED IN THE TABLEAU
 BEGINNING CLASS, EXCEPT FOR A LIMITED FEW, THAT WILL BE TAUGHT IN THIS
 CLASS. IF YOU CAN COMPLETE THE EXERCISES ABOVE, YOU ARE READY TO
 CONTINUE ON WTH THE TABLEAU DESKTOP 2 CLASS.**

[1]: The Workbooks folder is located in the downloaded student data
    files at the following link:

    https://github.com/ONLC-Classes/XTBM10---Tableau-Desktop-Level-2
