# jenkins
Jenkins is a CI tool

pipeline with shared libraries
pipeline jobs are two types 

- scripted pipeline
- declarative (DSL) pipeline
- declarative (yaml) pipeline --> future

BELOW CI & CD Process:
----------------------
CI (commitChanes--> Triggerbuild --> build --> notify of build outcome --> Runtests --> notify of test outcomes) + CD (Deliver build for staging -- > deploy to production)

DevSecops:
----------
version control --> build --> unit tests --> quality control --> deploy on test.env --> integration test --> regression test--> acceptance test--> deploy to release.env --> deploy to production 
