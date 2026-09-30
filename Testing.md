# Testing

## Test Case 1 – Standard Laptop Request

**Input:** Valid standard laptop request.

**Expected Result:** The configured Flow Designer workflow is triggered and the request moves through the defined workflow stages.

**Status:** `[Pass / Fail]`

## Test Case 2 – Approval Required

**Input:** Request that meets the configured condition requiring approval.

**Expected Result:** Approval activity is generated and the flow continues after the approval outcome.

**Status:** `[Pass / Fail]`

## Test Case 3 – Approval Rejected

**Input:** Request for which the configured approval is rejected.

**Expected Result:** The request follows the rejection handling configured in the flow.

**Status:** `[Pass / Fail]`

## Test Case 4 – Fulfilment

**Input:** Approved standard laptop request.

**Expected Result:** The required fulfilment activity is created or updated and the request progresses toward completion.

**Status:** `[Pass / Fail]`

## Test Case 5 – Completion

**Input:** Fulfilment activity completed.

**Expected Result:** The request reaches the configured completed state.

**Status:** `[Pass / Fail]`
