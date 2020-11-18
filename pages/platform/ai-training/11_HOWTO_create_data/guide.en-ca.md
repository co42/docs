---
title: Create Data via UI
slug: create-data
excerpt: Learn how to create Data object on AI Training via UI
section: How to
order: 1
---
*Last updated 29th October, 2020.*

## Objective

This guide covers the creation of [**data**](../data) objects in **AI Training** through the OVHcloud Control Panel and their association with Object Storage containers.

## Requirements

-   a [Public Cloud project](https://www.ovhcloud.com/en-gb/public-cloud/) in your OVHcloud account
-   **AI Training activated** for your account, see [how to submit a job Step 2](../submit-job)
-   a user for AI Training [how to submit a job Step 3](../submit-job)
-   access to the [OVHcloud Control Panel](https://www.ovh.com/auth/?action=gotomanager)

## Instructions

### Creating an Object Storage container

You can access the Object Storage page in the `Public Cloud` section of the [OVHcloud Control Panel](https://www.ovh.com/auth/?action=gotomanager) under `Storage` \> `Object Storage`.

![image](images/00_storage_menu.png){.thumbnail}

From the Object Storage page click `Create an object container`{.action}.

Select the location for you data container. To improve synchronisation performances, choose the closest location to the **AI Training** cluster you plan to use. For more information about available regions see the [capabilities](../capabilities).

![image](images/01_object_create_region.png){.thumbnail}

Once you set a location you need to select the type of container you want to use. For private data to use with **AI Training** it is recommended to use a `Private` container.

![image](images/02_object_create_type.png){.thumbnail}

Finally choose a name for your container and then click `Create the container`{.action}.

## Going Further

-   You can check the official documentation about [how to submit a **job**](../submit-job)

## Feedback

Please send us your questions, feedback and suggestions to improve the service:

-   On the OVHcloud [AI community forum](https://community.ovh.com/c/platform/ai-ml)
