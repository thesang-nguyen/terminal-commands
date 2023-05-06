# WSL commands

## Open `cmd`.

## Show all running WSL distros:
```c++
wsl --list --verbose
```

## Shutdown WSL:
```c++
wsl -t <distro_name>

# for example:
wsl -t Ubuntu-20.04
```

## Shut down all distros:
```c++
wsl --shutdown
```

## (Re)Start WSL:
```c++
wsl --distribution <distro_name>
```
