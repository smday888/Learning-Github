# Learning-Github
Documentation of my experience with the github welcome tutorial.

I have made it this far - editing a version of my readme document in a branch of the master branch of this repository. 

Initial confusion: I thought I named this branch readme-edits, but here I see I am editing something called readme.md. Is the .md a standard extension for branches? I suppose this will become clear as I continue to work on this.

Thus far I have learned that:
1. Each "project" requires the creation of a "repository".
2. Each repository has a "master branch" and potentially many other "branches" that or may not eventually be merged with the master branch to effectively modify the repository.
3. Each branch that is eventually "committed" should (must?) include a description of the changes made, the reasons for these changes, etc.

I notice that an automatic numbering editor took over in the above list. I wonder what other editing capabilities this basic editor has. I will learn.

Now I have "committed" the edits to the readme file (the creation of the readme file really), which I had initially thought would make changes to the master branch. Not so. There are subsequent steps (yes, plural) of "opening" a "pull request", which allows one to view the branch edits as compared with the master branch (differences being highlighted in green). Once one is satisfied that the changes are good, one must select a big green button to "create" the "pull request". One is not yet done, however. Another (bigger?) green button must be selected to again "create pull request". Finally, the pull request is created, and one has the option to "merge" the pull request. This was a simple change, and thus it was possible to simply merge with the master branch. I can imagine in more complicated situations, things would not be so simple.

I do not really understand why the process of "creating" a "pull request" has to be done twice. Merging was done once.

After I completed all of that, I tried to open a new branch so I could update my experiences. I called the new branch "readme-edits2". Unlike the original readme-edits which showed it was "under" (I think that's the word) the master branch, this time the program indicated my new branch readme-edits2 was equal to (or on the same level with) the master branch. I do not understand why this is. Quite confusing.

I will not try to commit these changes, then open a new pull request, then create pull request, then create pull request, then merge. I'm not sure how all this will work given that this branch is somehow on par with the master branch. This actually seems very counter-intuitive since the tutorial seemed to suggest that there was only one master branch and I thought therefore that every other branch must be below this. Well, here goes.

Well, that worked fine. And now I've started readme-edits3, and there seems to be no issue with this being equal or on the same level with master. I don't see that same message this time. Also, I note something that confused me with the original readme-edits: When one "commits" changes to this, there are two choices: (a) Commit directly to the master branch; or (b) create a new branch for this commit and start a pull request. However, if one chooses option (a), it doesn't really commit anything to the master branch. One must eventually open a pull request in order to eventually create a pull request and finally merge with master branch in order to actually commit any changes to the master branch. So I find this misleading.

I will leave this all now for a while (after committing these changes, then opening a pull request, creating a pull request, creating a pull request again, and finally mergeing that pull request with the master branch - all a bit comical it seems to me but I'm still convinced this is all a good way to keep track of changes especially in working collaboratively with others).

Well that was strange. I committed changes to readme-edits3 but when I opened the pull requests tab readme-edits3 was not an option for a pull request. I've come back to edit my readme-edits3 branch again to see if it shows up this time.

And I'm very confused now. This is my third attempt at edits3. I appears that the first two were actually committed to the master branch straight away. I apparently had somehow selected to create pull requests rather than branches the first two times. When selecting "branch" in the drop-down menu for "branch:master" and entering "readme-edits3" there is a green button that says "create pull request". I must have selected that, rather than the blue "create branch" button. This is a bit confusing. I note this time the buttons at the bottom have different choices: (a) commit directly to the readme-edits3 branch; or (b) create a new branch for this commit and start a pull request. Let me see if this works this time as it did with edits and edits2. Here I go again.

Okay, in edits4 now. And I have learned an important thing, which I consider an error in the tutorial. The tutorial says this:

To create a new branch

    Go to your new repository hello-world.
    Click the drop down at the top of the file list that says branch: master.
    Type a branch name, readme-edits, into the new branch text box.
    Select the blue Create branch box or hit “Enter” on your keyboard.

But if I hit "Enter", rather than selecting the blue "create branch box", it does not create a branch beneath master. It creates a branch "even" with master. Then if/when I commit changes to that branch, it makes the changes directly to master. This is why nothing shows up for edits3 when I eventually look to open a pull request.

I am satisfied I've completed the initial tutorial now - and found what I consider to be one misleading aspect to it.
