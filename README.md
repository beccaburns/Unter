## Unter Tech Interview Challenge
### Completed by Becca Burns 
### Interview conducted by Noel at CraftAcademy

Rails with testing frameworks and CI/CD

This week challenge assesses my ability to scaffold a new Rails project.

## Challenge
Your project team will be starting a new project - a crowdsourced transportation platform calledUnter. You were assigned the following chores by your team:

### Set up main repository
```
As a development team
In order to be able to collectively work on the same codebase
We would like to have a main repository on GitHub we all can use as the upstream repository
```
#### Tasks (Acceptance Criteria)
- Set up a repository on GitHub 
- Create a development branch and set it as the main branch of the project 
- Share repo with team

### Set up application structure
```
As a development team
In order to be able to start adding features
We would like to have an basic application structure
```
#### Tasks 
- Scaffold a Rails application 
- Turn off generators for helpers, assets and all specs (accept model specs
- Clean up the generated code from unnecessary comment for good readability

### Set up testing environment
```
As a development team
In order to be able to make sure our code is doing what it is supposed to do
We would like to be able to write and run automated tests
```
#### Tasks 
- Add and configure Cucumber for Acceptance tests
- Add and configure Rspec for Unit and Request specs

### Set up continuous integration
```
As a development team
In order to make sure that the code we add to the code base is functional
We would like to run full test suite on a remote service
```
#### Tasks 
- Set up CI on Semaphore or Travis

### Set up test coverage metrics
```
As a development team
In order to see how much of our code is covered in tests
We would like to measure test coverage using a remote service
```
#### Tasks
- Set up Coveralls for the main repository
- Add and configure Coveralls for RSpec and Cucumber
- Coverage results needs to be merged in order to get metrics from both tools

### Set up continuous deployment
```
As a development team
In order to automate the deployment process during development
We would like all code that has been merged into the main code base, to be deployedto a server
```
#### Tasks
- Create an application on Heroku
- Set up deployment using the CI tool
