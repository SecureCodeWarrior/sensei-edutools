# Add A Cookbook

Sensei uses Cookbooks of Recipes which are designed to help you with a particular technology or for your Team coding standards.

To help with this tutorial, we have created a Cookbook on GitHub that you can add to this project. In this lesson we will install it because we'll need it to complete the next task.

## To install the Cookbook.

Open the Sensei Cookbooks manager, either by:

- clicking on the "Sensei Cookbooks" tab
- choose "Recipe Editor" from the main "Sensei" menu

Now we want to add a reference to the Cookbook on GitHub.

- Click the "+" button to add a new cookbook.
- Give it a CookbookId to uniquely identify it in this project e.g. "SenseiEdutools"
- For the location, use the URL of our recipe repo:
    - `https://github.com/SecureCodeWarrior/sensei-edutools-recipes.git|main`
  
> **Note:**
> 
> _The Github url is the repo path, with the addition of the branch to use._
  
Once you've installed it, Sensei will start analysing your code in real-time to find any Recipes that match.

If you've done this correctly then you'll see the cookbook in the "Locally configured cookbooks" list, and when you start the next task you see some code that has been highlighted by Sensei as being in error.
