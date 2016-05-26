SalesforceDeploymentSample/README.md

Gary Hamilton <ghamilton@acumensolutions.com>
Version 1.0

Sample project for continuous integration. 
Running Apache Ant in workspace executes deployeCodeCheckOnly task.
Run in Jenkins supplying sf.serverurl, sf.username and sf.password as parameters. sf.serverurl defaults to test.salesforce.com.

Jenkins will call ant with parameters -Dsf.username=xxxx -Dsf.password=yyyy -Dsf.serverurl=cs2.salesforce.com
