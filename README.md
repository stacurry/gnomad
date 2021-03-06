# GNOMAD
[![Build Status](https://travis-ci.org/chi-bumblebees-2017/gnomad.svg?branch=master)](https://travis-ci.org/chi-bumblebees-2017/gnomad)

Completed in 7 days as a capstone project for Dev Bootcamp, this mobile-first single-page web app allows travelers, or "gnomads," to connect with city residents, or "localhosts," in order to have an authentic local experience of their travel destination.

Uses a Ruby on Rails back-end, React front-end, Facebook OAuth for third-party authentication, Action Cable for real-time chats, and Semantic UI for a clean, responsive design.

Deployed on Heroku [here](https://gnomad.herokuapp.com/).

## Team
* Stacy Curry | stacurry
* Joe LeBeau | joelebeau1
* Tové Mercer | tovemercer
* Katrina Sabbak | ksabbak
* Simon Swartzman | rtzm

## Screenshots

## Create a new profile

![Create a new profile](./readme-images/create_profile.png "Create a new profile")

## View your dashboard

![View your dashboard](./readme-images/dashboard.png "View your dashboard")

## Search for a localhost

![Search for a localhost](./readme-images/simple_search.png "Search for a localhost")

## Use advanced search filters

![Advanced search filters](./readme-images/advanced_search.png "Advanced search filters")

## View another user's profile

![View another user's profile](./readme-images/profile_view.png "View another user's profile")

## Start a new chat

![Start a new chat](./readme-images/start_chat.png "Start a new chat")

## View a single, real-time chat

![View a single chat](./readme-images/view_chat.png "View a single chat")

## View your chat history

![View your chat history](./readme-images/view_chats.png "View your chat history")

##

## To Run This Application Locally
Note: this application is deployed on Heroku [here](https://gnomad.herokuapp.com/), but if you would like to download and run the application locally, you can do so with the following steps:

**clone & navigate to this repository:**

`$ git clone https://github.com/stacurry/gnomad`

`$ cd gnomad`

**install required dependencies:**

`$ bundle install`

`$ cd client`

`$ npm install`

`$ cd ..`

**set up database:**

`$ bundle exec rake db:create`

`$ bundle exec rake db:migrate`

`$ bundle exec rake db:seed`

**start servers:**

`$ bundle exec rake start`
