# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Release  
### __Stage description:__  
Stage 05: This involves preparing and deploying the application into production environments. Preparation may involve configuring applications as particular product-lines, enabling and disabling some features for a number of reasons:  
- Customer licensed modules and functionality (legal)
- Unfinished/Experimental features
- Target envrironmental requirements
  
The actual deployment may or may not be automatic depending onthe project state and requirements. We may not have access to the production enviroment and deployment may simpley be to make the installer available to customers.

| Pipeline Stage:<br>Release   | End User | Product Owner | Developer | QA Agent | Project Manager | System Admin |
|----------------------------- |--------- |-------------- |---------- |--------- |---------------- |------------- |
| App. Config. Legal           | I        | C             | C         |          | A, S            | R            |
| App. Config. Experimental    | I        | C             | C         |          | S               | R            |
| App. Config. Environmental   | I        | C             | C         |          | S               | R            |
| Automated vs Manaul deploy   | I        |               |           |          | S               | R            |
  
  
[Home](../index.md)  
