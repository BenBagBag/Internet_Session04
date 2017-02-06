GeoJSON for Seattle Restaurants
-------

* What does this do?
  * Prints a list of restaurants in downtown Seattle and their health inspection data
  * Ranks them by either their high score, average score, or total number of inspections
  * Results can be in descending or ascending order
  * Outputs a JSON file that can be used at [geojson.io](http://geojson.io/) to create a map of restaurants
    * Restaurants will be flagged green, yellow, or red based on safety rating

* How to use it
  * `$python3 mashup5.py [sort option] [number of results (optional)] [reverse (optional)]`
    * Sort options: `highscore`, `average`, `most_inspections`
    * Number of results: optional, defaults to 10
    * Reverse: "reverse" will give you the lowest results first (I assume you usually want to know where you *should* eat!)
  * Navigate to [geojson.io](http://geojson.io/) and drag the `my_map.json` file into the editor shown there
  * A map of the restaurants will appear
