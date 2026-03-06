# Test Case ID: TC-REG-002
## Title:
Verify registration with invalid email format shows error message

## Preconditions:
- User is on the registration page
- Browser cache and cookies cleared

## Test Data:
- Email: invalid-email-format
- Password: Test1234
- Confirm Password: Test1234

## Test Steps:
1. Open the registration page: https://example.com/register
2. Enter invalid email in the "Email" field
3. Enter valid password in the "Password" field
4. Confirm password in the "Confirm Password" field
5. Click the "Register" button
6. Observe the response

## Expected Result:
- Error message “Invalid email format” appears
- User account is not created

## Actual Result:
(To be filled during testing)

## Status:
Not Executed

## Priority:
High

## Severity:
Medium

## Notes:
- Check that no account is created in the system database
