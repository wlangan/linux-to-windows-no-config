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

### Step 3

- I will now issue a pull request to Wendy to see how the merge goes.

- There seems to be no issue with Line Endings, that is, CrLf versus Lf.

### Step 4

- Merge conflict resolved.
- Let's see what Tom gets
- He got nothing in the pull because he cloned from his fork

### Step 5

- He has now cloned from wlangan's repo
- Let's see what Tom gets now.

### Step 6

- I have changed the upstream to see how that affects the behavior of Tom's local VS Code experience if he issues a pull from upstream.

### Step 7

- These changes conflict with what Wendy did but she decided to keep them along with her's below.
- I have changed the upstream to see how that affects the behavior of Tom's local VS Code experience if he issues a pull from upstream but has made changes locally in the interim.

## Step 8

- Get one commit ahead of Tom

## Step 9

- Tom added this step. It will be in an upcoming PR.
