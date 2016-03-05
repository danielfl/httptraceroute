# httptraceroute - the url tracerouter

I've created this to test my apache/nginx redirects. 
Someone else might find it useful.

## Using

It is simple:

$ httptraceroute www.google.com

Start tracing www.google.com [216.58.222.100]

[0] - [www.google.com] -- [www.google.com] ... code 302

[1] - [www.google.com] -- [www.google.com.br/?gfe_rd=cr&ei=XCrbVv33LuTM8Afwyb3IBQ] ... code 302

[2] - [www.google.com] -- [www.google.com.br/?gfe_rd=cr&ei=XCrbVv33LuTM8Afwyb3IBQ&gws_rd=ssl] ... code 200


Any questions?
