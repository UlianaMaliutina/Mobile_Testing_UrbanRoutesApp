## Bug 1: Button "Next" in the "Dishes menu" screen is active when there are no dishes added to the order
# Description: 
The button “Next” on the 2 step “Dishes list” in Urban Lunch App is active when no dishes were added to the order.
# Preconditions:
Install Urban Lunch App: Urban Lunch.apk 
Allow access to geolocation to the app and open app
# Steps:
Choose desired pick-up point and proceed to the second step- “Dishes list” screen
Without adding any dish to the order click on the Next button(footer at the bottom of the screen, white arrow inside dark grey circle)
# Expected result: 
The button “Next” is inactive, unclickable
# Actual result: 
The button “Next” is clickable, leads to the pop-up message “Choose any food”
# Environment
Android, API 31, Pixel 5, 2340*1080 resolution
Urban Lunch App(version 1.0)

## Bug 2: The total amount at the 3 step contains only the price of all prepared dishes without delivery
# Description: 
The total amount at the 3 step(screen “Check order”) contains only the price of all prepared dishes without delivery
# Preconditions:
Install Urban Lunch App: Urban Lunch.apk 
Allow access to geolocation to the app and open app
# Steps:
Choose desired pick-up point
Choose dishes to the order
At the 3 step(screen with checking dishes in the order and total price) the “Amount” includes only cost of dishes without delivery
# Expected result: 
The “Amount” displays total cost of dishes and delivery
# Actual result: 
The “Amount” displays total cost of dishes without delivery fee
# Environment
Android, API 31, Pixel 5, 2340*1080 resolution
Urban Lunch App(version 1.0)

## Bug 3: The order tracking screen doesn't show remaining cooking time for dishes
# Description: 
The order tracking screen doesn't show remaining cooking time for dishes at the restaurants(only remaining delivery time)
# Preconditions:
Install Urban Lunch App: Urban Lunch.apk 
Allow access to geolocation to the app and open app
# Steps:
Choose desired pick-up point
Choose dishes to the order
Confirm order
# Expected result: 
The order tracking screen contains window with remaining cooking time from the restaurant to the pick-up point
# Actual result: 
The order tracking screen doesn't show remaining cooking time for dishes at the restaurants(only remaining delivery time)
# Environment
Android, API 31, Pixel 5, 2340*1080 resolution
Urban Lunch App(version 1.0)

## Bug 4: The map on "Order is delivered" screen doesn't correlate with layouts
# Description: 
The map on “Order is delivered” screen shows not desired pick-up location and route to it but shows desired pick-up location and route to it from chosen restaurants
# Preconditions:
Install Urban Lunch App: Urban Lunch.apk 
Allow access to geolocation to the app and open app
# Steps:
Choose desired pick-up point
Choose dishes to the order
Confirm order
Wait until the order is delivered to the pick-up point
# Expected result: 
The map shows desired pick-up location and route to it from current user’s location
# Actual result: 
The map shows pick-up location and route to it from restaurants where dishes were cooked.
# Environment
Android, API 31, Pixel 5, 2340*1080 resolution
Urban Lunch App(version 1.0)

## Bug 5: The restaurant's name below the dish ingredients in the "Dish details" displayed incorrect
# Description: 
The long restaurant’s name in the Dish details(step 2, below the dish ingredients) displayed incorrectly
# Preconditions:
Install Urban Lunch App: Urban Lunch.apk 
Allow access to geolocation to the app and open app
# Steps:
Choose desired pick-up point
Click on dish Tomato soup with croutons to proceed to Dish details
Scroll down the dish ingredients
# Expected result: 
The long restaurant name(The Aroma Lane) is displayed correctly, adjusted to the size of line
# Actual result: 
The long restaurant name(The Aroma Lane) is displayed incorrect, partially overlapping the price of the dish.
# Environment
Android, API 31, Pixel 5, 2340*1080 resolution
Urban Lunch App(version 1.0)