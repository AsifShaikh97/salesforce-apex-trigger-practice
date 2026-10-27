# Practice 02: Opportunity Description Update

## Scenario
When an Opportunity is created, if the Amount is not null and greater than 100,000, populate the Description field with `Hot Opportunity`.

## Concepts Covered
- Apex Triggers (`before insert`)
- Trigger Handler Pattern
- Conditional logic
- Null checking
- Bulkification basics

## Expected Result
When an Opportunity is created with an Amount greater than 100,000, its Description is automatically set to `Hot Opportunity`.

## Purpose
This practice demonstrates how to automate Opportunity field updates using Apex triggers and handler classes.