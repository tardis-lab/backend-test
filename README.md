# Tardis Labs - Back-end test

Welcome to the technical test for back-end developers. For this test, you'll need to make a simple HTTP server that responds with data fetched from [weather API](https://www.weatherapi.com/docs/). Make sure to read all the way to the end before starting.

## Requirements

- Make a private repo on Github
- Use TypeScript or JavaScript, ideally TypeScript. Other than that you can freely choose which libraries you use
- Create a server that handles a single route. If using REST then `GET /weather`, input for which should be `lat-long` (geolocation)
- The endpoint must handle all possible inputs (right and wrong) and try to think of all possible edge cases.
- Include a `README.md` that describes the steps needed to run your project and anything you might like to clarify
- You are done! invite [tarunmittal](https://github.com/tarunmittal) to the repo for reviewing and email your point of contact

### Response

The endpoint should respond with a payload similar to this, based on messages' text (more on that below). The provided values are all realistic but fake:

```
{
  "timestamp": "2024-06-21T06:05:48.332Z",
  "cityName": "Jodhpur",
  "temperature": {
    "celcius": 45,
    "farenheit": 115,
  },
}

## Bonus Points

- Use Typescript
- no use of `any` and everything is strongly typed
- Use reverse geo-coding to get the city name from the lat-long

