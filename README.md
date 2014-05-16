notify
======
CLI to send a notification to OSX Notification Center.  
Uses only Ruby and AppleScript, no need to install anything.  
Note: this [AppleScript command][AppleScriptDoc] is available on OSX 10.9+

Install:
--------
    TODO

Usage:
------
    notify [options] message
        -t, --title [TITLE]              Notification Title (default: Notify)
                                         NOTE: to pass more than one word you need to use quotes

        -T, --subtitle [SUBTITLE]        Notification Subtitle
                                         NOTE: to pass more than one word you need to use quotes

        -s, --sound-name [SOUND_NAME]    Notification Sound Name
                                         OSX Built-in:
                                         Basso, Blow, Bottle, Frog, Funk
                                         Glass, Hero, Morse, Ping, Pop
                                         Purr, Sosumi, Submarine, Tink

            --verbose                    Be verbose

        -v, --version                    Print version
        -h, --help                       Show this message

Exemple:
--------
    $ notify hello, world!

---

[![GPLv3][GPLv3logo]][GPLv3txt]

[AppleScriptDoc]: https://developer.apple.com/library/mac/documentation/applescript/conceptual/applescriptlangguide/reference/ASLR_cmds.html#//apple_ref/doc/uid/TP40000983-CH216-SW224
[GPLv3txt]: http://www.gnu.org/licenses/gpl-3.0.html
[GPLv3logo]: https://dl.dropboxusercontent.com/u/11524769/fsf/gplv3-127x51.png
