# tgdbdb - tmux + gdb + dashboard
This is a small script to get all of the above working together.

*Note that this is a work in progress.*

# Install
1. install tmux
2. install gdb
3. install libtmux
4. install [gdb-dashboard] (https://github.com/cyrus-and/gdb-dashboard/issues)
5. copy `tgdbinit` to `~/.tgdbinit`
6. add to `alias tgdb='tmux new gdb -x ~/.tgdbinit'` `~/.bashrc`

# Use
To use just run `tgdb` instead of `gdb` when debugging.
