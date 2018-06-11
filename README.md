# Overview

Cookie Quick Manager: A complete manager for cookies used during browsing.
The addon is available on [addons.mozilla.org (AMO)](https://addons.mozilla.org/firefox/addon/cookie-quick-manager/).
It allows you to view, edit, create, delete, backup, restore cookies and search them by domain names;
private browsing is also supported.

Cookie Quick Manager is designed for developers, testers or people
concerned about their privacy on the Internet.

This WebExtension is compatible with Firefox 57 and is inspired by addons like
[Cookies Manager+](https://addons.mozilla.org/fr/firefox/addon/cookies-manager-plus/) and
[Advanced Cookie Manager](https://addons.mozilla.org/fr/firefox/addon/cookie-manager/)
whose development has been discontinued due to the withdrawal of the support for "Legacy" extensions.

# Features

- Search: A user can search for cookies of a domain and subdomains which depend on it.
- Edit: All the attributes of a cookie can be modified: domain, path, name, value,
expiration date, as well as secure and httponly flags.
- Export: The export and import of a cookie or cookies from a domain in JSON or Netscape format is just as easy.
- User friendly: Each parameter and functionality is briefly described when the mouse is over the element.
- First-Party Isolation: Supported with some limitations from Firefox 59 (included) to Firefox 62 (not included),
and without limitations on Firefox 62 (sheduled on September 2018).
- Contexts: Contexts (also called containers, contextual identities, or stores) are supported.
A user can copy cookies from a container to another.

# Privacy

This addon does not store or leak any personal information.

It requires the following permissions to operate:

* Host permission for all urls: This allows you to edit the cookies of any visited site,
* Cookies: Allows access to the browser's cookie store,
* ActiveTab: Allows access to the currently consulted url, and its favicon if it exists.
* Storage: Allows the storage of the following user settings:
    - size of the windowed mode,
    - protected cookies (only the name of the domains),
    - the template used to import/export the cookies,
    - the skin.
* Browsing data: Enables extensions to clear the data that is accumulated while the user is browsing (LocalStorage here).
* Contextual Identities: Allows the addon to list the containers,
* Privacy: Access and modify various privacy-related browser settings (the FirstPartyIsolation flag here).

# Installation from sources

- open Firefox
- enter "about:debugging" in the URL bar
- click on "Load Temporary Add-on"
- open the file "./src/manifest.json" on the repository you just cloned
- that's it !

More information at [developer.mozilla.org](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Debugging).

# Support & source code

The extension is in full development with the launch of Firefox Quantum;
questions, bug reports and feature requests are open on the
[GitHub repository](https://github.com/ysard/cookie-quick-manager/issues).

# License

[GPLv3](https://github.com/ysard/cookie-quick-manager/blob/master/LICENSE).