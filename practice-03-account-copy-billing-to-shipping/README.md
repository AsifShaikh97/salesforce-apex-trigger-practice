# Practice 03: Copy Billing Address to Shipping Address

## Scenario
When an Account is created and the `CopyBillingToShipping` checkbox is selected, automatically copy the Billing Address fields into the corresponding Shipping Address fields.

## Concepts Covered
- Apex Triggers (`before insert`)
- Trigger Handler Pattern
- Checkbox-based conditions
- Working with Account address fields
- Bulkification basics

## Expected Result
When an Account is created with `CopyBillingToShipping` checked, the Billing Street, City, State, Postal Code, and Country are copied to their corresponding Shipping Address fields.

## Purpose
This practice demonstrates how to automate address field population based on a checkbox condition using Apex triggers and handler classes.