# NurtureSparkZoho

## ID Verification
Provides a form for users to submit ID verification details including Eid document upload, personal information, and contact details.
### validation logic
#### Validates mandatory fields and phone number not email
if (!EmiritesID || !firstName || !lastName || !residenceStatus || !emiratesIdNumber || !nationality || !phoneNumber || !dob) {
            alert('Please fill in all the required fields.');
            return;
          }
#### Emirites ID Document Varification (svg,png,jpeg,gif)allowed

## Income Validation
Requires input regarding employment details, income, expenses, and beneficiary information.
Validates mandatory fields and formats.

## Loan Details
Captures information related to the loan product, mortgage details, and document uploads.
Requires mandatory fields and performs basic validation.

## Agreement Section
Allows users to upload a signature, enter their name, and confirm reading the agreement.
Selects a payment method.

## Payment Submission
Finalizes the submission by processing the payment.
