# Crumb Flix FAQ

This is a simple FAQ page to answer some basic questions about the Service.

## Libraries Explained.

**[4k]** These are the 4k files, you need a 4k TV and a fast internet connection to access these. (More in a Dedicated Section Below)

**[Remux]** This library contains the highest Quality 1080p possible. These are the same quality as the BluRay disks we buy.

The below libraries are Dynamic and updated every night at midnight. Pulled from various sources like iMDB, and trakt.tv.
You can view my profile at https://trakt.tv/users/crumb4life and see lists. I believe if you make an account you can also suggest things to be added to each list.

**TV - Kids** -- People still wanted to keep these seperate. But I still needed to manage things easier. So I created this.

**Movies - Kids** -- People still wanted to keep these seperate. But I still needed to manage things easier. So I created this.

**TV - Trending** -- Pulls from the following

https://trakt.tv/shows/trending

https://trakt.tv/shows/watched/weekly


**Movies - Trending** -- Pulled from the following.

https://trakt.tv/movies/trending

https://trakt.tv/movies/watched/weekly

Movies - Hallmark

Movies - Christmas

## Features

*   [X]  Fetch service status dynamically from REST API using UptimeRobot
*   [X]  Fetch incident messages from GitHub Issues
*   [X]  Dynamically display issues as either Incidents or Maintenance
*   [X]  Top level notification bar to indicate overall status
*   [X]  Only displays up to last 30 days of incidents
*   [X]  Select from light or dark theme

## Future, aka Work-In-Progress
*   [ ]  Button to report an issue if everything ok but having a problem
*   [ ]  Subscription button to request getting notifications of status updates (RSS)
*   [ ]  Tooltip popups on individual monitors to provide more "details"
*   [ ]  Parsing of a special format for date/time of maintenance windows
*   [ ]  Don't display maintenance windows after they've passed even if they aren't closed
*   [ ]  Custom theme options
*   [ ]  Selective timeframe of incidents to show
*   [ ]  Choice of showing maintenance windows after they've been closed/past
*   [ ]  Selective timeframe of maintenance to show (if choosing to show after window expired)
*   [ ]  Markdown support
*   [ ]  Modify Github API usage to authenticated to reduce possible API limiting (currently GH only allows 60/hr)
*   [ ]  Render list in alphabetical order, or some order options
*   [ ]  Enable use of StatusCake (option for SC or UR)
*   [ ]  Validate usability on GitLab - possible load balance through DNS to GL and GH
*   [X]  ~~Report no maintenance scheduled if none exist~~
*   [X]  ~~Reduce API calls to GH by combining incident/maintenance request~~
*   [X]  ~~Show paused monitors as Operational instead of Major Outage~~

[MIT Licensed](https://raw.githubusercontent.com/flybaseio/status/gh-pages/LICENSE)
