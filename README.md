# Crumb Flix FAQ

This is a simple FAQ page to answer some basic questions about the Service.

## Configuration/Usage

Check the [Wiki](https://github.com/1activegeek/status/wiki) for details on configuration and usage.

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
