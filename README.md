Project Overview

The project is a social networking platform built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It incorporates two major features: an automated content moderation system and context-based authentication. These features are accompanied by common functionalities found in social media applications, such as profile creation, post creation and sharing, liking and commenting on posts, and following/unfollowing users


Automated Content Moderation

The platform's automated content moderation system utilizes various NLP (Natural Language Processing) APIs. These APIs include:

Perspective API: Used for filtering spam, profanity, toxicity, harassment etc.
TextRazor API: Integrated for content categorization.
Hugging Face Interface API: Utilized with BART Large MNLI for content categorization.
A Flask application has been developed to provide similar functionality as the Hugging Face Interface API's classifier. The Flask app utilizes the BART Large MNLI model. It operates as a zero-shot classification pipeline with a PyTorch framework


Context-Based Authentication


The platform implements context-based authentication to enhance user account security. It takes into consideration user location, IP address, and device information for authentication purposes. Users can conveniently manage their devices directly from the platform. To ensure data privacy, this information is encrypted using the AES algorithm and securely stored in the database.

In case of a suspicious login attempt, users are promptly notified via email and are required to confirm their identity to protect against unauthorized access


Features

 User authentication and authorization (JWT)
 User profile creation and management
 Post creation and management
 Commenting on posts
 Liking posts and comments
 Following/unfollowing users
 Reporting posts
 Content moderation
 Context-based authentication
 Device management
 Admin dashboard
 Moderator dashboard

Technologies


React.js
Redux
Node.js
Express.js
MongoDB
Tailwind CSS
JWT Authentication
Passport.js
Nodemailer
Crypto-js
Azure Blob Storage
Flask
Hugging Face Transformers
