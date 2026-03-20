**Bug ID:** RP-BUG-001  
**Title:** Unable to submit order after editing added unit (green checkbox disappears)  
**Page/Feature:** Add Units  
**Severity:** High  
**Priority:** High  

## Steps to Reproduce
1. Navigate to Add Units page  
2. Click “Click to add”  
3. Click “Confirm”  
4. Click “Edit” on the added unit  
5. Click “Confirm” again  

## Expected Behavior
- The green confirmation checkbox should remain visible  
- The unit should remain valid and editable  
- User should be able to submit the order successfully  

## Actual Behavior
- The green checkbox disappears after re-confirming  
- The unit appears to be in an invalid/unconfirmed state  
- User is unable to submit the order  

## Impact
Blocks users from completing the unit request process  

## Screenshots/Recording

# Bug Report 2
**Bug ID:** RP-BUG-002  
**Title:** Pickup request allows submission with quantity = 0  
**Page/Feature:** Pickup Unit  
**Severity:** High  
**Priority:** High  

## Steps to Reproduce
1. Navigate to Pickup Unit page  
2. Do not select any units (quantity remains 0)  
3. Click “Confirm”  

## Expected Behavior
- System should prevent submission when quantity = 0  
- “Confirm” button should be disabled OR validation message displayed  
- User should be required to select at least one unit  

## Actual Behavior
- “Confirm” button remains clickable  
- Form can be submitted with quantity = 0  

## Additional Notes
- The only way to increase quantity is by clicking “Select All for Pickup,” limiting flexibility  

## Impact
May lead to invalid or meaningless service requests being submitted  

## Screenshots/Recording


# Bug Report 3
**Bug ID:** RP-BUG-004  
**Title:** Map automatically rescales on browser resize and iOS scroll  
**Page/Feature:** Map Interaction  
**Severity:** Medium  
**Priority:** Medium  

## Steps to Reproduce
1. Navigate to any page that has the map frame 
2. Resize the browser window  
   OR  
3. Scroll down the page on an iOS device  

## Expected Behavior
- Map zoom level and scale should remain stable  
- User-selected view should persist  

## Actual Behavior
- Map automatically rescales/zooms unexpectedly  
- View changes without user intent  

## Impact
- Disrupts user interaction with map  
- Makes precise unit placement difficult  
- Reduces usability on mobile devices  

## Screenshots/Recording
