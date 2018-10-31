**LAB Book partners up with Practical Tableau Book: Used for Tableau
Desktop Level 2**

**This Lab book is Part 3 of 5 Parts**

**Part 3 -- Tips and Tricks**

**Chapter 47 - Exercise (Icons) - 8 Minutes -- Book Pages: 295-299**

1.  Before you begin:

    a.  Go out to Windows Explorer and go to: \\documents\\My Tableau
        Repository\\Shapes

    b.  Leave this open

    c.  Go to the Desktop Level 2 Folder (where our class files are)

    d.  Open the Images folder

    e.  Right click the "Sports" folder and press CTRL + C to copy

    f.  Go back to the open Windows Explorer and press CTRL + V to paste
        the folder into your Shapes Directory

2.  Create a new workbook using "Sample -- Superstore" Saved Data Source
    from the connection pane on Tableau's Start Page.

3.  Save and name the Workbook "PartThree.twbx". (There is a copy of
    this workbook in the WORKBOOKS folder that has the solutions for the
    labs.)

4.  Rename Sheet1 and call it "Icons". Color the sheet tab if desired.

5.  Get a new data source - Icons.xlsx -- located in your Data Sources
    folder(part of downloaded data).

6.  Select that data source in the Data tab to set the available fields
    for building the view.

7.  There is only one field called "Icon Name" -- drag it to the Rows
    shelf.

8.  Change the Mark type from Automatic to Shape on the Marks shelf.

9.  Drag Icon Name dimension to the Shape shelf in the Marks card.

10. Notice that Tableau encoded a shape to each of your Icon Names. Also
    notice you got a new legend to describe each shape.

11. Click the Shape card.

