# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Build  
### __Stage description:__  
Stage 03: The first stage of DevOps ~~magic~~automation.  
  
In addition to or in place of the Peer Review performed in the Code Stage; committed code  may be reviewed before merged into a main/master/shared branch to ensure there will be no conflicts and to address those conflicts.  
  
In a DevOps pipeline, we should now have triggered automation against those changes; Integration, Unit & Regression testing.

If there are issues, the changes will be rejected and the developer notified to correct them, else, the codebase is built to make application useable in the next stage of testing.  
  
For complete optimization and automation, this build process will make sure of a configuration management tool, Inrastructure as Code, to create an instance of a staging environment which could range from simple virtualisation, to docker and kubernetes instances.


| Pipeline Stage:<br>Build     | End User | Product Owner | Developer | QA Agent | Project Manager | System Admin |
|----------------------------- |--------- |-------------- |---------- |--------- |---------------- |------------- |
| Code/Peer Review             |          |               | R, A, C V | I        |                 |              |
| Automated Unit Testing       |          |               | I, C      | R, A     |                 |              |
| Staging (Code as Inf.)       |          |               |           |          |                 | R, A         |
  
  
[Home](../index.md)  
