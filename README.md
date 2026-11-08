# Fuel log

A small phone-friendly page (installable to the Android home screen) that shows
refuels and fuel consumption produced by a private mileage tracker.

The page contains no data. It reads `status.json` and `fuel_history.json` from a
GitHub gist whose ID is given in the URL fragment:

    https://janmdvoracek.github.io/fuel-log/#<gist id>

The fragment is never sent to a server; the ID is then kept in the browser's
local storage so the home-screen icon works without it.
