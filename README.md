# Bash script linker

Merge bash script with [source](https://www.man7.org/linux/man-pages/man1/bash.1.html#:~:text=source%20filename%20[arguments]) includes into a single file.

## Usage

Run `./bash-linker` with entry filename and result will be printed to stdout.

Redirect result to file:

```
$ ./bash-linker entry.sh > result.sh
```

## License

This software is distributed under the [MIT license](https://github.com/raiden-dev/bash-linker/blob/master/LICENSE).
