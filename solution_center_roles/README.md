# Solution Center Roles
The Developer Portal Solution Center has its own set of associated roles, and when a user is granted a role, they gain access to specific features for that application. Each role will be described in detail below, but there are a few general traits shared across roles that are worth noting:
* Some roles implicitly have access to the features of lower-level roles beneath them
Example- The Solution Center Administrator has access to every solution and instance on the platform, even if they have not explicitly been granted the Solution Administrator or Instance Administrator roles.
* Some roles must be granted against the entity which they are intended to protect
Example- The Solution Center Instance Administrator role must be granted against a specific instance, because we have to limit the administrative rights of the user to just that instance.
* Multiple roles can be assigned to a single user
Example- Roles are cumulative; a single user can be a CCA Security Administrator, a Solution Center Company Administrator, a Solution Center User, and a Messaging Tenant Admin all at the same time.


