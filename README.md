# COVID-19 World
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

<!-- ALL-CONTRIBUTORS-BADGE:END -->

COVID-19 is the infectious disease caused by the most recently discovered coronavirus. This new virus and disease were unknown before the outbreak began in Wuhan, China, in December 2019.

With the oubreak world-wide and increasing number of active patients, there are many efforts to project the data in some form for people to follow and understand.

`COVID-19 World` is yet another Project to build a Dashboard like app to showcase the data related to the COVID-19(Corona Virus).





# Analytics

`COVID-19 World` provides some basic but useful analytics to understand the depth and gravity of the situation.

## Home Page 

`Home` page provides the statistics on the data from country `India`, i.e, my Country.

- Total Number of Confirmed Cases
- Total Number of Active Cases
- Total Number of Recoverd Cases
- Total Number of Deaths
- Trends 
    - Number of New Cases Found per Day
    - New Cases Trends - % Changes Per day
    - Trends Change of Confirmed vs Active vs Recovered vs Deaths
- State Data Break-ups
- State: Most Affected
- State: Most Recovered
- District Wise Data Breakups for a State


`World` page provides the rich features and stats about the Countries affected by the virus:

- Compare Countries over the Weeks: Compare the Spreads by Selecting the Countries of your choice. The selection also gets persisted into the localstorage of the browser so that, you can montor those over times.
- Countries with Overall Death Impact
- Countries Recovering Well
- Total Cases and Splits
- Countries with maximum Deaths Today
- Major Country Spreads

## Countries Page 

`Countries` page list down all the countries affected by the Virus today. This page allows to:

- Find a Specific Country by type-down search.
- Select a Country to drill down on the details.
- Sort the Countries based on, total cases, active cases, deaths and recovery.

## Information Page

`Information` page provides general information about COVID-19.

## News Page 

`News` page shows the curated news about COVID-19 and Health from different publications over the globe.


# To Run from the Source

`COVID-19 World` is a ReactJS based project uses API from various sources to visualize and analyse the data to represent in most useful manner. Once you clone/fork the repo, you should be able to run it locally.

Make sure, you have NodeJS installed. Preffered Version of nodeJs is >=12.7.0

With Yarn, Do the followings:

- `yarn install`: Install the Projcect Dependencies
- `yarn start`: Start the app in dev mode. The app will be available on [https://localhost:4000](https://localhost:4000)
- `yarn build`: Build the app for production.

With NPM, Do the followings:

- `npm install`: Install the Projcect Dependencies
- `npm run start`: Start the app in dev mode. The app will be available on [https://localhost:4000](https://localhost:4000)
- `npm run build`: Build the app for production.

# Credits and Motivations


- [Coronavirus NovelCOVID API](https://github.com/NovelCOVID/API)
- [COVID Time-Series API(Pomber)](https://github.com/pomber/COVID19)
- Corona State Data(India)
- [API for News](https://newsapi.org/)

# Technologies

This app is built from the scratch using following User Interface Technologies:

- [ReactJs]
- [Bootstrap]
- [Recharts]

