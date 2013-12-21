Copyright Rob Wu <gwnRob@gmail.com> (https://robwu.nl/)
Last modified: 21 december 2013

## Files

- `crx` - Bash source that defines functions prefixed with "crx".
- `launch-chrome-extensions-on-startup/` - Extension that opens `chrome://extensions/` on startup

## Bash commands
```
crx             Create a Chrome extension in the current directory (if not existent).
crx [name]      Create a Chrome extension with a given name in the current directory,
                and changes current directory to the directory containing the new
                extension.

crxshow         Show whether profile directory for current instance exists.
crxtest         Starts Chrome, loading the Chrome extension from current path.
                After running crxtest once, the extension path will be remembered.
                If you want to reset this value, use __CRX_PWD=
crxdel          Deletes temporary profile.
```