### Information Studies (IS) Master Thesis LaTeX Template
This is the official LaTeX template for your Information Studies and Data Science MSc thesis. It includes all the files necessary for writing a great thesis and should streamline the formatting process so that you can focus on what is important: the content.
Official University Guideline[UvA Information Studies programme](https://www.uva.nl , 
Faculty: https://www.uva.nl/en/about-the-uva/organisation/faculties/faculty-of-science/faculty-of-science.html ,
Template maintainer: https://www.uva.nl/shared-content/programmas/en/masters/information-studies/information-studies.html) 

The folder structure follows the expected thesis structure:
- **Abstract:** A summary of results should be included. Avoid citations. Maximum length is 200 words.
- **Introduction:** Mention the scientific field, problem statement, research gap, and each research question. 
- **Related Work:** Your work needs to be grounded and compared to earlier work and the state-of-the-art.
Write about your related work here.
- **Methodology:** Focus on what you add to the existing method. Explain what you will do and why (and how).
Write about your methodology here. Here, you should also present all the settings used in your experiments and your experimental setup. Everything you do should be reproducible.
- **Results:** Give the outcomes for each research question in the form of a table or graphic (with caption).
Write about your results here.
- **Discussion:** Compare your results with the state-of-the-art and reflect upon the results and limitations of the study.
Write your discussion here. Furthermore, give an outlook on what could be added to your work or what further research it could enable.
- **Conclusion:** Answer each research question and explain how the limitations of the study qualify the conclusion.

This structure is flexible, but in general, this is how not only a thesis but also papers and great research work are structured.

## Importing this template to Overleaf
Simply download the `latex-template.zip`, which you can find in the root folder of this repository, and head over to Overleaf. There, you can create a new `Upload Project` which will ask you to upload a zip file. Select the `latex-template.zip` you have downloaded, and that's it! We might be adding the template to the Overleaf Gallery, but for now, this is the preferred workflow.

## Working offline
You can use Overleaf to work offline as well. However, this will require you to install a LaTeX compiler yourself on your machine and use Overleaf's `git` or `GitHub` functionality. Furthermore, you will need an editor such as Visual Studio Code, for example. If this mode of operation interests you, feel free to head over to: https://www.overleaf.com/learn/how-to/Working_Offline_in_Overleaf

## In Overleaf
Once you have imported the template into Overleaf, you should switch your main `tex` file to the one you are currently working on. You can do so by going to the `Menu` (top left) and selecting under `Main document` one of the three files in `setup`. The content you want to generate should be added to the respective `tex` files in the `sections` folder. Files in `setup`, `document-classes`, and the `latexmkrc` should not be altered without permission from the respective supervisor, examiner, and thesis coordinator, as the configured layout is the one you are supposed to be using (and submitting with).

## Zotero Integration - Citation/Reference Manager
There are links on Canvas (page linked below), but they are replicated here. Zotero integration is accomplished at the level of Overleaf's connection to Zotero (with your UVA email used in both cases).

https://canvas.uva.nl/courses/6056/files/10971181?module_item_id=2073316

Requirements: 

1. A desktop version of Zotero installed (Mac, Linux, or Windows is fine). https://www.zotero.org/

2. A Zotero account as well as the web picker, which is an add-on for a web browser of your choosing (use your UvA email to receive any benefit here). https://www.zotero.org/download/connectors

3. An Overleaf account (again, sign up with your UvA email to receive any benefits provided). https://www.overleaf.com/

4. Combined instructions are in the Overleaf documentation: https://www.overleaf.com/learn/how-to/How_to_link_Zotero_to_your_Overleaf_account

