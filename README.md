# Cpt4IncomeTax

Extra 4-3 Develop the Income Tax Calculator

In this exercise, you’ll use nested if statements and arithmetic expressions to calculate the federal income tax that is owed for a taxable income amount.

This is the 2020 table for the federal income tax on individuals that you should use for calculating the tax:

Taxable income
Income tax
$0 plus 10%
$ 987.50 plus 12% $4,617.50 plus 22% $14,605.50 plus 24% $33,271.50 plus 32% $47,367.50 plus 35% $156,235.00 plus 37%
Over...
$0 $ 9,875 $40,125 $85,525 $163,300 $207,350 $518,400
But not over...
$ 9,875 $40,125 $85,525
$163,300 $207,350 $518,400
Of excess over...
$0 $ 9,875 $40,125 $85,525 $163,300 $207,350 $518,400

1. Download the zip file on canvas.
file and js file that are also provided. Make sure to save them all in the same folder.
Note that the JavaScript file has some starting JavaScript code for this application, including the $() function and a DOMContentLoaded event handler that attaches a function named processEntry() to the click event of the Calculate button and moves the focus to the first text box.

2. Code the processEntry() function. It should get the user’s entry and make sure it’s a valid number greater than zero. If it isn’t valid, it should display an error message. If it is valid, it should pass the value to a function named calculateTax(), which should return the tax amount. That amount should then be displayed in the second text box. The focus should be moved to the first text box whether or not the entry is valid.

3. Code the calculateTax() function. To start, just write the code for calculating the tax for any amount within the first two brackets in the table above. The user’s entry should be converted to an integer, and the tax should be rounded to two decimal places. To test this, use income values of 9875 and 40125, which should display taxable amounts of 987.50 and 4,617.50.

4. Add the JavaScript code for the next tax bracket. (use else if statements to add the tax brackets)Then, add the JavaScript code for the remaining tax brackets. Test it as you go.

5. Once all your files are completed you will upload them to a Github Pages repository and submit a link to your index page so I can test your application. Make sure you test it before submitting the link.
