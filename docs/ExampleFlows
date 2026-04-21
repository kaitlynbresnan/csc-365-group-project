# Example Flows

## 1. Restaurant Search and Save (Mike)
Mike is a broke college student who wants to find an affordable restaurant that he can save for a date.

To do this he:
- Calls GET /restaurants/search/?price_max=[chosen-price-max]&sort_order=desc  
- Calls GET /reviews/search/?restaurant_name=[chosen-restaurant-name]  
- Calls POST /profile/restaurants/[chosen-restaurant-id]  

---

## 2. Write, Edit, and Delete Review (Sally)
Sally visits a restaurant and wants to leave a review.

To do this she:
- Calls POST /reviews/[her-review-id]  
- Receives an error (missing rating)  
- Calls POST /reviews/[her-review-id] again with corrected input  
- Calls PUT /reviews/[her-review-id] to edit later  
- Calls DELETE /reviews/[her-review-id] to remove the review  

---

## 3. Owner Interaction (Alice)
Alice is a restaurant owner who wants to monitor feedback and interact with customers.

To do this she:
- Calls GET /reviews/search/?restaurant_name=[restaurant-name]  
- Calls POST /reviews/[review-id]/reply  
- Calls POST /reviews/[review-id]/report  
