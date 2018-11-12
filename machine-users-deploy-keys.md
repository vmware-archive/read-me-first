## Machine Users and Deploy Keys

For single repository integrations, GitHub’s officially recommended workflow is to use [Deploy Keys](https://developer.github.com/v3/guides/managing-deploy-keys/#deploy-keys).  However, we are looking into some concerns that have been raised around how those keys are generated and how actions taken using those deploy keys later show in various audit logs.  An alternative that has been employed by many teams previously is the use of machine users. 

Due to the security risk a machine user poses, we are working to explore the various ways our organization actually uses those machine users and more secure ways we are able to achieve that same result.

**While we work to perform a threat analysis, identify use cases and more ways to achieve those same outcomes - we will be enabling machine users in this org.  _This is subject to change (and more than likely will).  Please stay tuned for future messaging around this._** 

If you believe you need a machine user, please reach out via an ask ticket with the following information: 

* Team Name 
* Machine User Name: 
* Use Case:
* Where the login credentials for this user will be stored: 
* How the credentials for this user will be managed (rotation cadence, who will have access, etc.) 
* Name and username of the individuals requesting the machine user has access: 
* Repo(s) the machine user needs access to: 
* Level of access the machine user needs: 


If you have any questions or concerns please send an ask ticket, CC’ing the GitHub Migration team. 

Thank you! 
