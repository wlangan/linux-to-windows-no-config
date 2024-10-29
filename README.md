<h1 align="center">Line Terminator Project</h1>

## Notes

- Note, to add `core.autocrlf input` machine wide you must execute the command `sudo git config --system core.autocrlf input`. That is, you need the elevated permissions provided by the sudo prefix to do this.
- To add this config option at the user level that is not necessary. A simple `git config --system core.autocrlf input` without the sudo prefix will do.
- To remove the core.autocrlf key use the command `udo git config --system --unset core.autocrlf`
- Note that the Hop Light extension by bubersson is what colorizes the text surrounded by single backticks.

## Steps

### Step 1

- First, ensure core.autocrlf input is not in a config file at any level, system, user or workspace. To do this use the command `git config --list`
- Now create a project on the linux side with a single readme.md and push this to Github
  - In order to do this I must first include my name and email address in git config at the `user level`, that is, use the `--global` option.
- When I opened this on the windows machine it considered the file clean.

### Step 2

I will now issue a pull request to Wendy to see how the merge goes
