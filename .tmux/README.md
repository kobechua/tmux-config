# tmux-config
Remove all folders except tpm:

```bash
find ./ -mindepth 1 -not -regex '^./README.md$' -not -regex '^./plugins/tpm\(/.*\)?' -delete
```

Then run the following command:

```bash
$ git clone https://github.com/tmux-plugins/tpm.git ./plugins/tpm
```
