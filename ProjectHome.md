**DEPRECATED** Go to https://github.com/tokland/chrome-type-ahead

## Motivation ##

[Type-ahead-find](http://www.mozilla.org/access/type-ahead/) (or _find as you type_) is an extremely useful accessibility feature (a core functionality in major browsers like Firefox or Safari), but it's not implemented in Chrome ([nor planned to be](http://code.google.com/p/chromium/issues/detail?id=150)).

## Status ##

The extension covers the goals I had when I start writing it, so its status is "maintenance-only mode". Fully functional patches are welcome, though.

## Notes ##

  * Start writing (or press /) to start text search.
  * Press ' to search only links.
  * Use F3 or Control+G or Alt+N/P to switch between matches.
  * Use F4 to toggle matching mode (text/links) once the search has started.
  * Blacklist support for sites that set up their own shortcuts.
  * Search and select options in HTML selects (disabled by default).

## Download ##

[Download the extension](https://chrome.google.com/extensions/detail/cpecbmjeidppdiampimghndkikcmoadk).

## How to install the extension from sources ##

First of all, read [this page](http://code.google.com/p/chrome-type-ahead/source/checkout). Then:

  1. Checkout code: _svn checkout http://chrome-type-ahead.googlecode.com/svn/trunk/ chrome-type-ahead_
  1. Open _Extensions_ page in Chrome.
  1. Disable old installed versions of the extension.
  1. Enable _developer mode_.
  1. Press button _load uncompressed extension_.
  1. Select the directory where you checked out the code to.

And that's it. Note that extensions installed that way provide a link to reload them easily.

[![](https://www.paypal.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=pyarnau@gmail.com&lc=NO&item_name=chrome-type-ahead&currency_code=EUR&bn=PP-DonationsBF:btn_donate_LG.gif:NonHosted)