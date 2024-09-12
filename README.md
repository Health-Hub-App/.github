# Welcome to HealthHub
This is the company page for HealthHub, a.k.a, the creators of the world famous **_MealCoach_** app.

Welcome!

## Tech Stuff
The HealtHub ecosystem consists of many services, all working in beautiful harmony :)

### The MealCoach App
The MealCoach app itself is a relatively simple Flutter app that compiles for Apple and Android, it has many features that you can check out [on the repo](https://github.com/Health-Hub-App/mealcoach-app).

It interfaces with the MealCoach API to handle user data and AI communication, which can be found below.

### The MealCoach API
The MealCoach API manages user data and communication with OpenAI. An in-depth description of what this does can be found [here](https://github.com/Health-Hub-App/mealcoach-backend).

### Mail
A ListMonk server manages mail campaigns, this can be accessed [here](https://listmonk.mealcoach.net). Additional system emails are sent to users by the MealCoach API, this is outside of the ListMonk system.

Mail hosting is provided by PurelyMail. The MealCoach API is configured for SMTP.

### MealCoach Landing Page
This is the face of mealcoach, found at [mealcoach.net](https://mealcoach.net).

This is a static html/css/js site hosted on GitHub, using bootstrap. It features a high-level overview of the app, along with a sign-up form for the mailing list.

### Domains
- The _mealcoach.net_ domain is owned by CosmoTown, using CosmoTown nameservers
- The _healthhub.business_ is owned by NameCheap, using NameCheap nameservers. _domain soon to be replaced_

### Hosting Infastructure
Static websites are hosted on GitHub where possible, making everything hosted there public domain. Everything else is to be hosted on a VPS in my shed, running docker, behind nginx, in an unraid instance.

There is no disaster recovery, but there are plans to use kubernetes in the future, or to use a hosting provider, idk, we can do whatever since everything is dockerised.

## Development Philosophy
- Don't get sucked in by vendor lock-in
- Develop what you need, and quickly

## Business
HealthHub App is a registered UK limited company.
