![](https://github.com/Microsoft/MCW-Template-Cloud-Workshop/raw/master/Media/ms-cloud-workshop.png "Microsoft Cloud Workshops")

# Enterprise-ready cloud setup

## Requirements

-   Local machine or a virtual machine configured with:

    -   Visual Studio 2015 or 2017 Community Edition or VS Code

-   Full global admin access to the Azure AD tenant associated with your Azure subscription

## Before the hands-on lab

Duration: 15 minutes

To complete this lab, you must have full global admin access to the Azure AD tenant associated with your Azure subscription.

### Task 1: Validate global admin access to Azure AD tenant

1.  Login to <http://portal.azure.com>, click on **All Services**, and type in **Azure Active Directory**

2.  Open the Azure Active Directory tenant. Click Users -\> New User

3.  Create a new user called testuser/test1. Use the tenant name on the header for the domain name of the email.

    ![Create user Azure portal blade with user name and email domain name highlighted.](images/Setup/image3.png "Create User blade")

**If you can create the user, you will enough permissions in Azure AD to complete the lab. If you cannot, you will need more permissions before proceeding.**

### Task 2: Setup a development environment

If you do not have a machine set up with Visual Studio complete this task, and use this VM to complete the remainder of the Lab.

1.  Create a DS2\_V2 Azure Virtual Machine using the Visual Studio Community 2017 image from the Azure Marketplace.
