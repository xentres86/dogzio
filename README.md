# dogzio

## Overview

This repository is a first draft for an app to track and manage fitness and nutrition data for pets (mainly dogs). It is modeled on kcal trackers and fitness apps for humans such as Yazio.

## Description

While it is no problem for humans to track their calorie balance accurately, it is not so easy for dogs. Many owners don't know how many kcal their dog really needs depending on size, breed, activity and gender. Unfortunately, the information on food cans is rarely helpful. Information such as "A dog weighing 5-10 kg needs 1/4 can" is more likely to cause confusion than provide clarity. However, with the help of scientific data and activity profiles for dogs, concrete information on the daily kcal requirement can also be recorded here. At the same time, the kcal density of wet and dry food can be calculated precisely. This makes it possible to give dog owners precise information about the daily amount of food.

## Goal

The aim is to provide dog owners with an app to manage the kcal requirements and kcal balance of their four-legged friend.

## Repo Info

The project is based on a microservice architecture. The services run in their own Docker containers. MongoDB (NoSQL) is used for data storage. The backend provides an API and is written entirely in GO (this repository). The front end is to be implemented in Flutter.

## Techstack

- MicroService Architecture
- Docker
- MongoDB (NoSQL)
- PostgreSQL (SQL)
- REST-API
- Caddy Webserver
- GO Backend
- Flutter Frontend
