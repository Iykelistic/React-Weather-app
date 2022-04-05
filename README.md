# React Weather

<img src="https://user-images.githubusercontent.com/25284536/90274607-2535a000-de76-11ea-9d21-ab8c3e68b3a9.png" width="400"> <img src="https://user-images.githubusercontent.com/25284536/90274626-29fa5400-de76-11ea-97a7-c6b67ec2f66a.png" width="400">

Weather App built with React.
[Live Demo](https://esnz-reactweather.netlify.app/)

## Tech Stack

**React, Typescript, Redux, StyledComponents**

## Features

- **Weather forecast for any city or place**
- **Find user location weather by utilizing GeolocationAPI**
- **One-click Celcius to Fahrenheit conversion and vice versa**
- **Dark Mode**

## Getting Started

First you need an API key from OpenWeatherMap, you can get one by creating an account on their website.
After you got your API key, create a **.env** file at root directory of project, copy the line below to the file and replace YOUR_KEY with your OpenWeatherMap API Key.

```
REACT_APP_WEATHER_API_KEY=YOUR_KEY
```

Finally clone this repository, install dependencies and run the local server



```bash
cd reactweather
npm install
npm start
```

## Credits

[OpenWeatherMap](https://openweathermap.org/ 'OpenWeatherMap') (Weather data API)

[Icons8.com](https://www.icons8.com 'Icons8.com') (Weather icons)


## Deployment Instructions To Docker

1. Create a Dockerfile with the following contents:

    - **FROM nginx**
    - **COPY container /**
    - **COPY build/usr/share/nginx/html**
    
2. Build the React application - This process generates the build/ directory containing static files

3. Build the Docker Image, it will create a runnable docker image.

4. Publish the Docker Image to some repository or run it on the local machine.
