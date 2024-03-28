# bash

- assicurarsi che il file `$HOME/.bash_profile` abbia i seguenti permessi: `-rw-r--r--`

  ```sh
  chmod 644 $HOME/.bash_profile
  ```

- impostazioni da mettere in `.bash_profile`

  ```sh
  bind '"\e[A": history-search-backward'
  bind '"\e[B": history-search-forward'
  shopt -s histappend
  ```

- vedere anche [linux-unix.md](linux-unix.md)

# linux/unix

- alias utili

  ```sh
  alias ll='ls -las'
  alias ..='cd ..'
  ```

