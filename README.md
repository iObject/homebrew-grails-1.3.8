homebrew-grails-1.3.8
=====================

homebrew-grails-1.3.8

Currently Grails Version 1.3.8 is not easily obtainable through homebrew.

Step 1)
Checkout and copy 'grails.rb' to '/usr/local/Library/Formula/'

Step 2)
$ brew unlink grails
$ brew install grails

Step 3)
Rejoice!


<b>*Note: You only need to do this once. Homebrew lets you switch between already installed versions easily.</b><br/>
Example:<br/>
$ brew swicth grails 1.3.8 //Switches you to 1.3.8<br/>
$ brew switch grails 2.2.2 //Switches you to 2.2.2
