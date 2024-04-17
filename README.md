# uetn-fontend-tests
UETN automation tests

## Running Configuration 

1. To run all tests use command:

``` mvn -U --define spring.profiles.active=qa --define suite=smoke clean verify ```

Where qa - is an environment to run, smoke -is a suite to be executed

2. To generate Allure report run next commant:
 ```mvn allure:serve``` and html page with all test results will be opened automatically
