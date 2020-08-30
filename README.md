# weather-forecast-proxy

This app has two implementations of WeatherForecastRetriever.
One of them is a class with delays in calling the methods and the other is a proxy.
It calls refreshData() method lazily, so eventually the weather forecast is retrieved faster.

