# git-github-practice-exercises

These are challenges for practicing the concepts we talked about in our training (<a href="https://frontend.ro/evenimente/git-incepatori" rel="nofollow">Git & GitHub training</a>)

## Challenges

To have the best results, don't hurry and carefully read each challenge. Make sure you **solve them in order**:

1. **Fork** this repo
2. `clone` the repo on your PC
3. Add a new cell into the **grid** from *exercitii.html* and write your name or nickname in there.
4. Add the "Fill-in info" component in *index.html* and write your name or nickname in there. (you can find it's markup at the bottom of this page)
5. Add **one commit** for each modified file. Let's keep the same convention as last time: `[username] - description`
6. `push` these changes on *master*
7. Create a new branch named **challenges**
8. Add in *exercitii.html* a new cell with a photo of yourself. `commit` and `push` this code.
9. Add another cell with some short info about yourself. It can be a favorite hobby, your job title, or why you want to learn Git?! After you're done, `commit` and `push` this code as well.
10. Let's use the "Commands list" component and add a list of all the commands used so far in the grid. `commit` the new modifications BUT don't push yet
11. We're about to use the `amend` command. Let's add this one to the list as well.
12. We don't want to make another commit. Instead we want to add it to the previous one. Let's run `add` and then `commit --amend`.
13. `push` this newly edited commit in the remote repo
14. Add in *exercitii.html* a new cell with the number of commits so far.
15. `push` changes in the remote repo
16. We're wondering whether instead of the list of commands we should add a description about Git/GitHub. Let's create a new branch named **challenges-v2** where we're gonna experiement with this.
17. `push` the branch in the remote repo. Now you should have 3 branches total.
18. `revert` the commit with the commands list
19. Add a small description about Git. Then `push` in the remote repo
20. Connect `GitHub pages` to your new branch from this repo.
21. Navigate to the deplyed app and see the result so far
22. We decide to keep the old version. Let's delete the `challenges-v2` branch from `remote` as well as from `local`.
23. We're ready to merge the `challenges` branch into master. Let's add one of the trainers as a contributor
24. Make a `PR` to master
25. After approval, merge it.
26. Navigate to `master` and `pull` the changes locally.
27. Test that everything looks ok.
28. Change `GitHub pages` to the `master` branch and see your final result deployed.

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
    git log
  </li>
  <li>
    git add
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