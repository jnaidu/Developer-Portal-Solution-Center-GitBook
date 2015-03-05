# Solution Center Solution Administrator Role
Solution Center Solution Administrators are those individuals within a company that have been given ownership over a solution.  They are primarily focused on tasks such as managing instances and releases for a solution.  This role must be granted to a user for each solution on which they need ownership.  Solution Administrators can access features of all subsequent roles, but only on solutions they own. They have complete read access to everything in their company, but no ability to change solutions for which they don't have ownerships.


## Update a solution
### Steps:
1. On the left panel, click **Solutions Center**. A list of all the solutions that have access to the solution center will be displayed.
2. Select your solution by clicking on the solution name.
3. Click **Edit Solution** to update a solution.




## Grant the Solution Center Solution Admin role to a user account for a solution
### Steps:
1. On the left panel, click **Solutions Center**. A list of all the solutions that have access to the solution center will be displayed.
2. Select your solution by clicking on the solution name.
3. Click the **Users** tab. A list of users who have access to your solution will be displayed.
4. To grant the role to a user account, click **Add role** corresponding to the desired user.
5. Click **Yes** on the pop-up window.
6. The user with the new role will show up under the **All Users** table.


## Create an instance
1. On the left panel, click **Solutions Center**. A list of all the solutions that have access to the solution center will be displayed.
2. Select your solution by clicking on the solution name.
3. Click the **Instances** tab. A list of all the instances for your solution will be displayed.
4. Click **Add Instance**.
5. Provide a friendly instance name in the field **Instance Name**.
6. Pick an instance type from the available configuration options. You have the ability to create multiple development and pre-production instances, however, you can only create one production instance.
7. Provide an instance alias name in the field **Alias**.
8. You can either create a new realm or choose from existing realms. If you choose an existing realm, the instance portal, identity APIs, ID Provision, and ID Broker will be configured to run against your selected realm.
8. Click the **Add Instance** button.
9. The instance creation does the following background work to set up the instance:
    1. Create Realm
    2. Create Portal
10. Once your instance has been successfully provisioned, note down the instance details for your reference.The admin login Id is always “SOLUTION ALIAS-INSTANCE ALIAS_ADMIN”, and the default password is “Covisint$2015”. This is the SEED ACCOUNT for this solution instance.
11. Click the **View Instance Settings* button to view instance details.

## Delete an instance
1. On the left panel, click **Solutions**. A list of all the solutions for your company that have access to the solution center will be displayed.
2. Select your solution by clicking on the solution name.
3. Click the **Instances** tab. A list of all the instances for the selected solution will be displayed.
4. Select an instance by clicking on the instance name to retrieve an instance.
5. Click **Edit Instance**. You'll be able to edit the name and the description fields.
6. Click **Delete Instance**.
7. Enter a reason for deleting the instance, and click the **Delete Instance** button and then **OK** to complete the step.



