# Practice 01: Update Account Rating for Media Industry

## Scenario
When an Account is created or updated, if its Industry is `Media`, automatically set its Rating to `Hot`.

## Concepts Covered
- Apex Triggers (`before insert`, `before update`)
- Trigger Handler Pattern
- Working with `Trigger.new`
- Updating fields without additional DML
- Bulkification basics

## Expected Result
When an Account's Industry is set to `Media`, its Rating is automatically populated as `Hot`.

## Purpose
This practice demonstrates how to use Apex triggers and handler classes to automate field updates on Account records.