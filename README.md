
# Repository Downloader

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Version](https://img.shields.io/npm/v/repository-downloader.svg)](https://www.npmjs.com/package/repository-downloader) [![Downloads](https://img.shields.io/npm/dt/repository-downloader.svg)](https://www.npmjs.com/package/repository-downloader)

> Download all the repositories from BitBucket and GitHub, including your account, teams and where you created pull requests.

## Installation
```sh
$ git clone https://github.com/IonicaBizau/repository-downloader.git repo-downloader
$ cd repo-downloader
$ npm i
$ npm i -g git-stats-importer
```
## Usage

 1. Copy `config.tmpl.json` into `config.json` and edit it with your GitHub and BitBucket usernames and passwords. If you're using [two factor authentication](https://help.github.com/articles/about-two-factor-authentication/) on github, please [create an access token](https://developer.github.com/v3/oauth_authorizations/#create-a-new-authorization) and fill it on password field.
 2. Run `./start` and wait! :smile:


:bulb: You can pass arguments which are understood by `git-stats-importer` (e.g. `./start -e 'alice@example.com,bob@example.com'`).


## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:



## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
