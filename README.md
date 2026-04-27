🌦️ Weather Data Collector (OpenWeather API)
📌 Project Description
This Python script allows users to retrieve weather data for selected cities in Germany using the OpenWeather API.
The application:


collects geographic coordinates of cities,


retrieves weather forecasts,


processes and structures the data into a pandas DataFrame.



⚙️ Features


User input of multiple cities via a GUI (Tkinter)


Geocoding API integration (latitude and longitude retrieval)


Weather Forecast API integration


Structured weather dataset including:


temperature


feels-like temperature


humidity


pressure


wind speed


weather description





🧰 Requirements
Install the required libraries:
pip install requests pandas
Tkinter is usually included with standard Python installations.

🔑 API Setup


Sign up at: https://openweathermap.org/


Get your API key


Insert it into the script:


API_key = "YOUR_API_KEY"

🚀 How to Run
Run the script:
python weather_app.py
Then:


Enter city names in the input dialog (e.g. Berlin, Hamburg, Munich)


The program will output weather data as a pandas DataFrame in the console



📊 Example Output
citytempfeels_likehumiditypressurewind_speeddescriptionBerlin17.115.83410233.4scattered cloudsHamburg12.911.54710242.7scattered clouds

🧠 How It Works


User enters a list of cities


Geocoding API returns coordinates (lat, lon)


Weather API retrieves forecast data


Data is parsed and stored in a structured DataFrame



📌 Possible Improvements


Add weather visualizations (matplotlib / seaborn)


Export data to CSV or Excel


Build a web app using Flask or Streamlit


Extend forecast to multiple days instead of a single snapshot



If you want, I can also:
✔ clean and refactor your code
✔ turn this into a Streamlit web app
✔ add charts and visual analytics
✔ or export results directly to Excel automatically 
###################################################################################################################
🌦️ Weather Data Collector (OpenWeather API)
📌 Opis projektu

Ten skrypt w Pythonie pozwala pobrać dane pogodowe dla wybranych miast w Niemczech, korzystając z API OpenWeather.
Aplikacja:

pobiera współrzędne geograficzne miast,
pobiera prognozę pogody,
przetwarza dane do formatu tabelarycznego (pandas DataFrame).
⚙️ Funkcjonalności
Wprowadzanie listy miast przez użytkownika (GUI – Tkinter)
Pobieranie współrzędnych geograficznych (Geocoding API)
Pobieranie danych pogodowych (Forecast API)
Tworzenie zestawienia danych pogodowych:
temperatura
temperatura odczuwalna
wilgotność
ciśnienie
prędkość wiatru
opis pogody
🧰 Wymagania

Zainstaluj wymagane biblioteki:

pip install requests pandas

Tkinter jest zwykle dostępny domyślnie z Pythonem.

🔑 Konfiguracja API
Zarejestruj się na: https://openweathermap.org/
Pobierz swój API key
W kodzie wstaw:
API_key = "TWOJ_API_KEY"
🚀 Jak uruchomić

Uruchom skrypt:

python weather_app.py

Następnie:

Wprowadź miasta w oknie dialogowym (np. Berlin, Hamburg, Munich)
Otrzymasz dane pogodowe w konsoli jako tabela pandas DataFrame
📊 Przykładowy wynik
city	temp	feels_like	humidity	pressure	wind_speed	description
Berlin	17.1	15.8	34	1023	3.4	scattered clouds
Hamburg	12.9	11.5	47	1024	2.7	scattered clouds
🧠 Jak to działa
Użytkownik wpisuje miasta
API geokodowania zwraca współrzędne (lat, lon)
API pogodowe zwraca dane meteorologiczne
Dane są przetwarzane do DataFrame
📌 Możliwe rozszerzenia
wykresy pogodowe (matplotlib / seaborn)
zapis do CSV lub Excel
interfejs webowy (Flask / Streamlit)
prognoza na kilka dni zamiast jednej próbki

Jeśli chcesz, mogę Ci też:
✔ poprawić kod (refaktoryzacja + obsługa błędów)
✔ zrobić wersję Streamlit (aplikacja webowa)
✔ dodać wykresy pogody
✔ albo zapisać wyniki do Excela automatycznie
