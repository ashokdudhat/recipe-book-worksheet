# Recipe Book

1. Clone this repository to your exercises folder
2. Create a branch with the following naming convention: `<your_name>/solution` (replace `<your_name>` with your actual name i.e. for itamar it would be `itamar/solution`)
3. Please follow all the exercises below. After you solve each exercise, **DON'T FORGET TO MAKE A COMMIT**.
4. When you are done solving all of the exercises push your branch up to github, create a pull request, and assign Itamar and another person in the class to review it.
5. Review your team mate's work by commenting on their pull request, pay close attention to:

- Make sure there is one or more commits per exercise (at least six commits)
- Proper indentation of HTML elements
- HTML validity (by using the [w3c validation service](https://validator.w3.org/#validate_by_upload))
- Correctness of each assignment (according to your idea of the solution)

## Exercise I

- [x] In the `recipes` folder, create a new file with the basic html structure, with the following naming convention `<your_name>-recipe.html` (replace `<your_name>` with your actual name i.e. for itamar it would be `itamar-recipe.html`).
- [x] Create a meta tag with the name author and your name as the value
- [x] Change the title of the page to the name of the recipe.

---

## Exercise II

- [x] Find and/or download an image for your recipe, and put it in the `img` folder.
- [x] Add the image of your recipe to the html page, the fallback text for the image should be the name of the recipe, the image must be 500 px wide

---

## Exercise III

- [x] Under the image, add the main heading of your page. The heading should be the name of your recipe.
- [x] Add two secondary headings to your page. The first should say "Ingredients" and the second should say "Preparation".

---

## Exercise IV

- [x] Under the "Ingredients" heading, add an unordered list for the ingredients of your recipe
- [x] Under the "Preparation" heading, add an ordered list for the preparation of your recipe

---

## Bonus Tasks:

If your have already created a pull request and reviewed at least one of your team mates pull requests, create a new branch called `<your_name>/homepage` (replace `<your_name>` with your actual name i.e. for Itamar it would be `itamar/homepage`), and follow the tasks below.

> **Important**: Please create a commit for each task

- [ ] Create a new file in this folder: `index.html`
- [ ] Add the basic html structure to that file
- [ ] The title of the tab should be "The WebUp Recipe Book" when the file is opened in the browser
- [ ] Add one heading in the body tag with the same text as above "The WebUp Recipe Book"
- [ ] Add an unordered list to the body:
  - The unordered list should contain as many list items as members of the team.
  - Each list item should contain a link to a solution file with the href set to `recipes/<member_name>_recipe.html` (replace `<member_name>` with the name of a team member i.e. for Itamar it would be `recipes/itamar_recipe.html`)
