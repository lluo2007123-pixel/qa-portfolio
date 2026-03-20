### Test Case ID: RP-007
**Module:** Order Form  
**Test Title:** End-to-end order submission with valid data  
**Priority:** High  
**Severity:** Critical  
**Test Type:** Functional  

#### Preconditions:
- User is on the homepage  
- Order form is accessible  

#### Test Steps:
1. Navigate to the order form  
2. Enter valid job site location  
3. Select number of units  
4. Choose service frequency  
5. Enter delivery date  
6. Fill in contact and billing details  
7. Click "Submit Order"  

#### Expected Result:
- Order is successfully submitted  
- Confirmation page is displayed  
- Confirmation email is received  

#### Status:
passed

### Test Case ID: RP-052
**Module:** Service Requests  
**Test Title:** Request pickup of a single unit  
**Priority:** High  
**Severity:** Critical  
**Test Type:** Functional  

#### Preconditions:
- User is logged in  
- User has an active order with multiple units  

#### Test Steps:
1. Navigate to dashboard  
2. Open an existing order  
3. Select "Request Pickup"  
4. Choose "Single Unit"  
5. Submit the request  

#### Expected Result:
- Pickup request is successfully submitted  
- Request is reflected in order history  
- Confirmation email is received  

#### Status:
passed 

#### Notes:
Verify correct unit selection behavior

### Test Case ID: RP-083
**Module:** Email  
**Test Title:** Order confirmation email content validation  
**Priority:** High  
**Severity:** Major  
**Test Type:** Integration  

#### Preconditions:
- User submits a new order  

#### Test Steps:
1. Complete and submit an order  
2. Check registered email inbox  
3. Open the confirmation email  

#### Expected Result:
- Email is received within expected time  
- Email includes:
  - Order details  
  - Delivery date  
  - Job site information  
- Content is clear and easy to understand  

#### Status:
passed

#### Notes:
Check for missing or unclear information in email content
