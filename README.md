# httptraceroute - the url tracerouter

I've created this to test my apache/nginx redirects. 
Someone else might find it useful.

Be aware that this script was made for studying purposes and is not following
KISS practices. ;-) For a more easy to read and light script use the "httptracelite" version
which has no regex, no repeated requisitions, and no bash hacks.

## Using

It is simple:

$ httptraceroute www.google.com 

Start tracing www.google.com [216.58.222.100] 

[0] - [www.google.com] -- [www.google.com] ... code 302 

[1] - [www.google.com] -- [www.google.com.br/?gfe_rd=cr&ei=XCrbVv33LuTM8Afwyb3IBQ] ... code 302 

[2] - [www.google.com] -- [www.google.com.br/?gfe_rd=cr&ei=XCrbVv33LuTM8Afwyb3IBQ&gws_rd=ssl] ... code 200 

Any questions?
