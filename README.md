# OpenOffice template for printing checks

The template for printing checks is an OpenDocument spreadsheet file that you can use to print a check onto a sheet of laser or inkjet check paper (like [this type of paper](http://www.amazon.com/gp/product/B00L3NC8A8)). 
The template is set up to print the check at the top of the page, and details about the check at the bottom, which is typically the part that can be separated via perforation.

Note that this template is localized to the United States.

This file is free to use, modify, or distribute.

Before you begin
----------------
1. Download and install the [free MICR TrueType font from Digital Graphics Labs](https://github.com/andrewstellman/excel-check-printing/blob/master/digital-graphics-labs_micr-encoding.zip?raw=true)

Prepare the template
--------------------
1. Download the [check printing template file](https://github.com/WorksOnMyBox/excel-check-printing/blob/master/Check%20printing%20template.ods)
2. (Optional) Download the [Accounts Template File](https://github.com/WorksOnMyBox/excel-check-printing/blob/master/Accounts%20-%20template.ods) and save as *Accounts.ods* in the same directory.
	- Alternatively, show the *Accounts* sheet in the check template and replace the cells with your information.
3. Open the *Accounts* file and add your information. This keeps your information separate from the template. I recommend maintaining the Sample account as whatever account is selected will be saved to the template if it's saved.
4. Open the *Check printing template* and click ok.  There are no macros, so the warning that macros will not be run is fine. 
5. You will be prompted to allow updating. Allow this to bring in your information from the *Accounts* file.
6. Use the dropdown list in cell 34 to choose your bank's location
7. Save the template

Using the template
------------------
1. Open the template you saved in step 7 above
2. Set the memo in cell F23
3. Set the check number in cell F24 - make sure this is a new number that has not been used on a check before
4. Set the check's "pay to the order of" recipient in cell F25
5. Set the check amount in cell F26 (do not include the dollar sign)
6. Print/save to a PDF
7. Open the PDF and verify that it looks correct
8. Print the PDF onto a blank check
9. Save the PDF as a record of your check

About
-----
This template is forked from [Andrew Stellman's excel-check-printing template](https://github.com/andrewstellman/excel-check-printing).
The modifications were made primarily for my needs and for LibreOffice. Excel does not appear to like my work, so if you need an Excel version I recommend using the original version.