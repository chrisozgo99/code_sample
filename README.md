# Paul Easton Basketball App Code Sample
A code sample from an app I have been working on for a renowned basketball trainer, Paul Easton. This code sample comes from a Beta version of the app, around v0.8.0. I own the rights to the intellectual property of this app, but due to lisencing agreements, I cannot make the entire v1.0 code open-source. The full working version of the app is available for [iOS](https://apps.apple.com/ma/app/paul-easton-basketball/id1572211821) and [Android](https://play.google.com/store/apps/details?id=com.pauleastonbasketball).

## Goal
The app aims to make a world-class basketball training experience more accessible to young players who cannot afford it. Most high-quality trainers (including Paul), charge upwards of $75 an hour for a single session which can get quite expensive if you train 5-6 days a week (a necessity to play college basketball).

## Functionality
Paul uploads monthly training drills and videos to the app. Users can then watch the videos, record themselves performing the drills, and send them to Paul for feedback within 12 hours. This service is available for $9.99 a month. A premium version allows the user to get feedback on the jumpshot as well, and is available for $12.99 a month.

## Stack
This app uses a React Native frontend, with a Google Firebase backend. There is also an adjacent admin app which was built using ReactJS. Paul's training videos are stored in an AWS S3 server.
