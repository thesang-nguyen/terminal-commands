# WSL commands

## Open `cmd`.

## Show all running WSL distros:
    wsl --list --verbose

## Shutdown WSL:
    wsl -t <distro_name>

    # for example:
    wsl -t Ubuntu-20.04

## Shut down all distros:

    wsl --shutdown

## (Re)Start WSL:
    wsl --distribution <distro_name>
