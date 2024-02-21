# Mobile_ADR_PairUpWithDan - Finished by Congyan 'Winko' Peng and Seungkwon 'Dan' Choi

# Title: Architecture Decision Record for FoodieGoodie App Development

## Context
   We're on the cusp of developing FoodieGoodie, a dynamic mobile app poised to revolutionize the way customers order food from their favorite local spots for delivery or pickup. This app is being designed with an array of features aimed at enhancing user engagement and streamlining operations. Among these are precise location services to guide users to nearby eateries, instant updates on order statuses, seamless integration with a variety of payment gateways, up-to-the-minute menu updates, a platform for users to share their dining experiences, efficient management of past orders, and timely notifications to keep users informed.

## Decision

- **Location Tracking:** By utilizing the GPS features present in smartphones, the app will identify users' locations to offer personalized restaurant suggestions, estimate delivery times, and highlight nearby dining options.
- **Real-Time Order Tracking:** We're integrating WebSocket technology to provide users with a live feed of their order's status, with React Native’s WebSocket API playing a key role in delivering these updates.

- **Payment Gateway Integration:** The app will support multiple payment options, including popular services like PayPal and Apple Pay, chosen for their robust security, user-friendly design, widespread availability, and cost-effectiveness, ensuring a user-friendly payment experience.

- **Menu Data Synchronization:** Through APIs connected to restaurant inventory systems, we'll ensure that the app's menu listings always reflect the most current options available to users.

- **User Reviews and Ratings:** We're creating a dedicated module for users to post and read reviews of their dining experiences, underpinned by a strong moderation system to maintain the credibility and usefulness of the feedback.

- **Order History Management:** We plan to use a relational database, such as MySQL or Oracle, to store and manage users' order histories efficiently, making it easy for users to revisit and reorder their favorite meals.

- **Notification System:** Leveraging Firebase Cloud Messaging, the app will feature a push notification service to keep users up-to-date on their orders and inform them of special offers, ensuring consistent delivery of notifications across Android and iOS devices.

## Status
   After careful review, this architectural plan has been greenlit for implementation.

## Consequences

- **User Experience:** The integration of instant order tracking, a variety of payment methods, and location-based recommendations is designed to provide a seamless and enjoyable user experience.
- **Operational Efficiency:** The app is crafted to improve the efficiency of the ordering process, making it smooth and effortless for users.

- **Scalability:** Our forward-thinking technical choices and architectural design are built to accommodate an increasing number of users and the potential addition of new features.

- **Maintenance:** We have a proactive maintenance strategy in place to ensure the app remains responsive to the changing needs of users and advancements in technology, maintaining its performance and relevance.

 
