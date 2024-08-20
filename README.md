# Computer Security: CS 161 Course Textbook

This is the source for the CS188 Course Notes. It is built through Github Pages.

All code comes from the [CS 161 course textbook](https://textbook.cs161.org), the original repository can be found [here](https://github.com/cs161-staff/textbook).

# Source Code Formatting

This repository has auto-formatting enabled. The preferred way to format source is through Prettier on your local machine. Install Node on your computer, run `npm install -g yarn`, and then run `yarn`. To format code, use the `yarn prettier` command, which will automatically format all .md and .html files.

There is also a GitHub Action to format code which can be dispatched manually. Go to the Actions tab, find the Auto-Format Source action, and manually trigger a workflow dispatch against the target branch.

A CI check is enabled which runs Prettier and fails if Prettier detects any formatting errors.
