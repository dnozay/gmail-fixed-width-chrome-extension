# gmail-fixed-width-chrome-extension

Extension to read email messages with fixed with font.

This is based on [a blog post from Leonardo Soto](http://blog.leosoto.com/2009/03/fixed-width-font-on-gmail-again.html) about making gmail messages use a fixed-width font.

#[How to load this extension](http://developer.chrome.com/extensions/getstarted.html#unpacked):

1.  clone this repository or [download it as a ZIP](https://github.com/dnozay/gmail-fixed-width-chrome-extension/archive/master.zip) ([older releases here](https://github.com/dnozay/gmail-fixed-width-chrome-extension/releases)),
1.  visit [chrome://extensions](chrome://extensions),
1.  make sure "developer mode" is checked,
1.  click "load unpacked extension" to select your git clone.

# Which fonts are used:
There are some factors that I considered

- loading fonts that are available on your system,
- loading fonts that are [considered best for programming use](http://www.slant.co/topics/67/~what-are-the-best-programming-fonts),
- falling back to a fixed width font I particularly liked ([Inconsolata](http://www.google.com/fonts/specimen/Inconsolata) from Raph Levien) with a permissive license.

#Wait, I like this other font better...

1. clone this repository
1. use your favorite fixed-width font in the `gmail-fixed.css` file
1. reload the extension :)