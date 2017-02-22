Curtis Marr - Use Case 2

<h5>Title:</h5> 
    Manager Determining Scan Information

Primary Actor: 
    Manager

Goal in Context: 
    The manager is able to access the scan DB and receive license and vulnerability information of a given software package.

StakeHolders: <br/>
    - Developer: To find out if the Developer's software packages are able to be used.
     -Manager: Look at specific packages and determine if they can be used.
    

Preconditions:
    The inputed package name is in the scan DB and there is information about it.

Main Success Scenario:
    The Manager's inputed software package which is sent to the scan DB, and has accurate information returned regarding
    the specified software package. 
    
Failed End Conditions:
    The Manager is not able to connect to the scan DB or is receives inaccurate information.

Trigger:
    The manager inputs the name of a software package.
