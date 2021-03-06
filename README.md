## Weather-app

https://weather-app-meta-weather.vercel.app/

https://weather-app-meta-weather.herokuapp.com/

https://github.com/coding-to-music/WeatherApp

Excellent Original version by: https://github.com/besartm7/WeatherApp

Their version viewable at: [weatherapp-besartm.vercel.app](https://weatherapp-besartm.vercel.app/)

This project bootstrapped with Next.js Framework.
There is public Rest API https://www.metaweather.com/api/ which I'm using to query and get data.

## Refresh node packages

- Delete package-lock.json file.
- Delete node_modules.
- Run npm update
- Run npm install

```java
npx browserslist@latest --update-db
rm package-lock.json
rm -rf node_modules/
npm update
npm audit fix --force
npm install
npm outdated | awk 'NR>1 {print $1"@"$4}' | xargs npm install
npm run dev
```

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3800](http://localhost:3800) with your browser to see the result.

Build project:

```bash
npm run build
```

Run build project:

```java
npm run start
```

View:
![WeatherApp](https://i.pinimg.com/originals/7c/8f/8d/7c8f8d6c1d31299983169c717250ee9c.png "WeatherApp")

## Installation on Vercel

```java
npm i -g vercel
```

# to create a new project

```java
vercel init svelte film-api-svelte-mongodb
```

# now that this project is created, you can deploy it to Vercel

```java
vercel
```

Environment variables:

```java
vercel env add
```

Then the variable
Then the value
Then the environment(s)
