# omarchy-liveatc-feeds

Public station catalog for the [omarchy-liveatc](https://github.com/whiskeytuesday/omarchy-liveatc)
plugin. Regenerated daily by a scraper running in a private repo.

Fetched at runtime from:
`https://whiskeytuesday.github.io/omarchy-liveatc-feeds/stations.json`

Do not send PRs here — it's a mirror. Any manual edit will be overwritten on
the next scrape.

## Format

```json
{
  "generated": 1788217256,
  "source": "liveatc.net feedindex + ourairports.com",
  "stations": [
    {
      "icao": "KJFK",
      "name": "John F Kennedy International Airport",
      "city": "New York", "country": "US",
      "lat": 40.6413, "lon": -73.7781,
      "region": "US-B",
      "feeds": [
        {"mount": "kjfk_twr", "name": "KJFK Tower", "status": "up"}
      ]
    }
  ]
}
```

## Attribution

Feed metadata is scraped from [LiveATC.net](https://www.liveatc.net).
Airport coordinates and names from [OurAirports](https://ourairports.com/data/).

If you're LiveATC and this bothers you, see the scraper repo for contact.

## License

MIT for the catalog structure. Underlying feed metadata © LiveATC.net.
