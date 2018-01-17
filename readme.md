DMN in Business Central
=======================

A really simple process that include the DMN Rule.

To lauch the process run this:

	curl -X POST "http://localhost:8080/kie-server/services/rest/server/containers/DMNTest_1.0.0/processes/DMNTest.RuleFlow/instances" -H "accept: application/json" -H "content-type: application/json" -d "{}"
