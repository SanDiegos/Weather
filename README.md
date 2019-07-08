# Weather
WeatherApp

Uruchamia się na http://localhost:8080/weathergui. Dane pogodowe są pobierane z serwisu https://www.metaweather.com/api/ o pełnej godzinie każdego dnia lecz dane w serwisie są aktualizowane kilka razy dziennie (prawdopodobnie 5 razy) więc w ciągu całego dnia przez klika godzin wpisy będą się powtarzały. Ze względu na powyższe dane w bazie danych zapisywane są z dwoma datami tzn. a datą i godziną faktycznego utworzenia pomiarów według podanych w serwisie pogodowym oraz z datą i godziną wykonania requestu a tym samym zapisania danych w bazie danych. Na GUI dane pobierane są według godziny wykonania requestu.
