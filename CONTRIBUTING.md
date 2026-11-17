# Contributing to Apex Linux

Read the
[engineering standards](https://github.com/apex-linux/apex/blob/main/docs/engineering.md)
first. In short:

1.  Branch from `main`. Keep the branch to one purpose and merge it within
    two days.
2.  Run the repository's `just` recipes (`just lint`, `just test`) before
    you push. CI runs the same recipes.
3.  Open a pull request whose title is a commit subject: imperative mood,
    capitalized, no trailing period, 50 characters or fewer. Use the
    description to explain what changed and why.
4.  Merge with squash when CI is green.

Report bugs and propose features in the
[`apex` issue tracker](https://github.com/apex-linux/apex/issues).
