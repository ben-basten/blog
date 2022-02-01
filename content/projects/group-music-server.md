---
title: "Group Music Server"
description: "An mp3 music server with listening rooms for multiple clients to join and listen to the same music. "
technologies: ["react", "javascript", "java", "websockets", "spring-boot", "gradle"]
repo: "https://github.com/ben-basten/group-music-server"
draft: false
---

![Listening Room Screenshot](/images/projects/group-music-server.png)

## Overview

One of the degree requirements for Computer Science majors at NMU was to do a capstone "Senior Project". It was up to me to come up with an idea, write out the project requirements for grading, and develop the app.

After spending Spring 2020 quarantining with my family and spending countless hours on the phone with my friends playing [skribbl.io](https://skribbl.io/) (online pictionary) and watching Netflix over Skype calls, I knew that I wanted to create a tool that could bring people together from afar. Hence the idea for the Group Music Server (AKA "Listening Party") was created.

The idea? Using my library of MP3 music, create an app where clients can join private listening rooms and simultaneously listen to the same music queue as everyone else in the room. 

## How it works

When a user navigates to webpage, they are greeted with a lobby where they can either join or create a room. When a room is created, it is assigned a unique 4 digit number that can be used to invite others to join your listening room.

In the listening room, clients can see the queue, available music to add to the queue, current information about what's playing, and options to skip/pause the music. Any updates made to the queue, whether it's skipping a song or adding a new one, is immediately refreshed for everyone else who's listening in the room.

## Technologies

* **React**: frontend JavaScript framework
* **Spring Boot**: backend microservice, written in Kotlin with Gradle build automation
* **@stomp/stompjs**: WebSocket library used for realtime queue updates and song skips
* **Spock**: unit/integration testing for the controllers

## Diagram

![How it works diagram](/images/projects/gms-diagram.png)