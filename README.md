# Rasa covid chatbot

A basic chatbot for answering covid-19 related questions built using the Rasa framework with the Rasa X framework

Able to integrate with a variety of platforms, a comprehensive guide for which can be found at: https://rasa.com/docs/rasa/user-guide/messaging-and-voice-channels/

A list of intents on which the model is presently trained on and the queries that trigger them can be observed below:

## intent: corona_intro
Queries:
- what is corona?
- what is the corona?
- what is the corona virus?
- what is covid?
- what is covid-19?
- can you tell me about covid-19?
- can you tell me about the coronavirus?
- what is the novel corona virus?

## intent: corona_spread
Queries:
- how does corona spread?
- how does covid-19 spread?
- how is corona spreading?
- how does the virus spread

## intent: corona_food_spread
Queries:
- Does corona spread from food?
- how can corona virus spread from food?
- can corona virus spread from food?

## intent: weather_effect
Queries:
- will warm weather stop corona?
- will hot weather stop corona?
- will covid-19 stop with increase in warm weather?

## intent: risk
Queries:
- who is at risk from the corona virus?
- who is at risk from covid-19?

A Telegram integrated Chatbot Implementation snapshot:
![Telegram_chatbot](https://user-images.githubusercontent.com/40641427/89032326-0c939900-d352-11ea-8633-05f7d1b5c492.jpeg)

References used: 
1) https://www.youtube.com/watch?v=Z-G1PlWr5Bo&list=PLZoTAELRMXVN2V3kc2W-8rNu5UekkIhwF&index=1
2) https://rasa.com/docs/
