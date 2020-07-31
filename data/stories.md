## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## what is corona
* corona_intro
  - utter_corona_intro

##how does corona spread
* corona_spread
  - utter_corona_spread

##corona food spread
* corona_food_spread
  - utter_food_spread
 
##corona weather spread
* weather_effect
  - utter_weather_effect

##corona risk
* risk
  - utter_risk