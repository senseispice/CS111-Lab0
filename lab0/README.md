# A Kernel Seedling
TODO: intro
This program counts all currently running processes and writes this info to the /proc/count file.

## Building
```shell
TODO: cmd for build
make
```

## Running
```shell
TODO: cmd for running binary
sudo insmod proc_count.ko
```

```shell
TODO: results?
cat /proc/count
135
```

## Cleaning Up
```shell
TODO: cmd for cleaning the built binary
sudo rmmod proc_count
```

## Testing
```python
python -m unittest
```
TODO: results?
Ran 3 tests in 13.486s


Report which kernel release version you tested your module on
(hint: use `uname`, check for options with `man uname`).
It should match release numbers as seen on https://www.kernel.org/.

```shell
uname -r -s -v
```
TODO: kernel ver?
5.14.8
