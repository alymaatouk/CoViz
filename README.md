# CoViz = Covid 19 + Visualization 
[An Interactive Decision Making tool](https://alymaatouk-coviz-covid-app-9v99om.streamlitapp.com/), that represent healthcare analytics regarding the Covid 19 situation in California. A tool that tracks California's COVID-19 cases by region in Real Time!

[Coviz](https://alymaatouk-coviz-covid-app-9v99om.streamlitapp.com/) Provides Californian Health Decision Makers with insights about the Covid 19 trends and situation in different California counties. This enables them to make decisions regarding locking down or opening the counties, and when to apply quarintine measures.

![ezgif-1-4c3e890927](https://user-images.githubusercontent.com/115188345/194586803-2977959b-ce1c-441a-8d7d-b784f63aaac4.gif)

## Context

The COVID-19 pandemic has highlighted the importance of constant and real-time disease surveillance to better control unprecedented local outbreaks. Early on in the pandemic, the state of California came up with its own distinct phases for opening the economy and community activities. These phases were based on county-wide thresholds of daily COVID-19 incidence, test positivity, and availability of ICU beds in the county. While county-wide data is continuously available, a composite picture of a group of counties is not as easy to understand. Such information is especially useful for bigger organizations that serve regional communities, such as universities, corporate companies, or dense urban regions that are highly connected.

## Data 

Drawing from statistics already provided by the [California Department of Public Health](https://covid19.ca.gov/), [John Hopkins University](https://github.com/CSSEGISandData/COVID-19) and [CovidActNow.org](https://covidactnow.org/?s=1337332), I have created a COVID-19 tool that lets the health authorities better understand the regional data and plan the day-to-day decisions.

## Creating the tool in Streamlit

By using Streamlit I was able to convert the Python code into an interactive tool that enables users to select counties of interest and get composite COVID-19 intelligence for the combined region. [You can check out the tool here](https://alymaatouk-coviz-covid-app-9v99om.streamlitapp.com/) and [the source code for the tool here](https://github.com/alymaatouk/CoViz/blob/main/COVID_app.py).

## Glimpse about the App

The application starts with displaying a dashboard that shows composite data of three counties surrounding the University of California Davis (Yolo, Sacramento and Solano). Users can either choose a single county or a combination of multiple counties of their choice to get trends on A) daily new cases per 100,000 population (averaged over the last seven days), (B) daily incidence (new cases), (C) Cumulative cases and deaths and (D) Daily new tests (testing data is available only for a few counties in California).

If you'd like to learn more about how to interpret these metrics, [covidlocal.org](https://covidlocal.org/) is a good resource - but in short, the initial reopening of a community is indicated when daily cases decline for 21 consecutive days and estimates for new cases per 100,000 are below 25 cases per day (Phase 2). Similarly, Phase 3 economic recovery opening is indicated when estimates for new cases per 100,000 are below 10 cases per day.

![Recording #7](https://user-images.githubusercontent.com/115188345/194589199-cea80001-f83a-484e-9be4-aee40e96375e.gif)

