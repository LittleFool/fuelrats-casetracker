# Fuel Rats caseTracker

This script saves the case number together with the client name. This enables alises to use case numbers and ping the client. It is designed to work with the [fuelrats-dispatch-aliases](https://github.com/LittleFool/fuelrats-dispatch-aliases).

## Installation

### mIRC

In mIRC press `ALT+R` and copy the content of the `mIRC/remote.ini` file into the window. If you already have a `on 1:EXIT:` section then merge the contents. There can only be one `on 1:EXIT:` section in all files combined. Then switch to the `Aliases` tab and copy the contents of the `mIRC/aliases.ini` file into the window.
When done click OK to save the changes.

### AdiIRC

In AdiIRC press `ALT+R`, then click on `File` - `New`. Copy and paste the content of the `AdiIRC/aliases.ini` and `AdiIRC/remote.ini` file from this repository into the editor. If you already have a `on 1:EXIT:` section then merge the contents. There can only be one `on 1:EXIT:` section in all files combined. Then click on `File` - `Save`, enter a filename such as `caseTracker.ini` and save it under `%LOCALAPPDATA%\AdiIRC\Scripts` (default).
