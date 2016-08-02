# collaborative_github_exercise


In this exercise we will use the repo to collaboratively generate and collate trait evolution time-series through github.

***

## your mission

Each participant will create and contribute a file specifying the parameters to generate and plot a trendline for their species.

<br>

#### github: fork 

- fork the repo into your own account
- copy repo url link local files to github repo 

<br>

#### rstudio: clone locally

- create new project
- checkout from version control/git
- paste github repo link

<br>

#### rstudio: create parameter `.R` script

A template is provided in the repo, in folder `/params` named `params_tmpl.R`. Open the `params_tmpl.R` and **save as** to create a duplicate template. Name the template using the name of your species. 

<br>

#### rstudio: edit your params `.R` script

The parameters each participants need to supply are:

- **`sig2`:** A numeric value greater than 0 but smaller than 5

- **`species.name`:** a character string e.g. `"anas_krystallinus"`. Try to create a species name out of your name!

- **`color`:** e.g. `"red"`

    
pick a color at: <http://www.stat.columbia.edu/~tzheng/files/Rcolor.pdf>

<br>

#### rstudio: save and commit the changes

- Use the git tab, tick the box next to your new script and commit. 

- Supply a descriptive message of the commit.

<br>

#### rstudio: push to github
- push your changes to github

<br>

#### github: create pull request

<br>

***

### outcome:

 After merging all participant pull requests, we'll run the code to generate the trendlines and plot all species!