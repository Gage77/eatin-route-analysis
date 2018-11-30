# ESO (Engineers Serving Others) Meals on Wheels Route Analysis and Optimization

This simple web application serves to take an input of addresses provided by Meals on Wheels Norman and establish optimal routes for all drivers for a given day.

## Goals/Constraints:

- Generate and display most possible route
- Keep routes under 1.5 hours (usually done between 11 - 12:30)
- Keep routes under 20 miles (less if possible)
- Space is generally not an issue, time is a big one
- Many drivers have been volunteering for a long time and will not want to change route
- Getting volunteers for more routes is difficult, but not impossible

## Current tools being used:

- mealdeliverysoftware.com/software/
- Current routes are available by logging in and downloading a csv by going to "Delivery" -> "Delivery Reports" -> "Delivery Address Data".
- HTML, CSS, Javascript
- Bootstrap 4.0
- Google Maps API

## Todo

- [x] Create route analyzer for all routes
- [x] Create route analyzer for individual routes
- [x] Output analytical data
- [ ] Design more user friendly frontend
- [ ] Beautify front end (CSS)
- [ ] Thoroughly bug test route generation
- [ ] Produce product documentation detailing how to use this app
