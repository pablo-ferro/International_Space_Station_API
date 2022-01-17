# International Space Station API

- Update! Now the API gives back Astronauts in the space, not only in the ISS, but also the Shenzhou 13.

Trying the basic functionalities of the ISS API. How many people are in the Space right now? Let's code and see.

The API and all the information related can be found here: http://open-notify.org/Open-Notify-API/People-In-Space/

We get the information by connecting to the site:
```
response = requests.get("http://api.open-notify.org/astros.json")
print(response.status_code)
```
