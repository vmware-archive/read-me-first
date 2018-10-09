# Security and Minimizing Risk in the org 

When approaching security around your code, there are few things to keep in mind that revolve around knowing where you are committing your code, who has access to that code, and what you are putting into your code. 

When working, please keep these things in mind: 

### Be careful where you commit
 
 Some common examples include: 
 
* Committing a branch to the wrong repo
* Cloning something outside of the org
* Also, please don’t clone any private repositories into personal orgs without prior approval from to Open Source Review Team (OSRT)

### Be careful what you commit

* Avoid storing credentials in GitHub repos whenever possible.

* Please do not store any customer or personal information (anything sensitive) in any of our GitHub repositories.

### Other things to keep in mind / Best practices

* We recommend that you rotate your credentials every 90 days

    * i.e. SSH Keys, Personal Access Tokens, etc. 

* Add a SECURITY.md file in your repositories that outlines:
    * Disclosure policy
    * Security Update policy
    * Security related configuration
    * Known security gaps & future enhancements

_If you ever have any questions about security, or anything else within this org, please don't hesitate to reach out to the admin team via an ask ticket._
