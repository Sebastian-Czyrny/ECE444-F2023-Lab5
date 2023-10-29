# ECE444-F2023-Lab5
## Author: Sebastian Czyrny

This repository was created by going through the following repository: https://github.com/mjhea0/flaskr-tdd#first-test

## Unit test in group project:
Please find the unit test I created for my group project here:
https://github.com/ECE444-2023Fall/project-1-web-application-design-group16-fieryflamingos/blob/models_development/tests/test_db.py#L48-L146

The unit test is called TestRegularUser, it tests the functionality of the regular user model and querying it from the database.

## What are the pros and cons of TDD?
### PROS
- **Well-defined functionality**. The unit tests define the expected behaviour of the function
- **Better collaboration**. One member can write unit tests, and other members can integrate the functionality. All members will understand what the code must do because it is defined by the unit tests.
- **Easier debugging**. TDD ensures that when the test fails, the developer can be certain of where it fails, since they only focus on making sure their function passes unit tests before moving on
- **Less defects**. Similar to the previous point, by ensuring that a small section of code works before moving on to work on other sections, the number of defects decreases

### CONS 
- **More code writing**. Will need to write additional code for the unit tests, and need to verify that the unit tests work as expected
- **Figuring out the correct amount of testing**. How many tests need to be written before it can be confirmed that the code works as expected? How do we know if we have enough tests? Who writes the tests and who writes the functions? Time needs to be taken to think about these questions for every function and takes time out of development 
- **Unit test bias**. Possible that the unit test writer is the same as the function writer and purposely or accidentally misses unit tests just to get their code working
- **Over reliance on unit tests**. Similar to previous point, unit tests don't always get all cases. If a test passes, it does not mean with absolute certainty that the code works as expected. After all, just like the code, the unit tests were written by humans
