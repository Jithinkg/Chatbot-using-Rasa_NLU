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
  
## order path
* order
  - utter_order_food
  
## offer path
* offer
  - utter_offer_applied
  
## order choose
* placed
  - utter_choose
  
## thank you
* thank_you
  - utter_thank_you

## okay
* ok
  - utter_ok