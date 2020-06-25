## out of scope path
* out_of_scope
  - utter_out_of_scope

## help
* help
  - utter_help

## thank
* thank
  - utter_welcome

## happy path
* greet
  - utter_greet
  - utter_help

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot


## incident form
* open_incident OR password_reset OR problem_email
    - open_incident_form
    - form{"name": "open_incident_form"}
    - form{"name": null}

## incident form interrupted
* open_incident OR password_reset OR problem_email
    - open_incident_form
    - form{"name":"open_incident_form"}
* help
    - utter_help
    - open_incident_form
    - form{"name":null}

## incident form interrupted
* open_incident OR password_reset OR problem_email
    - open_incident_form
    - form{"name":"open_incident_form"}
* out_of_scope
    - utter_out_of_scope
    - open_incident_form
    - form{"name":null}


## cw help basic
* greet
  - utter_how_canhelp
* bot_name
  - utter_botname
  - utter_help
* submit_reimbursement
  - utter_please_wait
  - utter_need_reimb_link
* skip_it
  - utter_no_prob
* ask_question
  - utter_whatisit
* get_purse_balance
  - utter_please_wait
  - utter_purse_amount
* thank
  - utter_welcome
* out_of_scope
  - utter_out_of_scope
* thank
  - utter_thanks
  - utter_any_aditional_help
* deny
  - utter_may_ask
* confirm
  - utter_ask_sutisfied
* confirm
  - utter_save_feedback


## real quick
* ask_question
  - utter_whatisit
* deny
  - utter_no_prob
* goodbye
  - utter_goodbye
