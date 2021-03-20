# git-github-practice-exercises

These are challenges for practicing the concepts we talked about in our training (<a href="https://frontend.ro/evenimente/git-incepatori" rel="nofollow">Git & GitHub training</a>)

## Challenges

To have the best results, **solve the challenges in the order we've written them**:

1. **Fork** this repo
2. `clone` the repo on your PC
3. Add your name inside *exercitii.html* and *index.html* (you'll find a section for *your name* inside *exercitii.html*. You'll have to copy this one into *index*)
4. Add **one commit** for each modified file. Let's keep the same convention as last time: `[username] - description`
5. `push` these changes on *master*
6. Create a new branch named **challenges**
7. Add in *exercitii.html* a list with all the comands used so far. (you'll find an example of this list in the same page)
8. `commit` the new modifications BUT don't push yet
9. We're about to use the `amend` command. Let's add this one to the list as well.
10. We don't want to make another commit. Instead we want to add it to the previous one. Let's run `add` and then `commit --amend`.
11. `push` changes in the remote repo
12. Add in *exercitii.html* the number of commits so far. (use the same "component" as for the name)
13. `push` changes in the remote repo
14. We're wondering whether instead of the commands used so far we should add a description about ourselves. Let's create a new branch named **challenges-v2** where we're gonna experiement with this.
15. `push` the branch in the remote repo. Now we should have 3.
16. `revert` the commit with the commands list
17. Add a small description about yourself. Then `push` in the remote repo
18. Connect `GitHub pages` to your new branch from this repo.
19. Navigate to the deplyed repo and see the result so far
20. We decide to keep the old version. Let's delete the `challenges-v2` branch from `remote` as well as from `local`.
21. We're ready to merge the `challenges` branch into master. Let's add one of the trainers as a contributor
22. Make a `PR` to master
23. After approval, merge it.
24. Change `GitHub pages` to the `master` branch and see your final result.

---

25. If everything is approved by the trainer, create a new branch named after your **username**.
26. Add a card with info about yourself in the *finalisti.html* page.
27. Create a PR into the original repo
28. Celebrate! 🎉

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
    Numele tău:
  </label>
  <p>
    Jon Doe
  </p>
</div>
```