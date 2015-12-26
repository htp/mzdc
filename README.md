# mzdc

A utility to make working on the Mazda Connect infotainment system easier.

## Installation

1. Get mzdc: `git clone https://github.com/htp/mzdc.git /path/to/mzdc`
2. Link it into your `$PATH`: `ln -s /path/to/mzdc/mzdc ~/bin/mzdc`

## Usage

```
Usage: mzdc <command> [<arguments>]

Available commands are:

    bootstrap     Prepare the infotainment system for modification.
    console       Open an SSH prompt to the infotainment system.
    help          List all commands or show documentation for a specific command.
    reboot        Reboot the infotainment system.
    screenshot    Save a screenshot of the infotainment system to your desktop.
    upload        Upload the specified file(s) to the infotainment system.

See `mzdc help <command>` for information about a specific command.
```

## License

mzdc is released under the [MIT License](http://www.opensource.org/licenses/MIT).
