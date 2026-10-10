# Working on Word Salad

## Who you're working with

Jon, the owner of this repo, is not technical. Word Salad is a low-stakes, just-for-fun website. Jon only interacts with this project through Claude, so Jon won't be reviewing diffs, merging pull requests, or running anything directly.

## Ship by default

Unless Jon says otherwise, push every finished change straight to production. Don't wait for Jon to say "merge" and don't leave it for Jon to do.

- Production is the `main` branch. GitHub Pages republishes https://wordsalad.ink/ from `main` within a minute or two of a push.
- If a session gives you a working branch, do the work there, then open a pull request into `main` and merge it yourself (or push the same commits to `main`). Either way, the change should be live on `main` by the end of the task.
- After shipping, tell Jon in plain language what changed and that it's live, with the link to the site.

## When to pause instead

Ask Jon before shipping only if Jon asks you to hold off, or if you think a change genuinely needs a second look. Examples: deleting or replacing a lot of content, changing the domain or hosting setup (`CNAME`, Pages settings), anything that could take the site down, or anything touching secrets, payments, or personal data. When you do pause, explain the concern in plain, non-technical terms and offer a simple yes/no choice.

## Writing for Jon

Keep explanations short and jargon-free. Don't use em-dashes, and don't use "It's not X. It's Y." style constructions.
