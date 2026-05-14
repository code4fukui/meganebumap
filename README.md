# MEGANEBU MAP

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An interactive map for "seichi junrei" (holy site pilgrimage) to the real-world locations featured in the opening sequence of the anime *Meganebu!* (メガネブ！).

## Demo

**[http://codeforfukui.github.io/meganebumap/](http://codeforfukui.github.io/meganebumap/)**

## Features

-   📍 Interactive map displaying all filming locations from the anime's opening.
-   📸 Click a marker to see a photo of the location, scene details, and a link to open in Google Maps.
-   🗺️ A scrollable list of all locations below the map for quick browsing and navigation.
-   🛰️ Center the map on your current GPS location to find nearby spots.
-   🔍 Zoom to fit all locations on the map with the "View All" button.

## Data and APIs

-   Location data is sourced from the [Meganebu! Location RDF](https://linkdata.org/work/rdf1s1093i) open dataset on Linkdata.org.
-   The interactive map is powered by the [Google Maps API](https://developers.google.com/maps).

## Development Setup

To run this project locally, you need a Google Maps API key.

1.  Clone the repository.
2.  In `index.html`, replace the API key in the `<script>` tag URL with your own:
    ```html
    <script src="https://maps.google.com/maps/api/js?key=YOUR_API_KEY_HERE&language=ja"></script>
    ```
3.  Open `index.html` in a web browser.

## License and Attribution

This project is licensed under the MIT License — see [LICENSE](LICENSE).

The included `fukuno.js` library is provided under a CC BY license by Taisuke Fukuno (@taisuke).