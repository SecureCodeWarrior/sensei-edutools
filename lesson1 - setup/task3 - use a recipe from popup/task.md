# Use A Cookbook Recipe

The "SenseiEdutools" cookbook that you added from Github has a recipe called:

- "convert Hello World to Welcome to Sensei"

This will have marked the `return "Hello, World!";` line in the source code as having an error.

## Hover Over the Error

Hover the mouse over the line of code in error.

You should see a dialog that says `use Sensei to convert the String "Hello, World!"`

This is because the recipe "convert Hello World to Welcome to Sensei" found the String `Hello, World!` and is configured to report that as an error.

## Fix the Error Using the Hover Popup Dialog

Sensei allows us to create recipes that 'find' errors, and allow use to create QuickFixes for those errors. We can apply the QuickFix for this error in a number of ways.

- when you have hovered the mouse over the line of code and can see the dialog
- click on the link that reads `say "Welcome to Sensei!"`

The code should now change to ` return "Welcome to Sensei!";`.

Click the Check button to complete this task.


