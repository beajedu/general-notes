## Azure Cloud - Access Controll(IAM)

To add a user as contributor to directory's(Azure Active Directory) resource group, follow following steps (assuming you're logged in and have directory selected):

1. View Resources on Home Page (https://portal.azure.com/#home)

![resources](./images/1-home-page.png)

2. Select any of Resource you're going to give access to

![view-resource-group](./images/2-view-resource-group-page.png)

3. Select **Access Control**(IAM)

![resource-group-iam](./images/3-resource-group-iam.png)

4. Click on Add (Access Controll --> Add)

![resource-group-iam-add](./images//4-resource-group-iam-add.png)

5. On **Role** Tab, click on *privillaged Administrator Roles* sub-tab

![iam-role-privillaged-adminstrator-page](./images//5-iam-role-privilaged-administrator-page.png)

6. On Privilaged Adminstrator Roles, select your desire role e.g. *Contributor*

![iam-role-privilaged-adminstrator-contributor-role](./images/5-iam-role-privilaged-adminstrator-contributor-role.png)

7. Once done with selecting appropriate role, next step is to select member. We need to add members from existing added members or a new one by entering users's
email

![iam-member-tab](./images/6-iam-member-tab.png)

8. Make sure member is selected as

![iam-member-selected](./images/7-iam-member-selected.png)

9. Once done with selecting appropriate role and member, click on **Review + Assign**

![iam-review-assign-tab](./images//8-iam-review-assign-tab.png)

That's all. We've successfully invited a member to a resource group to manage resources and all services running under that resource group.