# vscode-snippets

Code snippets for [Visual Studio Code](https://code.visualstudio.com/).

## Golang code snippets:

- Fan-out goroutines: Multiple worker goroutines read from the same inbound channel until that channel is closed; workers also send data to the same outbound channel and that channel is closed when all workers are stopped.
- Interrupt signal goroutine: Close \"done\" channel when interrupt signal is relayed.


## Installation 

```
go get github.com/fxamacker/vscode-snippets
```

After downloading this repository, copy code snippets files (*.json) to `~/.config/Code/User/snippets/` or merge with your existing user defined snippets by hand.