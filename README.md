Rally Enhanced Burndown Chart
======================

![Title](https://raw.github.com/RallyApps/EnhancedBurndownChart/master/screenshots/title-screenshot.png)

## Overview

The Enhanced Burndown Chart app exposes the health of an Agile release that is sometimes masked with a typical burndown. 

## How to Use

### Running the App

If you want to start using the app immediately, create an Custom HTML app on your Rally dashboard. Then copy App.html from the deploy folder into the HTML text area. That's it, it should be ready to use. See [this](http://www.rallydev.com/help/use_apps#create) help link if you don't know how to create a dashboard page for Custom HTML apps.

Or you can just click [here](https://raw.github.com/RallyApps/EnhancedBurndownChart/master/deploy/App.html) to find the file and copy it into the custom HTML app.

### Using the App

The chart captures the original planned work left to do above the baseline and tracks changes in scope (work added) below the baseline.

Knowing both metrics helps a team predict a release completion date by computing two trend lines based on the committed work and work added (see figure below). The intersection of both trends lines provides an expected release date based on current release velocity. Current release velocity means that the team continues to accept work at the same rate.

## Customize this App

You're free to customize this app to your liking (see the License section for details). Since this app uses a very old version of Rally's SDK, the app is only presented in its deployed form.

## License

EnhancedBurndownChart is released under the MIT license.  See the file [LICENSE](https://raw.github.com/RallyApps/EnhancedBurndownChart/master/LICENSE) for the full text.
