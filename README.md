# b2

b2 is a CLI to interact with [Backblaze](https://www.backblaze.com) using its [API](https://www.backblaze.com/b2/docs/).

The command `shellcheck --shell=sh b2` is used to verify
the POSIX compliance.

It is using the shell library [b2-sdk-shell](https://github.com/sbourlon/b2-sdk-shell).


## Install
```sh
git clone https://github.com/sbourlon/b2.git
ln -sf $PWD/b2/b2 /usr/local/bin
```

## Usage
```sh
$ b2
Interact with Backblaze

Usage: b2 COMMAND

COMMAND:
  upload         upload a file from stdin
  download       download file to stdout
  list           list file to stdout
  help [COMMAND] show usage

Environment variables:
  B2_ID          key ID (required)
  B2_KEY         application key (required)
  DEBUG          trace the script execution
```
