# Fuel Rats caseTracker

This script saves the case number together with the client name. It is designed to work with the [fuelrats-dispatch-aliases](https://github.com/LittleFool/fuelrats-dispatch-aliases).
You can then use the dispatch-aliases with case numbers only e.g. `/wing 2` will print `<client name of case 2> now, please invite your rat(s) to a wing.` and then `!wing 2`. So it only pings the client for actualy readable text and no commands/facts.

## Installation

### mIRC

In mIRC press `ALT+R` and copy the content of the `mIRC/remote.ini` file into the window. If you already have a `on 1:EXIT:` section then merge the contents. There can only be one `on 1:EXIT:` section in all files combined. Then switch to the `Aliases` tab and copy the contents of the `mIRC/aliases.ini` file into the window.
When done click OK to save the changes.

### AdiIRC

In AdiIRC press `ALT+R`, then click on `File` - `New`. Copy and paste the content of the `AdiIRC/aliases.ini` and `AdiIRC/remote.ini` file from this repository into the editor. If you already have a `on 1:EXIT:` section then merge the contents. There can only be one `on 1:EXIT:` section in all files combined. Then click on `File` - `Save`, enter a filename such as `caseTracker.ini` and save it under `%LOCALAPPDATA%\AdiIRC\Scripts` (default).
