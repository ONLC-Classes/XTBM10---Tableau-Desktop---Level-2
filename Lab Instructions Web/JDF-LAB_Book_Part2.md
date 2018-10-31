**[LAB Book partners up with Practical Tableau Book: Used for Tableau
Desktop Level 2]{.underline}**

**This Lab book is Part 2 of 5 Parts. **

**Part 1 LAB BOOK has been designed for anyone who wants to prepare for
Parts 2-5. **

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

Part 2 -- Chart Types

The charts starting on Page 110 and going to Page 193 are considered
"Common Charts", however, they are excellent because they do NOT use the
"Show Me" option. The Solutions for these charts are located in the
Workbooks Folder and the file is called "PartTwo.twbx"
(XTBM10\-\--Tableau-Desktop-Level-2-master\\Workbooks\\PartTwo.twbx).
You will learn how to create these charts from scratch, for a particular
business reason. Glance through the arts, and pick and choose or do them
all! However, if you want a challenge, flip to Page 195 (and move down
the Lab Exercises in this book to Chapter 33).

Chapter 19 - Exercise (Highlighted Table) - 3 Minutes -- Book Pages:
110-112

1.  Create a new WORKBOOK. Use the Excel Sample Super Store as your data
    source, Double Click the ORDERS Table to obtain the Dimensions and
    Measures for this Workbook.

2.  *ALT: Create a new workbook based upon the newly created "**My
    Superstore Data Source**." This is located on Tableau's Start Page,
    under the Saved Data Sources category located in the left connection
    panel in the application window.*

3.  Save the Workbook "PartTwo.twbx". (There is a copy of this workbook
    in the WORKBOOKS folder that has the solutions for the labs.)

4.  Rename Sheet1 and call it "Highlight Table". Color the sheet tab if
    desired.

5.  Drag the Order Date field to Column shelf, and using the down arrow
    on the pill, change the Order Date to Month (leave it discrete/blue,
    as a *Date Part*)

6.  Drag the Sub-Category to the Row shelf.

7.  Drag the Sales Measure to Label card on the Marks shelf.

8.  Change the chart type to "Square" on the Marks shelf.

9.  Drag a second Sales measure to the Color card on the Marks shelf.

10. Edit the Color card, using the Border tool to put a white border on
    your table.

Chapter 20 - Exercise (Heat Map) - 8 Minutes -- Book Pages: 114-117

1.  Get a new Sheet and name it "Heat Map". Color the sheet tab if
    desired.

2.  Drag Order date to the Column shelf, leave it discrete and change it
    to Month

3.  Drag Sales measure to the Row shelf

4.  Drag Sub-Category to the Color card.

