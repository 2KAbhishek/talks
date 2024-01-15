# Git Interactive Rebase Guide 

**Abhishek Keshri**

Master the art of crafting a clean and cohesive commit history

---

## Use Cases 

1. **Cleaning Up History:** Remove unnecessary commits.
2. **Reordering Commits:** Rearrange commits for logical progression.
3. **Feature Branch Refinement:** Polish feature branches before merging.
4. **Interactive Squashing:** Condense multiple commits into a single, cohesive one.
5. **Fixing Mistakes:** Edit or reorder commits to rectify errors.

---

## Start Interactive Rebase 

```bash
git rebase -i <base_commit>
```

---

## Actions 

- **Pick (p):** Keep the commit as is.
- **Reword (r):** Change the commit message.
- **Squash (s):** Combine with the previous commit.
- **Fixup (f):** Similar to squash, discarding the commit message.
- **Drop (d):** Remove the commit.
- **Edit (e):** Pause for changes.

> _DEMO_

---

## Best Practices 

1. **Keep It Simple:** Aim for clear, concise commits.
2. **Logical Order:** Arrange commits for logical flow.
3. **Use Edit Wisely:** Make necessary changes, but avoid unnecessary alterations.
4. **Regular Rebasings:** Keep feature branches up-to-date with the main branch.

---

## Tips for Success 

- **Backup:** Always create a backup branch before rebasing.
- **Collaboration:** Communicate with your team before rebasing shared branches.
- **Practice:** Experiment with interactive rebase in a safe environment.

---

## References 

- [Git Interactive Rebase Documentation](https://git-scm.com/docs/git-rebase#_interactive_mode)
- [Pro Git Book — Rewriting History](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History)

- [Slides](https://github.com/2KAbhishek/talks/blob/main/interactive-rebase-guide.md)

---

## Thanks 

