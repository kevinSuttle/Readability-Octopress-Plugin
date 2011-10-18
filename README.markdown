# Readability Octopress Plugin

## Set up
Place 'sharing.html' in *[OCTOPRESS_REPO].themes/classic/source/post/*

If you don't have hidden files shown on OSX, 
open up Terminal and type the following 2 lines:

<pre>defaults write com.apple.finder AppleShowAllFiles TRUE
killall Finder</pre>

To hide hidden files again, type: 
<pre>defaults write com.apple.finder AppleShowAllFiles FALSE
killall Finder</pre>  

## Usage  
You've basically got 2 options:  
<ol><li>Show the usual 'Read Now | Read Later' button options

<pre>readability_basic_buttons: true # Read Now, Read Later</pre></li>

<li>Show the full set of Readability buttons
<pre>readability_all_buttons: false # Read Now, Read Later, Print, Email, Send to Kindle</pre></li>  

For support, open up an issue on the Github repo. Thanks!
Also, if you'd like to fork this, be my guest.  

For even more info on the Readability API, check out [their developer docs](https://www.readability.com/developers)