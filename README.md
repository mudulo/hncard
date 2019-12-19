# HN Card - Profile Overlay for HN

**Available for Chrome and Firefox.**

![Screenshot of HNProfile](https://github.com/mudulo/hnprofile/raw/master/screenshot.png)

HN Card lets you quickly glance at a user's profile without leaving the page
you're on. You can quickly see a user's bio, karma, account age - plus quick
links to their comments and submissions. Plus, if they have an email address
or Github account in their bio (providing they've set up a Gravatar or Github
avatar), you'll see their avatar too.

HN Card is available for Chrome and Firefox. You would want to
grab a copy from the appropriate extensions / addon store.

<!--- ### Safari: --->

<!-- Download here: https://github.com/timdavies/hnprofile/releases/download/1.0/hnprofile.safariextz --->

### Chrome:

Download here: https://chrome.google.com/webstore/detail/hn-card/medlpimkoihjpkajkdlkjmphcdgldgkm

### Firefox

Download here: https://addons.mozilla.org/en-US/firefox/addon/hn-card/

<!---## Setting up to build from source

1. Make sure you have Node.js and NPM installed.

1. Make sure you have gulp installed:

    `sudo npm install gulp -g`

1. Install the required packages for HNProfile:

    `npm install`

1. Run `gulp` to build the extension for all platforms. If you're developing,
  I recommend using `gulp watch` instead. This keeps track of file changes
  and runs gulp as required.

1. If you plan to build for Firefox (and if you're planning to submit a pull
  request, please take the time to test in all browsers if you can), you will
  need to [install the Mozilla Addon SDK](https://developer.mozilla.org/en-US/Add-ons/SDK/Tutorials/Installation).--->

## Testing & Debugging
<!--Make sure you've run `gulp` or are running `gulp watch` and then follow the
instructions for the browser you want to build for.

### Safari:
To add an extension to Safari, you'll need a developer license. They're free -
but you'll need to sign up at http://developer.apple.com/. Once you've set up
the license, go to the Develop menu and click on "Show Extension Builder". Then
click on the "+" icon in the bottom left and click "Add Extension...". Navigate
to the project directory, then go into `build/safari` and select the folder
"hnprofile.safariextension". Finally, to install the extension, click on the
"Install" button at the top right.

Every time you make changes to the extension, once gulp has built them, you'll
need to hit the "Reload" button. -->

### Chrome
Clone or download this repository, open chrome://extensions (type in address bar), click "Load Unpacked", then select the chrome folder.

### Firefox
Clone or download this repository, open about:debugging (type in address bar), click "This is Firefox", then "Load Temporary addon" then browse to the firefox folder and select manifest.json.

## Contributing
Think you could help debug, test and package, a Safari extension, please feel free to fork this
repository, Currently quickly rebuilt this for Chrome and Firefox
As HNProfile supports Chrome, Safari and Firefox, please test your code in all
browsers if you can. If you can't (e.g. you're on Linux and can't test in
Safari), please let me know and I'll test for you.
