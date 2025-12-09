---
title: How To Contribute
parent: Home
layout: default
nav_order: 2

---

The OpenAT design guide is a living document. We welcome improvements from people with disabilities, makers, disability professionals, engineers, and anyone designing OpenAT. This section includes instructions for making a correction or an improvement to an existing page, as well as instructions on how to add a new page to add something new to the guide.

You can contribute in two main ways:

1. **Suggest a correction or improvement** (e.g., better dimensions, clearer instructions).
2. **Add a new page** for a component or design element that is missing.

# Suggest a correction or improvement

If after testing a dimension or step in this guide, you find a better dimension or set of steps for a page in the guide, you can raise a GitHub issue to change the dimension in the guide.

To do so, click [this link](https://github.com/makersmakingchange/OpenAT_Design_Guide/issues). From here, click on the green 'New Issue' button at the top right. Give the issue a title that explains what feature in what part need to be changed (i.e., "Changing threaded hole diameter for #4 sheet metal screw") then fill out the issue description with more information about what you want to change, and why you think it needs changing.


# Adding a new page

If you have something that you think should be added to the design guide, you can create a pull request to add a page to the guide.

To do so, click [this link](https://github.com/makersmakingchange/OpenAT_Design_Guide/tree/Github-Pages-Version) to go to the project repository. Create a local copy of the repository, then copy the template.md file. Paste the copy into either the Commercial_Components folder or the Design_Elements_For_3D_Printed_Parts folder, depending on what you want to add to the guide. Once you have copied the template to the correct location, open the file and begin filling it out. 

This file, aside from the first 6 lines, is written in a language called Markdown. A basic Markdown syntax guide can be found [here](https://www.markdownguide.org/basic-syntax/)

The first 6 lines are the header, which gives the page its title, parent page, and navigation order. Change the title from template to something short but descriptive, keep the nav_order at 3, and change the parent to be either Commercial Components or Design Elements for 3D Printed Parts, depending on which folder you put the template in. Finally, fill in the rest of the template. The template was created from a commercial parts page, as that has the most sections, and sections can be removed or modified as needed for a Design Elements page.

Once you have created the page for your new entry, create a push request for the repository, and an MMC team member will review it and either add it to the guide, give feedback on what needs to be changed before adding it to the guide, or will not add it if the content is deemed inappropriate for the guide.

If you are unable to create a local version of the GitHub repo to modify the template file yourself, you can download and modify the template file as explained in the above instruction, then submit it through GitHub issues like in the Making a Correction section.

{: .note }
**Not comfortable with GitHub yet?**

That’s okay! You can still help. Open an issue describing your suggestion in plain language, or contact the Makers Making Change team with your notes, measurements, or photos. We can help turn it into a page in the guide.