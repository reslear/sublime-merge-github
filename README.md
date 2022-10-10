# Sublime Merge with github, gitlab, bitbucket integration

GitHub/GitLab/Bitbucket Integration (commands & menu items)

![Sublime Merge with github, gitlab, bitbucket](screen.png)

Based on research  [Original source](https://forum.sublimetext.com/t/github-gitlab-bitbucket-integration-commands-menu-items/53893)
by [@srbs](https://github.com/srbs)

## Install macOS

1. Open terminal in folder and run

```sh
sh alias
```

2. Copy `User` folder to 

```
~/Library/Application Support/Sublime Merge/Packages
```

3. done :)

## Changes

- add 🔗 (chain emoji) for better visual ux


## Scripts

### End line


```bash
git config --global alias.set-line-endings '!f() {                                                               
    python "~/Library/Application Support/Sublime Merge/Packages/SublimeMergeOobug/set-line-endings.py" $1 $2;
}; f'
```
