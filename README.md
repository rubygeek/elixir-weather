# ElixirWeather

Inpsiration Microservices in Phoenix: https://teamgaslight.com/blog/microservices-in-phoenix-part-1

A [worker](/lib/elixir_weather/worker.ex) - is set to read the weather every hour from [WeatherUnderground](wunderground.com) and will use a [Phoenix Model](web/models/weather.ex) to save to a database. The UI is simple for now, but will be improved.

Todo:

* get the forcast temp for each day
* collect the high from the max of previous days temps
* compare the results to see how accurate the forecast was

Future Ideas:

* find other weather apis or do screen scraping to see who has the most accurate weather forecast



To start your Phoenix app:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.


