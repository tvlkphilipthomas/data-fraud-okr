# Fraud Data Science - OKR 2019
By: Po, Yx, Philip

## Objective
The objective of the DS-fraud team in 2019 is to build the fundamental building blocks that enable all fraud defense systems moving forward. What we are trying to achieve in 2019 is to build a feature store that helps the business to block fraud related activities for the following events: 

 - Account Takeover
 - Coupon Abuse
 - Payment Fraud

## Key Results: What are we going to build in 2019
**P0:**

 - ID management system (Project 22) 
 - Email similarities (Project Me!) 

**P1:**

 - Fraud score for new financial services layer (don't have the name for this yet, any suggestions?)

### Details for Project 22
Project 22 is about finding the relationship between all IDs that's being used in traveloka. For initial project we will covering 

> **profile_id**
> **device_id**
> **user_email**
> **booking_contact_email**

We will serve the relationship between all these related ids so that it's available to be exposed to the product engineering team. 

**Some examples:**

    Input: {profile_ids: 1092810}
    Output: {count_device_id: 3, 
    device_id_details:[89021, 21801, 2801], 
    count_user_email: 5, 
    user_email_details:[loca1@yx.net, loca2@yx.net, loca3@yx.net],
    count_booking_contact_email: 3,
    booking_contact_email_details: [loca1@yx.net, loca2@yx.net, loca3@yx.net]}

### Details for Project Me!
Project me! is about serving similarities score to email address that is being used in payments/accounts/all events in traveloka. This is very important as many current angle of attacks (be it related to paylater abuse or coupon fraud) can be tied back to email address.

**Some examples:**

    Input: "loca1@yx.net"
    Output: {email_fraud_score: 90
    ,similar_emails: 5,
    similar_email_details: [loca2@yx.net, loca3@yx.net, loca4@yx.net, loca5@yx.net, loca6@yx.net]}
