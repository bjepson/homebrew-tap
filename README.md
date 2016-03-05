Brian Jepson's Taps
===================

Here are some taps I created for my own enjoyment, and maybe yours.

How To Install
--------------

`brew tap bjepson/homebrew-tap`

`brew install bjepson/homebrew-tap/mutt --with-compressed-folders-patch`

Notes
-----

You'll need to add the hooks shown in https://www.spinnaker.de/mutt/compressed/doc.html[the documentation for this patch] to your ~/.muttrc, then you should be able to open archived folders with `mutt -f file.gz`.
