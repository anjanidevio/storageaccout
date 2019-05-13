# Creating Cloud Storage (Object) – Introduction

## Table of Contents

[Overview](overview)

[Pre-Requisites](#pre-requisites)

[Recommended Learning Assets](#recommended-learning-assets)

[practice 1: Log In to OCI Console](#practice-1-log-in-to-oci-console)

[practice 2: Create Object Storage Bucket](#practice-2-create-object-storage-bucket)

[Practice 3: Upload an Object and Provide Access to the Object](#practice-3-upload-an-object-and-Provide-access-to-the-object)



## Overview:

Welcome to the Cloud Storage (Object) self-paced lab from Oracle!

**How to use the lab interface:**


Click **Start** to get started!

## Pre-Requisites

- Oracle Cloud Infrastructure account credentials (User, Password, and Tenant)
- Region and compartment with limits for a few small instances (1.1 or 2.1 is sufficient)
- A VCN created with at least one subnet, internet gateway, default route to internet gateway and security groups allowing at least port 22/SSH in.
- Ability to SSH into compute instances

## Recommended Learning Assets

- Recommended 1
- Recommended 2
- Recommended 3
- Recommended 4


## practice 1: Log In to OCI Console

**Before you Begin:**

1) All screen shots are examples ONLY. Screen shots
can be enlarged by Clicking on them

2) Every User MUST keep below credentials handy.

User Name

Password

Compartment Name (Provided Later)

Cloud Tenant Name

3) Do NOT use compartment name and other data from 
screen shots.Only use  data(including compartment name) 
provided in the content section of the lab

**NOTE: OCI UI is being update. Please read below:**

Some screen shots might show the older layout with Services displayed Horizontally or expanded vertically.In Current UI All services can now be accessed by clicking menu.

In this section we will login to the OCI console and adjust your screen size (if needed).

Step 1. Sign in to your account using the below 

**credentials (Please type in your credentials):**

**Cloud Tenant** : {{4990c081-caee-dae5-1918-2346642fe7ef.output.tenancy_name}}

**Username**: {{4990c081-caee-dae5-1918-2346642fe7ef.output.usernames_list}}

**Password**: {{4990c081-caee-dae5-1918-2346642fe7ef.output.ui_passwords_list}}

**Note**: Your password should be updated automatically for you, but sometimes you may be asked to change it after signing in the first time. If prompted, pleaseupdate the password. You can use this one to expedite things: Oracle123!!!! . It will not be saved after this lab expires.

Step 2. Reduce the browser display size  as needed(Below example is for Chrome). 

 
## practice 2: Create Object Storage Bucket

In this section we will create Object storage bucket. Using Object storage does not require creating any other resource.

Step 1. From the OCI Services menu, click Object Storage


Practice 3: Upload an Object and Provide Access to the Object

In this section we will go over the steps needed to upload an object (text file, media file, image etc) and how to create a pre-authenticated request so the object is accessible from the internet.

Step 1. Click on the **Apps** icon  and select **Git-Bash** to open a terminal window. 






