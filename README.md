# bpftrace-2048

## Requirements

+ Linux 5.3 or greater
+ [bcc](https://github.com/iovisor/bcc) master branch version
+ [bpftrace](https://github.com/iovisor/bpftrace) master branch version

## How to run

```
sudo bpftrace 2048.bt
```

## How to move

Default key is vim keybind.
```
h -> left, j -> down, k -> up, l -> right
```

If you exec ```sudo bpftrace 2048.bt emacs```, you can play emacs keybind!!(b -> left, n -> down, p -> up, f -> right)
Also ```wasd```, you can play wasd keybind too!!(a -> left, s -> down, w -> up, d -> right)
