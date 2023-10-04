# FoxLabs Auth Server (foxlabs-auth)
Building a free and a simple OpenID authentication platform that is powerful and flexible for all.

![GitHub](https://img.shields.io/github/license/InariTheFox/foxlabs-auth)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/InariTheFox/foxlabs-auth/main)
![GitHub release (with filter)](https://img.shields.io/github/v/release/InariTheFox/foxlabs-auth)

## Project Description
Frustrated with products such as Keycloak, the lack of features available in modern solutions like Authentik, and the need to build out an entire UI along with the new pricing scheme for Identity Server, I decided it was time to build my own authentication service and make it accessible for all. Having a deep understanding and experience with the realm of OpenId, OAuth and application security, it was time to put that knowledge and skill set to good use.

Built upon the .NET Core Framework with scalability, durability, security and ease-of-use all in mind. This project aims to provide users with a simple, drop-in solution that gives them the flexibility to tailor the user experience with modern sensibilities.

With this project, I am not looking to make my break as an independant developer or as a startup, I want to provide a solid, easy-to-use product that anyone, including businesses can use for free. My only request is that if you wish to use the product, please help to make it better!

## Feature Goals
To be a product that is usable, there are many different features that I feel that need to be offered. Its one thing to be an OAuth service, its another to offer a wide-range of features which make the product appealing to a wider range of individuals and organizations. Below are just some of the features on the roadmap.

- Full OAuth2 compliance
- Full OpenID Connect compliance
- Federation support
    - SAML
    - LDAP
    - SCIM
- RADIUS
- Mutli-tenancy
- Multi Factor Authentication
    - TOTP
    - HOTP
    - Challenge-Response
- Passwordless Authentication
    - Email
    - Authenticator
    - Passkeys
- Granular and customizable permission schemes
    - Role Based Access Control (RBAC)
    - Claim Based Access Control (CBAC)
- Fully customizable rules and policies
- Localization
- Theming
- RESTful API
    - GraphQL support
- Self-serve functionality
    - Account creation
    - Password resets
    - Client registration/deregistration
- Wide range of deployment options
    - Bare-metal
    - Docker
    - Kubernetes

One of my primary goals is to ensure that the product passes completely the baseline OpenId Connect certification suite. This is a key indicator to the functionality of the solution and ensures at the very least the product meets industry standards.