
All contributions are welcome, please send a pull request and I will try to review and merge it as soon as possible.

### How to contribute?

1. Fork this repository.
2. Clone this repository locally on your machine and move into the slack-themes folder.
4. Create a branch with a name appropriate to the task, preferably the theme name if you are adding a custom theme.
6. Commit the changes to that branch in your cloned repository. Pushed the changes to your forked repository branch with the same name.
7. Create a Pull Request and wait for approval/comments.


### Commit message guidelines

- Commit messages must have a subject line and may have body copy. These must be separated by a blank line.
- The subject line must not exceed 50 characters
- The subject line should be capitalized and must not end in a period
- The subject line must be written in imperative mood (*Fix*, not *Fixed* / *Fixes* etc.)
- The body copy must be wrapped at 72 columns
- The body copy must only contain explanations as to *what* and *why*, never *how*. The latter belongs in documentation and implementation.

### Example

This is an example of a complete commit message that adheres to this standard. Parts of this are optional, so read on.

```txt
Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
```

### Subject and Body

- A body copy is not required for commits that are overly simple. If you find yourself repeating the subject line in the body copy, it's a good sign that the body might be superfluous.

To perform a *simple* commit, a single command if sufficient:

```sh
$ git commit -m "Fix my subject line style"
```

### Adding your custom theme

1. Add it to the custom themes section similar to how default themes have been added.
2. Make sure the add a screenshot as well following the guidelines the section below.
3. Name your theme as per your wish, add a link to your Github profile beside the theme name in parentheses so every using it is aware of the creator.
4. Refrain from using foul, offensive or indecent language in custom theme names.

### Adding screenshots for existing themes - make sure to follow these guidelines:

1. Make sure the screenshot size is small so that users with slow internet connection can open this README without much hassle.
2. Most importantly the text in the screenshot should be decent and not be offensive in any way. Such screenshots will not pass PR approval.
3. Add the screenshots under `assets/images/` folder where the name of the screenshot should be the name of the theme. e.g. The screenshot for aubergine should be aubergine.jpg or aubergine.png or any other extension that works best. For theme names with multiple words use hyphenated strings e.g. choco-mint
4. Add a collapsible section with message `Click to see screenshot` under each hex code and add the screenshot inside the collapsible section. This should be done so that all collapsible sections are closed whenever a user opens the README and is able to scroll through easily without having to see all screenshots.
