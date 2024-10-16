
# E-Commerce Test Automation Project

## Overview
This project demonstrates the automation of test cases for a sample e-commerce website. It includes functional tests, login tests, UI tests, and form validation tests using Tricentis Tosca.

## Prerequisites
- Tricentis Tosca installed
- Access to the e-commerce website (https://www.inmotionhosting.com/)

## Test Cases
1. **Functional Test: Search and Checkout**
   - Test Case ID: TC_Func_001
   - Description: Search for a product, add it to the cart, and proceed to checkout.
   - Expected Result: Product should be added to the cart, and checkout should work correctly.

2. **Login Test (Valid)**
   - Test Case ID: TC_Login_001
   - Description: Validate login with valid credentials.
   - Expected Result: User should be logged in successfully.

3. **Login Test (Invalid)**
   - Test Case ID: TC_Login_002
   - Description: Validate error message for invalid login.
   - Expected Result: Appropriate error message should be displayed.

4. **UI Test**
   - Test Case ID: TC_UI_001
   - Description: Verify the presence of key UI elements on the homepage.
   - Expected Result: All UI elements should be displayed correctly.

5. **Form Validation Test**
   - Test Case ID: TC_Form_001
   - Description: Validate registration/contact form.
   - Expected Result: Proper validation messages for empty fields and successful submission for filled fields.

## Execution Steps
1. Open **Tosca Commander**.
2. Import the test case folder.
3. Select the test cases to execute.
4. Right-click and select **Run** to execute the tests.
5. Monitor the execution results in the **Execution Results** section.

## Generating the Test Report
1. Navigate to the **Execution Results** section after running the tests.
2. Right-click on the execution result and select **Export to Excel**.
3. Choose the columns to include and save the report.

## Video Presentation
A video presentation demonstrating the execution of the tests and report generation is included in the submission.

## Notes
- Ensure that your test environment is properly set up with the necessary configurations.
- Review the comments in the Excel report for details on test execution.

## License
This project is for educational purposes only.
