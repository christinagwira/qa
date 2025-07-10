Test Case ID:
01

Summary:
Restrict artifact creation based on future effective date

Description:
To prevent the creation of a consent for a date in the future.

Issue Type:
Test

Test Type:	
Cucumber

Cucumber Test Type:	
Scenario

Cucumber Scenario:
Given user places a create call to the  API
And the effective date of the artifact is in the future
When the call is made
Then an error should be returned similar to the following, "'ArtifactID' cannot be created as effective date is in the future."

Automation Assessment:
A: In Sprint Automation


**********************

Test Case ID:
02

Summary:
Restrict search for an artifact based on future effective date

Description:
To prevent the search of a consent for a date in the future.

Issue Type:
Test

Test Type:	
Cucumber

Cucumber Test Type:	
Scenario

Cucumber Scenario:
Given user places a search call to the  API
And the effective date of the artifact is in the future
When the call is made
Then an error should be returned similar to the following, "'ArtifactID' cannot be searched as effective date is in the future."

Automation Assessment:
A: In Sprint Automation


**********************

Test Case ID:
03

Summary:
Restrict retrieval for an artifact based on future effective date

Description:
To prevent the retrival  of an artifact for a date in the future.

Issue Type:
Test

Test Type:	
Cucumber

Cucumber Test Type:	
Scenario

Cucumber Scenario:
Given user places a retrieve call to the  API
And the effective date of the artifact is in the future
When the call is made
Then an error should be returned similar to the following, "'ArtifactID' cannot be retrieved as effective date is in the future."

Automation Assessment:
A: In Sprint Automation