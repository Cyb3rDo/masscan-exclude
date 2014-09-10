masscan-exclude
===============
Is what it sounds like. It is an exclude file for masscan.

The top portion is a copy from the masscan repository.

There are many more IP addresses that I found at http://www.waraxe.us/ftopict-346.html. I have no idea the validity of the second file. The post is old. The IP addresses are separated from the comment string by a :. There is also heavy usage of an asterisk (*) in portions of the IP address. I don't know if masscan can handle that or not. Judging by the contents of the file included with masscan I'm inclined to think not. But it is something I need to verify.

My goals are to simply reformat the list into something that is useable for masscanning. I'd like to verify and validate the ip addresses in the second list as belonging to who they are shown as. I'd like to replace the *'s with 0's. Remove duplicates, and where possible use CIDR notation, and then ranges.

I'm working on this for my personal purposes, but I'm posting it here as it may be useful to others.

Inclusion
=========
If you are a network operator and would like your ranges added please send a pull request and I'll merge it.

Removal
=======
If you are of the mindset that scanning doesn't pose any threat to your network and you find that your ranges are on here and would like them removed please issue a pull request.

License
=======
By using this exclude list with your masscans you agree that the file is provided as is. With no warrenty. You use this at your own risk. If you piss off an network admin somewhere because his range wasn't on here, well you tried. Send the range to us for inclusion with a pull request.
