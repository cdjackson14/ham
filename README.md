# Ham

Several Linux ham radio apps require multiple commandline executions.  Here I've created a script to run the various configurations I might want to run on when in the field or at home.

This is a Bash script, developed on Xubuntu, so should work on most any Debian based system.

Uses whiptail to create a nice menu.

Options are:

* Pat with Direwolf
* Pat with Mobilinkd (Bluetooth)
* Kill all kiss* processes IDs

For desktop icon to run, copy ham.desktop to ~/.local/share/applications/

```bash
cp ham.desktop ~/.local/share/applications/
```

![ham screenshot](ham_ss.jpg)

