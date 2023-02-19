# Cognito User Pool

---

### Agenda

- Understanding and getting started with AWS Cognito User Pool 
- Using Cognito with AWS Appsync

---
Sections covered in the code :

  1. Cognito Userpool
  2. Userpool Client
  3. Userpool Groups

---

Reference: [Enlear Academy](https://enlear.academy/) and AWS Documentation

---

## Notes (Referred from Docs)

- Amazon Cognito provides authentication, authorization, and user management for your web and mobile apps. Your users can sign in directly with a user name and password, or through a third party such as Facebook, Amazon, Google or Apple.
- The two main components of Amazon Cognito are user pools and identity pools. 
- User pools are user directories that provide sign-up and sign-in options for your app users. 
- Identity pools enable you to grant your users access to other Amazon services. You can use identity pools and user pools separately or together.
- Identity pools support anonymous guest users, as well as federation through third-party IdPs(identity providers).
- Common Amazon Cognito scenarios:
  - Authenticate with a user pool.
  - Access backend resources through a user pool.
  - Access API Gateway and Lambda through a user pool.
  - Access AWS services with a user pool and an identity pool.
  - Access AWS services through a third party and an identity pool.
  - Access AWS AppSync resources through a user pool or an identity pool.'

- With Appsync we provide access to APIs based on the User Groups the User is attached to. Refer the images in 'images' folder for output seen on AWS Console.
- For example: If the user belongs to Admin user group, he will be provided full access (i.e. access to all the APIs). But if the user belongs to Customer Group, he will be provided access to only limited APIs.

---
 > *This project is intended only for my personal understanding purpose. The data/code here is referred from Youtube & AWS Documentations.*
