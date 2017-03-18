# openhab-mcedit
## Description
markdown syntax file for mcedit

## Installing

To install the syntax highlighting execute these commands

```bash
# download syntax file
sudo curl -L -o /usr/share/mc/syntax/markdown.syntax https://github.com/CWempe/openhab-mcedit/raw/master/markdown.syntax

# download and apply patch for Syntax file
curl -L -o /tmp/Syntax.patch https://github.com/CWempe/openhab-mcedit/raw/master/Syntax.patch
sudo patch /usr/share/mc/syntax/Syntax < /tmp/Syntax.patch
```
