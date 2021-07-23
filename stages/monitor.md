# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Monitor  
### __Stage description:__  
Stage 08: As the "final" step in an iteration, this stage sets the stage for the next, and informs the planning. If effectively done, we can start to optimise delivery times, handle feedback faster, and increase customer satisfaction.  

Here we might monitor for customer feedback, or manage "canary" instances for new and experimental features. We might confirm that the initial [presumed]need upon which a change was made was correct and has been appropriately addressed through Planning and Code.  
  
If the system is provided using an "Infrastructure as a Service" model, we may have direct access to containers/instances to syphon our own feedback from production environments.  

It is critical that we learn from failures at this stage ("Encourage Failure") so that we can better plan for future iterations.


| Pipeline Stage:<br>Monitor   | End User | Product Owner | Developer | QA Agent | Project Manager | System Admin |
|----------------------------- |--------- |-------------- |---------- |--------- |---------------- |------------- |
| Handle Customer Feedback     | C, I, V  |  C, I         | I         | I        | R, A, S         |              |
| Analyse Automataed Metrics   |          |               |           |          | R, A            | C, I         |
| Analyse Performance Metrics  |          |               |           |          | R, A            | C, I         |
| Generate Work Items          |          |  R            |           |          | A               |              |
| Re-Prioritize Backlogs       |          |  R, A         | I         |          | C               |              |
  
  
[Home](../index.md)  
