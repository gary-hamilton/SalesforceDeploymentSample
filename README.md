#SalesforceDeploymentSample

Gary Hamilton <ghamilton@acumensolutions.com>
Version 1.0

Sample project for continuous integration. 
Running Apache Ant in workspace executes deployeCodeCheckOnly task.
Run in Jenkins supplying sf.serverurl, sf.username and sf.password as parameters. sf.serverurl defaults to test.salesforce.com.

Jenkins will call ant with parameters such as these: -Dsf.username=xxxx -Dsf.password=yyyy -Dsf.serverurl=cs2.salesforce.com

config.xml is Jenkins configuration file for sample job.

