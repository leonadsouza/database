# Creating a Custom Database Software Image using OCI Console.

## Introduction
This lab walks you through creating a custom Database Software Image using the OCI Console.

Database software images give you the ability to create a customized Oracle Database software configuration that includes your chosen updates (PSU, RU, or RUR) and optionally, a list of one-off (or interim) patches or an Oracle Home inventory file. This reduces the time required to provision and configure your databases and makes it easy for your organization to create an approved "gold image" for developers and database administrators.

While creating a DB Home in Lab 2, for the Oracle Database major version releases available in Oracle Cloud Infrastructure, by default, images are provided for the current version plus the three most recent older versions (N through N - 3). If you need to create a DB Home with PSU/RU older than the default options available, follow the steps below to create a Custom Database Software Image.

Estimated Time: 30 min

### Objectives
In this lab, you will learn to :
* Create a custom Database Software Image using the OCI Console.

### Prerequisites  

This lab assumes you have:
- A Free or LiveLabs Oracle Cloud account.
- IAM policies to create resources in the compartment.


## Task 1: Create a Custom Database Software Image using OCI Console.

1. Open the navigation menu in the OCI Console. Click **Oracle Database**, then click **Exadata on Oracle Public Cloud**.

  ![Navigate to Exadata on Oracle Public Cloud](./images/navigate-to-exacs-public-cloud.png "Navigate to Exadata on Oracle Public Cloud")


2. Choose your **compartment**.

  ![Compartment for DB Software image](./images/choose-compartment.png "Compartment for DB Software image")


3. Under **Resources**,

    * Click on **Database Software Images**.

    * Click on **Create Database Software Image**.

  ![DB Software image creation](./images/navigate-create-db-image.png "DB Software image creation")


4. Provide the below information for the database software image.

    * In the Display name field, provide your image a **Display name**. Avoid entering confidential information.

    * Choose your **compartment**.

    * Choose a **Shape Family**. A custom database software image is compatible with only one shape family. Available shape families for Exadata Cloud Services is **Exadata Shapes**.

    * Choose the **Database version** for your image. You can create a database software image using any supported Oracle Database release update (RU).

    * Choose the patch set update, proactive bundle patch, or release update.

    * Optionally, you can enter a comma-separated list of one-off (interim) patch numbers.

    * Click **Create Database Software Image**.

  ![DB Software image for ExaDB-D](./images/create-custom-db-image.png "DB Software image for ExaDB-D")


You may now **proceed to the next lab**.

## Learn More
- You can find more information about Managing Oracle Database Software Images [here](https://docs.oracle.com/en-us/iaas/exadatacloud/exacs/ecc-manage-images.html)


## Acknowledgements
* **Author** - Leona Dsouza, Senior Cloud Engineer, NA Cloud Engineering
* **Contributors** - Ramesh Babu Donti, Principal Cloud Architect, NA Cloud Engineering
* **Last Updated By/Date** - Leona Dsouza, Senior Cloud Engineer, NA Cloud Engineering, July 2022
