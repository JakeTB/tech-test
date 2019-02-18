# The DataShed technical test

## Overview

This document contains a set of instructions for engineering candidates to follow in order to complete the DataShed technical assessment. The purpose of the assessment is to gain an insight into the candidate’s approach to translating a set of system requirements into functioning code.

## Instructions

The completion of this technical test should result in the creation of a fully functioning application that meets the requirements outlined by the below objective. No constraints are imposed with regards to the framework or programming language chosen, nor is it expected that the assessment is to be completed within any set time frame. 

If the candidate requires any further information or encounters any issues in completing this assessment, please contact recruitment@thedatashed.co.uk  

Once complete, the generated codebase (including all source files) should be emailed to recruitment@thedatashed.co.uk, the source code should not be made available via a public code repository (E.G. github.com).

## Objective

At the DataShed we process a lot of data, sometimes this data can arrive in many formats and at varying levels of data quality. Given a subset of personal data --> [link](profile-data/DataShed_Technical_Test.csv), you are required to create a simple application that meets the below user story and acceptance criteria.

### Story

> “As a user, I want to understand the number of duplicate and unique records I have in my data, so I can be sure that I can identify unique and related records in the data that I hold.”

### Acceptance Criteria

* The application should read data from the target file;
* The application should output the number of unique records; 
* The application should output the number of duplicate records;
* The application should write the data that is considered duplicated/related to a file: relateddata.csv
* The application should consider data that is similar and classify it as a duplicated/related, E.G. ‘Wilyam Premadasta’ and ‘William Premadasa’ should be considered the same person

### Considerations

The application should meet the above requirement and acceptance criteria, the code should be maintainable and written with consideration to testing, performance and future enhancements.

The application should be relatable to real world experience and include appropriate tests, code practices and error handling.

The application can be created using any suitable programming language and should include clear instructions on how to execute the application to obtain the expected results.

