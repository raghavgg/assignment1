# assignment1
First of all, i have created Connection using config file.

Then i have created first resource of deployment using nginx image with 2 replicas. 
After creting, I list out the deployments. Then update the specification of deployments to 1 replica and image version change.
Once updation done, i list out again the deployments. 

Once i done these operations, i delete the deployment.

Now, i create next resource of namespace. Once creation done, i list out the namespaces.

Then, i created next resource of same deployment in the newly created namespace. After which i list out the deployments in the created namespace.
Now, i created a NodePort service, Then i list out the deployments using labelSelector.

Then i deleted the deployment, Deleted the service, and Deleted the NameSpace.
