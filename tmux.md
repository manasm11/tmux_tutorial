# Key Combinations

## Panes
| Keys                | Task                    |
| ------------------- | ----------------------- |
| ctr+b %             | Split pane vertically   |
| ctr+b "             | Split pane horizontally |
| ctr+b [left arrow]  | Move to left pane       |
| ctr+b [right arrow] | Move to left pane       |
| "exit" command      | Close a pane            |

## Tabs
| Keys        | Task                   |
| ----------- | ---------------------- |
| ctr+b c     | New tab                |
| ctr+b [num] | Switch to specific tab |
| ctr+b ,     | Rename current tab     |
>active tab is marked with asterisks.

## Sessions
| Keys                                  | Task                       |
| ------------------------------------- | -------------------------- |
| ctr+b d                               | Detach a session           |
| "tmux ls"                             | List sessions              |
| "tmux attach -t [session name/number] | Reattach to a session      |
| "tmux new -s [session name]           | Create a new named session |
| "tmux kill-session -t [session name/number]           | Kill a session|
>Sessions run in background even if the connection is accidentally lost.

Session contains multiple Tabs, 
Tab contains multiple panes
