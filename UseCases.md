Title: Determine License and Vulnerability Information
Primary Actor: Corporate Manager
Goal in Context: The corporate manager is able to determine license and vulnerabilityinformation from provided project information
Stakeholders:
  Manager: To receive clear and relevant project information
  Developer: To provide the relevant file/package level information
Preconditions:
  Relevant file/package information is in the NIST database
  Proper project information has been provided
Main Success Scenario: Manager receives accurate license and vulnerability information for the requested project packages
Failed End Conditions: Manager receives inaccurate or invalid license and vulnerability information for the requested project packages
Trigger: Manager uploads or identifies project information to which license and vulnerability information is provided

Title: Edit/Set/Retrieve policies
Primary Actor: Manager
Goal in Context:The manager is able to set new policies and edit or retrieve existing ones from a software policy database.
Stakeholders:
  Manager: Edit/Set/Retrieve policies
  Developer: Retrieve Software License and Vulnerabilities Info
Preconditions:
  Manager needs to be able to retrieve software license and vulnerability information
  Manager has to set a policy for the developer to request it
 Main Success Scenario: Manager can edit/set/retieve policies
 Failed End Conditions: Manager can't edit/set/retieve policies
 Trigger: Manager receives a software license and vulnerability information
 
 Title: Developer uploads software package
Primary Actor: Developer
Goal in Context:The developer uploads the software package so the manager can check the package's licenses and vulnerabilities.
Stakeholders:
   Developer: Upload software package
   Manager: check software for licenses and vulnerabilities and store this in a database
Preconditions:
  Developer has a software package to upload
 Main Success Scenario: Developer uploads a software package to be checked
 Failed End Conditions: Developer doesn't upload a software package
 Trigger: Developer needs to know a software package's license and vulnerabilities
