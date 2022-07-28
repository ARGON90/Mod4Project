# Route Summary
---
---
## Users Routes (/users)
### Sign Up a User
- POST /users/signup
### Log In a User
- POST /users/login
### Get the current user
- GET /users/current
### Spots feature - get all spots owned by current user
- GET /users/current/spots
### Reviews feature - get all reviews written by current user
- GET /users/current/reviews
### Booking feature - get all the current user's bookings
- GET/users/bookings
---
---

## Spots Routes (/spots)
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

---
## Reviews 'sub-routes' (spots/:spotId/reviews)
### Reviews feature - get all reviews by a spot Id
- GET /spots/:spotId/reviews
### Reviews feature - create a review for spot by Id
- POST /spots/:spotId/reviews
### Reviews feature - edit a review
- PUT /spots/:spotId/reviews/:reviewId
### Reviews feature - delete a review
- DELETE /spots/:spotId/reviews/:reviewId
### Image feature: Add image to review on review id
- POST /spots/:spotId/reviews/:reviewId/images
---

## Booking 'sub-routes' (spots/:spotId/bookings)
### Booking feature - get all bookings for spot based on spot id
- GET /spots/:spotId/bookings
### Booking feature - create booking from a spot based on spot id
- POST /spots/:spotId/bookings
### Booking feature - edit a booking
- PUT /spots/:spotId/bookings/:bookingId
### Booking feature - delete a booking
- DELETE /spots/:spotId/bookings/:bookingId
---

## Image 'sub-routes' (spots/:spotId/images)
### Image feature - add image to spot based on id
- POST /spots/:spotId:/images
### Image feature: Delete an existing image
- DELETE /spots/:spotId/images/:imageId
