# 🗔 Tmux Cheatsheet

###### Install tmux

```sh
sudo apt install tmux     
```

###### Key Bindings

**Key Combo**|**Description**
:-----:|:-----:
tmux new -s <SESSION\_NAME> |New Session
tmux ls |list all tmux sessions
tmux attach -t <SESSION\_NAME>|Attach to a particular tmux session
Ctrl+b |Prefix key
Ctrl+b c |New pane
Ctrl+b <0,1,2>|Move across panes
Ctrl+b , | Rename tmux window
Ctrl+b % |Horizontal Split
Ctrl+b "|Vertical Split
Ctrl+b Space-bar |Change orientation of panes
Ctrl+b <ARROW\_KEYS> |Change active window
Ctrl+b z|Zoom in/out of a pane
Ctrl+b { }|Reorder panes in a window
Ctrl+b ?|tmux help
Ctrl+b t |Time
Ctrl+b d |Detach from tmux session
exit |Close pane

###### References

- [`Copy and paste`](https://unix.stackexchange.com/questions/58763/copy-text-from-one-tmux-pane-to-another-using-vim)
