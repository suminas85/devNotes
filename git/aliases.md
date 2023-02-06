# Git aliases: streamline your git workflow

Git allows you to create custom shortcuts, known as aliases, to streamline your workflow and make common Git tasks easier and faster to perform.

To create a Git alias, use the command git config --global alias.<alias-name> <git-command>. For example, if you frequently use the git status command, you could create an alias for it with the following command:

```sh
git config --global alias.st status
```

Now, whenever you type git st in the command line, Git will automatically run git status for you.

Here are some commonly used Git aliases that can save you time and improve your workflow:

```sh
git config --global alias.nmerge merge --no-ff

git config --global alias.grog log --graph --abbrev-commit --decorate --all
--format=format:"%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(dim white) - %an%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n %C(white)%s%C(reset)"

git config --global alias.ci commit

git config --global alias.st status

git config --global alias.co checkout

git config --global alias.br branch
```

Git aliases are a simple but effective way to streamline your workflow and make Git easier and faster to use. Whether you're using Git for personal projects or collaborating with a team, customizing your Git workflow with aliases can help you be more productive and efficient.