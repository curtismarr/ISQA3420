Curtis Marr - Use Case 1

Title:<br/>
    Developer Uploading a Software Package

Primary Actor:<br/>
    Developer

Goal in Context: <br/>
    The Developer is able to submit a software package and have it get vulnerability and license information returned
  and set to the DB.

StakeHolders: <br/>
    Developer - To send the needed information to determine if the package can be used.<br/>
    Manager - Look at specific packages and determine if they can be used.

Preconditions:<br/>
    The Developer must send a software package that can be scanned for licenses and vulnerabilities.

Main Success Scenario:<br/>
    The Developer successfully submits the software package and gets accurate information back, as well as having the information added 
    to the DB properly.

Failed End Conditions:<br/>
    The Developer does not successfully submit the software Package, or the returned information is inaccurate.

Trigger:<br/>
    The Developer uploads a Software Package to be scanned.
 
