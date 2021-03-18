# AlfredWPscan
It's [WPscan](https://wpscan.org/), wrapped in an Alfred workflow. *With icons.*
V 0.2 changes the cask URL to the official wpscanteam one.

![alfredwpscanflow](https://github.com/itsTallulah/AlfredWPscan/blob/master/alfredwpscanflow.png)

# How To Install
Download [WPscanFlow.alfredworkflow](https://github.com/itsTallulah/AlfredWPscan/raw/master/WPscanFlow.alfredworkflow) and double click on it then hit Import.

# Requirements
[Alfred](https://www.alfredapp.com/), with the [Powerpack](https://www.alfredapp.com/shop/).

[Brew](https://brew.sh/): install from a Terminal with `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)`

[WPscan](https://wpscan.org/). This flow can install it via `wpscan update` if you don't have it.

# How to use?
Do your usual Alfred invokation thing 🎩 then type wpscan. The 5 keywords will pop up to tell you the rest. Select one, hit return.

# What are the keywords?
`wpscan url example.com` 
`wpscan loadout example.com` 
`wpscan everything example.com`  
`wpscan vuln example.com` 
`wpscan update` 

# Vulnerability Scanning?
If so, you'll need to add an api key from vulndb as an environment variable. Click the `[x]` in the top right of the workflow for details.

![thex](https://github.com/Automattic/vip-mega-alfred-workflow/raw/master/readme-images/settings.png)

# Improvements?
It's hard to git Alfred flows, so if you have ideas, ping me~

##### thankxies to @trepmal the flow inspirer for https://github.com/Automattic/vip-mega-alfred-workflow
