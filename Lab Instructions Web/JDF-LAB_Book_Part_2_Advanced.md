**[LAB Book partners up with Practical Tableau Book: Used for Tableau
Desktop Level 2]**

**This Lab book is Part 3 of 5 Parts. Part 1 of the LAB BOOK has been
designed for anyone who wants to prepare for Parts 2-5.**

**If you did not take the Tableau Desktop Level 1 class, you should work
your way through this Part 1 Lab Book, to be sure you understand the
concepts taught in that class.**

**Desktop Level 1 Skillset is expected for success in this Desktop Level
2 Class**

**\*\*Please note that the Exercises used in this Part2 Lab\_ Advanced
Book are created from scratch. However, there is a
"PartTwo\_Advanced.twbx" file in the Workbooks folder which contains all
the solutions.**

**\*\*Also note that the chapters in Part 2 will use the Marks card, in
order to create charts without the "Show Me" wizard.**

**For more help and information about [Practical Tableau],
please visit www.ryansleeper.com**

**Part 2 -- Chart Types - ADVANCED**

**Chapter 33 - Exercise (Sequential Path) - 3 Minutes -- Book Page:
195-198**

1.  Create a new workbook connected to the Sample -- Superstore.xlsx
    file and the Orders worksheet.

    a.  Alternatively, you can create a new workbook based upon the
        Saved Data Source \| Sample -- Superstore located on the
        connection pane on Tableau's Start Page.

2.  Save this workbook as: **PartTwo\_Advanced.twbx**.

3.  Rename Sheet1 as "Sequential Path". Color the sheet tab if desired.

4.  Open a new Data Source (Click on Data Menu, choose new Data Source)
    (Page 197 in the book shows you how to create this data source in
    excel up at the top. For the purpose of time, this excel sheet has
    been created for you)

    b.  Choose Excel and choose the "StopStart.xlsx file located in the
        Lab Files under Data Sources.

5.  In the worksheet, select this data source in the Data tab.

6.  Right-click the "Stop" measure and choose "Convert to Dimension"

7.  Drag the data source's Longitude measure onto the Columns shelf -
    \[not the *Longitude (generated*) measure.\]

8.  Drag the data source's Latitude measure onto the Rows shelf - \[not
    the *Latitude (generated*) measure.\]

9.  In the "Automatic" chart type section, choose "Line" as your type --
    this will add a "Path" card to the Marks shelf

10. Drag your Stop Dimension into the new Path card on the Marks shelf

11. Compare your chart to page 198

**Chapter 34 - Exercise (Custom Background) -- 5-15 Minutes (depending on
your choice below) -- Book Page: 199-206**

1.  Get a new Sheet and name it "Back Image". Color the sheet tab if
    desired.

2.  There are TWO Data Sets for this Exercise. One is the "coords.xlsx"
    data set and the second is the "coords\_complete.xlxs". You can
    choose to do this using either from scratch and create with
    completed dataset. PLEASE OPEN BOTH to look at them and see the
    difference. One is nearly empty and the other is complete. Below
    find both ways to complete Exercise:

**FROM SCRATCH:**

1.  Add the "coords.xlsx" data source (from PartTwo\_Advanced folder)

2.  Add a background image to your view:

    -   Click on Map, Background Images (see the cords dataset and click
        it)

    -   Browse to Baseball Diamond Image in Desktop Level 2 Images
        Folder.

    -   The pop-up box needs to be completed as follows: (be sure that
        there is both and X and a Y entry by using dropdown)

        -   X Position: 0 Left, 500 Right

        -   Y Position: ) Bottom, 500 Top

3.  Open the Data Source in Microsoft Excel -- keep it open in the
    background

4.  Drag the X Measure to the Columns shelf

5.  Drag the Y Measure to the Rows shelf

6.  Turn-off Aggregation (Analysis \|Aggregation)

7.  See your image on the view.

