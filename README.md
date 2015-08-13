### git commit template
Use `gct` to write a better commit quickly.

See the below links to learn what's a better commit:
- https://ruby-china.org/topics/15737
- https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message
- http://ablogaboutcode.com/2011/03/23/proper-git-commit-messages-and-an-elegant-git-history/
- https://web-design-weekly.com/2013/09/01/a-better-git-commit/

#### Steps:
1. `git clone https://github.com/fahchen/git-commit-template`
1. `ln -s /path/to/gct /usr/local/bin`
1. you may need to add permition to file.(`sudo chmod +x /usr/local/bin/gct`)
1. `cp /path/to/.gittemplate your/gittemplate/path`
1. set `template.file` as `your/gittemplate/path` at `your/gitconfig/file`
1. `cd your/git/repo`
1. `mkdir .gittemplates`
1. `touch .gittempalets/first_commit_message`
1. `gct`
1. chose the template
