This is a simple Python script that grabs the most current METAR weather report from any airport in the US. It uses the tabulate library to display data in an organized way, it includes imperial and metric measurements for most categories, but adding in the visibility and wind speed is still a work in progress.

The API is sourced from [CheckWX API](https://www.checkwxapi.com/) and is completely free, and allows for up to 3,000 requests every day at no charge

Eventually this code will be implemented into a web app, once I have the time to learn Flask or Django. You can simply put this code into any code editor (it was compiled in VS Code) and run the script.

Feel free to add on to this on your own, it's very basic and has room to add some cool features. 

Below there is an example METAR from Los Angeles International Airport (KLAX)

Have fun!


Example output from KLAX:

| Station | Temperature | Dew Point | Wind | Visibility | Pressure | Conditions |
|---------|------------|-----------|------|------------|----------|------------|
| KBOI    | 12°C       | 5°C       | 10 kt | 10 sm      | 1015 hPa | Clear      |


**Github refused to display it how it displays in the code editor but it should look similar to this**