8.  We will "find" the positions for each player on the field by using
    the "Annotation" pointer:

    -   Right click the view and choose "Annotate" and then "Point".

    -   By default, you will see the pop up with X and Y points.

    -   Click OK and go back to your View

9.  Drag the Position Dimension onto the Detail card on the Marks shelf.

    -   You will see your background picture.

    -   Use the "Point" and drag it around to each "position" on your
        image. Record these points in your Excel (cords) Spreadsheet.

    -   Right click the cords data source and choose "Refresh" (or F5
        *Refresh* key).

    -   See each point with the coordinates

    -   Delete the Annotation

        Create with COMPLETE Data Source:

<!-- -->

1.  Add the coords\_complete.xlsx data source (from the downloaded Data
    Sources folder)

2.  Add a background image to your view:

    a.  Click on Map, Background Images (see the cords\_complete dataset
        and click it)

    b.  In File or URL address text box, choose Browse and find the
        bdiamond.jpg file located in the downloaded data folder path:

       i.  Tableau L2 Instruction Data and
           Examples\\XTBM10\-\--Tableau-Desktop-Level-2-master\\Images\\
           bdiamond.jpg.

    c.  The Pop-up box needs to be completed as follows: (be sure that
        there is both and X and a Y entry by using dropdown)

       ii. X Position: 0 Left, 500 Right

       iii. Y Position: ) Bottom, 500 Top

    d.  Click OK until you return the main editing window in Tableau.

3.  Drag the X Measure to the Columns shelf

4.  Drag the Y Measure to the Rows shelf

5.  Turn-off Aggregation (Analysis \|Aggregation). This changes the
    scale (500 x 500) and allows a larger view of the background image.

6.  Drag the Y field into the COLOR card on the Marks shelf, choose a
    palette (something with red would be good) -- compare your chart
    with page 206 in the book.

7.  In addition, you can also drag the Position Dimension onto the Text
    card on the Marks shelf to see the positions labeled.

8.  Change Mark type to Circle, change Color and Size.

 If you want to "hide" the Lookup mark, create an Area annotation and
 place it atop the Lookup Mark. Type something like: "Player positions
 in Baseball."

\*\*\*\*Either way you complete it, do this final format:

**Chapter 35 - Exercise (Custom Polygon)** --

This exercise should be skipped as we have seen much of same previously.
If the students want to complete it, they should follow the directions
on pages 207-210. However, they will need to create a custom data set in
excel for the purposes of this lab.

**Chapter 36 - Exercise (Gantt) -- 10 Minutes -- Book Pages: 211-215**

1.  Create a new worksheet and name it "Gantt". Color the sheet tab if
    desired.

2.  Add a new Data Source named "Projects.xlsx" -- you can find this in
    the data source folder in the downloaded Data Sources folder.

3.  In the worksheet view, drag Start Date dimension to the Columns
    shelf. Choose Day (Continuous -- 2^nd^ Day choice in the menu) as
    how to show the data from the underlying date field.

4.  Drag Project and Person dimensions to the Rows shelf. (Project, then
    Person on the shelf)

