setup.git
=========
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure both the machine and your individual development environment as
follows:

```sh
cd $HOME
sudo apt-get install -y git-core
git clone https://github.com/startup-class/setup.git
./setup/setup.sh   
```

See also http://github.com/startup-class/dotfiles and
[Startup Engineering Video Lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index)
for more details.

## Emacs Shortcuts

* Move between functions: C-M-e / C-M-a : end/beginning-of-defun
* Move between parens: Similar C-M-n / C-M-p : backward/forward-list

* Mark function body : C-M-h : expand-region (mark-js-function)

* Kill next expression : C-M-k : kill-forward-sexp

## Mintty backward delete
https://github.com/rpavlik/git-windows-mintty/issues/2

## 24 bit colors

* Emacs
  https://emacs.stackexchange.com/questions/32506/conditional-true-color-24-bit-color-support-for-iterm2-and-terminal-app-in-osx
* Screen -> Tmux
  https://robots.thoughtbot.com/migrating-from-screen-to-tmux

