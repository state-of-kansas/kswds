# State of Kansas Web Design System

The same [USWDS](https://designsystem.digital.gov/) you know and love, with Kansas theming!

Forked from the [NASA Web Design System](https://github.com/bruffridge/nasawds).

### KS Theme customizations

* Minor tweaks to colors in `_uswds-theme-color.scss`
* Headings use helvetica instead of source sans pro font in `_uswds-theme-typography.scss`
* Kansas favicons in `theme/favicons`
* Dark header option and other minor visual tweaks in `_uswds-theme-custom-styles.scss`
  * To use the dark header option, add the `.usa-header--dark` class to the `<header>` element.
  * For the close icon in the mobile slideout menu to appear white instead of dark gray replace `close.svg` with `close-white.svg` in this line of html `<button class="usa-nav__close"><img src="/assets/img/close.svg" alt="close"></button>`

### How to Use

Like USWDS, KSWDS has two installation options: 

* **Direct download** - Download the .zip file attached to the latest stable [release](https://github.com/state-of-kansas/kswds/releases) under the assets section. Extract then add the files to your project's code base. For more details see [this section](https://designsystem.digital.gov/documentation/developers/#download) in the USWDS developer documentation.

* **Install using npm** - KSWDS is available as an [npm package](https://www.npmjs.com/package/kswds). To install via npm, follow [these instructions](https://designsystem.digital.gov/documentation/developers/#install-using-npm), but where it says `uswds` replace with `kswds`.

For more detailed installation and usage instructions see the [USWDS developer documentation](https://designsystem.digital.gov/documentation/developers).

### Updates

KSWDS updates to the latest version of USWDS automagically. (thanks [GitHub Actions](https://github.com/features/actions)!)

KSWDS uses a GitHub Action workflow to check for an updated version of USWDS every 15 days and updates itself automatically with the latest version on the develop branch, and releases a beta pre-release on GitHub and NPM. A two week window is provided for testing. Any issues found should be opened in this repository. After two weeks, if no unresolved issues are present in this GitHub repository, a GitHub Action workflow creates a new stable release on GitHub and NPM and merges develop into master.

