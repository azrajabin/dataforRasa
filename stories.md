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
  
## memory
* memory
  - utter_memory
## latency
* latency
  - utter_latency
## whoami
* whoami
  - utter_whoami

##cpu_check
* cpu_check
  - utter_cpu
## overall_score
* overall_score
  -utter_overall_score