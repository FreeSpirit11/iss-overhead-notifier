# ISS Overhead Notifier

This Python script checks if the International Space Station (ISS) is overhead near your location during the night and sends an email alert.

## Getting Started

Before running the script, make sure to provide your email credentials (`MY_EMAIL` and `MY_PASSWORD`) and your location's latitude (`MY_LAT`) and longitude (`MY_LONG`).

To find your latitude and longitude, you can use the website [latlong.net](https://www.latlong.net/). Enter your address or city name in the search bar, and the website will display the latitude and longitude coordinates.

## Prerequisites

Make sure you have the `requests` library installed. If not, you can install it using pip:

```bash
pip install requests
```

## How to Use

1. Clone the repository or download the script.
2. Open the script and set your email credentials and location coordinates.
3. Run the script.
4. The script will run continuously and check for the visibility of the ISS in the night sky.
5. If the ISS is visible near your location, you will receive an email alert.

**Note:** The script will check the ISS position every minute. To change the frequency, modify the `time.sleep(60)` value.

## Acknowledgement

This project is a part of the "100 Days of Code" challenge by Angela Yu.

## Author
- [Mansi Yadav](https://github.com/FreeSpirit11/iss-overhead-notifier)
  
Now, whenever an email comes, you can look up and watch the ISS passing over your head!
