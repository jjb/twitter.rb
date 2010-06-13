twitter.rb
==========

Installation
------------
1. `git clone git://github.com/jjb/twitter.rb.git`
2. Edit the top line of the script to use your username.
3. `ln -s twitter.rb/twitter ~/bin/twitter``
4. `chmod 755 ~/bin/twitter`

 **or**

1. Copy the script from [the web rendering](http://github.com/jjb/twitter.rb/blob/master/twitter)
2. paste it into a text editor and save it as ~/bin/twitter
3. `chmod 755 ~/bin/twitter`


Usage
-----
`$ twitter 'I am tweating from the command line!'`

Keychain will ask you for permission for the script to access your twitter password. Click "Allow" or "Always Allow".

Problem: http://apiwiki.twitter.com/ tells me that basic authentication is being discontinued June 2010 (this month!). I've done twitter oauth authentication, but how does the typical Twitter password-requesting desktop app authenticate? I guess they all got xAuth permission? See lower right [here](http://dev.twitter.com/pages/auth_overview).

It somehow seems unlikely that ALL desktop apps do this, since it's described as "least desirable".

If anyone knows, let me know. Thanks!
