# Sleep

A personal sleep tracker for Fitbit Air, made for iPhone (add it to the home screen from Safari).

- Counts every wake-up in the night, like Whoop's disturbances: Google Health's short awakenings plus awake periods, merged when less than a minute apart.
- Shows the night minute by minute (stages, wake-ups, time out of bed, heart rate) and trends from 7 nights to a year.
- Runs entirely in the browser. The phone signs in to Google itself (authorisation code + PKCE) and reads the Google Health API read-only. Data is kept in the browser's own storage on the device. There is no server, no analytics and no third party.
- Until it is connected it shows clearly labelled sample data.

To use it you need your own Google Cloud OAuth client with the Google Health API enabled, with this site's address as an authorised JavaScript origin and redirect URI.

Not a medical device.
