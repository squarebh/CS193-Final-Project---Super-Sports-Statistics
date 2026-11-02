# CS193-Final-Project---Super-Sports-Statistics

Super Sports Statistics provides a free way for you to find the statistics of sports players.

## The Problem

For me, watching sports is more than just my team winning; instead, I love analyzing various statistics and play calls / types. However, many of the sites online that provide in-depth statistics are usually paywalled, and this hinders me from enjoying my hobby as it is much harder to analyze statistics. This is why I want to make a site that allows me to search any player in any sport and provide statistics based off of specific filters.

## How It Works

I am going to build a website that allows users to find any players statistics in any sport supported by the website. They can also filter each players statistics for specific numbers and see if their recent statistics are over or under that number.

## Tech Stack

I am going to be writing in mostly java. I will be using the HttpClient library, the Jackson processing library, JUnit, standard java libraries, and exception imports. For the MVP, I will be storing data in a JSON file. For external sources, I will be using ESPN's public JSON endpoints accessed through HTTPS with HttpClient GET requests.

## MVP Scope
-Support at least NBA, NFL, and MLB\
-Support searching for a specific player’s stats\
-Support all statistics which are provided by the ESPN tracked stats for all supported sports

## Roadmap

-Support sports like NHL and WNBA\
-Filtering for players based off of jersey numbers\
-Add statistics for overall teams, not just players - like team totals, total shots, etc.\
-Pulling statistics from other websites, like Yahoo Sports, Fox Sports, and CBS Sports (3.0+?)

## Author

Matthew Cheng

