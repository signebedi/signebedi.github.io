---
layout: page
title: libreforms
description: 
importance: 1
category: technology
# related_publications: einstein1956investigations, einstein1950meaning
---


<hr>

Since about 2022, I have been developing an open-source project called libreforms, which implements a specification I wrote under the same name that combines a form configuration language, and associated communication protocol built on HTTP requests, optimized for managing institutional forms over a network.

Modern bureaucracies often rely on complex processes that tend to send you mad (https://asterix.fandom.com/wiki/The_Place_That_Sends_You_Mad). These processes are typically built around the idea of institutional forms, a type of data that has a tendency to require multiple users with varying institutional roles to repeatedly access and modify individual records in processes that vary in their formality and clarity, and which tend to change over time as formal organizational goals change or the cadres of people that make these organizations up shift in their composition. The libreForms API is purpose-built to manage data in such environments while keeping forms simple and flexible to changes in form layout and business processes.

I've implemented this system in Python twice: first, as a Flask UI; second, as using FastAPI and Pydantic to create an asynchronous API and a UI built almost entirely on top of this API. The latter project remains actively maintained by me and is used by multiple organizations. You can find the links to these applications under the "repositories" page of this website.