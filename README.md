# Git Advanced Commands

A collection of custom Git commands to enhance your Git workflow.

## Commands Included

1. **git sync-branches**: Synchronizes local branches with their corresponding remote branches.
2. **git clean-remotes**: Deletes all cached remote-tracking branches except the ones that have a corresponding local branch.
3. **git stage-fetch**: Fetches commits in stages, from newest to oldest, for a specific branch.

## Installation

1. Clone the repository to your local machine:
   ```
   git clone <https://github.com/KareemSarhan/Git-Advanced-Commands>
   ```

2. Make the scripts executable:
   ```
   chmod +x Git-Advanced-Commands/Command-Scripts/git-*
   ```

3. Add the `Command-Scripts` directory to your `PATH` so you can run the git commands from anywhere:
   - For Linux/Mac:
     ```
     echo 'export PATH=$PATH:/path/to/Git-Advanced-Commands/Command-Scripts' >> ~/.bashrc
     source ~/.bashrc
     ```
   - For Windows Git Bash:
     ```
     echo 'export PATH=$PATH:/path/to/Git-Advanced-Commands/Command-Scripts' >> ~/.bash_profile
     source ~/.bash_profile
     ```

## Usage

### git sync-branches

Synchronizes local branches with their corresponding remote branches.

**Usage:**
```
git sync-branches
```

### git clean-remotes

Deletes all cached remote-tracking branches except the ones that have a corresponding local branch.

**Usage:**
```
git clean-remotes
```

### git stage-fetch

Fetches commits in stages, from newest to oldest, for a specific branch.

**Usage:**
```
git stage-fetch <remote> <branch>
```

- `remote`: The remote repository to fetch from.
- `branch`: The branch to fetch.

## License

[MIT](https://choosealicense.com/licenses/mit/)