# git-aliases
Common git aliases that I use on a regular basis.

**For Windows:-**
  - Open .gitconfig file located at ```'C:\Users\{username}\.gitconfig'``` . Then add the following lines:
  - If you cannot find the .gitconfig file then open the folder from vscode you might see it then. Otherwise, just create a new .gitconfig file.

**Commands:**
```
[user]
        # Current user profile
	email = j***@gmail.com    # replace with your email.
	name = jeevu94            # replace with your git id.

[alias]
	# Add
	f = fetch --prune --all

	# Add
	a = add .

	# Diff
	d = diff

	# Merge
	m = merge

	# Branch
	b = branch

	# Status
	s = status

	# Commit
	c = commit -m

	# Pull
	p = pull origin

	# Push
	h = push origin

	# init
	i = init

	# checkout
	co = checkout

	# checkout New Branch
	nb = checkout -b
```

**Usage: Using command prompt**
```
# Status
D:\example_project_folder\example_project>git s

# commit
D:\example_project_folder\example_project>git c "the commit message"

# checkout
D:\example_project_folder\example_project>git co staging
```
