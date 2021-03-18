# AlfredWPscan
It's [WPscan](https://wpscan.org/), wrapped in an Alfred workflow. *With icons.*

![alfredwpscanflow](https://github.com/itsTallulah/AlfredWPscan/blob/master/alfredwpscanflow.png)

0.2 changes the WPscan brew URL to the official wpscanteam cask.

If updating from 0.1 or you used another wpscan brew cask before, do `brew wpscan remove` first.

# How To Install
Download [WPscanFlow.alfredworkflow](https://github.com/itsTallulah/AlfredWPscan/raw/master/WPscanFlow.alfredworkflow) and double click on it then hit Import.

# Requirements
[Alfred](https://www.alfredapp.com/), with the [Powerpack](https://www.alfredapp.com/shop/).

[Homebrew](https://brew.sh/): It's a one line install.

[WPscan](https://wpscan.org/). This flow can install it via `wpscan update` if you don't have it.

# How to use?
Do your usual Alfred invokation thing 🎩 then type wpscan. The 5 keywords will pop up to tell you the rest. Select one, add the URL and hit return.

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
It's hard to git Alfred flows! Contributions are awkward. Ideas welcomed.

# Who uses this?
We do: https://automattic.com/work-with-us/ | https://wpvip.com/careers/

##### thankxies to @trepmal the flow inspirer for https://github.com/Automattic/vip-mega-alfred-workflow
