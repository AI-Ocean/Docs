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

## Create a new Instance

An instance is your personal remote development environment. You can easily configure Tensorflow, Pytorch, etc. environment with a few clicks. SSH and VS Code are supported, so you can choose the environment you want to use.

1. In Menu-bar, Click Instance > Add new Instance button to open the new instance dialog.
2. Fill the new instance name, image, machine type and volum, Click `Create` button.

    ![Create Instance](/assets/images/Quickstart/create-instance.png)

3. You can check your instance list in Main area of Instances page.
4. You also access SSH with SSH port and VSCode to click `editor link`.

> The default password of SSH and VSCode is your email address. Please make sure to change your password.

> Volume is mounted at `/root/<Volume name>`

> Please working on volume path. When Instance or Job is deleted, All of your data will be deleted except in the volume data.

## Create a new Job

The jobs allows the code and development environment written in the instance to operate by changing only the machine type to the version with GPU as it is. 
Similar to an instance, the difference is that it is a one-time computing resource that only runs executable scripts. 
You can also submit easily from the Ocean-CLI inside the instance.

1. In Menu-bar, Click Jobs > Add new Job button to open the new job dialog.
2. Fill the new job name, image, machine type and volum like create instance. Here, Additionally fill executable scripts and number of repeat. Then click `Create` button.

> All of executable command can be filled in `executable scripts`.

> If you designate number of repeat larget then 1, multiple job will be created.

    ![Create Job](/assets/images/Quickstart/create-job.png)

3. You can check your job list in Main area of Job page.
4. You also check your job's status and you can see job's logs with `see logs` button.

## Home page
On the home page, you can view the `machine types`, `instances`, and `jobs` set above, and you can quickly navigate to each menu.

![Home Page](/assets/images/Quickstart/home-page.png)

## More things to read
[Ocean CLI Documentation](https://ocean-cli.herokuapp.com/)