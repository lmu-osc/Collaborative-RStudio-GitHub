# Commit changes locally

***
To avoid conflict during this collaborative coding exercice (i.e. contributors editing the same line of code at the same time), today, we will work on different files altogether. To avoid conflict in future projects, nothing replaces good communication. If need be, you could still [resolve conflicts using the command line](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-using-the-command-line). Today, you will copy a template file and edit your own copy.

1. RStdudio: select `params/params_tmpl.R` and click 'More' and 'Copy'

<!--     ![](./assets/params-params_tmpl.png)  -->

2. RStdudio: 
* **rstudio:** create and edit your `.R` script

A template is provided in the repo, in folder `/params` named `params_tmpl.R`. Open the `params_tmpl.R` and **save as** to create a duplicate template. Name the template using the name of your species. 

 **!! PLEASE DO NOT EDIT THE `params_tmpl.R` FILE !!**

The parameters each participants need to supply are:

- **`sig2`:** A numeric value greater than 0 but smaller than 5

- **`species.name`:** a character string e.g. `"anas_krystallinus"`. Try to create a species name out of your name!

- **`color`:** e.g. `"red"`, `"#FFFFFF"` (tip: **pick a color using Rstudio's Color picker:**)


<img src="assets/colour_picker.png" width="500px" />

* **rstudio:** save and commit the changes

- Use the git tab, tick the box next to **your new script ONLY** and commit. 

- Supply a descriptive message of the commit.


***