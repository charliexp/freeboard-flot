Freeboard Flot Widget
=====================

This is a charting plugin for [Freeboard][fb] that uses [Flot][flot] to display
attractive charts.

[fb]: https://github.com/Freeboard/freeboard
[flot]: http://www.flotcharts.org/

## Installation

Just drop `flot.plugins.js` onto your web server, and add it to the list of
loaded plugins, after `freeboard.js`.

## Usage

 1. Add a new pane.
 2. Add a new widget to that pane.
 3. Select `Flot Line` as the type.
 4. Enable `Show Points`.
 5. In the value section, insert the following (adapted for your datasource):
`
[[datasources["data"]["x-axis"], datasources["data"]["y-axis"]]
`
 6. Save the widget!
