###
Perl script to support tabs on urxvt with powerline symbols!! Yess

In addition to standard tabbedex it also allows you to select first 10 tabs
using Alt-number.

![screenshot](https://raw.githubusercontent.com/wgallios/tabbedex-urxvt/master/screenshot.png)

## Install
To install clone the repository:

    git clone https://github.com/wgallios/tabbedex-urxvt.git
    cd tabbedex-urxvt
    sudo cp tabbedex /usr/lib/urxvt/perl/tabbedex

## Configuration

    URxvt.perl-ext-common:  default,matcher,tabbedex
    URxvt.url-launcher:      dwb
    URxvt.matcher.button:   1
    URxvt.colorUL: #4682B4
    URxvt.tabbed.tabbar-fg: 2
    URxvt.tabbed.tabbar-bg: 0
    URxvt.tabbed.tab-fg: 2
    URxvt.tabbed.tab-bg: 0
    URxvt.tabbed.autohide:  yes
    URxvt.tabbed.new-button:  no
    URxvt.tabbed.title: yes
