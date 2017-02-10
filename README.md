# Spamty API Docs

[![Open Issues](https://img.shields.io/github/issues/spamty/api-docs.svg)](https://github.com/Spamty/api-docs/issues)

[![License](https://img.shields.io/badge/license-CC--BY--ND_GNU--GPL--v3-blue.svg)](https://github.com/Spamty/api-docs/blob/master/LICENSE.md)
![Twitter](https://img.shields.io/twitter/follow/Spamty.svg?style=social&label=Follow&maxAge=2592000)


This is our API documentation which [can be viewed here](https://dev.spamty.eu/).
And also on [apiary](http://docs.spamty.apiary.io/).

## Build the docs

The API documentation is in the [API Blueprint](https://apiblueprint.org/) file `apiary.apib`.

The documentation (`index.html`) is generated with [snowboard](https://github.com/subosito/snowboard).
Do not edit this HTML file! Only edit the API Blueprint file and the template (`template.html`) to generate the site.

Run this command to generate the HTML file:

    snowboard html -i apiary.apib -o index.html -t template.html

## Issues & Bugs

Report issues and bugs [on GitHub](https://github.com/Spamty/api-docs/issues)
or [send me an email](https://3q3.de/spamty).

## License

Copyright (c) 2017 by
[Spamty team](https://github.com/Spamty) &
[contributors](https://github.com/Spamty/api-docs/graphs/contributors)

The **source code of this API documentation** (especially HTML code)
is licensed under the **GNU General Public License**
version 3 as published by the Free Software Foundation.

You should have received a copy of the GNU General Public License
along with this work. If not, see <http://www.gnu.org/licenses/>.

The **text and content of this API documentation**
is licensed under a Creative Commons
**Attribution-NoDerivatives 4.0 International** License.

You should have received a copy of the license along with this
work. If not, see <https://creativecommons.org/licenses/by-nd/4.0/>.



*Support Spamty and donate Bitcoins to:*
*1NRoifJBzLAKP3K6pkNikcrydENYw2EoF6*



Built with
[snowboard](https://github.com/subosito/snowboard),
[API Blueprint](https://apiblueprint.org/),
[Prettify](https://github.com/google/code-prettify/),
[Bootstrap](https://getbootstrap.com/) and
[GitHub Pages](https://pages.github.com).
