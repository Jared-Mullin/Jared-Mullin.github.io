---
title: "FediUni - Initial Progress"
date: 2022-01-04T15:34:15Z
draft: false
---

Currently, I am in my fourth and final year of studying "Computer Science and Information Technology" at the National University of Ireland, Galway. As part of my undergraduate degree, I am working on a final year project I have called "FediUni". The documentation for this project will be hosted at https://docs.fediuni.xyz.

The project proposes to build an [ActivityPub](https://www.w3.org/TR/activitypub/) service targeted specifically at third level students. The idea is that any society or club could deploy their own instance of the FediUni service such that they can interact with members at a local level or with other societies at a higher level. The ActivityPub protocol facilitates interaction between instances that implement it even if they're developed seperately, for example, a FediUni user on some FediUni instance could interact with a user on a Mastodon instance. This would be similar to a Facebook user following their friend on Twitter with the ability to like their posts and interact with their content. 

Last year, I wrote the project definition document with the assistance of my supervisor and work on the project began following the winter examinations. Today, I managed to view my FediUni profile from a Mastodon instance. 

![Mastodon Search Page](/search_page.png)
![Mastodon Profile Page](/profile_page.png)

As a result, I can now move on to content creation to the inbox and outbox of FediUni users such that they can send and receive content. I will also need to make progress on the FediUni Electron client, but for now the work in progress API is hosted at https://fediuni.xyz