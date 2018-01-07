# firefox-security-settings
Firefox security hardening via system wide locked preferences

Configurations aggregated from these sources:
 - https://vikingvpn.com/cybersecurity-wiki/browser-security/guide-hardening-mozilla-firefox-for-privacy-and-security
- https://web.archive.org/web/20160606093146/https://vox.space/blog/98/mozilla-firefox-security (archived)
- https://www.privacytools.io/#browser

# Installation (system-wide configuration)

1. Clone the repository
2. Copy files
  - `local-settings.js` -> `/usr/lib/firefox/defaults/pref/`
  - `mozilla.cfg` -> `/usr/lib/firefox/`
3. Re/start Firefox
4. Visit `about:config`, locked preferences will be shown in italic

# Alternatives
If you want a more comprehensive solution, check this repository from @pyllyukko https://github.com/pyllyukko/user.js
