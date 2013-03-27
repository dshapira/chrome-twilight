# Chrome Inspector Twilight Theme ( with thin Toolbar )

This is just Remy Bach's implementation with some small modifications from me and is probably not 100% what you would expect. The way the Chrome inspector wraps things is different to how code editors do it, so it's not possible to get it _identical_, but we can get a close approximation.

Includes the Elements, Resources (view js/css/html file), Sources (view js/css/html file), and Console panels; styles for the toolbar (Elements/Resources/Network/etc); and even view source styles (note: not JS/CSS view source though - that's not possible at the moment).

As always, if you see something that you can improve on, please do so and send a pull request :)

## DISCLAIMER

Please note: custom themes are unofficial and may potentially break existing DevTools functionality.

As always, if you encounter bugs with the DevTools, please [report them][crbug], but disable the theme and test again, first. ;)

## Screenshots

Thin Toolbar

![Elements Panel](https://raw.github.com/dshapira/chrome-twilight/master/resources/thin_toolbar.png)

## Installation

[This post][installation] by [Darcy Clarke][darcy-clarke] should help you out.

## Known Issues

* If you come across any issues, please let me know by submitting an issue using the link above. Bonus marks for submitting a pull request to fix the issue!

## Credits

Remy Bach based this file off of the [mnml Theme][mnml] by [Michael P. Pfeiffer][michael-pfeiffer], which itself was based off of [the Tomorrow Theme][tomorrow] by [Ben Truyman][ben-truyman].



[ben-truyman]:https://github.com/bentruyman
[codepen-3d]:http://codepen.io/remybach/details/fGdJB#pen-details-tab
[crbug]:http://crbug.com
[darcy-clarke]:http://darcyclarke.me/
[installation]:http://darcyclarke.me/design/skin-your-chrome-inspector/
[michael-pfeiffer]:https://github.com/frontdevDE
[mnml]:https://github.com/frontdevDE/mnml-devtools-theme
[no-3d]:https://github.com/remybach/chrome-twilight/tree/no-3d
[tomorrow]:https://gist.github.com/3040634