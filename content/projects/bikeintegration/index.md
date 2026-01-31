---
title: "Bike Integration in Västtrafik's Journey Planner"
date: 2025-10-06
draft: false
project_tags: ["web", "api"]
summary: "Integrating bike routes into Västtrafik's journey planner to enhance multimodal transportation options"
weight: 3
---

### Overview

Have you ever noticed that you can find a much faster route of your
daily commute if you combined biking with public transport?
This project aims to integrate bike routes into Västtrafik's journey planner,
allowing users to plan trips that combine cycling and public transport seamlessly.

This project was developed in collaboration with Västtrafik,
as a form of advancement toward environmental sustainability
and to promote healthier lifestyles.

### Motivation

The primary motivation behind the project was that the journey planner
used by Västtrafik only had support for showing bike routes
as a separate entity from public transport routes.
This meant that users had to manually combine the two modes of transport,
which was inconvenient and time-consuming and was no better than using the
journey planner in conjunction with something like Google Maps.

We (the project group) proposed that bike routes
would be a part of the generated routes based on the user's preferences,
like if they want to take their bike with them on the bus,
if they want to bike the whole way, or if they simply want to
rent a bike for the trip (through the city's rental bikes "Styr & Ställ").

### Results

The webapp we ended yp with had an interface for selecting parameters for your trip, and gives multiple route options sorted by travel time.
The routes are displayed on a map, with different colors for different modes of transport and with markers for viable bike rental stations.

The webapp was built upon Västtrafik's existing API for journey planning, with a lot of custom logic for integrating bike routes thanks to OpenStreetMap's API for bike routes.
The project was well-received by Västtrafik, and it just so happened that they released a experimental verion of the journey planner supporting combined routes with rental bikes a year after the end of the project.

{{< figure src="featured.png" width="100%" >}}
