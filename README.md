# Lab-03-Assigning-licenses-using-group-membership
I created a security group, assigned a license to the group, and verified that a member of the group inherited the license. This exercise showed how group-based licensing scales license management beyond per-user assignment.
 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
My organization has decided to use security groups in Microsoft Entra ID to manage licenses. You need to configure a new security group and assign a license to that group and verify group member license’s have been updated.
<br />


<h2>Walk-through:</h2>
Browse to Microsoft Entra admin center at https://entra.microsoft.com, and sign in using a Global administrator account for the directory.
In the left navigation, under Entra ID, select Groups, then select All groups.

In the Groups page, on the menu, select New group.





<p align="center">
Launch  Microsoft Entra admin center: <br/>
<img src=https://i.imgur.com/udeuzoo.png/>
<br />
<br />
Create a group using the following information:

Setting	Value
Group type	Security
Group name	-SC300-O365
Membership type	Assigned
Owners	Assign your own administrator account as the group owner
Select the No members selected text under Members.

Select Delia  from the list of users.

Select the Select button.

:  <br/>
<img src=https://i.imgur.com/1etKXoo.png/>
<br />
<br />
Connect to Microsoft 365 admin center at http://admin.microsoft.com.

Log in as your administrator account if prompted.

From the menu on the left, select Billing and then select Licenses.

Select Office 365 P2 license from the list.

Select the Groups tab on the licensing screen.

Choose the + Assign licenses item.

Search for -SC300-O365 group the select it from the list.

Once you have added the group, select Assign.

: <br/>
<img src=https://i.imgur.com/xHRVYz0.png/>
<br />
<br />
Confirm your selection:  <br/>
<img src=https://i.imgur.com/X6kgERN.png/>
<br />
<br />
  <br/>
<img src=https://i.imgur.com/k4dEBDJ.png/>
<br />
<br />
Returned to the browser tab with Microsoft Entra admin center open.

Navigated back to the All groups in the left navigation, under Entra ID, select Groups.

In the Groups page, select -SC300-O365.

In the left navigation, select Licenses.

Notice that the Office 365 P2 license has been assigned.:  <br/>
<img src=https://i.imgur.com/XcIy9zS.png/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
