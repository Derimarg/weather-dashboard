# weather-dashboard
>  link web page  : https://derimarg.github.io/weather-dashboard/

## Description

A web application that allow to search for a city to get the current weather and 5 day forecast. Cities that users previously search will be displayed as history.

### Features

- This weather dashboard will give the user the ability of search for a city.

- will show current and future conditions of weather for that city.

- For current weather conditions for that city, will be displayed a list with city name, the date, an icon representation of weather condition, the temperature, the humidity, the wind speed, and the UV index.

     - The UV index will be presented with a color that indicates whether the conditions are favorable, moderate, or severe.
        - Favorable: Green
        - Moderate: Yellow
        - Severe: Red

    - The Temperature will show in Fahrenheit.
        ```html
        -> Convertion used

        F = C x 1.8 + 32
        C = K - 273.15 
    
        F = (K - 273.15) x 1.8 + 32 

        -> Funtion that handle convertion:

        function k2f(K) {
            return Math.floor((K - 273.15) * 1.8 + 32);
        }
        ```

         > If you want a different unit, here are a list of convertions:

        ```html
            Converting Temperatures

            It is sometimes necessary to convert temperature from one scale to another. Here is how to do this.

            1. To convert from oC to oF, use the formula: oF = oC x 1.8 + 32.
            2. To convert from oF to oC, use the formula: oC = (oF-32) ÷ 1.8.
            3. To convert from K to oC, use the formula: oC = K – 273.15
            4. To convert from oC to K, use the formula: K = oC + 273.15.
            5. To convert from oF to K, use the formula: K = 5/9 (oF – 32) + 273.15.
            6. To convert from K to oF, use the formula: oF = 1.8(K – 273.15) + 32.

          -> Having the convertion you would like to use, replace it in this function:

            function k2f(K) {
                return Math.floor("insert convertion to use");
            }
        
         ```

- Will display Future weather conditions for that city presenting the next 5 days showing a list with date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity.

- City search will be added to a history and displaye below.

- Clicking on a city in the search history will display current and future conditions for that city

- Will allow to clear the history.


    Example:

![Project Demo](./resources/videos/demo.mp4)
---

### Table of Contents

- [Weather-dashboard](#weather-dashboard)
- [Description](#description)
- [Download](#how-to-download)
- [License](#license)
- [Author Info](#author-info)
---

#### Technologies
- HTML
- CSS
- JavaScript
- jQuery
- Font Awesome
- Bootstrap
- OpenWeather One Call API

[Back To The Top](#weather-dashboard)

---

>## How To Download

- Simply copy the **SSH** to the terminal or Download the **ZIP File**:

>## Installation

 Use the follow command at your terminal, **git clone** (Create a working copy of a local repository):

```html
git clone git@github.com:Derimarg/weather-dashboard.git
```

After cloned the repository, create your own repository, copy the files to your repository and type in your terminal the follow commands. 

```html
git status

git add -A

git commit -m "Message to commit."

git push or git push origin main
```

[Back To The Top](#weather-dashboard)

---

## License

MIT License

Copyright (c) 2021 Derimar Gray

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#weather-dashboard)

---

## Author Info

- GitHub - [Derimar Gray](https://github.com/Derimarg)

[Back To The Top](#weather-dashboard)