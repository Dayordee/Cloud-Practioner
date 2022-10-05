# Identity and Access Management (IAM)

## Working in Billing Unit

The image below shows two employee in the finance unit. They are to be granted workspace on AWS. 

![ass1_1](/images/ass1_1.png)

Perform the following task as described on the attached image


![ass1_2](/images/ass1_2.png)


Note:
At the end of the lab, you should perform clean up operations.




Guides:

https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_billing.html

1. I Activated my IAM access
![](../../images/edit.png)

2. I creater the users fix them in the required groups
![](../../images/FM.png)
![](../../images/FU.png)

3. I created both Policies
![](../../images/policies%20created.png)

4. I tested both users to confirm if the policies I attached works

For:- 
a. Finance Manager that has the Full Billing Access , when I tried modifying the billing preference Access was granted because it has the full Access attached in it's policy created.
![](../../images/granted.png)

b. Finance User had only the read access and cannot modify the billing preference, so access was denied while I tried using it to modify billing preferences.
![](../../images/denied.png)

5. I cleaned Up
![](../../images/see.png)
![](../../images/Screenshot%20(467).png)
![](../../images/Screenshot%20(469).png)