# Vantiq-Utility-Procedures


A set of procedures for Vantiq to extend functionality

## PostDeployment.AddRestrictedUsers()
This procedure adds any non admin user to the restricted users list in a Vantiq Client. It is meant to be used as a post deployment script as it edits the client to add the users.  The reason this procedure is neccesary is becuase when you deploy a client it will not preserve the restricted users list.





