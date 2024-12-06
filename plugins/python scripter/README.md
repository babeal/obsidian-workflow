# Python Scripter Scripts

Instructions for setting up `Obsidian Workflow`

1. Make sure you are using the version of python that you expect to use in the next step `which python3`.
1. After cloning run `pip install .`, then move on to the next step.

Instructions for setting up Python Scripter.

1. Add Python Scripter plugin to Obsidian.
1. Add `.obsidian/plugins/python-scripter/data.json` to `.gitignore` to prevent python path from being checked into git.
1. Run `which python` to determine path to python, then open `Python Scripter` settings in Obsidian and copy path.
1. Copy all script folders to `.obsidian/scripts/python/`.
1. Restart Obsidian

To test daily note workflow:

- Select a daily note and press CMD+p, then select `Python Scripter: Run process daily note`.
