**Tmux**

**Pane:**(One terminal among others)

- Opened tmux using command: **tmux**
- Open new horizontal pane by: **ctrl+b %**
- Switch pane using: **ctrl+b <left or right arrow>**
- Switch vertical pane using: **ctrl+b “**
- Exit the pane: **exit**

**Window:**

- Create a window by: **ctrl+b c**
- Switch window by: **ctrl+b <index of window>**
- Rename window by: **ctrl+b ,**

**Sessions:** 

- List all the sessions: **tmux ls**
- To detach or exit a session: **ctrl+b d**
- To attach with any session: **tmux attach -t <index of session>**
- Rename session: **tmux rename-session <previous name> <new name>**
- Create new session with naming it: **tmux new -s <name of session>**
- Kill the sessions: **tmux kill-sessions -t <name of the session>**


