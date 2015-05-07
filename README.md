# HNProfile - Profile Overlay for Hacker News

HNProfile lets you quickly glance at a user's profile without leaving the page
you're on. You can quickly see a user's bio, karma, account age - plus quick
links to their comments and submissions. Plus, if they have an email address
or Github account in their bio (providing they've set up a Gravatar or Github
avatar), you'll see their avatar too.

HNProfile is available for Chrome, Safari and Firefox. Most users will want to
grab a copy from the appropriate extensions / addon store.

### Safari:

Download here:

### Chrome:

Download here:

### Firefox

Download here:

## Building from source

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
  need to [install the Mozilla Addon SDK](https://developer.mozilla.org/en-US/Add-ons/SDK/Tutorials/Installation).

## Contributing

As HNProfile supports Chrome, Safari and Firefox, please test your code in all
browsers if you can. If you can't (e.g. you're on Linux and can't test in
Safari), please let me know and I'll test for you.
