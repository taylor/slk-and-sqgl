# slk-and-sqgl

_Slack + Sqwiggle wrapper for use as desktop app._

![Screenshot](http://i.imgur.com/AzZ7y5A.png)

Uses [node-webkit] to provide a single-purpose window
with Sqwiggle and Slack's web apps.

Based on [slk](https://github.com/passcod/slk)

NOTE: Will not work with node-webkit < 0.10.

[node-webkit]: https://github.com/rogerwang/node-webkit
[release]: https://github.com/taylor/slk-and-sqgl/releases

## running…

### …from source:

```bash
$ $package_manager install node-webkit
$ git clone git://github.com/taylor/slk-and-sqgl.git
$ cd slk-and-sqgl
$ nw .
```
Optionally build a NW package (zip file) with

```./build.sh``

which creates ~/slk-and-sqgl.nw.  Which can be ran with `nw ~/slk-and-sqgl.nw`

## legal

Slack, SlackHQ, and the Slack logo are trademarks
of, and copyrighted to, SlackHQ, Inc.

Sqwiggle owns some stuff also.

All other files are released in the Public Domain as per
my [policy](https://passcod.name/PUBLIC.txt).
