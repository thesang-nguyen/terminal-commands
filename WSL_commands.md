# WSL commands

## Open `cmd`.

## Show all running WSL distros:

```shell
wsl --list --verbose
```

## Shutdown WSL:

```shell
wsl -t <distro_name>
```

for example:

```
wsl -t Ubuntu-20.04
```

## Shut down all distros:

```shell
wsl --shutdown
```

## (Re)Start WSL:

```shell
wsl --distribution <distro_name>
```
