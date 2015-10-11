openmrs-distro-platform-uganda
==============================

A project for packaging the OpenMRS Platform for Uganda

###Building the project
 * Check out the project onto your machine if you haven't yet.
 * Change the project version to match the platform release version you are about to release
 * Add the latest build of the openmrs war file to the root of the project
 * In the root pom file, make sure you have updated the **openMRSVersion** and **webservices.restModuleVersion** property values to match the latest released OpenMRS core and module versions respectively
 * Build the distributable by running the command below: 
 
  ``` 
  mvn clean install
  ```