5.  Create a new Calculated Field called "Days" Type in this calculation
    (or use SOLUTION "PartTwo\_Advanced.twbx" and copy. Here is the
    calculation:

 \[End Date\] - \[Start Date\]

6.  Drag this new Days measure to the Size card on the Marks shelf.

7.  Drag Person Dimension to Color card on the Marks shelf.

8.  Right Click on x-Axis, Add a Reference Line. Choose these options
    from the pop up:

    a.  Type: Line

    b.  Scope: Entire Table

    c.  Value: Change to "Constant" in the dropdown, then type this into
        the text box: 6/1/2018 12:00:00 AM

    d.  Change line color to RED

9.  Drag Percentage Complete Measure into the Label card on the Marks
    shelf -- Click on the Label Card and change horizontal alignment to
    CENTER

10. FORMAT the PANE for Percent Complete and change the number format to
    PERCENT with NO Decimal places. Also make the font to 10pt. and
    bold.

11. Drag Person dimension to Color shelf.

12. This chart will look a bit different from the book due to data
    differences. But the overall chart should resemble page 215 in your
    book.

**Chapter 37 - Exercise (Waterfall) -- 5 Minutes -- Book Pages: 217-221**

1.  Get a new Sheet and name it "Waterfall". Color the sheet tab if
    desired.

2.  Use the Superstore data source.

3.  Drag the Profit measure to the Rows shelf.

4.  Drag the Sub-Category dimension to the Columns shelf.

5.  RIGHT CLICK the Horizontal (bottom) axis and choose "FORMAT", Under
    the HEADER Tab, choose ALIGNMENT in the DEFAULT section. Choose the
    middle "A" to turn the Axis data to "Vertical"

6.  Change the chart type to "Gantt" from the Automatic Chart Type on
    Marks shelf

7.  Create a calculated field called "Negative Profit" This is a simple
    calculation: -\[Profit\]

8.  Drag the new Negative Profit field to the Size card on the Marks
    shelf.

9.  Change the SUM(Profit) to a Table Calculation of "Running Total".

10. Check your Waterfall chart with page 221 in your book.

11. Alt: drag Sub-Category to Color card in Marks shelf and Show Mark
    Labels.

**Chapter 38 - Exercise (Slope) -- 5 Minutes -- Book Pages: 223-225**

1.  Create a new worksheet and name it "Slope". Color the sheet tab if
    desired.

2.  Get a new data source. It is called "Slope.xlsx" in the Data Sources
    Folder

3.  Drag the Year Dimension to the Column shelf. Change Year pill to
    Discrete.

4.  Change Fit settings to Fit Width in the view.

5.  Drag the "Measure" measure to the Rows shelf.

6.  Drag the Category dimension to the Detail card on the Marks shelf.

7.  Drag Category field and the Measure field (measure) to the Label
    card on the Marks shelf.

8.  If needed, change the Mark type to Line.

9.  Format the labels by clicking on the Label card. Click on LINE ENDS
    and select the three Options check boxes to show line ends on both
    sides.

10. Check your chart with page 226.

**Add a Dual-Axis to slope concept (5 Minutes) -- 226-230**

1.  Create a new worksheet and name it "Slope Dual". Color the sheet tab
    if desired.

2.  Get a new data source. It is called "DualSlope.xlsx" in the Data
    Source Folder.

3.  Drag Social Network dimension to the Columns shelf.

4.  Drag Company dimension to Column shelf, next to Social Network.

5.  Drag the Size of Audience measure to Rows shelf.

6.  Change the chart type to LINE on the Marks shelf

7.  Click the Color card on the Marks shelf and choose the middle
    "Markers" -- this shows data marks along the line.

8.  Drag another Size of Audience measure to Row Shelf, placing if after
    the one already there.

9.  Select this second Size of Audience pill and change the chart type
    to Circle in the Marks shelf. You now have two charts.

10. Click on the SECOND Audience pill and choose "Dual Axis" from the
    pill's menu choices; both charts are now combined.

11. Synchronize the Axis.

12. Select the All header in the Marks shelf. Drag the Company Dimension
    to Color card on the All header in the Marks shelf

13. Important: select the LAST (2nd) Size of Audience pill in the Rows
    shelf. Drag Size of Audience to Label Card in Marks shelf

14. In Marks shelf, right-click on Sum(Size of Audience) pill currently
    controlling Label display, ...add a Quick Table calculation: Percent
    Difference. Then, change table calculation Compute Using: Pane
    (across)

15. Use Label card to format and change alignment as desired. Also, you
    can change the size of the circle marks to add more visuals to the
    view.

16. To hide the secondary scale (right), turn off the Header for
    right-hand axis (i.e., 2^nd^ Size of Audience scale).

17. Check your chart with page 230 to compare.

**Chapter 39 - Exercise (Donut) -- 10 Minutes -- Book Pages: 231-237**

1.  Create a new worksheet and name it "Donut". Color the sheet tab if
    desired.

2.  Select the Sample - Superstore data source.

3.  Create a new calculation called "Sales Goals -- Actual Sales":
    8000000 -- SUM(\[Sales\])

4.  Change the Chart type to "Pie" on the Marks shelf

5.  Create a calculated field called "Placeholder", Calculation: Min(0)

6.  Drag the Placeholder field to the Rows shelf. Make a copy of this
    pill on the Rows shelf -- you now have 2 Placeholder pills on the
    Rows shelf.

7.  Click the arrow pointing down on the second placeholder and choose
    "Dual Axis"

8.  Change the second placeholder chart type to Circle. Change the color
    the "White." Play with the size to make it smaller to get the
    "donut" effect.

9.  Select the 1st Placeholder pill on Rows shelf. Then, drag Measure
    Names to Color card on Marks shelf

10. Drag Measure Values to the "Angle" card (which was created when you
    changed chart type to pie) on the marks shelf

11. Put a filter on Measure names. ONLY include Sales and Sales Goals --
    Actual Sales Measures

12. Format the Chart by making it bigger, adding a border and change the
    colors that you like for Sales and Sales -- Actual Sales

13. Check your chart with page 236 to compare.

14. Could create a calculation named: "% of Goal" with the calculation

 SUM(\[Sales\])/\[Sales Goals - Actual Goals\].

15. Show this at center of 2nd pill for placeholder in donut. Format
    as percentage.

16. Show other Text labels as desired.

17. Hide all Axis Headers (showing 'Placeholder').

**Chapter 40 Exercise (Funnel) -- 5 Minutes -- Book Pages: 239-246**

1.  Create a new worksheet and name it "Funnel". Color the sheet tab if
    desired.

2.  Get a new Data Source called Players.xlsx -- find this in the Data
    Sources Folder.

3.  Drag the "Step" Measure into the "Dimensions" area to convert it to
    a Dimension.

4.  Right-click on Step dimension, choose Aliases; change Alias Values:
    1 = Highschool; 2 = College; 3 = Professional.

5.  Drag the Step dimension to the Rows shelf.

6.  Drag the Players measure to the Columns shelf.

7.  Change the chart type to Area on the Marks shelf.

8.  Change VIEW to "Entire View"

9.  Create a calculated field called "Negative Players", the calculation
    is: -\[Players\]

10. Drag the new Negative Players Measure to the Columns shelf (Place to
    the LEFT of the Players Measure)

11. Hide Headers for Players and Negative Players (pills) in the view.

12. Compare picture to page 243 of your book.

13. There are optional exercises on pages 244-246. You can continue if
    desired, however this will involve a change to the data source. To
    keep it simple for class, we will leave it here.

 **Chapter 41 Exercise (Pace) -- 15 Minutes -- Book Pages: 247-255**

14. Get a new Sheet and name it "Pace". Color the sheet tab if desired.

15. Get a new Data Source called "Pace.xlsx". Find this in the Data
    Sources folder.

16. Create a new Calculation named "% of Goal" :

SUM(\[Current\])/SUM(\[Goal\])

17. Drag % of Goal calculated measure to the Columns shelf.

18. Create another Calculation name "Pace" : (1/52) \* 42

19. Drag Pace measure to the Details card in Marks shelf.

20. Drag the "Measure" Dimension to the Row shelf

21. Change the view to "Fit Height"

22. Go to the Analytics Tab in Sidebar and Add a Reference Line (to the
    TABLE)

    a.  Change the Value to:

       i.  *Sum of Pace*: Minimum

       ii. Choose "Custom" Label and type PACE. Format as a red line,
            slightly fatter.

23. Go back to the Analytics tab, add a second Reference Line (to the
    TABLE)

    b.  Change the Value to:

       iii. *AGG of % of GOAL*: Maximum,

    c.  Choose "Custom" Label and type in GOA. Format as a red line,
        slightly fatter.

24. Create one more Calculated field as follows:

    d.  Name: Pace Score

    e.  Calculation:

 IF \[% of Goal\] / \[Pace\] \>= 1 THEN \"On Pace\"

 ELSEIF \[% of Goal\] / \[Pace\] \>= .9 THEN \"Slightly Behind Pace\"

 ELSE \"Behind Pace\"

 END

25. Drag the new Pace Score measure/calculation to the Color Card.

26. Check your work with page 253

27. There is a variation on Pages 254-255 if you wish to continue on.
    This will require changing the Data Source

28. Extra: Create a parameter to control the weeks determined for PACE
    in calculation in Step 18. Show the parameter control and adjust.

**Chapter 42 Exercise (Pareto) -- 10 Minutes -- Book Pages: 257-263**

1.  Create a new worksheet and name it "Pareto". Color the sheet tab if
    desired.

2.  Create a new data source connection to Sample Superstore. Name this
    connection "Orders and Showing Returned Orders".

3.  Drag Orders and Returns worksheets into the connection canvas area
    to the right. Then, change the JOIN type to LEFT JOIN (the second
    Venn diagram option from left.)

4.  Go to the Pareto sheet (notice the "Returns" worksheet data section
    is now part of the Dimensions area.

5.  Create a calculated field called "Returns". Type in this
    calculation:

 COUNT(\[Returned\] = "Yes")

6.  Drag the Sub-Category dimension to the Columns shelf.

7.  Drag the newly created Returns measure to the Row shelf -- change
    the chart type from Automatic to BAR on the Marks shelf.

8.  Drag a SECOND Returns Measure to the Rows shelf --Change the chart
    type to LINE on the Marks shelf.

9.  Set this pill (2nd Returns) to Dual Axis.

10. Go to the SECOND Returns Pill and click the and click "Quick Table
    Calculation" -- choose "Running Total"

11. Click the SECOND Returns Pill AGAIN and click "Edit Table
    Calculation". Check the box at the bottom which says "Add Secondary
    Calculation". Change the secondary calculation to "Percent of
    Total". For a picture of this pop up and choices, see page 262 in
    your book.

12. Click the first SORT tool on the toolbar.

13. Check your chart with the picture on page 263 of your book.

**Chapter 43 Exercise (Control) -- 3 Minutes -- Book Pages: 265-269**

1.  Get a new Sheet and name it "Control". Color the sheet tab if
    desired.

2.  Use the Excel Sample Superstore (Orders) Data Source.

3.  Drag the Order Date field to the Columns shelf. Click the arrow
    pointing down on the pill and choose "Week Number" (Continuous).

4.  Drag the Profit Ratio measure to the Rows shelf.

5.  Right click the Profit Ratio Axis and "Add Reference Line"

    a.  Line as type

    b.  Scope set to Entire Table

    c.  Value: AGG(Profit Ratio), Average

    d.  Label: Custom; Computation \| Value

    e.  Formatting: Dashed, thicker, Blue.

    f.  Click OK.

6.  Again, right click the Profit Ratio Axis and "Add Reference Line"

    g.  Choose "Distribution" as the type

    h.  For the Distribution Value, select Standard Deviation

    i.  Change the factors to -3 and 3 (see page 268 in your book to
        confirm choices)

    j.  Choose the Line option and choose RED for the color

    k.  Click OK.

7.  Check page 269 in your book to compare your chart.

 **Chapters 44-46:** The three remaining charts are variations of charts
 you have already created in this book. Feel free to re-visit anytime
 and use the directions provided in your text book to get through them.
 Since you have previous experience with all the options, the text book
 will be sufficient to get through.

 **44 -- Dual Axis Bump**

 **45 -- Dumbbell**

 **46 - Jitter**
