+++
title = "4. Reviewing a company registration application"
description = "Demonstration of a sample Conforma system"
date = 2021-05-01T08:20:00+00:00
updated = 2021-05-01T08:20:00+00:00
draft = false
weight = 13
sort_by = "weight"
template = "docs/page.html"

+++

Head back to the log in page of the demo system (preferably in an another broswer!) by navigating to:
https://conforma-demo.msupply.org:50000/ 

Now for this part of the tutorial we are going to log in as a staff member of the Regulatory Agency. 

We are going to use the following staff members account:

![Internal user details](/docs/about/demo/24.png)

As noted above, Alice's role is as a Business Services Admin, and part of her role is to mananage company registration applications.

Go ahead and log in using Alice's credentials (above).

### Navigating the system as a Regulatory Staff user

Once you have logged in you will be taken to Alice's dashboard homepage. You may have noticed that the dashboard layout looks very similar to the home page of your external user account you made earlier.

However, there are of course differences between external and internal user accounts!

Within this section we explain some of the key differences. 

**To begin with let's go over the differences when looking at the dashboard:**

1. In the top right left hand corner you will see that internal staff members are assocaited with the organisation 'Regulatory Authority'

![Internal organisation](/docs/about/demo/25.png)

2. The types of applications/workflows you can interact with are limited by your permissions

    Below are examples of two different staff members of Regulatory Authority. The first is Alice, and the second is a Bob Vance a section head of the medicines registration section. 

3. The applications overview section shows the relevant applications are or can work on.

4. The databases are internal databases that include all approved application products (e.g. A database of all registered companies)

<div class="note">
As noted above, different staff will have different access to different modules/applications based on their permissions.

For example Alice is able to view and interact with company registration applications but not with product registration applications.
</div>



---------------

### Looking at an application review page
 
 OK, let's take a look at the review page of the application you submitted earlier.

 1. Click **Reviews awaiting assignment** to filter the list of applications to those that still need assigning.


    This will then display a filtered list like:

    ![Filtered application list](/docs/about/demo/26.png)

 2. Click on the link of the application you just submitted.

   ![Application link](/docs/about/demo/27.png)


 3. This will take you the review page of the application. 
 
    The review page has the 4 tabs of informaation/function that are described below.

    **Overview tab**

    Within the overview tab you can see information such as:

    - Application details: *Basic information related to the application such as who it was submitted by, the date of submission and application ID*

    - Activity history: *This section shows a detailed history of the application's workflow process. It is especially helpful for applications with more than one stage to monitor and track it's progress*

    ![overview tab](/docs/about/demo/28.png)


     **Assignment tab**

     Within the assignment tab you can assign applications and view current and past assignments for all stages of an application.

     For most applications when you assign one section, it will assign all sections of an application to the user. For complex applications, that may need to reviewed by multiple people at one time, each section can be assigned to a different staff member.
        

     ![assignment tab](/docs/about/demo/30.png)

     **Internal notes tab**

     The internal notes tab allows internal staff members to add comments and adhoc files related to an application. A history of who made each comment is recorded in the system.

     In the below example another staff member attached an email enquiry related to an application. 


     ![internal notes tab](/docs/about/demo/29.png)

     **Documents notes tab**

     Within the documents tab you will be able to see any system generated certificates related to an application (e.g. Product registration certificate). In the case where there is no certificates that have been generated, this section will be blank. 

     ![Documents tab](/docs/about/demo/31.png)

----------------

### Assigning the application to your workload
 
Now you are familiar with the review page and it's functionality, let's start reviewing that company registration application you previously submitted. 

First, we need to assign the application to ourself so we can begin reviewing.

1. Navigate the assignments tab of the application

<div class="tip">
You can access assignments tab directly from the application list, just click the self-assign button!
</div>

![self-assign](/docs/about/demo/32.png)

2. Using the drop down list that displays **Not assigned** select 'Yourself' from the list.

3. Now click the **submit** button

![assignment tab](/docs/about/demo/30.png)

4. You have now been assigned the application. 

    This is now reflected in assignments tab.

![assignment tab](/docs/about/demo/33.png)


<div class="tip">
Don't forget that this activity is also reflected in the Activity section of the overview tab.
</div>

-----------

### Reviewing a company registration application

Now the application has been assigned to yourself, you can now get to work and start reviewing the application.

1. Within the assignments tab of the review page, click the **Start** button.

![assignment tab](/docs/about/demo/35.png)

2. Within the application each application form, all reviewable fields can be reviewed. To review an individual field click the **Review** button. This opens up the a space for the reviewer to mark the form requirement as either Conform (meets requirements) or Non-conform (does not meet requirements). 

    Move through the review form and mark each requirement as either a conforming or non-conforming field. For this tutorial please mark eveything as a conform for now (we will get the rest later!)   
    
    The comments field within the review box can be used to record internal notes as needed. Internal notes for conforming form fields are not visible to the applicant. 
    
    However when a field is marked with a non-conform outcome, a comment to be communicated to the applicant is required (.e.g. Provide direction to the applicant).
    

<div class="tip">
You can also use the Approve all button to mark all fields within that section as conforming requirements.
</div>

![assignment tab](/docs/about/demo/37.png)


<div class="warning">
Remember if you record form elements with a non-conform outcome and issue a list of questions (or request for information) to the applicant, any comments including in those non-conforming fields will be visible to the applicant.
</div>


3. Once you have completed your review of all of the form fields, it is time to record your review outcome for that application. For this application there is only stage. 

    The following diagram outlines for this application what the outcomes mean.

    ![assignment tab](/docs/about/demo/38.png)

    The review outcome buttons appear at the bottom of the page, and change depending on your review of the form fields above.

    Because we selected Conform for all the fields above, our only option is to mark the application outcome as **Conform**.

    ![assignment tab](/docs/about/demo/39.png)

4. The last field to fill out is the **Overall comment** field. 

    This is field is a free text box that can be used as follows:

    - If the outcome is to approve or send a list of questions to the applicant, the overall comment can be used to record a note regarding the internal decision. This will not be visible to the applicant. 

    - if the outcome is to reject the application, the overall comment **must** be used to record the rejection reason. This comment will be used by the system to generate rejection correspondence. 

![assignment tab](/docs/about/demo/40.png)


<div class="warning">
Remember if you marking the overall outcome the application as Non-conform to include the reason to for rejection to be provided to applicant within the Overall comment field. 
</div>

5. Once you are happy with your review click the **Submit review** button.

    A final confirmation pop-up will appear asking you to confirm you want to submit your review decision. 

    Click **Submit**

![submission message](/docs/about/demo/41.png)

6. Great, now you have approved the company registration application. You will see on the screen a summary of your review. This review record will be stored in the system and can be accessed at any time.

7. If you have used your email account to sign up for the system, you will have recieved an email that states the approval of the company registration application.

    Emails can be tailored for every application type and outcome. For this application the email should look like this:

    ![Company approval email](/docs/about/demo/42.png)

----------

Now you you have approved that company registration application, log out of Alice's account and head back into your created applicant user account. 

Then jump to section **5. Submitting a product registration application** of the tutorial to continue through the walkthrough.