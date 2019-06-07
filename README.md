Companies House Frontend ·
[![Build Status](https://travis-ci.org/companieshouse/ch-frontend.svg?branch=master)](https://travis-ci.org/companieshouse/ch-frontend)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
=====================

Companies House Frontend contains the code you need to build a user interface using components
designed specifically for Companies House platforms and services. Companies House Frontend is a counterpart to the Companies House Frontend codebase and both are required in order to build a complete user interface.

See live examples of Companies House Frontend components, and guidance on when to use
them in your service, in the [Companies House Design
System](https://ch-design-system.herokuapp.com/).

## Contact the team

Companies House Frontend is maintained by the interaction design team. If you want to know more about Companies House Frontend, please contact a member of that team by email or Slack.

## Quick start

There are 2 ways to start using Companies House Frontend in your app.

Once installed, you will be able to use the code from the examples in the
[Companies House Design System](https://ch-design-system.herokuapp.com/)
in your service.

### 1. Install with npm (recommended)

We recommend [installing Companies House Frontend using node package manager
(npm)](docs/installation/installing-with-npm.md).

### 2. Install by using compiled files

You can also [download the compiled and minified assets (CSS, JavaScript) from
GitHub](docs/installation/installing-from-dist.md).

## Browser support

Companies House Frontend will allow you to build services that comply with the [guidance
in the Service Manual][service-manual-browsers].

Currently, Companies House Frontend officially supports the following browsers:

| Operating system | Browser                                | Support     |
|----------------- |----------------------------------------|-------------|
| Windows          | Internet Explorer 8-10                 | functional  |
| Windows          | Internet Explorer 11                   | compliant   |
| Windows          | Edge (latest 2 versions)               | compliant   |
| Windows          | Google Chrome (latest 2 versions)      | compliant   |
| Windows          | Mozilla Firefox (latest 2 versions)    | compliant   |
| macOS            | Safari 9+                              | compliant   |
| macOS            | Google Chrome (latest 2 versions)      | compliant   |
| macOS            | Mozilla Firefox (latest 2 versions)    | compliant   |
| iOS              | Safari for iOS 9.3+                    | compliant   |
| iOS              | Google Chrome (latest 2 versions)      | compliant   |
| Android          | Google Chrome (latest 2 versions)      | compliant   |
| Android          | Samsung Internet (latest 2 versions)   | compliant   |

‘Compliant’ means that the components must look as good and function as well as
they do in other modern browsers.

'Functional' means the components may not look perfect in the given browser, but
must still be usable without errors and without 'looking broken'.

If you are including Companies House Frontend as part of a stylesheet that you are
generating in your application's build pipeline, you will need to [generate and
include a separate stylesheet in order to support Internet Explorer
8](docs/installation/supporting-internet-explorer-8.md).

[service-manual-browsers]: https://www.gov.uk/service-manual/technology/designing-for-different-browsers-and-devices#browsers-to-test-in

## Assistive technology support

Companies House Frontend will allow you to build services that comply with the [guidance
in the Service Manual][service-manual-assistive-technologies].

Currently, Companies House Frontend officially supports the following assistive technologies:

| Software                 | Version        | Type               | Browser                   |
|--------------------------|----------------|--------------------|---------------------------|
| JAWS                     | 15 or later    | screen reader      | Internet Explorer 11      |
| ZoomText                 | 10.11 or later | screen magnifier   | Internet Explorer 11      |
| Dragon NaturallySpeaking | 11 or later    | speech recognition | Internet Explorer 11      |
| NVDA                     | 2016 or later  | screen reader      | Firefox (latest versions) |
| VoiceOver                | 7.0 or later   | screen reader      | Safari on iOS10 and OS X  |

In addition, we test that all content is accessible with keyboard only.

We aim to support [users who adjust or override the colours of websites they visit][how-users-change-colours-on-websites]. We test this by [changing colours in Firefox][changing-colours-in-firefox], by [enabling 'High Contrast' mode in Windows][enabling-high-contrast-mode-in-windows] and by using the [High Contrast plugin for Chrome][high-contrast-plugin-for-chrome].

[service-manual-assistive-technologies]: https://www.gov.uk/service-manual/technology/testing-with-assistive-technologies#what-to-test

[changing-colours-in-firefox]:
https://support.mozilla.org/en-US/kb/change-fonts-and-colors-websites-use

[enabling-high-contrast-mode-in-windows]:
https://support.microsoft.com/en-gb/help/13862/windows-use-high-contrast-mode

[high-contrast-plugin-for-chrome]: https://chrome.google.com/webstore/detail/high-contrast/djcfdncoelnlbldjfhinnjlhdjlikmph?hl=en-US

[how-users-change-colours-on-websites]:
https://accessibility.blog.gov.uk/2017/03/27/how-users-change-colours-on-websites/

## Licence

Unless stated otherwise, the codebase is released under the MIT License. This
covers both the codebase and any sample code in the documentation. The
documentation is &copy; Crown copyright and available under the terms of the
Open Government 3.0 licence.

## Contribution guidelines

If you want to help us build Companies House Frontend, view our [contribution
guidelines](CONTRIBUTING.md).
