**[LAB Book partners up with Practical Tableau Book: Used for Tableau
Desktop Level 2]**

**This Lab book is Part 4 of 5 Parts**

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

2.  Create a new WORKBOOK. Use the Excel Sample Super Store as your data
    source, Double Click the ORDERS Table to obtain the Dimensions and
    Measures for this Workbook.

3.  Save and name the Workbook "PartThree.twbx". (There is a copy of
    this workbook in the WORKBOOKS folder that has the solutions for the
    labs.)

4.  Rename Sheet1 and call it "Icons". Color the sheet tab if desired.

5.  Get a new data source (icons.xlsx) in your Data Sources folder

6.  There is only one field called "Icon Name" -- Drag it to the Rows
    shelf

7.  Change your Automatic chart type to Shape on the Marks shelf

8.  Notice that Tableau assigned a shape to each of your Icon Names.
    Also notice you got a new legend to describe each shape.

9.  Click the Shape card

10. Under the "Select Shape Palette" Option click the arrow pointing
    down next to "Default" Look for your Sports Folder (if you do not
    see it, Click the "Reload Shapes" button at the bottom.

11. Assign each Sports Icon Name to a picture by clicking the name, then
    clicking the corresponding picture (EX: Women's Basketball to the
    icon that IS Women's Basketball).

12. When they are all associated, Click OK -- see each new custom Icon
    on your Worksheet.

13. Next, click the NEW DASHBOARD tab at the bottom of your Workbook

14. Name it "Icon Dashboard" and color it the same color as your Icon
    Worksheet (if you colored it)

15. Drag your only Worksheet (Icons) into it

16. Go to the "Dashboard" Menu above and choose "Actions" off the list

17. When in the Actions pop up, click "Add Action" at the bottom

18. Choose "Filter" off the list

19. Name this "Click Icons"

20. Under both SOURCE and TARGET, make sure that your "Icons" sheet is
    selected and be sure that your "Run Action On" option (right side of
    screen) is set to "Select". If it is not, Click "Select"

21. \*\*Also Notice the option that says \"Clearing the Selection Will"
    and notice the option is set to "Show All Values"

22. Click "OK" -- notice your new Filter Action in the Dialogue Box

23. Click "OK" again.

24. Click an Icon. Notice it will select that Icon and show it to you in
    a "Zoom" mode

25. To get back to all Icons, click in a white area around the image.
    This is because your option was set to "Show All Values" when
    choosing "Clearing the Selection" (from step 21).

**Chapter 48 - Exercise (What-If) - 8 Minutes -- Book Pages: 302-305**

1.  Get a new sheet and call it "What If". Color the sheet tab if
    desired.

2.  We will use the Sample Superstore (Orders Table)

3.  Right mouse click the white area underneath Measures and Select the
    option to "Create Parameter"

    a.  Name it "What If"

    b.  Change Type to Integer

    c.  Change the "Allowable Values" to Range

    d.  Click all three boxes (Minimum, Maximum, Step) and change
        Minimum to 0 (zero) and if necessary, change Maximum to 100.
        (Step should default to 1)

4.  Click OK

5.  Create a new calculated field:

    e.  Right Click the white area in "Measures"

    f.  Choose "Create Calculated Field"

    g.  Name it "What-If Sales"

    h.  Below, you can drag and drop your Sales Measure and your What-If
        Sales Parameter into the calculation as you type, or you can
        copy below: (or use Solution)

    i.  The calculation is: \[Sales\] \* (1 + \[What-If Sales\]

    j.  Click OK

6.  RIGHT CLICK the Order Date field and drag to the Column. In the Pop
    Up, choose the green (continuous) MONTH Order Date (4^th^ option
    from bottom)

7.  Drag your "Measure Values" Measure into the Rows shelf -- notice one
    of "each" Measure appears. In the end, you will only want the Sales
    measure and the "What-if Sales" measure here. The easiest way to
    accomplish this is to select "Discount" (The first measure), Then
    hold your Shift key down (and keep holding it down) and Select
    "Quantity" (so that it selects them both and everything in between).
    While you still have your SHIFT key held down, Right click into one
    of those selected fields and choose "Remove". All but Sales and
    What-If Sales should be removed.

8.  Notice that your Measure Names dimension will move to the FILTER
    shelf and if you edit it (just to look at it), you will notice it
    has been filtered for Sales and What-If Sales. -- also notice that
    the Measure Names appears in the Detail card on the Marks shelf.

9.  Move the Measure Names from Detail to the Color card on the Marks
    shelf -- you will now have two colored lines in your view. If
    desired, click on the Color card and re-associate Sales and What-if
    Sales to your desired color(s) and click OK

10. One thing left!!!! Right mouse click your parameter and "Show
    Parameter Control". Once that pops up on the top right of your view,
    you can slide the slider to change the Sales and the What-if Sales
    to show the "forecast" of sales if the What-If changes.

**Chapter 49 - Exercise (Alerts) - 15 Minutes -- Book Pages: 308**

1.  Get a new sheet and call it "Alerts". Color the sheet tab if
    desired.

2.  Right Click Order Date Dimension onto the Column shelf and choose
    Month (continuous)

3.  Drag Sales Measure to the Row shelf

4.  Create a Parameter as follows:

    a.  Name: Set Date Aggregation

    b.  Type: String

    c.  Choose "List" from Available Values

    d.  Type in your custom list by clicking first into the value field,
        then double clicking the Display field. Set them up as follows:
        (be sure to use all small letters on the Value (left) side.

| **13. day**       | **14. Day**     |
|:----------------  | :-------------- |
| **5.  week**      | **6.  Week**    |
| **7.  quarter**   | **8.  Quarter** |
| **9.  month**     | **10. Month**   |
| **11. year**      | **12. Year**    |



15. Create a calculation: Name it "Date Choice". Calc: DATETRUNC(\[Set
    Date Aggregation\], \[Order Date\])

16. Remove current ORDER DATE pill from column. Replace with new "Date
    Choice" Dimension.

17. Right Click Order Date to the Text card on the Marks shelf and
    choose MIN(\[Order Date\]) (continuous) off the list.

18. Right Click Order Date to the Text card on the Marks shelf and
    choose MAX(\[Order Date\]) (continuous) off the list.

19. Drag your Set Date Aggregation to the Text card on the Marks shelf

20. Click into the LABEL card (with the thought to format TEXT on the
    top of your view that will contain an alert about the data people
    are viewing). Make these choices:

    e.  Click on the TEXT field. This will open a pop up box. Make it
        look like this:

    f.  Shows dates from : \<MIN(Order Date)\> to: \<MAX(Order Date)\>

       i.  by : \<Parameters.Set Date Parameter\>

       ii. Hint: if you accidentally delete any of the fields, you can
            use the INSERT tool to get them back (take a look by
            clicking, to see what is available)

       iii. Format the text as desired and then click OK (once)

    g.  Back in the Label card:

       iv. Click on "Line Ends" -- Take middle check at bottom off
            (Label Start of Line)

       v.  In the Alignment section, click where you want the text to
           appear (for example: Left, Top) - it will appear as "custom"

**Chapter 50 - Exercise (Alerts 2) - 5 Minutes -- Book Pages: 309**

1.  Get a new sheet and call it "Alerts 2" Color the sheet tab if
    desired.

2.  Right Click Order Date Dimension to Column shelf and change to green
    MONTH(Order Date) Continuous.

3.  Drag Sales Measure to Row shelf

4.  Create a calculation:

    a.  Name it : Dynamic Label Alert

    b.  Calc:

> IF SUM(\[Sales\]) \>= 9700 THEN \" Extra Great\"
>
> ELSEIF Sum(\[Sales\]) \<= 12000 then \" Extra Terrible\"
>
> ELSE NULL
>
> END

c.  Drag your new Dynamic Label Alert to the Label card. Click the label
    card and format as desired (color? Red?)

<!-- -->

5.  Labels will automatically appear

**Chapter 51 - Exercise (Alert 3) - 5 Minutes -- Book Pages: 310-311**

1.  Get a new sheet and call it "Alerts 3" Color the sheet tab if
    desired.

2.  Drag Category and Ship Mode to Column shelf

3.  Drag Region to Row shelf

4.  On Marks card, Select Shape

5.  Create a calculation named: KPI Ratio:

> sum(\[Profit\]) / sum(\[Sales\])

6.  Create a second calculation named KPI Ratio Color and Shape:

> If \[KPI Ratio Numbers\] \> .12 then \"Green\"
>
> Elseif \[KPI Ratio Numbers\] \> .7 then \"Yellow\"
>
> Else \"Red\"
>
> End

7.  Drag KPI to Color. Then Edit the Color Card. Pick \"Traffic
    Light\" - Take the time to associate\"green\" with green color,
    \"red\" with red color\", \"yellow\" with yellow color.

8.  Next take the KPI Color and Shape and Drag it a second time onto the
    Shapes Card. Choose \"Thin Arrows\" from the palette Choices. Take
    the time to associate \"Green\" with UP arrow, \"Red\" with DOWN
    arrow, and \"Yellow\" with \"Right Arrow\"

9.  Expand View to \"Entire View\" just while we do the next part

10. Change the Default property of KPI Ration Numbers to \"Percent\"
    with NO decimal places (right click and go to default properties,
    number, then choose percent, and no decimal places)

11. Drag KPI Ratio Numbers to \"Text\" Card. Then Right click and format
    column to \"RIGHT\" - so that it moves to the right of the arrow.
