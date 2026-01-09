---
title: Using Prism Launcher via the Command Line
sidebar:
  label: Command Line Interface
---

```text
Usage: prismlauncher [options] [URL...]
Prism Launcher

Options:
  -d, --dir <directory>    Use a custom path as application root (use '.' for
                           current directory)
  -l, --launch <instance>  Launch the specified instance (by instance ID)
  -s, --server <address>   Join the specified server on launch (only valid in
                           combination with --launch)
  -w, --world <world>      Join the specified world on launch (only valid in
                           combination with --launch)
  -a, --profile <profile>  Use the account specified by its profile name (only
                           valid in combination with --launch)
  -o, --offline <offline>  Launch offline, with given player name (only valid
                           in combination with --launch)
  --alive                  Write a small 'live.check' file after the launcher
                           starts
  -I, --import <url>       Import instance or resource from specified local
                           path or URL
  --show <show>            Opens the window for the specified instance (by
                           instance ID)
  -?, -h, --help           Displays help on commandline options.
  --help-all               Displays help, including generic Qt options.
  -v, --version            Displays version information.

Arguments:
  URL                      Import the resource(s) at the given URL(s) (same as
                           -I / --import)
```

## What is an instance ID, and where do I find it?

The instance ID is the name of the folder where your instance is contained.

To find it, **right-click** on the instance you want to know the ID of, and then click on _Instance Folder_ within the context menu.

Now, just copy the name of the folder that opened.

## Prism Launcher is still opening after I close Minecraft

Currently, the _Close Prism Launcher after game window opens_ option opens Prism Launcher after closing Minecraft, even when launched from the CLI.

To disable this, open _Settings_, then select _Minecraft_, and finally, un-check _Close Prism Launcher after game window opens_ or check _Quit the launcher after game window closes_.