12. Under the "Select Shape Palette" Option click the arrow pointing
    down next to "Default" Look for your Sports Folder (if you do not
    see it, Click the "Reload Shapes" button at the bottom.

13. Assign each Sports Icon Name to a picture by clicking the name, then
    clicking the corresponding picture (EX: Women's Basketball to the
    icon that IS Women's Basketball).

    g.  Note: choosing to "Assign Palette" command will speed up this
        step.

14. When they are all associated, Click OK -- see each new custom Icon
    on your Worksheet.

15. Next, click the NEW DASHBOARD tab at the bottom of your Workbook

16. Name it "Icon Dashboard" and color it the same color as your Icon
    Worksheet (if you colored it)

17. Drag your only Worksheet (Icons) into it

18. Go to the "Dashboard" Menu above and choose "Actions" off the list

19. When in the Actions pop up, click "Add Action" at the bottom

20. Choose "Filter" off the list

21. Name this "Click Icons"

22. Under both SOURCE and TARGET, make sure that your "Icons" sheet is
    selected and be sure that your "Run Action On" option (right side of
    screen) is set to "Select". If it is not, Click "Select"

23. \*\*Also Notice the option that says \"Clearing the Selection Will"
    and notice the option is set to "Show All Values"

24. Click "OK" -- notice your new Filter Action in the Dialogue Box

25. Click "OK" again.

26. Set the Fit viewing option (on toolbar) to "Entire View."

27. Click an Icon. Notice it will select that Icon and show it to you in
    a "Zoom" mode

28. To get back to all Icons, click in a white area around the image.
    This is because your option was set to "Show All Values" when
    choosing "Clearing the Selection" (from step 23).

**Chapter 48 - Exercise (What-If) - 8 Minutes -- Book Pages: 301-305**

1.  Create a new worksheet and name it "What If". Color the sheet tab if
    desired.

2.  Select the Sample Superstore data source.

3.  Create a Parameter:

    a.  Name: "What If"

    b.  Data Type: Integer

    c.  Allowable Values: Range

    d.  Click all three boxes (Minimum, Maximum, Step) and change
        Minimum to 0 (zero) and if necessary, change Maximum to 100.
        (Step should default to 5)

4.  Click OK

5.  Create a new calculated field:

    e.  Name: "What-If Sales"

 ALT - you can drag and drop your Sales Measure and your What-If
 Parameter into the calculation as you type, or you can copy below: (or
 use Solution)

f.  The calculation is: \[Sales\] \* (1 + \[What-If\] /100)

g.  Click OK

<!-- -->

6.  Right-Drag the Order Date dimension to the Columns shelf. In the
    Drop Field pop-up, choose the green (continuous) MONTH Order Date
    (4^th^ option from bottom)

7.  Drag your "Measure Values" Measure into the Rows shelf -- notice one
    of "each" Measure appears. In the end, you will only want the Sales
    measure and the "What-if Sales" measure here.

    h.  One method to accomplish this is to select "Discount" (The first
        measure in the **Marks Shelf**!), Then hold your Shift key down
        (and keep holding it down) and Select "Quantity" (so that it
        selects them both and everything in between) in the Marks Shelf.
        While you still have your SHIFT key held down, Right click into
        one of those selected fields and choose "Remove". All but Sales
        and What-If Sales should be removed.

    i.  Another method, drag Method Names from Dimensions into Filters
        shelf, choose None, then select only Sales and What-If Sales to
        only show those measures in the filter.

8.  Notice that your Measure Names dimension will move to the FILTER
    shelf and if you edit it (just to look at it), you will notice it
    has been filtered for Sales and What-If Sales.

9.  Move the Measure Names dimension to the Color card on the Marks
    shelf -- you will now have two colored lines in your view (though
    overlapping/atop each other). If desired, click on the Color card
    and re-associate Sales and What-if Sales to your desired color(s)
    and click OK

10. Right-click the "What If" parameter and "Show Parameter Control".
    This control provides a slider to change the Sales and the What-if
    Sales to show the "forecast" of sales if the What-If (% increase)
    changes.

11. Edit the Title... for the color legend to list: "Showing Sales & %
    Increases"

12. Edit the Label card to Show Mark Labels \| Highlighted

13. Edit the worksheet Title to show:

 "The *What-If Sales* Multiplier shows a forecasted \<Parameters.What
 If\>% increase in sales."

 **Chapter 49 - Exercise (Alert 1) - 15 Minutes -- Book Pages: 307-311**
 Note: Chapter 66 is also referenced to create the Parameter &
 calculated field.

1.  Get a new sheet and call it "Alerts 1". Color the sheet tab if
    desired.

2.  Choose to use Sample -- Superstore data source for the worksheet.

3.  Create a Parameter as follows:

    a.  Name: Set Date Aggregation

    b.  Type: String

    c.  Choose "List" from Available Values

    d.  Type in your custom list by clicking first into the value field,
        then double clicking the Display field. Set them up as follows:
        (be sure to use all small letters on the Value (left) side.


| > day     | > Day     |
| ----      |   ----    |
| > week    | > Week    |
| > quarter | > Quarter |
| > month   | > Month   |
| > year    | > Year    |

4.  Show the parameter control. Change format/layout of the parameter to
    Single Value List.

    e.  Create a calculation and name it "Date Choice".

       DATETRUNC(\[Set Date Aggregation\], \[Order Date\])

5.  Place the Sales measure on the Rows shelf.

6.  Right-drag Date Choice dimension onto the Column shelf and choose
    the first option \[**Date Choice (Continuous**)\].

7.  Right-click drag Order Date dimension to Label card in Marks shelf
    and choose MIN (Order Date).

8.  Repeat and choose MAX (Order Date).

9.  Next, change the Title of the worksheet to read:

 "This worksheet shows data aggregation by date range set to:
 \<Parameters.Set Date Aggregation\>."

i.  Hint: if you accidentally delete any of the fields, you can use the
    INSERT tool to get them back (take a look by clicking, to see what
    is available)

ii. Format the text as desired and then click OK (once).

<!-- -->

10. Play the Set Date Aggregation parameter control by changing the date
    parts to reflect different granularities.

 **Chapter 49 - Exercise (Alert 2) - 5 Minutes -- Book Pages: 309**

1.  Create a new worksheet and name it "Alerts 2" Color the sheet tab if
    desired.

2.  Right-drag Order Date Dimension to Columns shelf and change to green
    MONTH \[(Order Date)\] Continuous.

3.  Drag Sales measure to Rows shelf.

4.  Create a calculation:

    a.  Name: Dynamic Label Alert

    b.  Calc:

 IF SUM(\[Sales\]) \>= 97000 THEN \"Extra Great\"

 ELSEIF SUM(\[Sales\]) \<= 12000 THEN "Extra Terrible\"

 ELSE NULL

 END

5.  Drag your new Dynamic Label Alert measure to the Label card. Format
    the Label card as desired.

6.  Copy Dynamic Label Alert to Color card.

7.  Labels will automatically appear

 **Chapter 49 - Exercise (Alert 3) - 5 Minutes -- Book Pages: 310-311
(different example than book's example)**

1.  Get a new sheet and call it "Alerts 3" Color the sheet tab if
    desired.

2.  Drag Category and Ship Mode dimensions to Columns shelf.

3.  Drag Region dimension to the Rows shelf.

4.  Change the Marks type to Shape.

5.  Create a calculation to show Profit as a % of Sales named: KPI
    Ratio:

 SUM(\[Profit\]) / SUM(\[Sales\])

6.  Create a second calculation named "KPI Ratio Color and Shape":

 IF \[KPI Ratio\] \>.12 THEN \"Greater than 12%\"

 ELSEIF \[KPI Ratio\] \<.05 THEN \"Less than 5%\"

 ELSE \"Between 5% and 12%\"

 END

7.  Drag the KPI Ratio Color and Shape measure to the Color shelf.

8.  Perform another drag and place the KPI Color and Shape field on the
    Shapes Card.

    a.  Choose \"Thin Arrows\" from the shape palette choices.

       i.  Assign \"Greater than 12%" with the UP arrow

       ii. \"Less than 5%\" with DOWN arrow

       iii. \"Between 5% and 12"\" with the RIGHT arrow.

9.  Edit the Color Card. Pick \"Traffic Light\" --

    b.  Associate \"Greater than 12%\" with a Green color

    c.  \"Less than 5%\" with a Red color\"

    d.  \"Between 5% and 12%\" with a Yellow color.

10. Fit the view to \"Entire View\" just while we do the next part

11. Change the Default number format for the KPI Ratio calculated field
    to \"Percent\" with NO decimal places - right click and go to
    default properties, number, then choose percent, and no decimal
    places.

12. Drag KPI Ratio to Label card. Adjust mark label alignment if desired
    (e.g., right,

13. horizontal alignment)

14. Use the pill for KP Ratio Color and Shape, assigned to the Color
    card, to sort the names to follow a logical traffic light order -
    you will need to use a Manual sort. Proposed order below:

    iv. Green - \"Greater than 12%"

    v.  Yellow - \"Less than 5%\"

    vi. Red - \"Between 5% and 12"

 **Chapter 56 - Exercise (showing Concept of Dynamic Dashboard Views) -
 10 Minutes -- Rest of Book examples on Pages: 353-363**

DYNAMIC VIEWS:

1.  Use Sample -- Superstore as data source.

2.  Create a worksheet named: Dynamic View

3.  Create a Parameter and name it **MeasureOptions**

4.  Use the screenshot below to complete the parameter settings.

![](/media/part3image1.png)

5.  Create a calculated field: **ChoiceOfMeasure**

![](/media/part3image2.png)

Assemble:

6.  Right-drag Order Date dimension onto the Columns shelf and select
    continuous Month.

7.  Drag your new calculated field ChoiceOfMeasure to Rows shelf.

8.  Drag Segment to Color

9.  Right Click your Parameter (MeasureOptions) and choose Show
    Parameter Control

10. Additional formatting:

    a.  Right-click the ChoiceOfMeasure axis, Edit the Axis. & delete
        the text in the Title

    b.  Double Click Title of Worksheet and replace what is there with:

    c.  "You are now looking at: \<Parameters.MeasureOptions\>."

    d.  Use the Analytics tab, add an Average Line, setting the scope to
        Table, and Label to Custom (Computation \| Value).

11. Change the parameter values.

Now, you get the option of more than one view!!!
