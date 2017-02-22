Curtis Marr - Use Case 2

<h5>Title:</h5> 
    Manager Determining Scan Information

<h5>Primary Actor: </h5> 
    Manager

<h5>Goal in Context: </h5> 
    The manager is able to access the scan DB and receive license <br/> and vulnerability information of a given software package.

<h5>StakeHolders:</h5> 
    - Developer: To find out if the Developer's software packages are able to be used.
    - Manager: Look at specific packages and determine if they can be used.
    

<h5>Preconditions:</h5> 
    The inputed package name is in the scan DB and there is information about it.

<h5>Main Success Scenario:</h5> 
    The Manager's inputed software package which is sent to the scan DB, and has accurate information returned regarding
    the specified software package. 
    
<h5>Failed End Conditions:</h5> 
    The Manager is not able to connect to the scan DB or is receives inaccurate information.

<h5>Trigger:</h5> 
    The manager inputs the name of a software package.
