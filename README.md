

# The `cdr255-website` README

**Personal Homepage for Christopher Rodriguez.**

*Last Updated: 2022-07-26 (W30) 23:28:38 GMT*

This is my personal homepage (as opposed to my [blog](https://git.sr.ht/~yewscion/yewscion-blog)), and exists mostly to act
as a hub for myself on the internet.


# Installation / Usage (?)

Normally, this is where I would point to [GNU Guix](https://guix.gnu.org) and [My Guix Channel](https://git.sr.ht/~yewscion/yewscion-guix-channel), with some
fallback [Autotools](https://www.gnu.org/software/automake/manual/html_node/Autotools-Introduction.html)-based instructions if You want to do things by hand. However,
that isn't really something of use here: You don't need to "Install" or "Use" a
website.

Instead, the site is live [here](https://cdr255.com/). If You want to use/borrow stuff, see the license
info below.


# Contributing

Pull Requests are welcome, as are bugfixes and extensions. Please open
issues as needed. If You contribute a feature, needs to be tests and
documentation.

Development is expected to be done using [GNU Guix](https://guix.gnu.org/).
If You have `guix` set up, You should be able to enter a development
environment with the following:

    cd cdr255-website
    guix shell -D -f guix.scm bash --pure

If You've made changes without the above precautions, those changes will
need to be confirmed to work in the above environment before merge.

That said, as this is my *personal* website, anything more than structural fixes
or accessibility stuff should probably go on *your* website instead 😉.


# License

The `cdr255-website` project and all associated files are ©2022 Christopher
Rodriguez, butlicensed to the public at large under the terms of the:

[GNU AGPL3.0+](https://www.gnu.org/licenses/agpl-3.0.html) license.

Please see the `LICENSE` file and the above link for more information.

