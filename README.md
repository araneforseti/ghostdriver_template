# ghostdriver_template
Template for creating a java project which uses java, gradle, selenium, and phantomjs

Requirements to use:
- gradle
- java

This project uses maven dependencies (via gradle) to install everything needed the first time you try to run a project using the gradle script. It uses Arquillian Phantom Driver to manage the dependency on phantomjs, so you do not need to have it installed on the target computer.

Screenshots will occur on failure to aid in resolving failing tests.
