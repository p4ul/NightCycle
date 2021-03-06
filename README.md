## NightCycle

Changes a users Sublime Text 2 colour scheme automatically according to what time of day it is.

## Usage

Install in your preferred fashion, then restart Sublime Text.

If desired, configure your time periods and desired colour schemes by editing the config file, which can be accessed through these steps:

Preferences menu -> Package Settings -> NightCycle -> Settings

The default time periods are 'day' and 'night', switching between Solarized Light and Solarized Dark at 0700 hours and 1700 hours respectively.

Time periods should not overlap, as this could result in rapid switching between the overlapping colour schemes.

If no configured time period is found for a given time, the current colour scheme will continue to be used.

Start and end times must use 24 hour time in the format Hour:Minute in order to be recognised, use the default config as a guide if unsure.

## Acknowledgements

Credit goes to urbushey on Reddit for giving me the idea for this plugin