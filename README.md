### https://cristhian2k47.github.io/REGtoYML/

# Does not work with multiple values in a single key:

[HKEY_CURRENT_USER\Control Panel\Mouse]

"MouseSpeed"="0"

"MouseThreshold1"="0"

"MouseThreshold2"="0"

# Use this instead:

[HKEY_CURRENT_USER\Control Panel\Mouse]

"MouseSpeed"="0"

[HKEY_CURRENT_USER\Control Panel\Mouse]

"MouseThreshold1"="0"

[HKEY_CURRENT_USER\Control Panel\Mouse]

"MouseThreshold2"="0"
