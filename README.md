# redmond-syntax theme

An Atom syntax theme for fans of the Visual Studio Blue theme.

This is a syntax theme; for the complimentary UI theme, please also download [redmond-ui](https://atom.io/themes/redmond-ui).

There is plenty left to do, and a few shortcomings in how Atom parses the languages prevent more accurate highlighting.

**Decent Support:**
  * TypeScript
  * CSS
  * Markdown

**Basic Support:**
  * C#

Written by [Steve Ognibene](http://www.legendaryapps.com/) ([@nycdotnet](https://twitter.com/nycdotnet)).

## Example for TypeScript
![redmond-ui-2015-07-13](https://cloud.githubusercontent.com/assets/3755379/8652466/d0b10e18-294c-11e5-81cf-503c88b5fa42.png)

## Example for C Sharp
![redmond-syntax C#](https://cloud.githubusercontent.com/assets/3755379/8398216/0fdbefee-1db4-11e5-9f05-8da4e7fa60b5.PNG)

#### Developing

Uninstall `redmond-syntax` if you have it already.  Make sure the folder is deleted under `~/.atom/dev/packages/`.
Clone the `redmond-syntax` repo, open a command-prompt there, and run `apm link --dev` to symlink the repo to `~/.atom/dev/packages`.
Run a separate instance of Atom in dev mode: `atom --dev` to enable refreshing it when you change the `.less` files in this package.

#### Publishing Checklist
  * Check everything in to GitHub.
  * Update CHANGELOG.md and say vNext with a date.
  * To [publish](https://atom.io/docs/v0.186.0/publishing-a-package), run `apm publish patch`.  (Will need SSH key or run command line from GitHub for Windows to setup)
  * Update CHANGELOG.md with the actual patch version.
