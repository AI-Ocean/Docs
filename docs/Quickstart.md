---
layout: default
title: Quick Start
nav_order: 2
---

# Quick Start

## Overview
Ocean Quick Start will follow the content.

![Overview](/assets/images/Quickstart/overview.png)

## Registration

Go to the ocean domain and register as a member.

![Registration](/assets/images/Quickstart/registration.png)

## Basic Page configuration

1. Menu-bar: Main menu navigation (Home, Jobs, Instances, Volumes, Quota requests, etc.)
2. Top-bar: Top menu (Fold/Unfold, My-page, logout)
3. Main area: area to display content

![Basic Page configuration](/assets/images/Quickstart/page-configuration.png)

## Quota Request
You should use pre-setted `machine types` to use `Jobs` or `Instances` that is `computing resources` of Ocean.
First, you can requests the `quota` of `machine types` to use.

1. In Menu-bar, Click `Request Quota` and `Request` button to open quota request dialog.
2. Select the machine type in available machine types list.
3. Set number of requests, preiod, object and click request button.

    ![Quota Request](/assets/images/Quickstart/quota-request.png)

4. You can check your quota request list in Main area of Quota Request page. You should wait for the response from the admin to accept or reject your quota request and it also displayed.
5. If you want to cancel the quota request, click `Cancel` button.

![Quota Request List](/assets/images/Quickstart/quota-request-list.png)

## Create a new Volume
Volume is remote storage in Ocean that store your source code or dataset. Volume is autometically mounted on your computation resources (Instance, Job).

1. In Menu-bar, Click Volumes > Add new Volume button to open the new volume dialog.
2. Fill the new volume name, object and capacity, Click `Create` button.

    ![Create Volume](/assets/images/Quickstart/create-volume.png)

3. You can check your volume list in Main area of Volumes page. You also can check where the volume is mounted in `Where to use` field.
4. If you want to delete the volume, click `Delete` button. But if it is mounted in some where, then you cannot delete the volume.

![Volume List](/assets/images/Quickstart/volume-list.png)

## Create a new Instace

