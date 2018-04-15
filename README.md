# Semantic Git TDD commit messages

Inspired by Sparkbox's awesome article on [semantic commit messages](http://seesparkbox.com/foundry/semantic_commit_messages).

## What is this?
These are **very simple** custom git commands that enforce the git user to write better git commit messages. If still confused, read the article above.

## Installation:

Install with [Antigen](https://github.com/zsh-users/antigen): antigen bundle alexrochas/zsh-git-tdd-semantic-commits

Or if you feel like doing it the old-fashioned way:

```shell
mkdir -p ~/src
git clone git://github.com/alexrochas/zsh-git-tdd-semantic-commits.git ~/src/zsh-git-semantic-commits
print 'source ~/src/zsh-git-tdd-semantic-commits/zsh-git-tdd-semantic-commits.plugin.zsh' >> ~/.zshrc
```

## Usage

There are 8 new Git commands now.

New command -> what it does:
* ```git red "commit-message-here"``` -> ```git commit -m 'red: commit-message-here'```
* ```git green "commit-message-here"``` -> ```git commit -m 'green: commit-message-here'```
* ```git refactor "commit-message-here"``` -> ```git commit -m 'refactor: commit-message-here'```

If you would still like to use your text editor for your commit messages
you can omit the message, and do your commit message in your editor.

* ```git green``` -> ```git commit -m 'green: ' -e```

## How to contribute
Open a pull request/issue or fork this repo and submit your changes via a pull request.
