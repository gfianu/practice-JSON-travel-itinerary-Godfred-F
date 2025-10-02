Pair Practice Questions: Godfred and Robyn

Nesting: I put email and phone inside a nested contact object under traveler. This keeps related info together and makes the data easier to read and find.

Array: I used arrays for destinations and each destination’s activities. Arrays make it easy to loop over items and add/remove entries without changing the overall structure.

Scalability: We can add new fields like hotel or transportation as more nested objects (e.g., hotel: { name, checkIn, checkOut }). This keeps growth organized without breaking the current shape.

Real-World Application: A travel app/API could read this JSON to show trip details, list activities by day, and calculate totals (like costs). It also makes syncing between front-end and back-end simpler.
