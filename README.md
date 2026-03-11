Cosmic Ext Applet Workspaces

Cosmic's numbered workspaces applet, with extensions.

# Testing note
When an applet is run, COSMIC passes the `COSMIC_PANEL_OUTPUT` environment variable to the applet, but when it's run from `cargo r` as part of a test this environment variable isnt set.

To test, run with `COSMIC_PANEL_OUTPUT` set to the name of the display you want to test for.

Display names in COSMIC can be fetched using this tool: https://github.com/nick42d/cosmic-ext-protocols-cli
