Curtis Marr - Use Case 1

Title:
    Developer Uploading a Software Package

Primary Actor: 
    Developer

Goal in Context: 
    The Developer is able to submit a software package and have it get vulnerability and license information returned
  and set to the DB.

StakeHolders: 
    Developer - To send the needed information to determine if the package can be used.
    Manager - Look at specific packages and determine if they can be used.

Preconditions:
    The Developer must send a software package that can be scanned for licenses and vulnerabilities.

Main Success Scenario:
    The Developer successfully submits the software package and gets accurate information back, as well as having the information added 
    to the DB properly.

Failed End Conditions:
    The Developer does not successfully submit the software Package, or the returned information is inaccurate.

Trigger:
    The Developer uploads a Software Package to be scanned.
 
