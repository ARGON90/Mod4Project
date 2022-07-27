# API DOCUMENTATION

## Route Summary
---
---
## /login ROUTES
### Log In a User
- POST /login
---

---
## /signup ROUTES
### Sign Up a User
- POST /signup
---
---
## /users ROUTES
### Get the current user
- GET /users/:userId
### Spots feature - get all spots owned by current user
- GET /users/:userId/spots
### Reviews feature - get all reviews written by current user
- GET /users/:userId/reviews
### Booking feature - get all the current user's bookings
- GET/users/bookings
---
---
## /spots ROUTES
### Spots feature - Get all spots
- GET /spots
### Spots feature - Get details of spot from an Id
- GET /spots/:spotId
### Spots feature - Create a spot
- POST /spots
### Spots feature - Edit a spot
- PUT /spots/:spotId
### Spots feature - Delete a spot
- DELETE /spots/:spotId
### Reviews feature - get all reviews by a spot Id
- GET /spots/:spotId/reviews
### Reviews feature - create a review for spot by Id
- POST /spots/:spotId/reviews
### Reviews feature - edit a review
- PUT /spots/:spotId/reviews/:reviewId
### Reviews feature - delete a review
- DELETE /spots/:spotId/reviews/:reviewId
### Booking feature - get all bookings for spot based on spot id
- GET /spots/:spotId/bookings
### Booking feature - create booking from a spot based on spot id
- POST /spots/:spotId/bookings
### Booking feature - edit a booking
- PUT /spots/:spotId/bookings/:bookingId
### Booking feature - delete a booking
- DELETE /spots/:spotId/bookings/:bookingId
### Image feature - add image to spot based on id
- POST /spots/:spotId/images
### Image feature: Add an image to a review based on the review's id
- POST /spots/:spotId/reviews/:reviewId/images
### Image feature: Delete an existing image
- DELETE /spots/:spotId/images/:imageId
---
