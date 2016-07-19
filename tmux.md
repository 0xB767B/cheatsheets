# Default Keybindings & Functionality

Keybinding | Functionality | My tmux.conf Binding | Comment
-----------|---------------|----------------------|--------
**Ctrl-b c** | Create new window | |
**Ctrl-b d** | Detach cuurent client | |
**Ctrl-b l** | Move to previously selected window | |
**Ctrl-b n** | Move to next window | |
**Ctrl-b p** | Move to previous window | |
**Ctrl-b &** | Kill the current window | |
**Ctrl-b ,** | Rename he current window | |
**Ctrl-b %** | Split the current window into two panes | |
**Ctrl-b q** | Show the pane numbers | Used to switch between panes |
**Ctrl-b o** | Switch to next pane | |
**Ctrl-b ?** | List all keybindings | |
**Ctrl-b :** | To execute commands interactively | |

# Basic Pane Handling

Keybinding | Functionality | My tmux.conf Binding | Comment
-----------|---------------|----------------------|--------
**Ctrl-b %** | Split the window vertically | **Ctrl-b -** |
**Ctrl-b : "split-window"** | Split window horizontally | **Ctrl-b pipe** | Todo: Fix the pipe symbol! |
**Ctrl-b o** | Go to next pane | |
**Ctrl-b q** | Show the pane numbers | | When the numbers show up type the key to go to that pane
**Ctrl-b {** | Move the current pane left | |
**Ctrl-b }** | Move the current pane right | |
**Ctrl-b x** | Kill pane | |
