Curtis Marr - Use Case 1

Title: 
    Developer Uploading a Software Package

Primary Actor: 
    Developer

Goal in Context: 
    The Developer is able to submit a Software Package and have it get Vulnerability and License information returned
  and set to the DB.

StakeHolders: 
    Developer - To send the needed information to determine if the package can be used.
    Manager - Look at specific Packages and determine if they can be used.

Preconditions:
    The Information for the the Software Package must actually contain files for a Software Package.

Main Success Scenario:
    The Developer successfully submits the Software Package and gets accurate information back, as well as having the information added 
    to the DB properly.

Failed End Conditions:
    The Developer does not successfully submit the Software Package, or the returned information is inaccurate.

Trigger:
    The Developer uploads a Software Package to be scanned.
