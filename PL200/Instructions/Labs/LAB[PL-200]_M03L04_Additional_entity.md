---
lab:
    title: 'Lab 3.4: Additional entity options'
    module: 'Module 3: Work with Dataverse'
---

Module 3: Work with Dataverse
====================

## Lab 3.4: Additional table options

### Important Notice (Effective November 2020):
Common Data Service has been renamed to Microsoft Dataverse. Some terminology in Microsoft Dataverse has been updated. For example, entity is now table and field is now column. 

While the application is in the process of updating its user experience, some references to terminology like the Common Data Service (now **Dataverse**), entity (now **table**), field (now **column**), and record (now **row**) may be out of date. Please keep this in mind as you work through the labs. We expect to have our content fully up to date very soon. 

For more information and for a complete list of affected terms, please visit [What is Microsoft Dataverse?](https://docs.microsoft.com/en-us/powerapps/maker/common-data-service/data-platform-intro#terminology-updates)

Scenario
--------

You are a functional consultant for your organization Contoso. You are assigned
to work on a project for your client Fabrikam. You are working on the data model
you started in the prior practice. In this practice you are enabling some entity
options that can only be done using the classic solution explorer.

To view the data model you are building, **view  Image[MB-200]_M02L02_Creating_Entities_Fields.png in the Lab Resources**.

In this practice, you will be performing the following tasks.

1.  Enabling the Feedback option on Knowledge Assessment. This will cause the
    system to create the relationship between Knowledge Assessment and the CDM
    Feedback entity.

2.  You will enable auditing on the Knowledge Assessment entity.

3.  You will be updating the icon on the Knowledge Assessment entity, so it is
    not using the default icon.


Exercise 1 – Enable Entity Options
----------------------------------

In this exercise, you will enable the Feedback option on Knowledge Assessment as
well as enable auditing. You will then update the icon on the Knowledge
Assessment entity.

### Task 1 – Enable Feedback and Auditing Options for Knowledge Assessment

1.  Navigate to <https://make.powerapps.com/> and make sure you are in your
    **Practice** environment.

2.  Select **Solutions**.

3.  Click to open **Common Data Services Default Solution**.

4.  Click on the ellipses and select **Switch to Classic**.

5.  Expand **Entities**.

6.  Select the **Knowledge Assessment** entity.

7.  Scroll down to the to the **Communication and Collaboration** section.

8.  Select the **Feedback** checkbox. *Note:* Enabling any option with a + cannot be undone, so always confirm
    before you enable any of those features that you are on the right entity and
    need the feature.

9.  Scroll down to the **Data Services** section.

10. Check the **Auditing** checkbox. *Note:* Remember auditing must be turned on at the environment settings,
    entity and field to produce any audit data. By default, fields are enabled
    for auditing.

11. Click **Save**.

12. Click **Publish.**
