I developed this set of solutions after a couple of weeks of suffering hand and arm pain due to work. I spent 8+ hours a day in front of my computer, so the combination of arm movement between the trackpad and keyboard, and the trackpad (later mouse) itself were provoking me a lot of inflammation related pain. A week of only using the keyboard, and it was gone!

Something like this is great for people with Carpal Tunnel Syndrome or related ailments, I can vouch for it. If you need help setting it up, just say so in the comments, and I'll do my best to help.

###  Google Chrome
It's all about [cVim](https://github.com/1995eaton/chromium-vim), Vim for Chrome.

[![](http://3.bp.blogspot.com/-WVdJ69ppXhM/VMDakJrEjOI/AAAAAAAANSQ/zMK1qp9aLSk/s640/Screen%2BShot%2B2015-01-22%2Bat%2B11.49.24.png)](http://3.bp.blogspot.com/-WVdJ69ppXhM/VMDakJrEjOI/AAAAAAAANSQ/zMK1qp9aLSk/s1600/Screen%2BShot%2B2015-01-22%2Bat%2B11.49.24.png)

My favorite features:

*   j/k to move up/down, d/u for page up/down, gg for top of the page, G for bottom
*   :pintab to pin tabs with the keyboard (finally!)
*   f to follow links,
*   F to follow them on a new page,
*   gy to copy a link's URL to the keyboard
*   / to find text, v to select and copy it
*   .cvimrc to re-enable keyboard shortcuts in sites like twitter, github, and others, and make it compatible with [JK Navigator](https://chrome.google.com/webstore/detail/jk-shortcuts-navigator/chgfodomgimhbcmlfljhkgildehakgif). [Here's mine](https://gist.github.com/mparramont/581d04d9035003e1b1e3),  still tweaking it though.

### Mac OS X

*   Enable cycling between all controls with Tab:
    <div class="separator" style="clear: both; text-align: center;">
[![](http://3.bp.blogspot.com/-EDWrfok4S5I/VL_20t8ObGI/AAAAAAAANRM/heYGdKxnSdE/s400/Screen%2BShot%2B2015-01-21%2Bat%2B19.14.47.png)](http://3.bp.blogspot.com/-EDWrfok4S5I/VL_20t8ObGI/AAAAAAAANRM/heYGdKxnSdE/s1600/Screen%2BShot%2B2015-01-21%2Bat%2B19.14.47.png)</div>

*   Use Caps Lock for Escape when pressed alone or Control when pressed with another key. Here's [a great writeup on this](http://stevelosh.com/blog/2012/10/a-modern-space-cadet/#controlescape) using [Karabiner](http://www.developingandstuff.com/), which also lets you increase the key repeat, and other fancy keyboard-related stuff.
*   [Alfred](http://www.alfredapp.com/), better Spotlight.

<!--more-->*   [Homebrew Cask](http://caskroom.io/), to install apps with the command line. No more go-to-webpage-download-dmg-mount-drag-open nonsense.
*   Grid, window manager. Move windows around and between monitors:
[![](http://4.bp.blogspot.com/-cB9l0Cr5ULA/VMJGH_F8VZI/AAAAAAAANTg/HIOh4KiaMDY/s1600/Screen%2BShot%2B2015-01-23%2Bat%2B13.58.33%2B2.png)](http://4.bp.blogspot.com/-cB9l0Cr5ULA/VMJGH_F8VZI/AAAAAAAANTg/HIOh4KiaMDY/s1600/Screen%2BShot%2B2015-01-23%2Bat%2B13.58.33%2B.png)

[![](http://1.bp.blogspot.com/-V7w8BL4TaJs/VMJGH5KJjJI/AAAAAAAANTk/sHAZGiMAmZc/s1600/Screen%2BShot%2B2015-01-23%2Bat%2B13.58.33.png)](http://1.bp.blogspot.com/-V7w8BL4TaJs/VMJGH5KJjJI/AAAAAAAANTk/sHAZGiMAmZc/s1600/Screen%2BShot%2B2015-01-23%2Bat%2B13.58.33.png)
Here's it working with my two screens. PD: It's unsupported software though, not available online anymore. If you want the .dmg, just ask :)

*   [Shortcat](https://shortcatapp.com/), use the keyboard to click anything on the screen in Mac OS X.
[![](http://1.bp.blogspot.com/-DL8yGzERcuo/VMooLy9XFUI/AAAAAAAANaA/Qfs4V9fA97Y/s640/Screen%2BShot%2B2015-01-29%2Bat%2B13.31.27.png)](http://1.bp.blogspot.com/-DL8yGzERcuo/VMooLy9XFUI/AAAAAAAANaA/Qfs4V9fA97Y/s1600/Screen%2BShot%2B2015-01-29%2Bat%2B13.31.27.png)
### 
Atom editor

Plenty of shortcuts out-of-the-box, the ones I use the most:

*   ⇧ + ⌥ + K: Delete line
*   ⌘ +  D: "Magic" selector, just like Sublime Text:
[![](http://4.bp.blogspot.com/-uFcVOfMLO6I/VMDVUqtCX4I/AAAAAAAANSA/wdw5niqKTcc/s640/magic2.gif)](http://4.bp.blogspot.com/-uFcVOfMLO6I/VMDVUqtCX4I/AAAAAAAANSA/wdw5niqKTcc/s1600/magic2.gif)

*   ⌘ +  L: Select line
*   Ctrl + ⌘ + Up/Down: Move line(s) up and down
*   ⌘ + Z,Y: Go back to where I was (hacky, but works!)

### Slack

I'm using the web version now, it feels as performant as the native one (which seems to use node-webkit or something like that), and I can use all the  cvim shortcuts. The only change I've had to get used to is using ⌘ +  K instead of ⌘ +  T to switch between chats.

### iTerm

[Readline](http://www.bigsmoke.us/readline/shortcuts) all the way! Lots of command line utilities use it or mimic it, they even work in places like Chrome's omnibar. This are the ones I abuse the most:

*   Ctrl + A: Go to start of line
*   Ctrl + E: Go to end of line
*   Ctrl + U: Kill line
*   ⌥ + D: Delete word in front of the cursor
*   Ctrl + P / Ctrl + N: Navigate history
*   ⌘ +  Up: Scroll up one line
*   ⌘ +  Down: Scroll down one line
*   Fn + ⌘ +  Up: Page Up
*   Fn + ⌘ +  Down: Page Down
To use  Ctrl + P / Ctrl + N I put this on my .zshrc:

<pre class="prettyprint">  bindkey '^P' up-history
  bindkey '^N' down-history
</pre>

### 
Pending work (comment if you know how to fix these things please!)

* Chrome tab-hell: After doing ⌘ + L to focus the omnibar, I can't find a way to focus the tab's content without tabbing through all the extension buttons. 
* Gmail: It has too many keyboard shortcuts to ignore them in the .cvimrc, but by itself I can't click on links easily.</li>
* Move tabs around in Chrome and Atom: Can be done in iTerm with ⌘ + ⇧ + Left/Right, but can't find a way to do it anywhere else.</li>

Most of all, 


[![](http://3.bp.blogspot.com/-KvEPn-GwQ0Q/VL_4h9AUR1I/AAAAAAAANRY/1Zu8PbGkQyc/s640/gnpum.jpg)](http://3.bp.blogspot.com/-KvEPn-GwQ0Q/VL_4h9AUR1I/AAAAAAAANRY/1Zu8PbGkQyc/s1600/gnpum.jpg)

Every time you find yourself reaching for it, think again—there's surely a better way without it, you just haven't discovered it yet.