> See Page 114 to compare to book. (Notice how messy these lines are and
> in some case are overlapping. The goal will be to create a heat map.

5.  Clear the work sheet

6.  Drag the Order Date field to Column shelf and change to discrete
    Month

7.  Drag the Sub-Category to the Row shelf

8.  Drag the Sales measure to Color card on the Marks shelf

9.  Drag a second Sales measure to the Size card on the Marks shelf

10. Change the chart type on the Marks card to circles. Play with the
    size tool until your chart looks like page 117 in your book -- use ½
    way mark on scale.

11. Change the chart type on the Marks care to square, just to see the
    "typical" heat map. Play with the size tool until you like it!

12. Sort Sub-Category by Sum of Sales, Descending.

Chapter 21 - Exercise (Dual-Axis/Combination) - 4 Minutes -- Book Pages:
119-123

1.  Get a new Sheet and name it "Dual-Axis". Color the sheet tab if
    desired.

2.  Drag Order date to Columns shelf, change it to Year (continuous)
    field.

3.  Drag the Sales measure to the Row shelf -- Notice the "timeline"
    chart you get.

4.  Drag the Discount measure to the Row shelf, place it to the right of
    the Sales Measure -- your View just got to be "two rows" of data.

5.  Click the Discount measure down arrow and choose Measure, Average.

6.  Click the arrow again and choose "Dual Axis". Now both the Sales and
    Average Discount will share your view. Check the picture on bottom
    of Page 121 to check for accuracy. (colors will not match book,
    leave this alone)

7.  Change the chart type of the SALES Measure to "BAR". Notice how fat
    the bars are -- new with version 10 and higher of Tableau

8.  Change the Order Date pill to Discrete. The bars will get skinnier.

9.  Drag the Category dimension onto the Columns shelf, to the right of
    the Order Date Pill.

10. Change the Average Discount chart type to LINE on the marks card.

11. Set the Fit of the view to Entire View.

12. Change Color of lines to Red and bars to Blue. Select ALL Marks for
    the line -- under Color edits.

13. Check your final picture with Page 123 of your book.

Chapter 22 - Exercise (Scatter Plot) - 5 Minutes -- Book Pages: 126-128

1.  Get a new Sheet and name it "Scatter Plot". Color the sheet tab if
    desired.

2.  Drag Sales measure to the Column shelf.

-   Either COPY and PASTE the Profit Ratio Measure from the
    "PartOne.twbx" Workbook or create a new Measure called "Profit
    Ratio".

-   ALT: If you created this workbook using the data source saved
    called: "**My Superstore Data Source"** or the default saved data
    source "**Sample -- Superstore**", this calculation already exists.
    If you are typing the formula from scratch (or you can copy the text
    below), here is the calculation:

> If calculated field (measure) is needed - Name: Profit Ratio
>
> Calculation: SUM(\[Profit\]) / SUM(\[Sales\])

3.  Drag the "Profit Ratio" measure to the Row shelf. Notice you have
    only ONE circle. -- This is because you have no "level of detail"

4.  Drag the "Product Name" dimension onto the Detail card on the Marks
    shelf. -- Check your picture with page 127 of your book.

5.  Next, we will add TWO RED Reference lines to this chart:

    a.  Right-Click the Profit Ratio Axis and add a RED REFERENCE line a
        little thicker than the default. Keep computation set to default
        (Average). See first pic below:

    b.  Right-Click the Sales Axis and add a RED REFERENCE line a little
        thicker than the default. Keep computation set to default
        (Average). See second pic below:

  -------------------------------------------------------------------------------------- -------------------------------------------------------------------------------------
  ![](.//media/image1.png){width="1.9085247156605425in" height="2.6345286526684166in"}   ![](.//media/image2.png){width="2.1051509186351707in" height="2.644449912510936in"}
  -------------------------------------------------------------------------------------- -------------------------------------------------------------------------------------

Check Page 128 of your book for accuracy.

Chapter 23 - Exercise (Tree Map -- Four Ideas) - 15 Minutes -- Book
Pages: 131-135

Tree Map 1

1.  Get a new Sheet and name it "Tree Map1". Color the sheet tab if
    desired.

2.  Drag Profit Ratio measure to Color card on Marks shelf

3.  Drag Sales measure to Size card on Marks shelf -- Notice you have
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

    a.  ![](.//media/image3.png){width="4.254717847769029in"
        height="4.254717847769029in"}

4.  Look at page 133 in your book to see that your chart looks similar
    to the book.

Tree Map 3

1.  Duplicate the "Tree Map1 (2)" sheet. Leave name as is. Leave color
    as is (if you colored it)

2.  Move the State dimension from the Detail Card to the Label Card.

3.  Click the Color card and Edit the colors. Change the STEPS to "2".
    This will make any profits for Sub-Category that are negative, will
    be RED. It will also make any profits for Sub-Category that are
    positive, will be NAVY.

4.  Check page 134 in your book for validation of how your chart will
    look.

Tree Map 4

1.  Duplicate the "Tree Map1 (3)" sheet. Leave name as is. Leave color
    as is (if you colored it)

2.  Drag a Sub-category into the FILTER card.

3.  Set the filter scope to NONE. Apply.

4.  Select Accessories and Apply. Continue to play with this filter by
    taking checks on and off sub-categories. Try one or more of these on
    your view.

-   (\*\*tip -- click on "Show Filter" to change the "Sub-Category"
    filter to see the view change.

5.  Drag Sales and Profit Ratio measures to the Label card.

6.  Format Profit Ratio and Sales to show Percentage and Current
    (Standard) in the Labels.

7.  Customize the Label Appearance to show the what you see in the book
    -- page 135.

8.  Check page 135 in your book for how your chart should look.

Chapter 24 - Exercise (Sparklines) - 8 Minutes -- Book Pages: 138-144

1.  Get a new Sheet and name it "Sparklines". Color the sheet tab if
    desired.

2.  Drag Measure Names to the Row shelf, Drag Measure Values to the Row
    shelf next to it. -- Change the view to "Fit to Height" - Look at
    page 138 and check your chart to be sure it looks like the book.

3.  Right-drag the Order Date field to the Columns shelf and choose the
    GREEN (continuous) Month (4th from bottom). Notice the sparklines
    already running across your view.

4.  Make the width of the graph smaller by taking your mouse to the
    right most side of the graph and dragging it in to approximately
    half the size it was. This will make your sparklines "pop".

5.  Right click any of one of the LEFT Axis (Your measures). Then click
    on "Edit Axis". Take the check box OFF the "Include Zeros" box, in
    an effort to get rid of the zeros on your view.

6.  Edit the Measure Name filter to show the following:

-   Discount

-   Profit

-   Profit Ratio

-   Quantity

-   Sales

7.  Now remove any lines that do not help your view.

    1.  Click on FORMAT menu and choose "Lines" and Rows tab in Format
        pane.

        i.  Format by taking ALL the lines off the sheet, rows and
            columns. This will give your sparklines a clean background.

    2.  Right-click "Value Axis" and deselect the "Show Header" menu
        choice.

8.  Click the COLOR card and choose your desired color for your
    sparklines.

9.  Check Page 144 to see that it is similar (except for color) to the
    Sparkline chart on that page.

Chapter 25 - Exercise (Small Multiples) - 5 Minutes -- Book Pages:
148-151

1.  Get a new Sheet and name it "Small Multiples". Color the sheet tab
    if desired.

2.  Drag the Region dimension onto the Column shelf.

3.  Drag the Segment dimension onto the Row shelf.

4.  Drag the Sales measure onto the Row shelf, next to the Segment pill.

5.  Right-drag the Order Date dimension onto the Column shelf and choose
    the continuous (green) MONTH option (4th from bottom)

> Check page 149 to check your progress.

6.  There are some formatting options on the bottom of page 151 that
    will make your chart look nicer. Give any/all a try, as desired. To
    Format the Font for the remaining headers, go to Format Menu and
    choose "Font". This will allow you to make the remaining headers
    larger.

7.  Change the worksheet title to read: **Sales by Region, Segment, and
    Calendar Month**. Format this title as 20 pt. and Bold.

8.  Check page 151 to see if your chart appears as the picture in the
    book.

Chapter 26 - Exercise (Bullet Graphs) - 15 Minutes -- Book Pages:
153-160

1.  Create a new worksheet; name it "Bullet". Color the sheet tab if
    desired.

2.  Create TWO calculated fields. You can create the first one, then
    duplicate it and change the value within it, and the name:

-   Calc 1 Name: This Year's Sales,

    -   Calc: IF YEAR(\[Order Date\]) = 2018 THEN \[Sales\] END

-   Calc 2 Name: Last Year's Sales,

    -   Calc: IF YEAR(\[Order Date\]) = 2017 THEN \[Sales\] END

3.  Drag "This Year's Sales" measure onto the Columns shelf

4.  Drag Sub-Category to the Rows shelf

5.  Drag "Last Year's Sales" Measure to the Detail card on the Marks
    shelf

6.  Change the view to "Fit Height"

7.  Right-click the x-Axis (This Year's Sales), and "Add Reference Line"

8.  In the Reference Line pop up box:

    a.  Change the Scope to "Per Cell"

    b.  Change the value to SUM(Last Year's Sales)

    c.  Change the calculated value to Sum or Total.

    d.  Change the Label to "None"

    e.  Change the line to RED and make it a bit thicker

9.  Click "OK"

> The first part of your bullet graph is complete

10. For a second time, right-click the X-Axis (This Year's Sales), and
    "Add Reference Line"

11. In the Reference Line pop up box:

    f.  Change the type of reference line to "Distribution"

    g.  Change the "Scope" from Per Pane to Per Cell

    h.  Change the "Computation Value" by Clicking the arrow down and
        next to Percentages\| "Percent of", and change the value to
        "Last Year's Sales".

    i.  Change calculation below from Average to *Total* or *Sum*.

    j.  Change the label to "none"

    k.  Check the box that says "Fill Below" (for shading on the 60% and
        80% distribution)

    l.  Adjust Fill color combinations, if desired.

    m.  Click "OK"

12. Be sure to visit the Size card on the marks shelf and slide to the
    left to make the blue bar chart lines a bit skinnier. This will
    allow the shading to show through.

13. Check page 159 to see how your chart compares to the book.

> Chapter 27 - Exercise (Stacked Area) - 4 Minutes -- Book Pages:
> 161-167

1.  Get a new Sheet and name it "Area". Color the sheet tab if desired.

2.  Drag Order Date to Columns shelf and change to Month (discrete).

3.  Drag the Sales measure to the Rows shelf.

4.  Drag the Sub-Category to the Color (you now have a line graph --
    check page 162 for validation)

5.  Change the chart type on the Marks shelf to "Area" -- you now have
    the picture on page 163.

6.  Click the down arrow on the Sales pill and choose "Quick Table
    Calculation" and pick "Percentage of Total" -- this will allow
    percentage trends to show up for the many sub-categories in the left
    Axis.

7.  Change the left Axis to reflect ALL the percentages:

    a.  Click the down arrow on the Sales pill once again.

    b.  Choose "Compute Using" off the menu and choose "Table(down)".

8.  Now your area chart reflects 100% of the values for Sub-Category.
    Check Page 167 to see how your chart "stacks up" to the one in the
    book. 😊

> Chapter 28 - Exercise (Histogram) - 4 Minutes -- Book Pages: 172-173

1.  Get a new Sheet and name it "Histogram". Color the sheet tab if
    desired.

2.  Right-click the Quantity measure, Create, Bins\...

    a.  Change the "Size" of the bin to 2 and click OK

3.  Drag this newly created bin to the Columns shelf. This bin is called
    "Quantity (bin)" and is located in the Dimension area in Side bar.

4.  Drag the "Quantity" measure to the Rows shelf.

5.  Click the green quantity pill's down arrow and choose "Measure" and
    pick "Count" off the list.

6.  Notice the "ranges" that sales have been split into. -- Check page
    171 in your book to validate the look of your chart.

7.  Change Quantity (bin) to a Continuous type of data presentation in
    the view.

8.  For some different views, feel free to "edit" the bin and change the
    range (aka 'distribution') to any numbers (1, 3, 4, etc.) The higher
    your number goes, the less "ranges" you get. (Note: You could create
    a parameter to set the Quantity (bin) size and allow for interactive
    adjustments to distribution ranges.)

9.  Modify the worksheet title to show: "Histogram: Number of Orders
    with Given \# of Products per Order".

Chapter 29 - Exercise (Box and Whisker) - 3 Minutes -- Book Pages:
175-181

1.  Create a new worksheet and name it "Box & Whisker". Color the sheet
    tab if desired.

2.  Drag Sub-category dimension to Columns shelf.

3.  Drag Sales measure to Rows shelf.

4.  Drag Order Date to Detail card on Marks shelf. On that Order Date
    pill now in the Marks card, click the arrow pointing down and select
    the Date Part as "Month" (discrete)

5.  Right-click the Y-Axis (Sales) and choose "Add Reference Line" --
    select "Box Plot". The default "IQR" settings will be ideal. Click
    OK.

6.  Then, change the "Marks" chart type to circle.

7.  Lastly, using the Size card, make the bars and circles smaller by
    dragging it to the left until desired.

8.  Check page 181 for finished map to compare yours.

Chapter 30 - Exercise (Symbol Map) - 3 Minutes -- Book Pages: 177-181

1.  Get a new Sheet and name it "Symbol Map". Color the sheet tab if
    desired.

2.  Double click the Postal Code dimension -- see the "auto map" appear

3.  Drag the Sales measure onto the Size card in the Marks shelf.

4.  Increase the size of default marks in the view (Circles).

5.  Click on the Color card in the Marks shelf and play with the opacity
    and borders. You can make your map "pop" with these.

> Check page 185 (top) to compare yours.

Chapter 30 - Exercise (Map-Box Map) - 10 Minutes -- Book Pages: 185-186

1.  Get a new Sheet and name it "Map Box Map". Color the sheet tab if
    desired.

2.  Go to [www.mapbox.com/maps](http://www.mapbox.com/maps) (while
    leaving Tableau Open)

3.  Scroll down and click on/select the "San Francisco" Map

4.  Click the "Or View Live Map" link

5.  Copy the URL in the browser's Address area.

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

Chapter 31 - Exercise (Filled Map) - 2 Minutes -- Book Page: 187-189

1.  Create a new worksheet and name it "Filled Map". Color the sheet tab
    if desired.

2.  Double click the State dimension and get the default map

3.  Click on chart type from the Marks shelf "Automatic" section and
    choose "Map" -- map will now be filled with color.

4.  Drag the Region dimension into the Color card on the Marks shelf.
    The map will now be "Regionalized"

5.  Compare page 189 with yours

Chapter 32 - Exercise (Dual Axis Map) - 5 Minutes -- Book Page: 191-193

1.  Get a new Sheet and name it "Dual Axis Map". Color the sheet tab if
    desired.

2.  Double-click the State dimension and get the default map.

3.  Add the Sales measure to the Size card on the Marks shelf.

4.  Add the Country and the City dimensions to the Detail card on the
    Marks shelf.

5.  Drag a SECOND *Latitude(generated)* measure to the Rows shelf.

6.  Click the Color card on the Marks shelf and change the color to
    something that will stand out -- Black is the best, though your book
    uses white.

7.  Select the 1^st^ *Latitude(generated)* and remove the Sales,
    Country, and City pills from the Marks card.

8.  Add the Region Dimension to the Color card.

9.  Change the chart type to "Map".

10. Click on the SECOND *Latitude(generated)* pill on the Rows shelf and
    choose "Dual Axis".

> Although they become one map, if the filled map is covering the symbol
> map, reverse the order by dragging the second Latitude pill in front
> of the first one.

11. Check page 193 to compare yours. Change Size card and the Color card
    settings for Sum(Sales) circle marks, if desired.

PAGE 195 - The Remaining Charts for this chapter are considered
ADVANCED. They are in the class data Workbooks folder
(XTBM10\-\--Tableau-Desktop-Level-2-master\\Workbooks), in a workbook
called "PartTwo\_Advanced.twbx". Please feel free to do as many as you
can/desire, or save them for a later time when you want a challenge. Be
sure to understand the Business Reason for each chart!
