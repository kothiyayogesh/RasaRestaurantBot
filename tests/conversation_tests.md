## A basic end-to-end test
* greet: hello
   - action_bot_greet
* restaurant_search: i am feeling hungry
    - utter_ask_location
* telling_location_cuisine: i am looking to eat [chinese](cuisine) food in mumbai
    - slot{"cuisine":"chinese"}
    - action_show_restaurants
    - utter_ask_for_booking
