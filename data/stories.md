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

## say my name
* mood_good
    - utter_master

## say minimum wage 1
* minimum_wage
    - utter_minimum_wage
* yess
    - utter_minimum_wage_af

## say minimum wage 2
* minimum_wage
    - utter_minimum_wage
* noo
    - utter_minimum_wage_de

## file a wage 
* file_a_wage
    - utter_file_a_wage

## wage theft yes
* wage_theft
    - utter_wage_theft
* yess
    - utter_wage_theft_af
* yess
    - utter_wage_theft_af_af

## wage theft no 1
* wage_theft
    - utter_wage_theft
* noo
    - utter_wage_theft_de
* deny
    - utter_goodbye

    
## wage theft no 2
* wage_theft
    - utter_wage_theft
* noo
    - utter_wage_theft_de
* yess
    - utter_ok





