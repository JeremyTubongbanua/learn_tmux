# learn_tmux

Learning how to use [tmux](https://tmuxcheatsheet.com/)

## Install tmux on Mac (with Homebrew)

- [homebrew](https://brew.sh/)
- [tmux](https://github.com/tmux/tmux/wiki)

```sh
homebrew install tmux
```

## Using tmux

1. New session with name `lemonade`

```sh
tmux new -s lemonade
```

2. Rename a session with `Ctrl` + `b` + `$` (Shift + 4)

`Ctrl` + `b` + `$`

3. Detach from current tmux session

`Ctrl` + `b` + `d`

4. Delete all tmux sessions

```sh
tmux kill-ses -a
```

5. Attach to an existing tmux session

```sh
tmux a -t <session>
```

6. Create a session but detatch (`-d`)

```sh
tmux new -d -s lemonade
```