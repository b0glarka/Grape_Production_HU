## Peer Review

**Data Science 1**

**Fall 2025**

**Reviewer: Katharina Burtscher**

#### Reproducibility Report

For the analysis I did not have to change a single line of code and it ran without an error. Boga used a relative path to load the data, which means that even without knowing anything about the project, the folder structure or the data, I would have been able to reproduce the analysis.

There are only very few minor improvements that could be considered, even though some of them are more a question of taste.
* In my environment, both the requirements.txt and environment.yml didn't open, throwing an error that they are not encoded in UTF-8. However, this might be some incompatibility issue with my operating system, as my laptop is very old.
* I'm assuming the raw data is in the "docs" folder? In your tree it shows a "raw" folder, but unfortunately it must have gotten lost in the process. Overall the "docs" folder could have been more meaningfully named to give a clue of its contents.
* I personally like having multiple kernels to run and getting of a "feel" for the data. Your choice to run the entire analysis in one kernel is of course more sleek.

Overall, the Project is well structured and it is straightforward to navigate the folders. The README is coherent, covers all the necessary information in a well formated manner and immediately enables the collaborator to get started with the reproduction. The code includes plenty of explanations, so it's possible to follow every step Boga took in her analysis. I think this is an exemplary implementation of the the assignment.
