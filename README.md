# HTML Backing Up Changes

<iframe width="640" height="480" src="//www.youtube.com/embed/Sh4wSwzf7n0?rel=0&modestbranding=1" frameborder="0" allowfullscreen></iframe>

<p><a href="https://www.youtube.com/watch?v=Sh4wSwzf7n0">HTML Back Up Changes</a></p>

If you've been following along on these lessons using your own personal
repository, adding, committing and pushing at the end of each lesson, you've
maintained an excellent git workflow! Clone down your repository and checkout
the `main-pages` branch

```
git clone https://github.com/<your_username_here>/exceptional-realty
cd exceptional-realty
git fetch --all
git checkout main-pages
```

Most often, its better to make more commits rather than less. Commit code
whenever you've completed any particular thing you're proud of, or when you're
done with a specific task. It is possible to access any of these commits in the
future, in the event that you need to roll back to a previous version of a
repository, or want to look at some code from the past you've since removed.
More commits with specific messages regarding what was accomplished means a
clearer picture of the path you took to create a project.

Now that we've built out a functioning website on the `main-pages` branch, we
can go ahead and merge this branch to our `master`. To do this, checkout
`master`, then run `git merge main-pages`. This command will take whatever
branch you've listed at the end, and merge it with the branch you're currently
on (`master`).

Go ahead and add, commit and push up your `master` branch to your remote
repository. Now, if you want to continue to build this website, you have a
fully functioning `master` branch that you can pull down and branch off from
for the new features!

## Does this need an update?
 Please open a [GitHub issue](https://github.com/learn-co-curriculum/phrg-html-backing-up-changes/issues) or [pull-request](https://github.com/learn-co-curriculum/phrg-html-backing-up-changes/pulls). Provide a detailed description that explains the issue you have found or the change you are proposing. Then "@" mention your instructor on the issue or pull-request, and send them a link via Connect.

<p data-visibility='hidden'>PHRG HTML Backing Up Changes</p>
