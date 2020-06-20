# Flight Information Coding Challenge

Thanks for taking the time to do our front-end coding test. The challenge has two parts:

1. a task to create a basic flight results front-end site to show flight prices

2. some follow-up questions

# You will be graded based on the following have been met:

Your implementation works as described in the task.

Your solution looks like the provided design.

# Task
Fetch flight results from the provided flights.json and format them into client readable results.

You are not required to serve this separately from the dev server (i.e. npm start).

Use the returned data to display a page of results that matches the given design.

Times should be displayed in 24 hour format.

# Design
We've provided a design for small-screens (320px) and 4K screen. Your end goal is to mimic it with your own take on the UI. You don't have to use our styleguide or our components -- picking colours from the image and rolling your own css to save time is absolutely fine.

For the airline logos, insert the airline id to the following url: https://logos.skyscnr.com/images/airlines/favicon/{client_id}.png

Flight results
The provided flights json will return two collections of different items:

Itineraries - These are the containers for your trips, tying together Legs, and prices. Prices are offered by an agent - an airline or travel agent.

Legs - These are journeys (outbound, return) with duration, stops and airlines.

# Linting and Testing

Unit tests are mandatory to be done using "npm lint" and "npm test"

A FOLLOW-UP.md file is attached with the project. At the end of the project, please commit it with answers to the follow-up questions.

The commits should not include node_modules and must be added to the .gitIgnore

# Standard practices to be used:

Code must be broken into components which can be reused if required.

Code must be based on a heirarchical structure.

Minimal use of custom styling is very important.

