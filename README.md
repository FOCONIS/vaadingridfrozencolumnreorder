vaadingridfrozencolumnreorder
=============================

Demonstrate the problem in GitHub issue #10546 grid column frozen column reorder issue with SelectionMode.MULTI</description>

*Steps to reproduce:*
- Drag the first frozen column behind the second column.

Workflow
========

To compile the entire project, run "mvn install".

To run the application, run "mvn jetty:run" and open http://localhost:8080/ .

To produce a deployable production mode WAR:
- change productionMode to true in the servlet class configuration (nested in the UI class)
- run "mvn clean package"
- test the war file with "mvn jetty:run-war"
