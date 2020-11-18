---
title: Users
slug: users
excerpt: Learn the concept behind AI Training users
section: Concepts
order: 2
---
*Last updated 29th October, 2020.*

## Definition

The **users** of the AI Training platform are simply your Public Cloud users that you can create in the OVHcloud Control Panel. To give access to **AI Training** to any of your users, you need to grant them the role **AI Training Operator** role. Then you can use this user's credentials to authenticate.

**AI Training** includes the OVHcloud Object Storage as a persistent storage solution for your [data](../data). To use these features the user needs to be granted the role **Objectstore Operator** since it implies read/write access to the Object Storage.

### Roles

There are 2 available roles :

-   `AI Training Operator` : Grants access to **AI Training**.
-   `Objectstore Operator` : Grants read/write access to the OVHcloud Object Storage.

## Considerations

-   Access to **AI Training** can be revoked at all moment by deleting the user or removing its **AI Training Operator** role.
-   To be able to use the OVHcloud Object Storage, make sure that the user has the **Objectstore Operator** role.

## Going further

-   You can check the [OVHcloud documentation on how to submit a job](../submit-job).

## Feedback

Please send us your questions, feedback and suggestions to improve the service:

-   On the OVHcloud [AI community forum](https://community.ovh.com/c/platform/ai-ml)
