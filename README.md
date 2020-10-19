# LSY Tech Radar

This repository contains the CSV file of our [technology radar](https://lhsystems.github.io/technology-radar/).

## Implementation details

We are using the Thoughtworks Technology Radar's [engine](https://www.thoughtworks.com/radar/how-to-byor), hosted by Thoughtworks to visualize our CSV file as a Tech Radar.
The only difference is that instead of Google Sheets, we host and maintain our CSV file inside this repository.

The Thoughtworks Radar engine fetches the CSV that you provide as an URL in the `sheetId` query parameter, and then renders the radar. Eg: `https://radar.thoughtworks.com/?sheetId=<path_to_your_csv_with_uri_encoding>`.
We've set up a simple client-side redirection on the `gh-pages` branch of this repository to redirect the above URL to the raw CSV file inside this repo (on the `master` branch).

In case there are changes to the CSV file, the GitHub page URL of this repository (https://lhsystems.github.io/technology-radar/) will always redirect the visitor to the rendered radar of the latest version of the CSV file on `master`.

## Contributing

Please check out the [contributing guideline](CONTRIBUTING.md) before sending a pull request!
