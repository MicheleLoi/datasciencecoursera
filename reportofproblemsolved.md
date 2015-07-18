By mistake I had synched the original repo of "datascientist" with my "datasciencecoursera" local directory, instead of forking it first on github, and then synching the forked repo with my "datascience" local directory. 
As a result, I had a README.md file in that directory that wasn't the one I had originally created with the datasciencecoursera repo, but the one copied from the datascientist repo.
To go back to the original state in the "dasciencesciencecoursera" directory, including the files I had created for that repo, I did the following:
1. I selected the datasciencedirectory
2. git remote -v, to show me connetions with remote repos
3. git showed me that "upstream" was set with the http address of the original datascience repo
4. to return to the original situation: git remove upstream

checking the situation with git remote -v showed me th problem was solved
opening the file with a text editor showed me I was back to the original README.md file.

P.S. I should learn the technical terms for "synch" or "upload" a repo.