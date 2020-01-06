
### *collaborative github exercise:*
# **Welcome to the evolutionary lottery of skull and beak morphology**

<br>

> [**Beak and skull shapes in birds of prey (“raptors”) are strongly coupled and largely controlled by size.**](http://eprints.whiterose.ac.uk/99452/1/Bright%20et%20al.%202016_SelfArchive.pdf)

gif provided by the awesome **Jen Bright** [**@MorphobeakGeek**](https://twitter.com/MorphobeakGeek)!

![](gif.gif)

***

In this exercise we will use a github repo to collaboratively collate and simulate evolutionary trajectories for each participants' species body size using a simple brownian motion evolutionary model. This assumes evolutionary steps to progress comletely at random. You could say, it's a bit of lottery! 


## **our mission**

- Each participant will **create and contribute a file** specifying the parameters required to simulate and plot their species evolutionary trajectory. 
- We'll collect all participants' files in the master repo. 
- Once all trajectories are simulated they'll be plotted together. 
- Participants will then get to **see the skull and beak shape** corresponding to their species relative body size!



<br>


# **GO!**
[link to full session handout](https://annakrystalli.me/Mozfest_github-rstudio/evolottery.html)

#### **github:** fork 

- fork the repo into your own account
- copy repo url link local files to github repo 

<br>

#### **rstudio:** clone locally

- create new project
- checkout from version control/git
- paste github repo link

<br>

#### **rstudio:** create parameter `.R` script

A template is provided in the repo, in folder `/params` named `params_tmpl.R`. Open the `params_tmpl.R` and **save as** to create a duplicate template. Name the template using the name of your species. 

##### **!! PLEASE DO NOT EDIT THE `params_tmpl.R` FILE !!**

<br>

#### **rstudio:** edit your params `.R` script

The parameters each participants need to supply are:

- **`sig2`:** A numeric value greater than 0 but smaller than 5

- **`species.name`:** a character string e.g. `"anas_krystallinus"`. Try to create a species name out of your name!

- **`color`:** e.g. `"red"`, `"#FFFFFF"` (tip: **pick a color using Rstudio's Color picker:**)


<img src="assets/colour_picker.png" width="500px" />


<br>

#### **rstudio:** save and commit the changes

- Use the git tab, tick the box next to **your new script ONLY** and commit. 

- Supply a descriptive message of the commit.

<br>

#### **rstudio:** push to github
- push your changes to github

<br>

#### **github:** create pull request
 - create a pull request to merge your changes to the master repo
 
#### **github:** check to see my response to your request
 - most likely it'll be a thumbs up! But I might also **request a correction** if I spot an error.

<br>

***

### Once all parameters are collated, look out for the [results](http://rpubs.com/annakrystalli/278074)!

### Links to previous evolution lottery sessions:
 
 - [**Mozfest Github :heart: Rstudio session**](https://rpubs.com/annakrystalli/MozFest_EvoLottery2)
 - [**ISBE Reproducibility Symposium**](https://malikaihle.wordpress.com/openscienceworkshop/program/): [evolutionary lottery](http://rpubs.com/annakrystalli/200121)
 - [**UNAM OpenScience workshop series**](https://annakrystalli.github.io/UNAM/index.html): [evolutionary lottery](http://rpubs.com/annakrystalli/205756)
