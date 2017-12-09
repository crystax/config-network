Reliable way to reconfigure network on Debian/Ubuntu machines over SSH
======================================================================

Just clone this repository and run `./reconfigure` script. It will open
the editor and allow you to edit `/etc/network/interfaces`. When done,
just save it and exit from the editor. The script will apply new configuration
and ask for explicit confirmation. If no input received within 30 seconds,
it will revert everything back, so you would be able to connect again
and fix if something was wrong.
