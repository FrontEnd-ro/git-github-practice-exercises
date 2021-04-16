# git-github-practice-exercises

These are challenges for practicing the concepts we talked about in our training (<a href="https://frontend.ro/evenimente/git-incepatori" rel="nofollow">Git & GitHub training</a>)

## Challenges

To have the best results, don't hurry and carefully read each challenge. Make sure you **solve them in order**:

### Learning challenges

1. **Fork** this repo
2. `clone` the repo on your PC
3. Add a new cell into the **grid** from *prep.html* and write your name or nickname in there.
4. Add a new commit following the convention: `[username] - description`.
5. Push those changes on *master*
6. Add a photo of youself inside the `assets/participants` folder. Let's name it after your `username`.
7. Add that photo to the cell from  **step 3**.
8. Add **one commit** for each modified file. Let's keep the same convention as last time: `[username] - description`.
9. Push both commits on *master*.
10. Create a new branch from *master* named **prep-challenges**

--- From now on work on this new branch

11. Add in *prep.html* a new cell with a description of yourself. 
12. `commit` and `push` this new cell.
13. Add one of the trainers as a contributor in your project
14. The trainer will add in *prep.html* a new cell with a photo of himself/herself.
15. Trainer pushes on **master** directly.
16. Create a PR (Pull Request) to add your code in **master**.
17. Fix the *merge conflicts*
18. Merge branch. Now on master will be both descriptions!
19. Hooray! You've finished the learning challenges. You can move on to the next which you'll implement on your own.
### <img src="https://www.pngitem.com/pimgs/m/80-800968_vscode-visual-studio-logo-png-transparent-png.png" width="25" align="center"> Practice challenges #1 (via VSCode)

1. Move to the *master* branch of the repo.
2. Create a new branch called **vscode**.
3. Add a new cell into the **grid** from *exercitii.html* and write your name or nickname in there.
4. Add the "Fill-in info" component in *index.html* and write your name or nickname in there. (you can find it's markup at the bottom of this page)
5. Add **one commit** for each modified file. Let's keep the same convention as last time: `[username] - description`
6. `push` these changes on *master*
7. Create a new branch from the current one (vscode) named **challenges**

--- From now on work on this new branch

8. Add in *exercitii.html* a new cell with a photo of yourself. `commit` and `push` this code.
9. Add another cell with some short info about yourself. It can be a favorite hobby, your job title, or why you want to learn Git?! After you're done, `commit` and `push` this code as well.
10. Let's use the "Commands list" component and add a list of all the actions used so far in the grid.
11. `commit` and `push` the new modifications
12. Add in *exercitii.html* a new cell with the number of commits you've done so far.
13. `commit` and `push` changes in the remote repo
15. We're wondering whether instead of the list of actions we should add a description about Git/GitHub. Let's create a new branch named **challenges-v2** where we're gonna experiement with this.

--- From now on work on this new branch

16. `push` the branch in the remote repo. Now you should have 3 branches total.
17. `revert` the commit with the actions list
18. Add a small description about Git inside a new cell from *exercitii.html*. Then `push` in the remote repo
19. We decide to keep the old version.
20. Make a `PR` to `vscode` from `challenges` branch.
21. After approval, merge it.
22. Navigate to `vscode` branch and `pull` the changes locally.
23. Test that everything looks ok.
24. Done! 💪

### <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" width="25" align="center"> Practice challenges #2 (via CLI)

0. Create a new branch from **master** named *cli*.
1. Add a new cell into the **grid** from *exercitii.html* and write your name or nickname in there.
2. Add the "Fill-in info" component in *index.html* and write your name or nickname in there. (you can find it's markup at the bottom of this page)
3. Add **one commit** for each modified file. Let's keep the same convention as last time: `[username] - description`
4. `push` these changes on *cli*
5. Create a new branch named **challenges**

--- From now on work on this new branch

6. Add in *exercitii.html* a new cell with a photo of yourself. `commit` and `push` this code.
7. Add another cell with some short info about yourself. It can be a favorite hobby, your job title, or why you want to learn Git?! After you're done, `commit` and `push` this code as well.
8. Let's use the "Commands list" component and add a list of all the commands used so far in the grid. `commit` the new modifications BUT don't push yet
9. We're about to use the `amend` command. Let's add this one to the list as well.
10. We don't want to make another commit. Instead we want to add it to the previous one. Let's run `add` and then `commit --amend`.
11. `push` this newly edited commit in the remote repo
12. Add in *exercitii.html* a new cell with the number of commits so far.
13. `push` changes in the remote repo
14. We're wondering whether instead of the list of commands we should add a description about Git/GitHub. Let's create a new branch named **challenges-v2** where we're gonna experiement with this.

--- From now on work on this new branch

15. `push` the branch in the remote repo. Now you should have 3 branches total.
16. `revert` the commit with the commands list
17. Add a small description about Git. Then `push` in the remote repo
18. Connect `GitHub pages` to your new branch from this repo.
19. Navigate to the deplyed app and see the result so far
20. We decide to keep the old version. Let's delete the `challenges-v2` branch from `remote` as well as from `local`.
21. We're ready to merge the `challenges` branch into master. Let's add one of the trainers as a contributor
22. Make a `PR` to master
23. After approval, merge it.
24. Navigate to `master` and `pull` the changes locally.
25. Test that everything looks ok.
26. Change `GitHub pages` to the `master` branch and see your final result deployed.
---

After trainer approval:


29. On master, "navigate back" to the last commit by us. You'll have to use `checkout`.
30. Create a new branch from here named after your **username**.
31. Add a card with info about yourself in the *finalisti.html* page.
32. Create a PR into the original repo
33. We merge & celebrate! 🎉

## Components

### Commands list

```html
<ol class="commands-list my-5">
  <li>
    commit
  </li>
  <li>
    push
  </li>
  <li>
    pull
  </li>
</ol>
```


### Fill-in info

```html
<div class="fill-in-info">
  <label>
    Numele meu:
  </label>
  <p>
    Jon Doe
  </p>
</div>
```