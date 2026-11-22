# bash-installer

Small Bash script that automates installing a package on a Debian/Ubuntu system.
Made for the Git mini exercise (Part 11) of the OOP AIDAMS course.

## What the script does

1. Prints `Starting installation...`
2. Updates the package list (`sudo apt-get update`)
3. Installs the `tree` package
4. Prints `Installation complete!`

## Usage

```bash
chmod +x install.sh
./install.sh
```

## Git workflow used

- `main`: README commit
- `feature-install` branch: added `install.sh`
- `feature-install` merged into `main`, then the branch was deleted
