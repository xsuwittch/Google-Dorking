# Google-Dorking
Google Dorking Cheat Sheet:
site:example.com	Show all indexed pages from a domain
site:example.com -www	Find subdomains of a target
intitle:"Index of /"	Find open directory listings
filetype:sql intext:password	Find exposed database files
ext:env OR ext:log OR ext:config site:example.com	Find sensitive configuration files
inurl:php?id=	Detect possible SQL injection points
site:example.com intext:"admin login"	Locate admin login pages
site:example.com ext:bak OR ext:old	Search for backup files
