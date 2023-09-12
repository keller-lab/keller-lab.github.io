
# Introduction

This repository contains the original source code for Keller Lab Group's webpage ([https://keller-lab.github.io](https://keller-lab.github.io)). Our codebase is not forked from other repositories. This approach provides us with the freedom to explore various ways to enhance and customize our webpage.

# Contribution

We highly encourage all members to actively contribute to the improvement of our group webpage. Your contributions can range from design enhancements, content updates, bug fixes, to adding new features. By collaborating together, we can create a more engaging and informative online presence for the Keller Lab Group.

Please feel free to submit pull requests, open issues, or share your ideas on how we can make our webpage even better. Your contributions are essential in maintaining an up-to-date and user-friendly online platform for our research group.

Thank you for being a part of our web development journey!

# How to Contribute

To edit or suggest edits to the webpage, follow these steps:

**1- Fork the Repository on GitHub:** Click the "Fork" button at the top right corner of this repository's page. This will create a copy of the repository in your GitHub account.

**2- Clone the Forked Repository:** Open the GitHub Desktop application and clone the forked repository to your local machine. You can do this by clicking the "Add" and then "Clone Repository..." button and selecting the repository from the list.

**3- Open the Webpage:** Use your preferred code editor (for example Visual Studio Code) to open the webpage code on your machine. You may want to choose "To contribute to the parent project".

**4- Make Your Edits:** You can make edits to content, design, or functionality, depending on your expertise and the nature of your contribution. (Please refer to the next section, if you want to add/move a member to/from the member page).

**5- Preview the Webpage:** Before submitting your edits, use Jekyll to preview the webpage and the suggested changes. You can use "bundle exec jekyll serve -w" to get a link to an offline version of the website. [Here is a useful link where you can learn how to do that](https://www.youtube.com/watch?v=EdFdxfIuEZk).

**6- Commit Your Changes:** After making your edits, commit the changes using GitHub Desktop. Provide a clear and concise commit message that describes the purpose of your changes.

**7- Push Changes to Your Fork:** Push your committed changes to your forked repository on GitHub. This will update the code in your fork with your edits.

**8- Create a Pull Request (PR):** Go to the original repository on GitHub and click the "New Pull Request" button. This will allow you to compare the changes you made in your fork with the original repository. Provide a descriptive title and additional context for your PR.

**9- Review and Collaboration:** Your PR will be reviewed by the maintainers of the original repository. 

**10- Merge Your Changes:** Once your PR is approved, it will be merged into the main repository. 

By following these steps, you can actively participate in improving our website and enhancing our online presence.



# Adding/Moving a Member from the Member's Page

Follow the steps 1-3 of **How to Contribute** to open the webpage in your text editor.

**If you want to add a new member to the website:**

1- Upload a 6"X 6" headshot to the "pics" folder.

2- In "people.html", find `<!-- Add a member -->`, copy the commented code, and change it using the member's information. Please assign a number (assign a unique number that follows the sequence of the previous members' numbers) to the new members and use that as `<member's_number>` in the code. `<member's_short_bio>` is approximately the first 120 characters of the member's bio. Please refer to previous members entries for examples. You can move that code between any two members as desired.

3- Similarly, in "style_people.css," find `/* Add a member */` and copy the commented code. Change the copied code using the member's assigned number from "people.html". Please refer to previous member entries for examples.

**If you want to move a member to the Alumna:**

1- In the 'people.html' file, delete the code section that was previously added for the member (please see step 2 of **If you want to add a new member to the website** for more info).

2- In "Alumni.html," find `<!-- Add a member -->`, copy the commented code, and change it using the member's information. Please refer to previous member entries for examples. The list is in alphabetical order. You can move that code between any two members as desired.

To submit these new adjustments to the website, follow steps 5 to 10 in **How to Contribute** section.

