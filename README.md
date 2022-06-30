# CodingAssessment
Take home assessment for Hypori's server team

Exercise - Expose an API for querying against a dataset:
The goal of this exercise is to design a read only API (REST or otherwise) that returns one or more records from one of the static datasets under the datasets directory (either 2vr3-k9wn.json or y77d-th95.json).  It is also a goal to be able to run this as a spring boot application.

Depending on the dataset you choose we want to be able to query based on the available fields. For instance:
* list the data based on one or more fields/attributes (e.g. /nearearthasteroid?h_mag[gte]20&&orbit_class[eq]Apollo)
* Be able to fetch a single record via a GET request (e.g. /meteorite_impact?id=448)

Note:
* The examples above are not a contract, feel free to design the URL structure and modify the json schema in a way that you think creates the best client experience.

Evaluation Criteria:
* Put into an accessible public repository like github (or other like bitbucket)
* Be a Spring Boot application
* Code compiles with unit test coverage
* Unit test code to be treated equally with business logic code
* SOLID design principles 
* (Stretch-Goal) Put this into a docker container to run in
* Need a readme.md with enough information for a dev to get started, please make mention of the architecture used and why
* roadmap.md - dream big where do you see this app going in the future, what would you have done differently, or what would you have done given sufficient time
