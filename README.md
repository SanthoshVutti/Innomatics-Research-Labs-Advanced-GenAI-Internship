# Innomatics-Research-Labs-Advanced-GenAI-Internship
Food Delivery Data Hackathon

## Final Dataset
The file `final_food_delivery_dataset.csv` is the single source of truth for all analysis and MCQs.

### Data Sources
- orders.csv (Transactional data)
- users.json (User master data)
- restaurants.sql (Restaurant master data)

### Join Logic
- orders.user_id → users.user_id
- orders.restaurant_id → restaurants.restaurant_id
- Join type: LEFT JOIN

### Analysis Scope
- Order trends
- User behavior
- City & cuisine performance
- Membership impact
- Revenue & seasonality
