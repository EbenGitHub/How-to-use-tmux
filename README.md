# Getting Started
#
## Installation
> For Ubuntu
```bash
sudo apt-get install tmux
```
> In Mac
```bash
brew install tmux
```
#
## Using your tmux
> To start new session
```bash
tmux
```
> To split panel into left and right
```bash
Ctrl-b %
```
> To split panel into top and bottom
```bash
Ctrl-b "
```
> To navigate between panels
```bash
Ctrl-b <arrow key>
```
> To close a panel
```bash
exit
```
or you can also
```bash
Ctrl-d
```
> To create a new window
```bash
Ctrl-b c
```
> To switch to the previous and next window (according to the order in your status bar)
```bash 
Ctrl-b p
```
```bash
Ctrl-b n
```
```bash
Ctrl-b <number>
```
#
## Session Handling
> To detach your current session
```bash
Ctrl-b d
```
```bash
Ctrl-b D
```
> To see/list sessions that are running
```bash
tmux ls
```
> To connect to that session you start tmux again but this time tell it which session to attach to
```bash
tmux attach -t <number>
```
> To start a new session with preferred name
```bash
tmux new -s <name>
```
> To rename your existing session
```bash
tmux rename-session -t <number> <name>
```
> To connect to existing session using name
```bash
tmux attach -t <name>
```
#
## Moving on
> To list all the available commands
```bash
Ctrl-b ?
```
> To toggle the panel between full screen and shrink to the previous size
```bash
Ctrl-b z
```
> To resize the panel in any direction
```bash
Ctrl-b Ctrl-<arrow key>
```
> To rename the current window
```bash
Ctrl-b ,
```
#
#
__EbenGitHub__
