# create_an_IAM_user_on_AWS

**WHO IS AN IAM USER?** - an IAM (Identity and Access Management) user is an entity that you create to represent an individual person or application that interacts with AWS resources. IAM users are part of AWS’s access management system and can be assigned permissions to access and manage AWS services and resources.

**Let's create Adminstrator as an IAM user.**

- Start with creating a AWS Account
- From the log in page, sign in as the root user with password.
- Then proceed to the IAM console.
  ![](design.png)
- From the left sidebar of the IAM Console, click **Users** and then click **Add user**
  ![](Users.png)
- Enter User name as **Administrator.**
  ![](Admin.png)
- Tick **Provide user access to the AWS Managemen** Console check box.
- Choose **I want to create an IAM user**
- - Choose Custom password and enter a password of your choice. 
- Uncheck the Users must create a new password box. 
  ![](C-IAM.png)
- Click Next.

# Set Permissions.
- Choose **Attach policies directly**,
  ![](Attach.png)
- tick **AdministratorAccess** option.
- ![](Admin-access.png)
- Then click **Next.**
  ![](Admin-next.png)
- Review and create user.
  ![](User-create.png)
- Copy the URL or download the cvs file.
  ![](download.png)
Log out from the **root user** and then log in to the **Administrator user** you just created.
![](New.png)

# Conclusion.

We have created IAM user to perform tasks, instead of performing tasks directly with root user.
