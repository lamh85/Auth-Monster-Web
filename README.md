# Why did I create this?

I worked in 2 different companies where the authentication and authorization systems have exploded: they just kept adding more features. The code design patterns and conventions quickly became outdated, and not fit for such scale.

This repo has some proofs of concept for scalable code.

# Some examples of features

NOTE - Some of these add little complexity to an existing app. Others significantly change code pattern.

## Subscription

Discounted membership plans for any of the following reasons
* marketing campaign
* bundled
* loyalty
* grandfathered

Get more rewards if you enter your credit card.

Pause memberships.

Pro-rate membership.

## Authentication

Sign in as a guest. The user can complete registration in a later part of a UX flow.

Sign in with multiple types of IDs: email, username, phone number, etc.

OAuth: Google, Facebook, etc.

Two-factor authentication.

Forgot password.

Stay logged in.

Magic link.