Curtis Marr - Data Flow Diagram Dictionary

Entities:
Developer - Person who is able to upload a software package to have the license and vulvernabilities scanned, then have the
  results returns and put into a database.
  
Manager - Person who is able to see the software package database, as well as create, edit, and apply policies.


Processes:
Verifier - Takes in a software package, confirms it is a software package, then sends it out for a scan of the licenses and
  vulnerabilities. When the information is returned, sends the results back to the Developer and to the software package
  results database.

License Scanner - Gets sent a software package, which it scans for what licenses are applied to it. Returns the license results.

NIST Vulnerability DB - External database not controlled by the user. Lists all known vulnerabilities published for a given
  software package.

Software Package Results DB - Database created for the purpose of listing the results found for all Software Packages uploaded by
  Developers.
  
Policy Data Base - Keeps record of all policies and the details of each.
  
Get License & Vulnerability Info - With an inputed Package name, searches the Software Package Results DB for the Package. If results
    are found, returns the details about it.
    
Apply Policy - Given a Package name, will send it to the Policy Data Base to check against any current policies, then returns results.
  
Create/Edit Policy - Given a policy name, it will check if it is currently in the Policy Data Base. If it is, then it will update that
    policy with the new information provided, otherwise it creates a new policy with the information provided.
    

Data Flows:
Software Package - The Software Package that will be scanned.

License Scan Results - A list of what licenses apply to a Software Package.

Package Name - The name of a Software Package that will be searched against the NIST Vulnerability DB.

Vulnerability Scan Results - A list of what Vulernabilities apply to a Software Package.

Package Info - Information of a specific package that would like to be searched if it is in the Software Package Results DB.

Policy Name - The name and information for a policy to be added/Updated in the Policy Data Base.

Policy Info - Information applying to a given policy.

Package Policy - List of Policies that apply to a specified Software Package.
 
